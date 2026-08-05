# Version History

**Version Control Policy:** This audit maintains detailed version history following ISO 19011:2018 continuous improvement, ISO 15489-1:2016 records management, Keep a Changelog methodology, OSINT documentation standards, and research integrity principles. See [Version Control Policy](version-control-policy.md) for complete methodology.

**Note:** This log records significant revisions only. Minor corrections, typographical fixes, and formatting changes are not individually listed but are preserved in the repository's commit history. Best efforts are made to document substantive changes; this log is not exhaustive.

**Last updated:** 29 July 2026


---

## Table of Contents
- [Post-1.9.3 Release Notes](#post-193-release-notes)
- [Version 1.9.3 (14 June 2026)](#version-193-14-june-2026)
- [Version 1.9.2 (26 March 2026)](#version-192-26-march-2026)
- [Version 1.9.1 (7 February 2026)](#version-191-7-february-2026)
- [Version 1.9 (14 January 2026)](#version-19-14-january-2026)
- [Version 1.8 (6 January 2026)](#version-18-6-january-2026)
- [Version 1.7.4 (28 December 2025)](#version-174-28-december-2025)
- [Version 1.7.3 (22 December 2025)](#version-173-22-december-2025)
- [Version 1.7.2 (20 December 2025)](#version-172-20-december-2025)
- [Version 1.7.1 (18 December 2025)](#version-171-18-december-2025)
- [Version 1.7.0 (17 December 2025)](#version-170-17-december-2025)
- [Version 1.6.1 (14 December 2025)](#version-161-14-december-2025)
- [Version 1.6.0 (December 2025)](#version-160-december-2025)
- [Version 1.5.1 (December 2025)](#version-151-december-2025)
- [Version 1.5.0 (December 2025)](#version-150-december-2025)
- [Version 1.0 (27 November 2025)](#version-10-27-november-2025)


## Post-1.9.3 Release Notes (v1.9.4 — Statutory citation verification, primary-source additions and documentary-scope refinements)

[Commits v1.9.3...HEAD](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/compare/v1.9.3...HEAD)

*Changes since the v1.9.3 release. Findings, ratings, and conclusions unchanged throughout (3 Fully / 10 Partially / 6 Not Documented; mean severity 3.47). Prior versions remain accessible via Git history, the Zenodo DOI, and the NLA snapshot.* 

### Permanent archive and links
- Uploaded updated `permanent-archive-records-2026-06-17` file.
- Updated 2 links to the permanent-archive-records file (17-06-2026).
- Updated Ombudsman and OAIC status dates to reflect current position as of 17 June 2026.
- Added research infrastructure stack table to `blockchain-and-archival-verification`.

### README, terminology, and references
- Replaced discontinued ANAO Better Practice reference with ANAO Performance Audit Standards in README.
- Replaced "under oath" with accurate Senate Estimates terminology in README.
- Added live SSRN DOI link to the Senate citation paragraph in README.
- Added link to the TGA OAIC submission PDF in the Evidence Base paragraph in README.
- Regulatory Accountability Audit Framework: updated "Commonwealth Performance Series" to "Commonwealth Performance Framework" (correct PGPA term) and "probative value" to "evidential weight" for consistency with audit documentation language.

### TIMELINE.md
- Added a full chronology of FOI requests, OAIC proceedings, Senate engagement, and oversight-body submissions from February 2022 to present in a separate `TIMELINE.md`. Included a link and description in the Oversight and Accountability section of the main `README.md` and in the main index.

### Primary-source additions from the TGA OAIC submission (20 September 2024, MR22/00538)
- **Quote 1 - page 15:** the Department's formal submission states that "there is unlikely to be a set of discrete documents evidencing the TGA's preparedness (because no audit of preparedness was undertaken)." Added to the README Evidence Base section and to ISO 19011 conformity assessment Finding 1 (systematic tracking mechanism).
- **Quote 2 - Attachment D (contemporaneous TRIM search records):** a TGA search officer recorded in real time that "I have been unable to find any relevant documents in this search. If you have any other suggestions for search terms, I will conduct further searches as necessary." Added to the README Evidence Base section and to ISO 19011 conformity assessment Appendix B (OAIC-directed search results), before the Gaps Identified section.
- Both quotes are primary-source evidence from TGA's own formal OAIC proceedings and operational search records, directly corroborating the audit's central finding from within TGA's own documentary record.
- Added expanded search context (Attachment A rows 7 and 8) from the TGA OAIC submission to Appendix B in the ISO 19011 conformity assessment.
- Added two further observations from the TGA OAIC submission: (i) the Principal Medical Advisor's covering email estimated the search exercise would take "no longer than 30 minutes" - added to the Observations section of the search methodology comparison with contextual interpretation, and as a single factual sentence to ISO 19011 Appendix B; and (ii) search term 7 returned one document - a draft Pharmacovigilance Branch input summarising the Plan for inclusion in the Australian COVID-19 Vaccination Policy, noted by the searcher as containing no timelines for each planned action - added to ISO 19011 Finding 8 evidence. Both additions are cited to the primary source with page references.

### Version Classification Framework
- Introduced a Version Classification Framework and Blockchain Release Rule: defined criteria for Major Updates (X.0.0) affecting methodology, scope, or findings; specified conditions for blockchain timestamping (major updates and anchor releases); and established a classification layer between Scope and Release Workflow.

### Evidence framework alignment
- Streamlined the audit to a single, consistently applied evidence hierarchy. The four-tier source-reliability hierarchy - ranking evidence by verifiability, reliability, and evidential authoritativeness (Tier 1 Primary Statutory through Tier 4 Tertiary Contextual) - is now expressed identically across the main audit report (Section 9.4), README, dataset codebook, and dataset paper. A secondary evidence descriptor previously carried only in the README was consolidated into this single hierarchy for clarity; it was not used in the evidence matrix and its removal does not affect any classification.
- Codebook: stated source-reliability criteria (verifiability, reliability, evidential authoritativeness) in Section 3 and aligned the hierarchy note with audit report S9.4 and README. Bumped dataset version reference to v1.9.3 and corrected codebook metadata.

### ISO 19011 conformity assessment
- Relabelled the evidence hierarchy as "Evidence Weight by Source Origin" to distinguish origin-based weighting from the source-reliability hierarchy used in S9.4, codebook, and README; updated the table, paragraphs, and Appendix A accordingly. Tightened Finding 5 signal-figure phrasing (no documented rationale, not "did not lead to action"). Fixed a doubled word in Appendix A, a README link, and the SocArXiv DOI reference.
- Statutory citation alignment: Freedom of Information Act 1982 references aligned across all documents, with the reasonable-steps obligation cited as s24A and practical-refusal provisions cited consistently. Therapeutic Goods Act 1989 provisional-approval section references verified and aligned across the main report, ISO conformity assessment, and audit summary presentation.
- Benchmark criteria clarification: international pharmacovigilance standards (ICH E2E, CIOMS, EMA GVP, PIC/S) expressed consistently as recognised good-practice benchmarks, with major non-conformity findings anchored to the Plan's own commitments and Commonwealth records and performance obligations.

### Evidence matrix (output-assessment-evidence-matrix.xlsx)
- Added a README sheet as the first sheet, providing a self-contained orientation document for the dataset: title, version, and description; variable definitions matching the Evidence Matrix column headers; clickable hyperlinks to the repository README, audit framework, ISO 19011 conformity assessment, codebook, and replication code; DOI links to the dataset paper (Zenodo and SSRN), audit report (Zenodo and SSRN), and dataset archives (Harvard Dataverse and Mendeley Data); parliamentary record noting the Senate citation of 24 March 2026; licence (CC BY 4.0), citation, and contact details; and a reproducibility and falsifiability note linking to the Limitations and Falsifiability section of the repository README.
- Corrected errors across four sheets: phantom ISO 19011 clause references (5.2.2 and 6.3.1) replaced with correct references (cl 5.5.2 and cl 5.2); output count corrected from 20 to 19 (five instances); Senate testimony characterisation corrected from "under oath" to "under parliamentary privilege" (two instances); ANAO Better Practice replaced with ANAO Performance Audit Standards; spelling "assessement" corrected to "assessment". README sheet updated: variable-name underscores removed to match Evidence Matrix column headers; audit-context description paragraph added.
- Updated the Summary sheet governance clause reference to "5.5.2 and 5.2" (consistent with the Output Assessment sheet and codebook) and corrected the Communications min/max severity rating. No change to classifications or statistics.
- Corrected the ISO 19011:2018 clause reference in the Evidence Boundaries / Assurance Level statement from 6.4.10 (closing meeting) to 6.4.9 (determining audit conclusions), the correct clause for conclusions drawn from available evidence within scope.
- Standardised objective labels in the Summary sheet - "Regulatory Actions" (formerly "Actions (Regulatory)") and "Signal Detection & Investigation" - to match the codebook and dataset paper. No change to underlying data, classifications, ratings, or summary statistics.
- Added a new section within the existing Rating Criteria sheet, documenting the criteria for assigning severity 3 versus 4 within "Partially Implemented" outputs — previously an unstated distinction in the decision tree. Criteria wording matches the dataset codebook's existing Moderate/High definitions exactly, and cites ISO 19011:2018 clause 6.4.8 (verified directly against the primary standard text) as the basis for quantitative severity grading. No change to any rating, score, or audit finding.

### Figure and label consistency
- Standardised the OAIC-directed search figure (2,218 pages across 531 TRIM containers) and signal-count reporting (148 per Senate testimony; 150 per QON 559) across all documents including visual summaries. Aligned documentation-status percentages in the implementation-status tables and summary dashboard, and confirmed the three-category classification scheme (Fully Implemented, Partially Implemented, Not Documented) throughout, with "Not Documented" defined as absence of locatable documentary evidence rather than a claim that an activity did not occur.

### One-page flowchart
- Removed the duplicated evidence-hierarchy block from the audit-steps panel, retaining a single listing relabelled "Evidence Weight by Source Origin." Corrected Senate testimony characterisation to parliamentary privilege (not under oath).
- Subsequently replaced the origin-weighting panel with the source-reliability hierarchy used in the audit report S9.4, codebook, README, and summary deck, so "Tier" denotes source-reliability consistently across all artefacts. Re-ordered to primary statutory (FOI, OAIC, TGA communications) at Tier 1 and parliamentary records (Senate testimony, QON 559) at Tier 2. Updated heading to "Evidence Hierarchy" and added a caption preserving the origin point. Retained the independent-validation grouping (OAIC reviews, external legal analysis, peer-reviewed publication).

### Audit summary presentation (ppt deck)
- Statutory citations reviewed and verified against the FOI Act 1982: the OAIC-directed searches (s55V(2)) and practical-refusal grounds (s24AA) confirmed correct; the s24A row recast to the documents-cannot-be-found scenario it governs. Document figure standardised to 2,218 pages across 531 TRIM containers, consistent with the OAIC submission and all other documents. International pharmacovigilance standards (ICH E2E, CIOMS, EMA GVP, PIC/S) presented consistently as recognised good-practice benchmarks rather than binding obligations. Documentation-status percentages, objective labels, evidence-hierarchy labelling, and Strategy/Objective terminology aligned with the main report.
- Corrected the evidence-weight heading to "Evidence Weight by Source Origin" and clarified Tier 4 to "published regulatory actions" (public-record sense); removed duplicate listing of Senate testimony under Tier 4.
- Improved alignment of the TGA Act and provisional-approval guidance to the Provisional Approval Lifecycle Framework analysis.
- Align FOI s 24AA refusal wording with the June 2025 decision letter framing (s 24(1)(b); s 24AA tests) to pose the statutory-test interaction as an open question pending OAIC review; refine legal-framework and records-management terminology.
- Aligned the summary deck with audit categories and removed personal names: replaced the origin-weighting evidence panel with the source-reliability hierarchy (Tier 1-4) used in audit report S9.4, codebook, and README; added a caption preserving the origin point; added QON 559 to Tier 2; standardised status language to the documentation categories ("fully documented", not "implemented") across the outputs breakdown; corrected the Governance row percentages in the status table (Partial 0%, Not Documented 100%); removed personal names from testimony references, attributing to roles or the agency, and softened "confirms" to "consistent with" where a conclusion was attached; fixed the Plan-name reference, a slide-title typo, and reform numbering.
- Added a status-by-objective chart showing documentation status across objectives, reproducing the matrix summary figures.
- Parliamentary-privilege characterisation and classification labels in the one-page flowchart and audit summary presentation brought into line with the main report.

### Compensation analysis — citation updates, international comparison, and QON 559 integration
- Corrected mismatched and missing citations throughout the international transparency comparison and signal-example sections, and added a reference for FOI 4029-03, previously cited but missing from the list.
- Replaced the international comparator table with current, dated figures from official sources (US, UK), after the originals were found outdated, and added Japan and a peer-reviewed 14-country study to position Australia's rate against the wider international standard. New Zealand and Canada were considered and excluded as comparators, with reasons given.
- Integrated Senate QON 559 (150 signals assessed, 93 with no recorded disposition) as the primary current figure throughout, replacing the earlier testimony figure (148) except where specifically describing the 9 October 2025 hearing itself. Added QON 559 as a reference.
- Reordered the full reference list into strict first-appearance citation order (1–28, verified), and corrected a scope error attributing signal-investigation-specific documentation to OAIC Decision AICmr 54, which addressed Safety Plan implementation documentation more generally.
- No change to the audit's core findings or the Australian claims data (4,962 lodged / 522 approved), all independently re-confirmed against source during this review.

### Replication code
- Added the seven-category to_objective() derivation (from Output ID prefix) to the Python, R, and Stata blocks so status-by-objective and rating-by-objective operations reproduce the paper's seven-category tables rather than grouping by the raw 19-value objective column. Listed all six matrix sheets. Updated the value_counts expected-output label for the current pandas.

### Codebook
- Updated Section 5 category labels to "Signal Detection & Investigation" and "Regulatory Actions" to match the matrix summary sheet and dataset paper. Added a note to Section 7 explaining that the Objective field is derived from the Output ID prefix, with a link to the replication README for runnable code. Corrected Output ID format (GOV.x).
- Broadened the Rating 5 (Critical) definition to cover Plan governance/accountability outputs. Rating 5 was defined solely as "no documentary evidence for a primary pharmacovigilance output", which excluded the governance/accountability outputs (GOV.1, GOV.2) also rated 5, creating a mismatch between assigned ratings and the written scale. Definition now reads "...primary pharmacovigilance output or a core governance/accountability commitment of the Plan", so all six Not-Documented outputs validate against the criterion. No ratings changed; mean severity 3.47 unchanged.

### Data codebook README - typos, labels, and consistency (28 June 2026)
- **Typos:** "evidence rix" to "evidence matrix" (Sec 1); "pharmacovigilance objecti" to "objectives" (Sec 5); "All source erials" to "All source materials" (Sec 9); footer "Codebook vesrion" to "version".
- **Label fixes (Sec 5 category table), to match matrix/data paper:** "Signal Detection" to "Signal Detection & Investigation"; "Actions (Regulatory)" to "Regulatory Actions".
- **Consistency fixes:** Sec 6 Output ID format "GOV-x" to "GOV.x"; Sec 6 "Assessment objective" row corrected to describe the full per-output text (the 7 categories are derived from Output ID) rather than wrongly stating the column holds the categories; Sec 7 derivation note added (the Objective field is derived from the Output ID prefix) with a link to the README; Sec 7 table heading "Pivot of Status x Objective category" to "Status x derived Objective category"; Sec 6 note "published rubric" to "published criteria". Document date updated to 28 June 2026.

### Discovery and indexing
- Added a plain-language discovery landing page (GitHub Pages, /docs) with search-facing metadata, Schema.org structured data, an FAQ, and a permanent-record block linking all deposits; added sitemap.xml and submitted both to Google Search Console for indexing.

### FOI 5082 register
- Softened "demonstrates...non-implementation" to "is consistent with non-implementation" in the FOI 5082 evidentiary-significance section, matching the documentary register used throughout. Removed a stray blockquote character in Key Findings.

### ANAO badge
- Updated ANAO badge text from "Better Practice" to "Performance Audit" to match the linked performance-audit-process page and avoid reference to the Better Practice Guides withdrawn in 2018.

### QON 559 analysis - finding-number reconciliation
- Aligned all Audit Finding cross-references in the QON 559 analysis to the main README numbering (Finding 4 = signal audit trails; Finding 5 = AusVaxSafety integration), removing the legacy "No Coordination Protocols / No Signal Pathways" labels that used an inconsistent scheme. Merged duplicate Key Updates entries; relabelled the ANAO badge to Performance Audit.

### Arweave presentation
- Pointed Arweave badges to the ViewBlock transaction record for on-chain verification (which loads reliably and demonstrates permanence) and to turbo-gateway for file retrieval, reflecting that Arweave permanence and gateway availability are distinct: the transaction is immutably confirmed on-chain (block 1,884,750), while retrieval of the 64.44 MiB bundle is served with varying performance across public gateways, per AR.IO network guidance that reliance on a single gateway domain is not the intended access model. Transaction ID: TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps; deposited version v1.9.2.

### NLA National edeposit
- Restructured as a multipart monograph at NED's advice. Citable reference updated from NED447016P1081502 to Title ID NED476889S65171; persistent Trove URL added (nla.gov.au/nla.obj-4238332288). AWA web-archive link unchanged. Subsequently updated the NED reference to NED477153P1133159 for deposit NED477153.

### Main Audit Report (July 2026)
- Updated the Main Audit Report: strengthened legislative provisional approval framework analysis, OAIC chronology, Appendix F resource links, version history, and formatting refinements.
- Refined scope wording to clarify that the audit assesses the documented implementation of the 17 enhanced monitoring strategies committed to by the TGA during the provisional approval period and specified in its February 2021 COVID-19 Vaccine Safety Monitoring Plan. 
- Refined the audit scope and key-finding language to clarify that the assessment evaluates verifiable documentary evidence demonstrating implementation, and corrected ANAO performance audit terminology. 
- Clarified the Section 9.4 evidence hierarchy criteria, including verifiability, reliability, and evidential authoritativeness. 
- Updated OAIC review documentation to incorporate the latest publicly available material relating to OAIC MR25/01153 (FOI 25-0166), including the current review status and associated records, strengthening the documented FOI escalation chronology. 
- Updated Appendix F (Links and Resources) to improve the organisation, categorisation, and accessibility of repository, archive, publication, and author reference links. 
- Revised the legislative framework for provisional approval to correct the statutory interpretation of the Therapeutic Goods Act 1989 (Cth), clarifying the distinction between provisional registration extensions under s29 and transition to full registration through applications under ss23 and 25. Improved and corrected related footnotes and references.
- Refined the legal basis and framework integrity assessment to distinguish statutory requirements from documented evidence of implementation, highlighting gaps in verification, traceability, and transparency relating to provisional registration conditions, risk management, and monitoring activities. 
- Applied minor formatting refinements throughout, including footnote presentation, table formatting, and layout consistency.
- Correct "(2024)" to "(2025)" in Appendix A.8, reference 7 (Senate Community Affairs Legislation Committee Estimates Hansard), matching the hearing date already stated in the same entry.
- Add supporting footnote citing Malikova MA (2020), "Practical applications of regulatory requirements for signal detection and communications in pharmacovigilance," Therapeutic Advances in Drug
Safety, 11:2042098620909614, alongside the existing ICH E2E/CIOMS traceability citation. Footnote auto-numbered by Word; all 81 prior footnotes verified unchanged and correctly shifted.
- No changes were made to the audit findings, ratings, methodology, or overall conclusions.

### Publications
- Included an update on the peer-review status of two related journal articles on the main README and PUBLICATIONS page.

### TGA Safety Plan Audit deck (July 2026)
- Revised the Commonwealth Framework slide (14) to a conformity-assessment format, aligned with the audit's ISO 19011 methodology: conformity verdicts (Non-conforming / Conforming / Indeterminate / Under review) replace severity ratings; Therapeutic Goods Act references updated to the verified provisions (ss 22D, 23AA, 28(2A)(aa) for the provisional framework; ss 23, 25 for transition); findings stated in documentary terms.
- Updated the FOI s 24AA findings (slides 7 and 14) to reflect the statutory-test distinction: refusal cited s 24AA(1)(b) while relying on ~177 hrs of s 24AA(1)(a) resource grounds against ~3 hrs identification.
- Aligned the provisional lifecycle slide (7) with the verified transition mechanism (s 23 application, s 25 evaluation).
- Set the PGPA s 37 / s 38 rows to reference governance outputs GOV.1 and GOV.2.
- Consolidated the international comparison slide (8) to a single current documentation column.
- Refined scope language across the findings and reforms slides to keep claims within the audit's documentary basis, including the slide 17 intro and closing lines and the slide 18 reform wording.
- Corrected the ICH E2E adoption date (2013 to June 2005); EMA GVP Module I (August 2025) confirmed.
- Corrected the slide 18 title text and minor typographical errors.
- **Verified against source:** Therapeutic Goods Act 1989 ss 22C/22D, 23AA, 25, 28(2A)(aa), 29(4)/29(8A); signal count (150), regulatory actions (57), output counts (17 strategies / 19 total), and dose figure (68.4m / 91.2%) confirmed consistent across slides.

## Version 1.9.3 (14 June 2026)

[Release Notes](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/releases/latest)

[Commits v1.9.2...v1.9.3](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/compare/v1.9.2...v1.9.3)

Core audit findings unchanged throughout. This release strengthens the evidence base (Senate QON 559, TGA Performance Reports review, July 2022 OAIC correspondence), corrects framework and statutory citations, and adds reproducibility infrastructure. The 7 major non-conformities, the 19-output scope, and the conclusion that the Plan's enhanced monitoring framework cannot be verified from available documentation are unchanged.

### Analysis and Methodology
- Added Senate Question on Notice 559 (SQ25-001584) gap analysis (`analysis/qon-559-gap-analysis.md`): assessment of TGA's formal written answer against all five Plan strategies, alignment with all seven audit findings, and ISO 19011 principles applied. Derived finding: 150 signals investigated and 57 regulatory actions taken, leaving 93 signals with no publicly documented decision rationale (from TGA's own parliamentary figures). NON-CONFORMING rating confirmed by TGA's own formal written parliamentary answer.
- Added review of the TGA Performance Reports for 2022-23 and 2023-24, identifying no explicit references to the COVID-19 Vaccine Safety Monitoring Plan despite discussion of COVID-19 vaccine evaluation and post-market monitoring.
- Amended Finding 2 to make the implementation inference explicit: TGA's "day-to-day processes" characterisation indicates the enhanced framework was not operationalised as distinct from routine surveillance.
- Noted the AusVaxSafety search-term omission in the evidence base discussion.
- Added Malikova (2020) peer-reviewed pharmacovigilance reference to the ISO analysis (Finding 5, AusVaxSafety integration gap) and to the surveillance data analysis (Finding 1, absence of documented data-source reconciliation; Finding 3, unexplained expected-rates methodology gap), with reference lists standardised.
- Updated `black-box-governance.md`: replaced Schmid et al. (2020) with Hood (2006) and Power (1997) for consistency with the transparency and auditability framework used across the work.
- Aligned README audit principles with ISO 19011:2018 Clause 4: added the risk-based approach (4 g) and Clause 4 sub-references for each named principle; previously listed principles verified as correctly attributed.

### Main Audit Report
- Citation-accuracy and readability revision. ISO 19011:2018 clause references corrected throughout and verified against the standard: audit criteria and scope anchored to Clause 5.5.2; evidence collection and verification to Clause 6.4.7; generation of findings to Clause 6.4.8; audit conclusions to Clause 6.4.9 (with 6.4.9.1 b) for the treatment of audit uncertainty).
- Re-anchored the two governance outputs (GOV.1, GOV.2) to the obligations that bind the auditee under the PGPA Act 2013 ss 37-39, rather than to ISO 19011, which provides the audit method.
- Updated ANAO references to current products (Audit Insights and the ANAO Audit Manual), reflecting the withdrawal of the ANAO Better Practice Guides in 2018.
- Re-characterised parliamentary evidence as given under parliamentary privilege rather than under oath, consistent with Senate estimates practice.
- Aligned records-management references to the Archives Act 1983 s 24 and the records duty under the PGPA Act 2013 s 37.
- Standardised status labels to the three-category scheme used throughout (Fully Implemented, Partially Implemented, Not Documented), correcting stray labels.
- Clarified AusVaxSafety figures in Strategy 2.4 as survey-response counts rather than unique individuals, with medical-attention figures noted as self-reported rather than confirmed attendances; percentages unchanged.
- Replaced "84% of Plan outputs not fully documented" with "Only 16% of Plan outputs have complete implementation documentation" in Key Findings.
- May 2026 amendment incorporated: added a keywords section and clarified enhanced-monitoring wording to better reflect the regulatory basis and documented surveillance obligations.
- Added date to the title page; added version-history amendment note; fixed a double negation (line 916). Readability edits throughout; no change to findings, ratings, or conclusions.

### Evidence Matrix, Codebook and Dataset
- Corrected transcription errors in the Summary sheet and cleaned the Evidence Matrix structure: corrected Rating by Objective values (Actions, Communications, National Collaborations); replaced the mean-of-means formula in the OVERALL row with a SUMPRODUCT weighted mean; corrected individual severity ratings for outputs 1.1, 1.2, 2.4, 2.5, 2.6 and 4.1; corrected the grand mean to 3.47; removed an orphan "Governance" header row, leaving a clean 19-row dataset. Status counts unchanged; no impact on audit findings.
- Added the dataset codebook as markdown for GitHub rendering.
- Aligned codebook evidence-tier definitions to Section 9.4 of the audit report for cross-document consistency.
- Added cross-reference notes distinguishing the codebook evidence classification, the source-reliability framework, and the implementation-proof framework; and distinguishing the ISO 19011 checklist evidence hierarchy from the Section 9.4 source-reliability framework.
- Revised the severity-rating scale definition to reflect output significance rather than documentation-gap severity, and aligned the Section 4 intro wording accordingly.
- Clarified that the dataset comprises documentary materials only (government records, FOI responses, parliamentary testimony, public regulatory publications) and contains no clinical-trial data, patient records, or individual health information.

### Replication and Reproducibility
- Added `analysis/replication-readme.md`: replication code for the evidence-matrix summary statistics in Python, R and Stata, with file-structure notes for all five spreadsheet sheets, Stata variable-name guidance, and links to the dataset paper, codebook, and evidence matrix.
- Added a Quick Start section to the replication readme with a minimal working example and expected output.
- Added a Replication Materials section to the analysis README and updated the evidence-matrix description with instructional guidance and cross-references.
- Added a verification bullet to the Quick Start path pointing readers to the Evidence Matrix with a five-minute reproduction path, linking to the data paper on SSRN.

### Primary Sources
- Added Senate QON 559 (SQ25-001584) to primary sources: TGA's formal written answer to the direct Plan-compliance question.
- Added the redacted TGA letter to OAIC dated July 2022 (MR22-00538), in which the Assistant Secretary acknowledges "ample documents" exist demonstrating actions corresponding to each Plan objective, contrasting with the earlier FOI 3643 assertion that records do not exist.
- Added the redacted TGA submission to OAIC (MR22/00538, September 2024) to the MR22-00538 folder, with links from the README and reference 26 of the ISO 19011 analysis.

### Publications
- Created `PUBLICATIONS.md` documenting the research-programme outputs, and added a Publications section to the main README linking to it.

### Main README
- Reframed the documentation headline to "Only 16% of Plan outputs have complete implementation documentation".
- Added the QON 559 entry to the evidence-base section with a link to the gap analysis.
- Edited the Senate citation heading and citation text.
- Added a verification/reproducibility bullet to the Quick Start (Evidence Matrix five-minute path; data-paper SSRN link).
- Added the Harvard Dataverse DOI badge and repository link; reorganised repository and archival badges into a clearer scholarly-infrastructure hierarchy.
- Added the Mendeley Data DOI to the Open Review Architecture page.

### Blockchain and Archival Verification
- Corrected the Arweave transaction ID from the metadata transaction to the data transaction (`TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps`, 64.44 MB); added an Arweave verification screenshot (ViewBlock, 1,468 confirmations, block 1,884,750) and an Arweave verification badge.
- Added Bitcoin timestamp verification for v1.9.2 (SHA-256 `eb0cbfc1b582f861b7c103120a491640ee3c1c4f1ac3606c80d0751564610347`, Bitcoin block 942725, 29 March 2026 AEDT); updated the Bitcoin Timestamp section to a dual-version format (v1.9.2 and v1.9.0) with verification screenshots, `.ots` proof files, and independent verification instructions; added a Bitcoin Block Explorer badge and standardised Bitcoin badge colours.
- Updated blockchain verification status from "pending" to "confirmed" for v1.9.2.
- Added the LOCKSS principle ("Lots of Copies Keep Stuff Safe") to the archival rationale and badge row.
- Added the three ISO standards badges to the badge header rows (ISO 19011:2018, ISO 15489-1:2016, ISO 14721:2025), previously referenced only in page content.
- Added the Harvard Dataverse repository record and metadata; reorganised the scholarly repository references.
- Added the ACRCR preservation statement and link to the Preservation Standard section.
- Refactored archive links (main README, FAQ, blockchain README) to point to `blockchain-and-archival-verification/` rather than a direct PDF; fixed broken link syntax in the Quick Start permanent-archive line; corrected Last Updated dates.

### Repositories and archival records 
- Uploaded audit report PDF and full repository zip to Internet Archive
- Triggered Wayback Machine snapshot of GitHub repository
- SocArXiv links and badges updated to current version 
- SSRN dataset paper posted (Abstract ID: 6610438)
- Zenodo dataset paper v2.3 published (DOI: 10.5281/zenodo.20637857)
- Permanent archive records updated

### Other Changes
- Updated reference lists and added new citations across affected documents.
- Format changes and minor corrections throughout (no impact to findings).

**Note: Core audit findings unchanged. The findings are strengthened by the QON 559 analysis, the TGA Performance Reports review, and the July 2022 OAIC correspondence. Prior versions remain permanently accessible via Git history, the Zenodo DOI, and the NLA snapshot**.

---

## Version 1.9.2 (26 March 2026)

[Release Notes](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/releases/latest)

[Commits v1.9.1...v1.9.2](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/compare/v1.9.1...v1.9.2)

### Analysis and methodology 
- Audit results: aligned assessments to exact TGA COVID-19 Vaccine Safety Monitoring Plan strategies and outputs (pp.6-11). Corrected inconsistencies between Plan commitments and evidence evaluations.  Top-line results adjusted slightly but core findings unchanged: Results adjusted to reflect corrected output alignment; core findings unchanged: 84% of outputs lack full documentation of systematic/enhanced processes as committed. Updated plan audit results throughout the repo including relevant Git pages, Main Audit Report and two visuals
- Reformat output-assessment-evidence-matrix- excel workbook for readability: update all audit results, merge headers, add visual hierarchy, fix spacing, correct typos, reorder tabs
- The audit defined two governance outputs—GOV.1 Implementation oversight and GOV.2 Performance measurement—to reflect requirements under the Public Governance, Performance and Accountability Act 2013 s37(2). These align with ISO 19011:2018 5.2.2 (audit programme objectives) and 6.3.1 (audit criteria). Total outputs audited: 19 (previously 20).
- Executive Summary scope clarified to 19 outputs with terminology note added in Main Audit Report
- Add new Key Finding no. 7 to main README and scope note to ISO 19011 conformity assessment: Safety Plan design and accountability. The Plan did not align with ISO 19011:2018 auditability principles or ANAO better practice guidance—outputs unnumbered, strategies conflated with deliverables, no implementation framework. Structure did not support systematic tracking of commitments.  Added anchored link to finding 7 in main README page
- Added GAO Yellow Book 2018 citation with paragraph reference (para. 8.10) to methodology section in ISO 19011 conformity assessment
- Added CIOMS Working Group VIII Chapter VIII citations to Output 2.3, Finding 5, and surveillance analysis sections in ISO-19011 conformity assessment 
- Added Senate Questions on Notice (December 2025) gap analysis: complete analysis of TGA's December 2025 responses to SQ13–19 including four-layer governance framework mapping, question-by-question assessment table, FOI evidence analysis, prior SQON pattern analysis, and governance failure conclusion
- Added "Case Study in Transparency" to Compensation Analysis: CDC MMWR report (August 2021) documenting quantified GBS risk (15.6/million in males 50–64), full methodology (observed/expected, 95% CI), and data sources (VAERS, VSD), contrasting with TGA's withheld equivalent analysis
- Refined Strategy 2.3 (Enhanced cumulative data reviews): integrated FOI 5275 (direct applicant copy via FOI 26-2581) across output-by-output breakdown, key supporting evidence, and pattern analysis; tightened FOI 5275 description to specify AIR-denominator methodology; added external validation that Strategy 2.3 incidence data was never produced
- Added markdown Table of Contents with anchor links and a back to the top link to ISO 19011 conformity assessment
- Updated file paths throughout to reflect repository restructure
- Format changes and minor corrections to text and references (no impact to findings)

### Audit Governance
- Created `regulatory-accountability-audit-framework.md`: principles and safeguards for citizen-led independent verification of public institution commitments using public records and professional audit standards (ISO 19011, ISO 31000, ISO 15489, FAIR data principles). Two-part structure: framework (methodology, evidence hierarchy, burden of falsification, reproducibility, integrity, independence) and safeguards (materiality, contemporaneity, proportional integrity, audit period, disclosure, negative evidence, scalability)
- Open Review Architecture page added to audit-governance (open-review-architecture.md) with references and links added to Supporting Documentation, Open Access Framework, and Peer-Review Status sections in main README and link to page in FAQ (Q.33)
- Updated Version Control Policy to include quality and records management, research transparency applied to regulatory accountability, expanded OSINT detail, changelog, open access framework, and additional relevant references
- Updated evidence storage methodology with repository folder structure explanation and ISO 15489-1:2016 alignment; updated international standards classification to reflect freely available status of ICH and CIOMS standards with local archiving noted
- Added ISO 15489-1:2016 as referenced standard in `release-checklist.md`
- Add version history policy note: significant revisions only, minor changes in commits

### Primary Sources
- Restructured primary-sources folder with seven subfolders (foi, oaic, senate-community-affairs-legislation-committee, tga-documents, aust-gov-policy, vaccination-data, vaccine-surveillance) and three FOI subfolders (foi-25-0166, foi-3643, foi-4029)
- Migrated primary evidentiary documents from reference-documents to primary-sources
- Added README files to all subfolders documenting folder contents and evidentiary significance
- Updated FOI 5275 entry: replaced third-party redacted copy (sourced from Russell Broadbent MP website) with direct FOI release to applicant (Paul Rekaris) obtained via FOI 26-2581 (decided 2 February 2026, decision maker: Fiona Turk, Director, Prescription Medicines Authorisation Branch). Updated filename to foi-5275-notice-of-decision.pdf. Updated primary sources README and Reference 25 in ISO 19011 conformity assessment accordingly.
- Added FOI 5225 / FOI 2389 (Pfizer COMIRNATY provisional registration  documents, July 2021) to primary sources. Evidentiary significance: richness of pre-approval documentation contrasts with absent post-market Safety Monitoring Plan implementation records, reinforcing accountability gap finding. Added to primary sources README in chronological order.

### Reference Documents
- Added ICH E2E Guideline and CIOMS VIII international pharmacovigilance standards for offline accessibility
- Added FOI 25-0166 folder with case decisions, key documents, and analysis
- Updated references throughout repository for Internet Archive direct upload section
- Replaced README to reflect restructured folder contents; removed duplicate references from ISO 19011 checklist

### Main README
- Sharpened callout statement to reference testimony given under oath by senior TGA officials
- Added four-layer governance hierarchy framework to repository description
- Added 21.2M recipient figure and largest provisional approval deployment context to Executive Summary
- Added Prime Minister and Cabinet Handbook citation referencing ministerial obligation to carry out Cabinet-endorsed decisions
- Added alternative explanations for absent records to Limitations and Falsifiability section
- Added Key Finding 5: AusVaxSafety integration cannot be demonstrated (Strategy 2.4 reference)
- Key Findings renumbered: former findings 5–7 become 6–8
- Added Archive and Preservation section with NLA monthly snapshot notifications and direct link to AWA; added NLA monthly snapshot of GitHub website to Australian Web Archive (distinct from dataset archiving)
- Added Multi-Layer Preservation Architecture badge and latest release version badge with auto-updating download icon
- Introduced navigation buttons: NLA/AWA, ZIP download, Version History, Permanent Archive, and Last Commit
- Changed project title to "TGA COVID-19 Vaccine Safety Monitoring Plan Audit" for consistency and deleted subheadimg
- Added SSRN and SocArXiv badges after Zenodo DOI badge; updated NLA badge text to Web 
- Archive; added SSRN citation to citation section and permanent archive section
- Expand ISO 19011 guiding standard description
- Updated internal link paths to reflect repository restructure; added local PDF link to Sparke Helmore case note
- Reformatted evidence base navigation links to inline prose
- Moved "No Commonwealth oversight initiated" to Accountability section; removed Scale and Context section to avoid duplication
- Added README scope footnote clarifying 17 Plan strategies + 2 governance outputs = 19 total audited (ISO 19011:2018 6.3.1/5.2.2, PGPA s37(2))
- Added Mendeley Data badge and link to main README (DOI: 10.17632/y5wmt6f8j9) and details to Permanent Archive section
- Reordered badge rows in main README by credibility and academic identity: Row 1 (Permanent Archive, NLA), Row 2 (Zenodo, Mendeley Data, SSRN, SocArXiv)
- Expanded ISO 15489-1:2016 description in Guiding Standards section
- Fix: Clarify 19 audited outputs (17 strategies + 2 governance. Update Key Findings #3, #6, and Implementation Status section to
distinguish audited outputs from Plan's original specifications.
- Format changes, updated anchor and page links and minor corrections throughout (no impact to findings)
- NLA Collection Development Policy link embedded in Official Archival Preservation section

### Blockchain and Archival Verification
- Preprint deposited on SSRN (DOI: 10.2139/ssrn.6333058), Mendeley Data companion dataset (doi.org/10.17632/y5wmt6f8j9.2 ) and SocArXiv (DOI: 10.31235/osf.io/sb4gz_v1) and updated relevant pages
- Added full SSRN and SocArXiv sections and DOIs with significance statement; added badges, opening paragraph, and Combined Verification bullet list.
- Updated Version Control Policy accordingly
- Expanded AWA significance section and removed PANDORA branding
- Added Internet Archive direct upload section; updated Internet Archive badge to Full Repository
- Updated permanent-archive-records with SSRN entry and March 2026 date; replaced PDF with text file
- Updated NLA record to include Australian Web Archive
- Added Zenodo section with full details, significance statement, GitHub integration, and concept DOI
- Fixed AWA heading levels and removed PANDORA reference
- Updated preservation layer count from seven to a multi-layer approach enabling future proofing
- Rationale for Platform Selection section added to Permanent Archive README documenting multi-layer archival stack across dissemination, reproducibility, and national permanence categories; changed name of badges and description to multi-layer across the repo to enable future proofing 
- Two-sentence reference added to main README linking to Rationale for Platform Selection
- Restructure permanent archive README — significance before access, add missing access sections, add rationale for platform selection
- Mendeley Data badge added to Blockchain and Archival Verification README (DOI: 10.17632/y5wmt6f8j9) and reordered badge rows by category: Row 1 (institutional), Row 2 (academic repositories), Row 3 (blockchain/web archive)
- Updated the Permanent Archive Records PDF to reflect the complete archival stack as at 19 March 2026. Added Mendeley Data and SocArXiv entries with full metadata. Standardised formatting across all entries including Title, Author, Licence, Status, and Indexed fields. Updated NED entry to distinguish Publication Title (NLA registered) from Document Title (PDF internal). Updated AWA entry with Trove-registered title, snapshot history, and monthly capture confirmation. Added ARK identifier and metadata to Internet Archive Direct Upload entry. Added GitHub Repository entry with current version.
- NLA Collection Development Policy badge and embedded link added to blockchain and archival verification README and Official Archival Preservation section in main README

### Traffic Monitoring Workflow
- Expanded institutional traffic monitoring to ten categories: Australian Government, Oversight Bodies, US Government, Academic, NGO/Advocacy, Consulting, Legal, Major Media, Health/Medical, and Corporate
- Added academic repository domains to institutional detection: Mendeley, SSRN, OSF/SocArXiv, SocOpen, and Elsevier
- Added AEST report timestamp and data-through date to summary header
- Expanded all-time stats with total unique cloners, total unique views, average daily unique cloners, and average daily unique views
- Added peak day tracking for clones, views, unique cloners, and unique views
- Replaced mechanical traffic commentary with event-driven key observations: new all-time peaks, clone/view milestones, institutional attention alerts, and engagement alerts
- Removed redundant engagement block (now covered by key observations and repository engagement totals)
- Improved summary formatting with section spacing for readability

### File Maintenance
- Kebab-case file naming applied throughout including media files
- Updated TOC to reflect renamed and restructured files
- Updated internal relative path references, anchors, and links

### Added
- Standards badges added across audit documentation pages:
- Audit-governance folder README: ISO 19011:2018, ISO 15489-1:2016, ISO 14721:2025, ANAO, OSINT Foundation, ODNI, Open Access, FAIR Principles, DPC, Semantic Versioning, Keep a Changelog, Zenodo, GitHub, OpenTimestamps, Arweave (15 badges)
- Version Control Policy: ISO 19011:2018, ISO 15489-1:2016, Open Access, Semantic Versioning, Keep a Changelog, OSINT Foundation, ODNI, Zenodo, GitHub, OpenTimestamps, Arweave
- Release Workflow Checklist: ISO 19011:2018, ISO 15489-1:2016, Semantic Versioning, Zenodo
- Evidence Storage Methodology: ISO 15489-1:2016, FAIR Principles, Open Access, DPC
- ISO 19011 Conformity Assessment: ISO 19011:2018, ISO 15489-1:2016, ISO 14721:2025, ANAO, GAO
- Analysis Documents README: ISO 19011:2018, ISO 15489-1:2016, ANAO, GAO
- Blockchain and Archival Verification README: ISO 14721:2025 (Preservation Standard section)
- Standardise reference formatting, and add two OSINT references in FOI systematic review
- FAQ Q21: added Strategy 2.4 reference for consistency with Key Finding 5
- Add to main README under Peer Review status and Q35 in the QandA that the public GitHub repository functions as an open review mechanism
- How to Engage with this Audit section in the Quick Start Section of README and the FAQ page
- Australian Senate Citation section (24 March 2026) in README and Primary Sources section — Senator Malcolm Roberts cited the audit by name in the Australian Senate adjournment debate,  referencing key findings from the SSRN publication including absence of implementation records, OAIC confirmation, and ISO 19011 conformity assessment results. Section includes summary, key messages cited, and YouTube link to senate proceedings and Hansard.
- Key correspondence folder containing communications from committees and agencies such as ANAO.
- Updated Oversight and Accountability section with ANAO response (19 January 2026) and Senate Community Affairs Legislation Committee response (2 March 2026)
- OAIC and Commonwealth Ombudsman status updates as of 26 March 2026
- Added correspondence folder with formal submissions and responses from ANAO and Senate Community Affairs Legislation Committee

### Other changes
- Added Table of Contents with anchor links to README files requiring navigation aids, based on document length and section complexity
- Created primary-source subfolders for OAIC cases MR22/00538 and MR25/01153; MR25/01153 README includes application details, FOI reference (FOI 25-0166), and agency details
- Added README files to both subfolders
- Make minor grammatical and administrative corrections throughout
- Fixed CITATION.cff: corrected repository to repository-code per CFF 1.2.0 specification

**Note:** Core audit findings unchanged. Finding strengthened.


---


## Version 1.9.1 (7 February 2026)

[Release Notes](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/releases/latest)

[Commits v1.9.0...v1.9.1](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/compare/v1.9.0...v1.9.1)


### Added

**Evidence Documentation**
- Output-by-output breakdown table showing all 20 Plan outputs with status and evidence basis to ISO 19011 audit
- Excel evidence matrix with complete output-by-output evidence trail including sources, findings, and documentation gaps
- Summary by objective showing conformity rates: Objective 2 (Signal Detection) at 0% fully implemented, Governance & Performance at 0% documented, overall 15% conformity rate
- Critical gap analysis documenting five key patterns: enhanced monitoring implementation failure, governance absence, enhanced vs routine indistinguishability, communication vs process divergence, international vs domestic transparency gap

**README Enhancements**
- Key Findings section with five structured findings providing executive-level summary between Executive Summary and Evidence Standard
- Guiding Standards section documenting ISO 19011:2018, ISO 15489-1:2016, ANAO Better Practice, OSINT methodology, and Open Access framework
- "A Note on Accountability" section establishing verification framework
- Sparke Helmore legal analysis (11 May 2025) to Evidence Standard and Timeline of Contradictions
- Administrative Law vs Accountability section distinguishing procedural FOI compliance from substantive policy implementation accountability
- Scale and context section after Key Findings (68.4M doses under provisional approval, 91.2% of rollout)

**ISO 19011 Audit**
- Prominent disclaimer box distinguishing audit methodology from ISO certification
- Dedicated Methodological Limitations section covering access limitations, evidence constraints, resource constraints, scope boundaries, and impact on findings
- FOI 4029-03 evidence integration proving internal capacity (ACV presentation Sep 2021) contrasted with public transparency absence

**Version Control Policy**
- Release Workflow section documenting three-phase release process (content → release and academic archival → blockchain verification)
- Verification Efficiency Principle section explaining minimum steps for cryptographic proof
- Workflow example with updated implementation showing post-release blockchain verification
- Revised rationale explaining post-release verification approach ensuring blockchain verifies published DOI-stable version
- 6 new references: Keep a Changelog, Semantic Versioning, GitHub releases/audit log, OpenTimestamps, Nakamoto Bitcoin whitepaper, Arweave Yellow Paper, Zenodo DOI versioning

**Release Checklist**
- Add four-phase release workflow checklist (content finalisation, release and academic archival, blockchain verification, post-release verification)
- Includes release type decision guide and semantic versioning convention
- Documents standards alignment (ISO 19011, SemVer, Zenodo, RDA)

**Surveillance Data Analysis**
- Visual Timeline table documenting surveillance degradation across five periods (Mar 2021–Nov 2023)
- "Expected Rates" methodology explanation to Finding 3 using WHO source and ICH E2E standards
- Expected Rates Evolution table tracking evolution from signal-focused investigations (2021) to unverifiable reassurance claims (mid-2022+)
- Enhanced compensation barrier documentation: TGA holds population-level evidence inaccessible to treating doctors, 4,440 rejected/withdrawn claimants unable to access signal validation data
- International comparison: US CDC/UK MHRA publish detailed methodologies within days vs TGA aggregates only
- CIOMS Good Pharmacovigilance Practices to standards framework

**Compensation Analysis**
- Timeline of Key Events tracking critical dates from Safety Plan publication (Feb 2021) through scheme closure (Sep 2024)
- Specific Examples of Information Asymmetry section with three detailed clinical scenarios (myocarditis in young males, menstrual disorders, GBS)
- International Comparison table with detailed comparison (US CDC, UK MHRA, AU TGA) documenting transparency levels, methodology publication, and compensation outcomes
- References with verified HRSA, UK Government, Telegraph, CDC MMWR sources

**Search Methodology Comparison**
- Methodological Note defending comparison validity despite different search environments (TRIM vs public websites)
- Implications for FOI Administration section raising three critical questions about s24A "reasonable steps" standard, output-specific terminology, and search scope

**FOI Systematic Review**
- Detailed search process section covering tools, quality control measures, and search parameters
- Comprehensive limitations statement covering TGA disclosure log reliance, s.11C public releases limitation, keyword-based approach limitations, and no access to refused/partially released documents
- 85% repository coverage metric clarification

**Disclaimer**
- Methodological boundaries statement clarifying citizen-led audit scope, evidence constraints, and verification framework
- Nature of This Audit section establishing that monitoring without defined metrics, tracking, and records is indistinguishable from no monitoring
- Updated table of contents

**Archival Registration**
- National Library of Australia National edeposit (NED) registration: Deposit ID NED447016. NLA reference ID NED447016P1081502 (3 February 2026). Fulfills Commonwealth digital legal deposit requirements, discoverable via Trove as part of Australia's official national collection.
- Internet Archive Wayback Machine preservation snapshots for key repository pages

**Peer Review Statement**
- Add peer review readiness statement to README disclaimer section explaining methodology employs recognised audit standards (ISO 19011:2018, ANAO) enabling independent verification and formal peer review

**FAQ**
- Hyperlinked footnotes with return navigation for dose statistics (75M total, 68.4M provisional)
- September 2025 timeframe clarification to dose references

**Black Box Governance**
- Falsification safeguards note to abductive reasoning section with three mitigation strategies

### Changed

**Repository Structure**
- Standardised all repository files to kebab-case naming convention for command-line compatibility and cross-platform consistency
- Standardised audit-governance markdown files to kebab-case
- Restructured permanent archive documentation for improved clarity and accessibility
- Consolidated blockchain verification records

**ISO 19011 Audit**
- Revised title to "Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan Implementation Using ISO 19011:2018 Guidelines"
- Revealed systematic pattern: communication outputs 100% delivered, process outputs 0-40% documented

**Version Control Policy**
- Replaced patch workflow with streamlined single-version approach
- Updated ICD-206 sourcing requirements URL
- included 19 references 

**Surveillance Data Analysis**
- Restructured section headers for improved navigation
- Enhanced Key Takeaways with international comparison

**Compensation Analysis**
- Corrected international compensation statistics: US CICP ~0.5% (~72/14,000+ claims), UK VDP ~1-3% (~600/17,000 claims)
- Corrected CDC timeline from "24-48 hours" to "days post-signal"
- Reframed comparison emphasising transparency gap: AU approval rate (10.5%) higher than US/UK but uniquely lacks published signal investigation methodologies

**FOI Systematic Review**
- Enhanced search methodology documentation
- Improved professional terminology and structure throughout
- Version updated 1.0 → 1.1

**Documentation Standards**
- Removed bold formatting from all hyperlinks throughout repository
- Maintained bold formatting only in navigation/wayfinding sections
- Updated internal documentation references throughout FAQ and primary sources
- Standardised internal document links to relative paths
- Updated Table of Contents to include new Guiding Standards section

**Reference Lists**
- Updated documenting FOI evidence sources and methodology (OSINT best practices, systematic search principles, evidence triangulation)
- Enhanced citations for international pharmacovigilance standards (ICH E2E, CIOMS) and Commonwealth accountability frameworks (PGPA Act, Archives Act, FOI Act)

**Version History Documentation**
- Streamlined version history and headers/descriptions by consolidating granular change details under major version updates while maintaining complete audit trail via commit log and archived release notes.

**Traffic Monitoring Workflow**
- Restructured CSV storage to save actual daily counts (`daily_clones`) instead of 14-day window snapshots (`total_clones`). Changed data extraction to use yesterday's single-day value (`clones_data['clones'][-2]`) rather than window total. Fixed all-time calculation from `.iloc[-1]` to `.sum()` and removed `.diff()` from averages. Added error handling, failure notifications, date to email subject, and expanded institutional domain tracking (9 categories vs 5). Distinguished "14-day window" (GitHub's rolling total) from "all-time stats" (cumulative daily tracking) in report labels.

### Fixed

**ISO 19011 Audit**
- Conformity assessment numbers: corrected to 11 partial (55%), 6 not documented (30%) to match PowerPoint Slide 9 and README verified data
- Removed "Checklist" from ISO 19011 audit link text for accuracy (document is full audit report)
- Added missing markdown link syntax to ISO 19011 audit description

**FAQ Updates**
- Footnote formatting: added superscript to footnote numbers and working bidirectional return links
- Corrected AICmr 54 citation formatting to standard legal format
- Remove peer review submission reference from limitations section (Q33)

**Documentation**
- Anchor links throughout repository to reflect new kebab-case file naming structure
- Relative paths for improved mobile app compatibility
- Markdown syntax errors in ISO 19011 methodology section

**General**
- Added Version Control Policy reference statement to version history header
- General formatting improvements, line breaks, bold emphasis, and readability enhancements throughout README and supporting documents

### Note

Core audit findings unchanged. Version 1.9.1 focuses on enhanced presentation of evidence through structured findings, output-by-output breakdown with conformity analysis, timeline visualisations, corrected international statistics with detailed comparison tables, clinical examples demonstrating information asymmetry, Sparke Helmore third-party validation, Administrative Law vs Accountability framework, Release Workflow documentation with Verification Efficiency Principle, methodological transparency enhancements including boundaries statement and Nature of This Audit clarification, repository maintenance through kebab-case standardisation and permanent archive restructuring, and formatting consistency improvements across all documentation and source verification. All changes recorded under commit messages.

**Archive:** Zenodo DOI current. Blockchain verification pending.

---

## Version 1.9 (14 January 2026)

### Added

**FOI Evidence**
- Complete FOI 4029 suite demonstrating TGA presented Strategy 2.3 methodology to Advisory Committee on Vaccines (September 2021)
- FOI 5275 (August 2024) showing TGA response that monthly incidence data for AusPAR-specified monitoring conditions "does not exist" 3.5 years post-approval
- Systematic FOI search methodology documentation across four-year investigation
- Infrastructure evidence synthesis combining FOI 5082 (documentation capability), FOI 4029 (internal Plan tracking), and "burn out" screening protocol

**Analysis Documents**
- Systematic review of six TGA COVID-19 vaccine safety reports (2021-2023) documenting zero Plan framework references across 150+ published reports
- Compensation analysis v1.0 examining FOI evidentiary asymmetry affecting Vaccine Claims Scheme applicants with verified statistics: 148 signals/57 actions, 4,962 claims lodged/522 approved, 140k+ DAEN reports
- Senate testimony reference documentation for 9 October 2025 with timestamped video link (2:30:40-2:37:00), Hansard transcript, and key exchange analysis

**Methodology**
- Version control principles section explaining detailed version history methodology aligned with ISO 19011:2018, ISO 15489-1:2016, OSINT documentation principles
- Cabinet commitment and policy framework clarification establishing three-tier accountability (Cabinet policy commitment → national framework → TGA operational implementation)
- ISO 19011 audit methodology assessment and evidence of inadequate OAIC search scope excluding advisory body containers

**Documentation**
- Abstract to main audit report
- ORCID identifier (0009-0000-1338-9578) to citation metadata
- Full document suite archived in `/reference-documents/foi-4029/`

### Changed

**Evidence Analysis**
- Enhanced OSINT description for logical flow (ISO 19011 framework first)
- Tightened audit scope distinction between routine pharmacovigilance versus enhanced monitoring framework implementation
- Streamlined audit methodology section by replacing ISO 19011 conformance self-assessment with direct conformance statement
- Refined documentary hierarchy characterisation to distinguish National Cabinet endorsement, national pharmacovigilance plan umbrella framework, and TGA operational plan

**Visual Summary**
- Fixed arithmetic error in outcome percentages (now correctly totals 100%: 15% fully documented, 55% partial, 30% not documented)
- Updated vaccine rollout to 91.2%
- Clarified evidence hierarchy as "Source Reliability" with Tier 1 annotation
- Updated Senate testimony terminology to "parliamentary privilege"

**Methodology**
- Corrected audit conduct period to October 2025 - January 2026
- Clarified evidence collection period as 2022-2026
- Enhanced repository description emphasising ISO 19011:2018 principles and falsifiable methodology

### Fixed

**Documentation**
- Removed version numbers from all filenames for maintenance simplicity
- Updated all internal cross-references for consistency
- General formatting and readability enhancements
- Checked and updated URLs

### Note

Core audit findings unchanged. Version 1.9 adds critical FOI evidence (4029, 5275), documents systematic search methodology, corrects presentation errors, and synthesises infrastructure evidence. Audit scope remains unchanged (TGA operational plan with verifiable outputs). Core finding unchanged (cannot demonstrate implementation of framework intended to deliver Cabinet's enhanced monitoring commitment).

**Archive:** Zenodo DOI updated, blockchain storage and timestamp pending.

---

## Version 1.8 (6 January 2026)

### Added

**Primary Evidence**
- Department of Health "no different" video analysis (3 February 2021) positioned against formal Cabinet commitments
- TGA email responses (18 & 22 February 2022) to direct inquiries requesting Safety Plan implementation evidence
- FOI 5082 correspondence trail
- COVID-19 vaccination statistics primary data files (XLS/PDF, 27 July 2023)
- Bitcoin blockchain timestamp proof file
- Arweave permanent storage confirmation

**Infrastructure**
- Permanent archival framework: Bitcoin blockchain timestamp proof (31 December 2025), Arweave permanent storage (1 January 2026), combined verification documentation in `/blockchain-verification/`
- Automated traffic monitoring: daily GitHub traffic data collection with email summaries (8 AM AEDT), permanent CSV storage beyond GitHub's 14-day API window, trend analysis, private repository archival (`TGA-Audit-Traffic-Data`)
- Zenodo academic archive (DOI: 10.5281/zenodo.14634063)

**Analysis**
- Public communications contradiction documentation: four-year pattern from February 2021 "no different" messaging through 2025 Senate testimony confirming "day-to-day processes" never systematically tracked
- Pre-FOI evasion pattern establishment: identical template text claiming "enhanced dramatically" and "most intense monitoring ever conducted" whilst providing zero Plan-specific documentation

### Changed

**Statistics**
- Updated vaccination coverage from 94% (October 2024) to 91.2% (October 2025)
- Updated to 68.4 million provisionally approved doses administered to 21.2 million Australians through July 2023 reporting period

**Documentation**
- Enhanced FOI 5082 significance clarification as critical comparative evidence demonstrating TGA's documentation capacity versus absence of Safety Plan implementation records
- Streamlined disclaimer section to improve clarity whilst maintaining legal protections

### Fixed

**Technical**
- Updated links and references
- Formatting consistency enhancements
- Timeline refinements
- Navigation improvements

### Archive & Verification

This release is preserved through multiple independent archival systems: GitHub (version-controlled repository with release tags), Zenodo (academic archive DOI v1.74: 10.5281/zenodo.14634063), Bitcoin Blockchain (cryptographic timestamp proof via OpenTimestamps), Arweave (permanent decentralised storage), Private Backup (automated daily traffic monitoring with historical preservation). All verification proofs available in `/blockchain-verification/` directory.

---

## Version 1.7.4 (28 December 2025)

### Changed

**Statistics**
- Updated to 68.4 million provisionally approved doses administered to 21.2 million Australians, correcting earlier conflation of total population with vaccinated individuals
- Updated vaccine recipient numbers throughout for consistency

**Compliance**
- Added comprehensive conflicts of interest declaration
- Added CC BY 4.0 licence reference
- Revised fair-dealing disclaimer in README footer clarifying scope, intent, legal basis, and good-faith public-interest purpose

**Methodology**
- Clarified ISO 19011/ANAO (ISSAI-aligned) methodology statement in README
- Added description of one-page audit methodology flowchart
- Removed outdated references to Bayesian scoring

**Documentation**
- Added direct references to ISO 19011 Management Systems Audit Checklist in README quick-start section
- Clarified description of TGA COVID-19 vaccine safety reports (weekly March 2021–June 2023, then monthly from July 2023)
- Added reference to ANAO Performance Audit Process and compliance standards (ISSAI-aligned)

### Added

**Oversight Documentation**
- OAIC MR25/01153 case number to FAQ
- Commonwealth Ombudsman complaint reference (April 2025, Ref: 2025-806374) to FAQ
- Page 13 context from Australian COVID-19 Vaccination Policy (November 2020) clarifying original "enhanced monitoring" commitments

### Fixed

**Technical**
- Corrected broken links and typos
- Minor spacing and formatting edits
- Updated COVID-19 Vaccination Policy URL

### Removed

- Obsolete `documentation-gap-analysis_v1.5.1.pdf` file (superseded by revised main audit documentation)

---

## Version 1.7.3 (22 December 2025)

### Added

**Audit Documentation**
- ISO 19011 Management Systems Audit Checklist: standalone text-based application of ISO 19011:2018 auditing standards including audit criteria, evidence hierarchy, non-conformity ratings, and overall conformity/confidence assessment
- One-page ISO 19011-based audit methodology flowchart documenting audit process (planning, evidence hierarchy, analysis, reporting)

### Changed

**Legal and Regulatory Claims**
- Refined wording around FOI, OAIC, Senate testimony, and Sparke Helmore case file ensuring all assertions are strictly evidence-based and anchored in primary sources
- Strengthened accuracy whilst preserving core findings on documentation gaps and non-conformities

### Fixed

**Documentation**
- Corrected and updated internal and external links
- Clarified section headings
- Minor edits to references and section text for accuracy and readability

---

## Version 1.7.2 (20 December 2025)

### Added

**Evidence**
- Phillips et al. (2021) peer-reviewed study documenting pre-rollout expert warnings: 17 Australian vaccine safety experts (July-October 2020) identified data linkage as "major gap," characterised surveillance systems as "parallel systems," recommended "significant enhancement" for COVID vaccines
- CDI 2021 AEFI surveillance report section clarifying it evidences intensive monitoring activity but not Safety Plan implementation or governance documentation
- Primary-sources folder with Department of Health video transcript (3 February 2021) showing public messaging contradiction: DoH stated COVID monitoring "will be no different" from routine surveillance same month TGA published 17-strategy enhanced Safety Plan
- "Public Communications vs Policy Commitments" section to README documenting day-one gap between public communications and formal Cabinet commitments

**Repository Structure**
- Analysis folder for main audit documents (documentation gap analysis, presentation slides, FOI timeline)
- Moved black-box-governance methodology to reference-documents folder
- Created primary-sources folder

### Changed

**Terminology**
- Refined wording on provisional approval and enhanced monitoring to "regulatory condition and expectation" consistent with TGA guidance

### Fixed

**Corrections**
- Corrected name of TGA official giving evidence to Senate Community Affairs Legislation Committee (9 October 2025) to Dr Daniel Dascombe in main audit report
- Minor editing, link updates, fixed typos

### Note

No changes to audit findings or evidence base.

---

## Version 1.7.1 (18 December 2025)

### Added

**Methodology**
- Explicit definition of "black box governance" integrated into methodological framing
- Commonwealth-state bilateral agreements context demonstrating formal intergovernmental governance frameworks requiring systematic TGA safety monitoring

**FAQ**
- Q32 on epistemological reasoning (deductive/abductive frameworks under incomplete evidence)
- Expanded Q35 personal statement with democratic accountability framing including formula "Transparency + Openness ⇒ Accountability ⇒ Trust"

### Changed

**Framing**
- Refined wording of government/TGA assurance statements to use accurate reported speech rather than implied verbatim quotes
- Aligned "Assurances Given to Australians" and "Why Documentation and Verification Matter" sections with audit test: existence (or absence) of systematic documentary evidence that Cabinet-endorsed "enhanced safety monitoring" commitments were implemented as traceable processes

### Fixed

**Documentation**
- Minor editorial and formatting improvements
- Corrected or updated links
- Directed readers to relevant items in /references folder

### Note

No changes to underlying evidence base or audit findings.

---

## Version 1.7.0 (17 December 2025)

### Added

**Methodology Document**
- "The Challenge of Black Box Governance for Private Citizens" addressing information asymmetry, epistemological challenges, and limited investigative powers facing citizen auditors under Australian law
- Theoretical framework (Akerlof, Hayek, Popper, Lipton, O'Neill, Stiglitz, Arrow) justifying audit scope, constraints, and reasoning approach

**Analysis**
- Enhanced UTS teaching materials analysis with full slide context (Slides 22-24) demonstrating gap between routine pharmacovigilance infrastructure presented in training and enhanced framework promised in Safety Plan

### Changed

**Framing**
- Strengthened Cabinet endorsement emphasis throughout document highlighting Safety Monitoring Plan elevation from TGA agency guidance to formal government commitment
- Established 17 numbered strategies as documented promise to Australian citizens and legal condition of provisional approval
- Refined audit scope clarifying inquiry focuses on whether Plan's 17 numbered strategies were implemented as distinct, systematically tracked processes with dedicated governance and audit trails
- Updated Executive Summary and Conclusion aligned with Cabinet commitment framing and clarified assessment scope

### Significance

This version explicitly frames audit question around verifiable implementation of Cabinet-endorsed commitments rather than engaging in routine vs enhanced definitional debate. Assessment acknowledges pharmacovigilance activities occurred; examines whether 17 strategies promised as conditions of provisional approval were implemented with systematic documentation, governance, and audit trails necessary for independent accountability.

### Note

No changes to audit findings or evidence base.

---

## Version 1.6.1 (14 December 2025)

### Added

- TGA October 2021 teaching presentation given at UTS describing Safety Monitoring Plan as "overarching framework" for enhanced monitoring
- Reference to Commonwealth-state governance framework requiring Statements of Assurance relying on systematic safety monitoring documentation

### Note

No changes to overall audit findings.

---

## Version 1.6.0 (December 2025)

### Added

- Comprehensive FAQ with "At a Glance" summary
- Navigation guide with 31 detailed Q&A
- Enhanced accessibility with quick reference sections for visual summaries
- Organised primary sources

---

## Version 1.5.1 (December 2025)

### Added

- Additional policy context documentation
- Enhanced repository navigation (Quick Start section and FAQ)

---

## Version 1.5.0 (December 2025)

### Added

**Analysis**
- Provisional approval verification gap analysis: comprehensive examination of legislation, guidance, OAIC search results, and AusPARs
- AusVaxSafety case study: detailed analysis of active surveillance performance and absence of documented TGA integration
- ANAO audit integration: situating pharmacovigilance within broader COVID-19 governance whilst clarifying scope limitations
- Structured counter-arguments: explicit responses to common objections (generic SOPs, expert committees, FOI decisions)

**Evidence Gathering**
- Systematic FOI and OAIC analysis: detailed review of TGA decisions, correspondence, and contradictions
- OAIC-directed TRIM searches: analysis of MR22/00538 results covering 531+ containers
- Structured online sweep: reproducible searches of government and partner websites for Plan-specific implementation documents outside FOI
- AusVaxSafety case study: analysis of 6.8 million survey outputs and absence of documented integration with TGA signal management
- Legislative framework analysis: review of Therapeutic Goods Act provisions and TGA guidance on provisional approval verification

### Changed

**Methodology**
- Stricter evidence hierarchy: recalculated implementation ratings reducing "fully implemented" findings from 5 to 3
- Refined recommendations: reordered and strengthened reform priorities (governance, records management, independent audit)

---

## Version 1.0 (27 November 2025)

### Added

- Initial publication

[↑ Back to top](#table-of-contents)
