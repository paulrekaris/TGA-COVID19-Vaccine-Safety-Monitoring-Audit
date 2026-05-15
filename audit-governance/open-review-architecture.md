# Open Review Architecture: Accountability Through Transparency

[![ISO 19011:2018](https://img.shields.io/badge/ISO-19011%3A2018-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/70017.html) [![ISO 15489-1:2016](https://img.shields.io/badge/ISO-15489--1%3A2016-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/62542.html) [![ANAO](https://img.shields.io/badge/ANAO-Better%20Practice-1B2A4A?labelColor=1B2A4A&style=flat-square)](https://www.anao.gov.au/work/insights/performance-audit-process) [![FAIR Principles](https://img.shields.io/badge/FAIR-Data%20Principles-000000?labelColor=000000&style=flat-square)](https://doi.org/10.1038/sdata.2016.18) [![Open Access](https://img.shields.io/badge/Open%20Access-MIT%20Press%202012-E67E22?labelColor=E67E22&style=flat-square)](https://cyber.harvard.edu/hoap/Open_Access_(the_book)) [![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?labelColor=181717&style=flat-square)](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) [![PGPA Act](https://img.shields.io/badge/PGPA%20Act-2013-1B2A4A?labelColor=1B2A4A&style=flat-square)](https://www.legislation.gov.au/C2013A00123/latest/text)

**Version:** 1.1  
**Date:** 24 March 2026

This audit uses GitHub’s public, forkable, permanently archived architecture—in alignment with open source and open science standards—as its primary accountability mechanism in place of traditional closed peer review. Anyone may verify, challenge, or build upon the work.

## 1. Purpose

This document describes the open review architecture underpinning this audit. It explains how the work achieves accountability and scrutiny without reliance on traditional closed peer review, and how it aligns with ISO 19011:2018 audit principles and ANAO performance audit standards.

## 2. The Open Review Model

This audit implements a continuous, distributed, public review architecture rather than traditional closed peer review:

| Feature | Description |
|---------|-------------|
| **Public repository (GitHub)** | Full version control, transparent revision history, public by default |
| **Forkability (CC BY 4.0)** | Anyone may copy, adapt, or redistribute. Forking is an invitation to correct, improve, or challenge |
| **Issues and discussion** | Public forum for questions, critiques, and corrections |
| **Permanent archiving** | NLA (AWA), Harvard Dataverse, Zenodo, SSRN, SocArXiv, Mendeley Data (persistent DOIs), Arweave, blockchain. The work is designed to resist suppression or retroactive alteration |
| **Deposited evidence** | All FOI documents, evidence matrices, and primary sources preserved and citable |
| **Falsifiability** | Any finding can be disproved by production of contradictory documentation |

### 2.1. How to Engage

[![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?labelColor=181717&style=flat-square)](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)

Any person or organisation may scrutinise, challenge, or build upon this work through:

- **Fork the repository** — create your own copy, correct errors, or publish alternative analysis
- **Open an Issue** — ask questions, raise concerns, or suggest corrections publicly
- **Cite the permanent archives** — use the NLA, Zenodo, or SSRN identifiers for scholarly or legal reference
- **Submit corrections** — email the author or open a pull request with proposed changes

All engagement becomes part of the permanent record via the National Library of Australia’s web archive.

## 3. Comparison to Traditional Peer Review

|Criterion         |Traditional Closed Peer Review              |This Open Review Architecture                                                                     |
|------------------|--------------------------------------------|--------------------------------------------------------------------------------------------------|
|**Reviewers**     |2–3 anonymous experts                       |Unlimited public reviewers                                                                        |
|**Timing**        |Single point in time                        |Continuous, ongoing                                                                               |
|**Transparency**  |Closed comments, sealed process             |Public issues, forks, discussions                                                                 |
|**Permanence**    |Publisher-controlled                        |Multiple permanent archives, blockchain-anchored; designed to survive platform changes or deletion|
|**Replicability** |Data and methods often not shared           |All evidence deposited, methods documented                                                        |
|**Accountability**|No requirement for audited entity to respond|Silence becomes part of permanent record                                                          |

## 4. Standards Alignment

**ISO 19011:2018** (including clauses on managing the audit programme, conducting audits, and auditor competence) requires that audit findings are based on verifiable evidence and that audit activities are planned, documented, and capable of independent evaluation. This architecture meets those requirements by depositing all evidence in permanently archived, citable locations, documenting search methodologies and evidence hierarchies, and inviting independent replication and challenge.

**ANAO Better Practice** guidance on the performance audit process emphasises that audits are independent, objective, and evidence-based, supporting transparency and accountability to Parliament and the public. This architecture makes all methods and evidence public, allows continuous scrutiny by any party, and creates a permanent record designed to resist retrospective alteration.

**ISO 15489-1:2016** (including clauses on principles and requirements for records management) requires organisations to create and manage records so that they remain authentic, reliable, have integrity, and are usable over time. Version control (via Git commit history), blockchain timestamping, and multi-layer archiving implement these requirements for the audit’s own governance. The complete revision history is publicly accessible in the GitHub repository.

**Public Governance, Performance and Accountability Act 2013** (including sections 37 and 41) requires Commonwealth entities to maintain records and performance information that properly document and demonstrate their performance. This audit tests whether such records exist; the absence of documentation is itself a finding preserved for oversight bodies.

## 5. Invitation to Formal Audit

This open architecture is not a substitute for formal audit by a statutory body with powers to compel documents and testimony. It provides a permanent, verifiable evidentiary basis for such an audit.

The Australian National Audit Office (ANAO) is invited to conduct a performance audit of the TGA’s COVID-19 vaccine safety monitoring framework using its statutory powers. The Senate, OAIC, and Commonwealth Ombudsman are similarly invited to use this work as a basis for inquiry.

## 6. Conclusion

This work does not claim to have undergone traditional peer review. Instead, it is designed for continuous public scrutiny, with the evidence permanently preserved for independent verification, challenge, replication, and reuse.

- **Transparency** — all evidence and methods are public and permanently archived
- **Verifiability** — anyone can replicate, challenge, or build upon the work
- **Permanence** — the work is designed to resist suppression or retroactive alteration
- **Accountability** — the audited entity and oversight bodies are invited to respond; silence is recorded

## Related Documents

|Document                                 |Location                                                                                                         |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------|
|Main Audit Report                        |[analysis/documentation-gap-analysis-audit-report.pdf](../analysis/documentation-gap-analysis-audit-report.pdf)  |
|ISO 19011 Conformity Assessment          |[analysis/ISO-19011-conformity-assessment-checklist.md](../analysis/ISO-19011-conformity-assessment-checklist.md)|
|Permanent Archive Records                |[blockchain-and-archival-verification/README.md](../blockchain-and-archival-verification/README.md)              |
|Limitations and Falsifiability           |[README.md#limitations-and-falsifiability](../README.md#limitations-and-falsifiability)                          |
|Peer-Review Status                       |[README.md#peer-review-status](../README.md#peer-review-status)                                                  |
|GitHub Open Source Guide                 |<https://opensource.guide>                                                                                       |
|Open Source Definition                   |<https://opensource.org/osd>                                                                                     |
|Regulatory Accountability Audit Framework|[audit-governance/regulatory-accountability-audit-framework.md](regulatory-accountability-audit-framework.md)    |



**Licence:** CC BY 4.0  
**Last Updated:** 15 May 2026
