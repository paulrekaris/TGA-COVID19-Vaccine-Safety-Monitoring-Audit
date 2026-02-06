# Version History

**Version Control Policy:** This audit maintains detailed version history following ISO 19011:2018 continuous improvement, ISO 15489-1:2016 records management, Keep a Changelog methodology, OSINT documentation standards, and research integrity principles. See [Version Control Policy](version-control-policy.md) for complete methodology.

---

## Version 1.9.1 (6 February 2026)

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
- Scale and context section after Key Findings (68.4M doses under provisional approval, 94% of rollout)

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
- Total 19 references with UK spelling throughout

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

**FAQ**
- Footnote formatting: added superscript to footnote numbers and working bidirectional return links
- Corrected AICmr 54 citation formatting to standard legal format

**Documentation**
- Anchor links throughout repository to reflect new kebab-case file naming structure
- Relative paths for improved mobile app compatibility
- Markdown syntax errors in ISO 19011 methodology section

**General**
- Added Version Control Policy reference statement to version history header
- General formatting improvements, line breaks, bold emphasis, and readability enhancements throughout README and supporting documents

### Note

Core audit findings unchanged. Version 1.9.1 focuses on enhanced presentation of evidence through structured findings, output-by-output breakdown with conformity analysis, timeline visualisations, corrected international statistics with detailed comparison tables, clinical examples demonstrating information asymmetry, Sparke Helmore third-party validation, Administrative Law vs Accountability framework, Release Workflow documentation with Verification Efficiency Principle, methodological transparency enhancements including boundaries statement and Nature of This Audit clarification, repository maintenance through kebab-case standardisation and permanent archive restructuring, and formatting consistency improvements across all documentation and source verification. All changes recorded under commit messages.

**Archive:** Zenodo DOI and blockchain verification current.

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
