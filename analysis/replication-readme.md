# Replication README

## TGA COVID-19 Vaccine Safety Monitoring Documentation Dataset

This file provides replication code for all summary statistics reported in the dataset paper. All operations are directly reproducible from the evidence matrix using standard analytical tools.

## Quick Start

Download the evidence matrix from [Harvard Dataverse](https://doi.org/10.7910/DVN/BDKZQJ) or [Zenodo](https://doi.org/10.5281/zenodo.20175557), then run:

```python
import pandas as pd

df = pd.read_excel('output-assessment-evidence-matrix.xlsx', 
                   sheet_name='Evidence Matrix', header=1)

print(df['Status'].value_counts())
```

Expected output:

```
◐ Partially Implemented    10
✗ Not Documented            6
✓ Fully Implemented         3
Name: count, dtype: int64
```

Full replication code for all three analytical operations is provided below.

---

## Resources

- **Dataset paper**: [SSRN DOI: 10.2139/ssrn.6610438](https://doi.org/10.2139/ssrn.6610438)
- **Codebook**: [analysis/dataset-codebook.md](dataset-codebook.md)
- **Evidence matrix**: [analysis/output-assessment-evidence-matrix.xlsx](output-assessment-evidence-matrix.xlsx)

## File Structure

The evidence matrix contains six sheets:

- **Summary** — pre-computed headline statistics
- **Methodology** — audit methodology and evidence quality assessment
- **Rating Criteria** — classification criteria and evidence types required to close each finding
- **Evidence Matrix** — primary dataset (19 rows, one per assessed Plan output)
- **Output Assessment** — output-by-output severity ratings and assessment details
- **Reference** — supporting reference information

All replication operations below use the **Evidence Matrix** sheet.

The status-by-objective and rating-by-objective operations group the 19 outputs into seven objective categories (the Plan's five objectives, with collaborations reported separately as national and international, plus governance). This grouping is derived from the `Output ID` prefix, as shown in each language below.

---

## Python

```python
import pandas as pd

# Load evidence matrix (headers on row 2)
df = pd.read_excel('output-assessment-evidence-matrix.xlsx', sheet_name='Evidence Matrix', header=1)

# Documentation status distribution
df['Status'].value_counts()

# Derive seven objective categories from the Output ID prefix
def to_objective(oid):
    s = str(oid)
    if s.startswith('GOV'): return 'Governance'
    if s.startswith('1.'):  return 'Enhanced AEFI Reporting'
    if s.startswith('2.'):  return 'Signal Detection & Investigation'
    if s.startswith('3.'):  return 'Regulatory Actions'
    if s.startswith('4.'):  return 'Communications'
    if s == '5.1':          return 'National Collaborations'
    if s == '5.2':          return 'International Collaborations'

df['Objective'] = df['Output ID'].apply(to_objective)

# Status by objective cross-tabulation
pd.crosstab(df['Objective'], df['Status'])

# Severity rating by objective
df.groupby('Objective')['Rating (1-5)'].agg(['mean', 'min', 'max'])

# Mean severity rating across all 19 outputs
df['Rating (1-5)'].mean()  # → 3.47
```

---

## R

```r
library(readxl)

# Load evidence matrix (headers on row 2)
df <- read_excel("output-assessment-evidence-matrix.xlsx", sheet = "Evidence Matrix", skip = 1)

# Documentation status distribution
table(df$Status)

# Derive seven objective categories from the Output ID prefix
to_objective <- function(oid) {
  s <- as.character(oid)
  if (startsWith(s, "GOV")) return("Governance")
  if (startsWith(s, "1."))  return("Enhanced AEFI Reporting")
  if (startsWith(s, "2."))  return("Signal Detection & Investigation")
  if (startsWith(s, "3."))  return("Regulatory Actions")
  if (startsWith(s, "4."))  return("Communications")
  if (s == "5.1")           return("National Collaborations")
  if (s == "5.2")           return("International Collaborations")
}
df$Objective <- sapply(df$`Output ID`, to_objective)

# Status by objective cross-tabulation
table(df$Objective, df$Status)

# Severity rating by objective
aggregate(`Rating (1-5)` ~ Objective, data = df, FUN = function(x) c(mean = mean(x), min = min(x), max = max(x)))

# Mean severity rating across all 19 outputs
mean(df$`Rating (1-5)`)  # → 3.47
```

---

## Stata

```stata
* Load evidence matrix (headers on row 2)
import excel "output-assessment-evidence-matrix.xlsx", sheet("Evidence Matrix") cellrange(A2) firstrow clear

* Note: Stata strips special characters from column names on import
* "Output ID" imports as "OutputID" and "Rating (1-5)" as "Rating15" — run describe to confirm
describe

* Documentation status distribution
tabulate Status

* Derive seven objective categories from the Output ID prefix
gen Objective = ""
replace Objective = "Governance"                       if strpos(OutputID,"GOV")==1
replace Objective = "Enhanced AEFI Reporting"          if strpos(OutputID,"1.")==1
replace Objective = "Signal Detection & Investigation" if strpos(OutputID,"2.")==1
replace Objective = "Regulatory Actions"               if strpos(OutputID,"3.")==1
replace Objective = "Communications"                   if strpos(OutputID,"4.")==1
replace Objective = "National Collaborations"          if OutputID=="5.1"
replace Objective = "International Collaborations"      if OutputID=="5.2"

* Status by objective cross-tabulation
tabulate Objective Status

* Severity rating by objective
bysort Objective: summarize Rating15

* Mean severity rating across all 19 outputs
summarize Rating15
```

---

## Notes

- Variable names and column headers are defined in the [codebook](dataset-codebook.md) Section 6
- Classification criteria are defined in the [codebook](dataset-codebook.md) Section 2–4
- The criteria for revising any classification are specified in the Rating Criteria sheet within the evidence matrix
- The seven objective categories are derived from the `Output ID` prefix (Section above); the raw `Assessment objective` column holds the full per-output objective text

For variable definitions, evidence tier classification, severity rating scale, and analytical objective categories, see the [codebook](dataset-codebook.md).

## Reference

Social Science Data Editors. (n.d.). *Template README for social science replication packages*. https://social-science-data-editors.github.io/template_README/

**Version:** v1.1  
**Last updated:** 28 June 2026
