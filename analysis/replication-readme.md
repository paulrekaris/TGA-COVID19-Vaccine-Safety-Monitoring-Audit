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
Name: Status, dtype: int64
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

All replication operations below use the **Evidence Matrix** sheet.

---

## Python

```python
import pandas as pd

# Load evidence matrix (headers on row 2)
df = pd.read_excel('output-assessment-evidence-matrix.xlsx', sheet_name='Evidence Matrix', header=1)

# Documentation status distribution
df['Status'].value_counts()

# Status by objective cross-tabulation
pd.crosstab(df['Assessment objective'], df['Status'])

# Severity rating by objective
df.groupby('Assessment objective')['Rating (1-5)'].agg(['mean', 'min', 'max'])

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

# Status by objective cross-tabulation
table(df$`Assessment objective`, df$Status)

# Severity rating by objective
aggregate(`Rating (1-5)` ~ `Assessment objective`, data = df, FUN = function(x) c(mean = mean(x), min = min(x), max = max(x)))

# Mean severity rating across all 19 outputs
mean(df$`Rating (1-5)`)  # → 3.47
```

---

## Stata

```stata
* Load evidence matrix (headers on row 2)
import excel "output-assessment-evidence-matrix.xlsx", sheet("Evidence Matrix") cellrange(A2) firstrow clear

* Note: Stata strips special characters from column names on import
* "Rating (1-5)" will import as "Rating15" — run describe to confirm
describe

* Documentation status distribution
tabulate Status

* Status by objective cross-tabulation
tabulate Assessmentobjective Status

* Mean severity rating across all 19 outputs
summarize Rating15

* Severity rating by objective
bysort Assessmentobjective: summarize Rating15
```

---

## Notes

- Variable names and column headers are defined in the [codebook](dataset-codebook.md) Section 6
- Classification criteria are defined in the [codebook](dataset-codebook.md) Section 2–4
- The criteria for revising any classification are specified in the Rating Criteria sheet within the evidence matrix

For variable definitions, evidence tier classification, severity rating scale, and analytical objective categories, see the [codebook](dataset-codebook.md).

## Reference

Social Science Data Editors. (n.d.). *Template README for social science replication packages*. https://social-science-data-editors.github.io/template_README/

**Version:** v1.0  
**Last updated:** 25 June 2026
