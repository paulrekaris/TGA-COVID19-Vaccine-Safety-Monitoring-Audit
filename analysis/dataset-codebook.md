# Dataset Codebook

**TGA COVID-19 Vaccine Safety Monitoring Documentation Dataset**

---

## 1. Purpose

This codebook documents the variables, classification codes, evidence tiers, and rating scales used in the evidence matrix underlying the TGA COVID-19 Vaccine Safety Monitoring Documentation Dataset (v1.9.2). The matrix assesses 19 analytical outputs derived from the TGA Safety Monitoring Plan (February 2021) — comprising 17 pharmacovigilance strategies and two additional governance-related outputs. The primary analytical unit is the assessed output classification, with each output mapped to associated documentary evidence, evidence tiers, severity ratings, and explanatory metadata. All summary statistics are directly reproducible from the matrix using standard analytical tools.

Documented classification outcome across all 19 outputs: 3 Fully Implemented, 10 Partially Implemented, 6 Not Documented.

The codebook should be read in conjunction with the data article: Rekaris, P. (2026). A documentation dataset for the Australian COVID-19 Vaccine Safety Monitoring Plan. SSRN. https://doi.org/10.2139/ssrn.6333058

---

## 2. Documentation Status Classification

Each of the 19 assessed outputs is assigned one of three documentation status labels based on evidence identified through FOI disclosures, OAIC review proceedings, Senate Hansard, parliamentary records, and publicly available agency documentation. Labels reflect the state of the documentary record; they do not assess clinical effectiveness or operational outcomes.

| Label | Definition | Classification Criteria |
|---|---|---|
| Fully Implemented | Substantial documentary evidence identified for the specified output. | Available documentation demonstrates the output was produced and disseminated in a manner consistent with Plan specifications in scope, frequency, and methodology. |
| Partially Implemented | Incomplete or fragmented documentary evidence identified. | Some documentation exists but material gaps remain in scope, frequency, methodology, or public accessibility. |
| Not Documented | No documentary evidence identified for the specified output. | No documentation identified through FOI processes, public records, or parliamentary proceedings despite targeted inquiry. |

> **Note:** Absence of documentary evidence is distinguished from evidence of absence where the record permits. Classifications do not determine whether undocumented activities may have occurred outside retrievable records.

---

## 3. Evidence Tier Classification

Collected materials are organised using a four-tier evidence classification framework based on source type and verification characteristics. Each of the 19 assessed outputs is mapped to corresponding documentary evidence using this framework.

| Tier | Label | Source Types |
|---|---|---|
| 1 | Independently verifiable published sources | Peer-reviewed literature; publicly accessible databases |
| 2 | Official government publications and released documents | TGA publications; FOI-released internal documents; agency reports |
| 3 | FOI process records, statutory review materials, and parliamentary records | FOI decision letters; OAIC submissions and determinations; Senate Hansard; Questions on Notice |
| 4 | Claims without supporting documentation | Statements unsupported by retrievable primary documentation |

---

## 4. Severity Rating Scale

Each assessed output is assigned a severity rating (1–5) reflecting the significance of the documentation position relative to the monitoring framework objectives. The mean severity rating across all 19 outputs is 4.0.

| Rating | Label | Definition |
|---|---|---|
| 1 | Minimal | Minor documentation gap; negligible impact on overall monitoring integrity. |
| 2 | Low | Limited gap with minor impact on completeness of safety signal detection or reporting. |
| 3 | Moderate | Partial gap with potential impact on a monitoring objective or pharmacovigilance output. |
| 4 | High | Significant gap materially affecting a core monitoring objective. |
| 5 | Critical | No documentary evidence identified for a primary pharmacovigilance output. |

---

## 5. Analytical Objective Categories

Assessed outputs are grouped under seven analytical objective categories used in status-by-objective cross-tabulation analysis. These categories reflect the Plan's five original pharmacovigilance objectives and two additional governance-related outputs.

| Category | Scope |
|---|---|
| Governance | GOV-prefixed outputs; oversight and performance measurement |
| Enhanced AEFI Reporting | Strategy outputs 1.x; all five outputs classified as at least Partially Implemented |
| Signal Detection | Strategy outputs 2.x; all eight outputs Partially Implemented or Not Documented |
| Actions (Regulatory) | Strategy outputs 3.x; regulatory response and risk management actions |
| Communications | Strategy outputs 4.x; public and stakeholder risk communication |
| National Collaborations | Output 5.1; domestic inter-agency coordination and data sharing |
| International Collaborations | Output 5.2; international information sharing and regulatory cooperation |

---

## 6. Evidence Matrix — Variable Reference

The following variables appear as columns in the primary evidence matrix, located at [`analysis/output-assessment-evidence-matrix.xlsx`](output-assessment-evidence-matrix.xlsx) in this repository. Column names match the headers in the Evidence Matrix sheet exactly.

| Variable | Type | Description | Values / Format |
|---|---|---|---|
| Output ID | String | Unique identifier for each assessed output | GOV-x; 1.x–5.x |
| Plan output | String | Plain-language title of the assessed output | Free text |
| Assessment objective | String | Analytical objective category grouping | One of seven categories (see Section 5) |
| Status | Categorical | Documentation status classification | Fully Implemented / Partially Implemented / Not Documented |
| Rating (1–5) | Integer | Severity rating of the documentation position | 1–5 |
| Evidence Sources | String | Sources consulted in support of the classification | Free text; cross-referenced to primary-sources directory |
| Findings | String | Summary of documentary evidence identified or basis for classification | Free text |
| Documentation Gaps | String | Identified gaps relative to Plan specifications | Free text |
| Key References | String | Primary references underpinning the classification | Free text; DOIs and URLs where available |

> **Note:** The Rating Criteria sheet within the evidence matrix specifies the evidence types that would close any finding currently classified as Partially Implemented or Not Documented. New documentary evidence may be tested against the published rubric and used to revise affected classifications.

---

## 7. Derived Summary Statistics

The following statistics are directly reproducible from the evidence matrix using standard pivot or groupby operations in Python, R, or spreadsheet software.

| Statistic | Derivation | Python Operation |
|---|---|---|
| Documentation status distribution | Count of outputs by Status | `df['Status'].value_counts()` |
| Status by objective cross-tabulation | Pivot of Status × Objective category | `pd.crosstab(df['Objective'], df['Status'])` |
| Severity rating by objective | Mean, min, max of Rating (1–5) grouped by Objective | `df.groupby('Objective')['Rating (1-5)'].agg(['mean','min','max'])` |
| Mean severity rating | Average of Rating (1–5) across all 19 outputs | `df['Rating (1-5)'].mean()` → 4.0 |

---

## 8. Scope and Limitations

The dataset evaluates the extent to which documentary evidence associated with the published monitoring framework can be identified and mapped to specified outputs. It does not assess clinical effectiveness, vaccine safety outcomes, or whether undocumented activities may have occurred outside retrievable records.

Classifications reflect the evidentiary position based on retrievable documentation as at March 2026. Each classification is anchored to identifiable documentary evidence, and the criteria for revising any classification are specified in the Rating Criteria sheet within the evidence matrix.

Later document releases or institutional disclosures may alter the available evidence base. Corrections and additional evidence are welcomed and will be incorporated into future versions with transparent version history.

---

## 9. Methodological Note

The dataset was developed using a documentation analysis approach informed by ISO 19011:2018 auditing principles, ANAO performance audit guidance, and pharmacovigilance standards including ICH E2E and CIOMS Working Group VIII. Classifications were assigned by the auditor (Rekaris, P.) through mapping of specified Plan outputs to corresponding documentary evidence using predefined classification criteria and evidence tier classification.

All source materials were obtained through lawful public accountability mechanisms. The full methodology, version history, evidence handling procedures, and open repository documentation are documented in this repository: https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit

---

**Codebook v1.0    
**Last updated: 8 May 2026 
