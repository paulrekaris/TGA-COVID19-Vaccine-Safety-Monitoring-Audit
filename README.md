<meta name="google-site-verification" content="Apib7-x98H0j5cPqHWwSMm6dNU4GmODRoqxLiDzdx9I" />

# Documentation Gap Analysis: Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan

[![Permanent Archive](https://img.shields.io/static/v1?label=Permanent+Archive&message=Multi+Layer+Verification&color=2D6F4D)](blockchain-and-archival-verification/README.md) [![NLA](https://img.shields.io/static/v1?label=NLA&message=Web+Archive&color=2D6F4D&labelColor=512B58)](https://webarchive.nla.gov.au/tep/221557)

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17731054-blue)](https://doi.org/10.5281/zenodo.17731054) [![Harvard Dataverse](https://img.shields.io/badge/Harvard%20Dataverse-10.7910%2FDVN%2FBDKZQJ-A51C30?labelColor=A51C30)](https://doi.org/10.7910/DVN/BDKZQJ) [![SSRN](https://img.shields.io/badge/SSRN-6333058-0a4d8c?labelColor=0a4d8c)](https://ssrn.com/abstract=6333058) [![SocArXiv](https://img.shields.io/badge/SocArXiv-10.31235%2Fosf.io%2Fsb4gz-C0392B?labelColor=C0392B)](https://osf.io/preprints/socarxiv/sb4gz) [![Mendeley Data](https://img.shields.io/badge/Mendeley%20Data-10.17632%2Fy5wmt6f8j9-000000?labelColor=000000&color=000000)](https://doi.org/10.17632/y5wmt6f8j9) 

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--1338--9578-green.svg)](https://orcid.org/0009-0000-1338-9578) [![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

[![Version](https://img.shields.io/static/v1?label=Version&message=v1.9.4&color=blue)](audit-governance/version-history.md) [![Download ZIP](https://img.shields.io/badge/⬇️%20Download%20Latest%20ZIP%20File-blue?style=flat)](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/archive/refs/heads/main.zip) [![GitHub last commit](https://img.shields.io/github/last-commit/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit)](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/commits/main)

## Quick Start

**New to this audit? Start here:**

- [Audit Overview](https://paulrekaris.github.io/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/) – Start here: a clear, non-technical overview of the audit and its findings.

- [How to Navigate This Audit](FAQ.md)

- [Frequently Asked Questions (FAQ)](FAQ.md#frequently-asked-questions---quick-index) – Orientation, methodology, limitations, and how to verify or challenge the findings.

- [Visual Summary: One-Page Audit Methodology Flowchart](analysis/tga-audit-one-page-flowchart.pdf) – Visual overview of the audit process, evidence hierarchy, and key findings.

- [Open Review Architecture](audit-governance/open-review-architecture.md) — How this audit achieves accountability through public, forkable, permanently archived methodology in place of traditional closed peer review.

- [Audit Summary Presentation](analysis/tga-safety-plan-audit.pdf) – Slide-style overview of key findings and documentation gaps.

- [Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf) – Primary, self-contained report with fully cited references, primary source 
  materials, findings, research methodology, and implementation status by Safety Plan objective.

- [ISO 19011 Management Systems Audit](analysis/ISO-19011-conformity-assessment-checklist.md) – Independent conformity assessment of TGA's COVID-19 Vaccine Safety Monitoring Plan implementation using ISO 19011:2018 guidelines,  audit standards, and four-tier evidence hierarchy. Documents 7 major non-conformities and overall NON-CONFORMING rating.

- [Surveillance Data Analysis](analysis/surveillance-analysis.md) – Systematic analysis of a sample of representative TGA COVID-19 vaccine safety reports (2021-2023) documenting zero Plan framework references across 150+ published reports.

- [Verify the Findings](analysis/output-assessment-evidence-matrix.xlsx) – Every classification is reproducible directly from the dataset. Open the file, go to the Evidence Matrix sheet (19 rows, one per Plan output), filter the `Status` column to see classifications by output. Full data paper: [SSRN 10.2139/ssrn.6610438](https://doi.org/10.2139/ssrn.6610438). See the [Dataset Codebook](analysis/dataset-codebook.md) and [Replication README](analysis/replication-readme.md) for variable definitions and replication code.

- [Permanent Archive](blockchain-and-archival-verification/) | [National Library of Australia: NED476889S65171](https://nla.gov.au/nla.obj-4238332288) | [Zenodo DOI: 10.5281/zenodo.17731054](https://doi.org/10.5281/zenodo.17731054) | [Harvard Dataverse: 10.7910/DVN/BDKZQJ](https://doi.org/10.7910/DVN/BDKZQJ) | [SSRN: 6333058](https://ssrn.com/abstract=6333058) | [SocArXiv: 10.31235/osf.io/sb4gz](https://osf.io/preprints/socarxiv/sb4gz) | [Mendeley Data: 10.17632/y5wmt6f8j9](https://doi.org/10.17632/y5wmt6f8j9) | [Bitcoin Timestamped 29 March 2026](blockchain-and-archival-verification/bitcoin-timestamp-verification-2026-03-29.png) | [Arweave Blockchain](https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps) | [Internet Archive](https://archive.org/details/tga-covid-19-vaccine-safety-monitoring-audit-v-1.9.3)

This README contains the narrative executive summary and overview. Key findings and detailed audit results, including references, are in the [Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf)

## Official Archival Preservation

[![National Library of Australia](https://img.shields.io/badge/National%20Library%20of%20Australia-Collection%20Development%20Policy-000000?labelColor=000000&style=flat-square)](https://www.library.gov.au/visit/about-us/corporate-information/collection-policies-and-plans/collection-development-policy)

This repository has been accepted for preservation by the National Library of Australia and is archived in the Australian Web Archive (AWA), the official national web archive of Australia. Inclusion reflects the Library's assessment that the material has ongoing research and documentary value, consistent with the [NLA Collection Development Policy](https://www.library.gov.au/visit/about-us/corporate-information/collection-policies-and-plans/collection-development-policy). Archival capture ensures long-term public access to the evidence, methodology, and findings independent of third-party platforms.

[View preserved AWA snapshot](https://webarchive.nla.gov.au/tep/221557)

## Table of Contents

- [Purpose](#purpose)
- [Guiding Standards](#guiding-standards)
- [Important Distinction: Routine vs Enhanced Monitoring](#important-distinction-routine-vs-enhanced-monitoring)
- [Australian Senate Citation](#australian-senate-citation)
- [Publications](#publications)
- [Executive Summary](#executive-summary)
- [Key Findings](#key-findings)
- [The Accountability Standard](#the-accountability-standard)
  - [FOI Compliance vs Governance Requirements](#foi-compliance-vs-governance-requirements)
- [The Evidence Base](#the-evidence-base)
- [The Investigation: Four Years of FOI Requests](#the-investigation-four-years-of-foi-requests)
  - [Timeline of Contradictions](#timeline-of-contradictions)
- [The Critical Question](#the-critical-question)
- [What This Audit Found](#what-this-audit-found)
  - [Implementation Status by the Numbers](#implementation-status-by-the-numbers)
- [Four Critical Documentation Gaps](#four-critical-documentation-gaps)
  - [Gap 1: Signal Investigation Audit Trail](#gap-1-signal-investigation-audit-trail)
  - [Gap 2: Enhanced Monitoring Verification at Provisional Approval](#gap-2-enhanced-monitoring-verification-at-provisional-approval)
  - [Gap 3: Enhanced Monitoring Framework Integration](#gap-3-enhanced-monitoring-framework-integration)
  - [Gap 4: Governance and Performance Measurement](#gap-4-governance-and-performance-measurement)
- [Public Communications vs Policy Commitments](#public-communications-vs-policy-commitments)
  - [The Public Message: "No Different"](#the-public-message-no-different)
  - [The Policy Commitment: "Enhanced Monitoring"](#the-policy-commitment-enhanced-monitoring)
  - [The Contradiction](#the-contradiction)
  - [Testing the Contradiction: 2022 Direct Inquiries](#testing-the-contradiction-2022-direct-inquiries)
  - [Resolution: 2025 Senate Testimony](#resolution-2025-senate-testimony)
  - [From "Molecule to Market" to Enhanced Safety Monitoring: The Teaching-Practice Gap](#from-molecule-to-market-to-enhanced-safety-monitoring-the-teaching-practice-gap)
- [Official 2021 AEFI Surveillance Report](#official-2021-aefi-surveillance-report)
- [Supporting Peer-Reviewed Literature of Systemic Gaps](#supporting-peer-reviewed-literature-of-systemic-gaps)
- [What This Audit Examines: Enhanced Safety Monitoring](#what-this-audit-examines-enhanced-safety-monitoring)
  - [Enhanced Monitoring as Defined by the Plan](#enhanced-monitoring-as-defined-by-the-plan)
  - [The Audit Question](#the-audit-question)
  - [Why This Matters](#why-this-matters)
- [The Challenge of Black Box Governance for Private Citizens](#the-challenge-of-black-box-governance-for-private-citizens)
- [ Audit History and the Pharmacovigilance Gap](#-audit-history-and-the-pharmacovigilance-gap)
- [Oversight and Accountability](#oversight-and-accountability)
  - [Investigation Timeline](TIMELINE.md)
- [The Call for Investigation](#the-call-for-investigation)
- [Methodology and Evidence Base](#methodology-and-evidence-base)
  - [Assessment Framework](#assessment-framework)
  - [Assessment Output Methodology](#assessment-output-methodology)
  - [Rating Criteria](#rating-criteria)
- [Evidence Sources](#evidence-sources)
- [Documentary Evidence of TGA Documentation Capacity](#documentary-evidence-of-tga-documentation-capacity)
  - [FOI 5082: TGA Vaccine Pharmacovigilance System](#foi-5082-tga-vaccine-pharmacovigilance-system)
- [Limitations and Falsifiability](#limitations-and-falsifiability)
  - [Scope](#scope)
  - [Meaning of Documentation Gaps](#meaning-of-documentation-gaps)
  - [Why the Gaps are Significant](#why-the-gaps-are-significant)
  - [Falsifiability](#falsifiability)
  - [Alternative explanations for absent records](#alternative-explanations-for-absent-records)
- [What's in This Repository](#whats-in-this-repository)
  - [Main Assessment Report](#main-assessment-report)
  - [Supporting Documentation](#supporting-documentation)
- [Open Access Framework](#open-access-framework)
- [Licence and Citation](#licence-and-citation)
  - [Licence](#licence)
  - [Citation](#citation)
- [Disclaimer and Declaration](#disclaimer-and-declaration)
  - [Nature of This Audit](#nature-of-this-audit)
  - [Scope and Intent](#scope-and-intent)
  - [Scope of Assessment](#scope-of-assessment)
  - [Regulatory Framework and Analytical Scope](#regulatory-framework-and-analytical-scope)
  - [Peer-Review Status](#peer-review-status)
  - [Accuracy and Good Faith](#accuracy-and-good-faith)
  - [Living Document](#living-document)
  - [Conflicts of Interest](#conflicts-of-interest)
  - [Legal Disclaimer](#legal-disclaimer)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)
- [Version History](#version-history)
- [Permanent Archive](#permanent-archive)


## Purpose

This repository documents an independent audit of the TGA's COVID-19 Vaccine Safety Monitoring Plan (February 2021), assessing evidence for 19 specified enhanced-pharmacovigilance outputs — 17 enhanced-pharmacovigilance strategies plus two governance outputs — over four years (2021-2026). 

During Australia's largest medical intervention in history, 68.4 million COVID-19 vaccine doses were administered under provisional approval. This analysis addresses a single question: whether the implementation of the COVID-19 Vaccine Safety Monitoring Plan can now be independently verified through records, as required for an enhanced monitoring framework relied upon for provisional approval.

Enhanced monitoring was presented in the relevant policy and regulatory materials as the compensating safeguard associated with provisional approval. The TGA's February 2021 Safety Plan set out that framework, and this audit examines whether it was implemented and documented in ways that enable independent verification of those commitments.

**Intended for:** Legal evidence, parliamentary inquiry, FOI appeals, accountability audits, research, and historical public record.

**Methodology:** Evidence-based analysis using publicly available material, lawful FOI processes, and audit principles from ISO 19011:2018 and  guidance, benchmarked against the TGA pharmacovigilance framework and international pharmacovigilance standards (ICH E2E, CIOMS).

## Guiding Standards

**ISO 19011:2018** — Guidelines for auditing management systems; provides the methodological framework for evidence-based, systematic, independent assessment of documented implementation against stated commitments.

**ISO 15489-1:2016** - Information and documentation — Records management; provides the framework for transparency, integrity, accountability, and availability of records. Applied through Git version control, structured changelogs, blockchain timestamping, and multi-layer permanent archiving ensuring the audit trail cannot be retrospectively modified.

**ANAO Performance Audit Standards** — Performance assessment against published plans and criteria, consistent with ANAO performance audit methodology and ISSAI standards. 

**OSINT Methodology** - Systematic evidence collection from publicly accessible sources following established open-source intelligence principles. 

**Open Access** - CC BY 4.0 licence; permanent archives via Zenodo DOIs, Harvard Dataverse, Mendeley Data, GitHub, and Arweave.

> **Provenance and Authenticity Statement**: This audit preserves a verifiable record of what could be independently established about the implementation of Australia's COVID-19 vaccine safety monitoring framework at a specific point in time, using only public accountability mechanisms. To ensure the integrity and historical persistence of that record, the audit's core artefacts and findings have been cryptographically timestamped and anchored to a public blockchain. This provides an immutable reference point, allowing future reviewers—including courts, inquiries, and researchers—to determine what evidence was publicly available, in what form, and at what time, independent of subsequent institutional reinterpretation, record reconstruction or changes to public accessibility.
>

## Important Distinction: Routine vs Enhanced Monitoring

This audit examines whether enhanced monitoring commitments were implemented and documented in a verifiable way. Routine pharmacovigilance activities are acknowledged in the record.

**The audit asks:** Can TGA demonstrate that COVID-19 monitoring was "enhanced" beyond routine processes, as expected for provisional approval and promised in the February 2021 Plan?

**The finding:** No verifiable documentation of Plan implementation has been produced over 4 years despite extensive FOI requests and OAIC review.

> **Why this matters:** The existence of routine pharmacovigilance activities does not, by itself, constitute evidence that the enhanced monitoring framework described in the Plan was implemented. Routine pharmacovigilance refers to standing surveillance activities that apply to all registered medicines. The COVID-19 Vaccine Safety Monitoring Plan described enhanced monitoring activities tied to provisional approval, including defined outputs, integration mechanisms, and governance expectations beyond routine processes.


## Australian Senate Citation

[![Hansard](https://img.shields.io/badge/Hansard-Senate%2024%2F03%2F2026-913831?labelColor=913831&style=flat-square)](https://www.aph.gov.au/Parliamentary_Business/Hansard/Hansard_Display?bid=chamber%2Fhansards%2F29212%2F&sid=0003)

On 24 March 2026, Senator Malcolm Roberts cited this audit by name in the Senate, referencing key findings from the SSRN publication ([doi.org/10.2139/ssrn.6333058](https://doi.org/10.2139/ssrn.6333058)), including the absence of implementation records, OAIC confirmation, Senate testimony that monitoring was never systematically tracked, and the ISO 19011 conformity assessment results. The audit's findings are now part of the permanent official parliamentary record of Australia. 

[Watch the Australian Senate speech](https://www.youtube.com/live/lXSeEoT-32g?t=30900) | [Read the Senate Analysis](primary-sources/senate-2026-03-24/README.md)

## Publications

This audit is part of a broader research programme on independent regulatory accountability. The audit report itself is published as a preprint on SSRN, with companion materials archived across multiple preservation platforms. Two papers from this research program are currently under academic peer review at international journals.

For the complete list of publications, preprints, and research outputs related to this work, see [PUBLICATIONS.md](PUBLICATIONS.md).

## Executive Summary

On 13 November 2020, National Cabinet endorsed the Australian COVID‑19 Vaccination Policy, which committed the Commonwealth to active and comprehensive post‑market safety monitoring of COVID‑19 vaccines, with TGA responsible for implementing appropriate pharmacovigilance arrangements for the rollout. In February 2021, the TGA’s COVID‑19 Vaccine Safety Monitoring Plan operationalised this national pharmacovigilance framework, specifying 19 outputs across 17 numbered strategies spanning AEFI collection, signal detection, regulatory action, communication and collaboration. AusVaxSafety, coordinated by NCIRS and funded by the Australian Government, subsequently described its large‑scale active surveillance program for COVID‑19 vaccines as operating as part of this national pharmacovigilance plan led by the TGA and the Australian Government, thereby positioning active surveillance as a core delivery mechanism within the TGA‑led safety‑monitoring framework.  

The Commonwealth signed formal bilateral agreements with Australian states and territories (including Victoria, signed 19 February 2021) that established governance frameworks requiring systematic reporting of vaccine safety and surveillance data through agreed channels and specified protocols, including adverse event monitoring via the TGA. These agreements operationalised the Australian COVID‑19 Vaccination Policy (endorsed by National Cabinet in November 2020), which anticipated enhanced TGA‑led pharmacovigilance and was given operational effect through the TGA’s February 2021 COVID‑19 Vaccine Safety Monitoring Plan. Together, this policy and intergovernmental framework created an expectation that the Plan’s enhanced monitoring strategies would be delivered and documented across jurisdictions. 

Between February 2021 and late June 2023, more than 68.4 million COVID‑19 vaccine doses (approximately 91% of the total rollout as at October 2025) were administered to 21.2 million Australians under provisional registration on the ARTG — Australia’s largest deployment of provisionally approved medicines.

Provisional approval under the Therapeutic Goods Act 1989 permits time‑limited registration on the basis of preliminary clinical data where usual pre‑market evidentiary requirements cannot be met in time for a public‑health emergency, and TGA’s provisional‑registration guidance states that such medicines are subject to enhanced post‑market surveillance, additional pharmacovigilance conditions and prioritisation within its monitoring and compliance framework, expectations that were consolidated in the February 2021 Safety Monitoring Plan.

This independent audit provides a systematic assessment of whether the Plan's 17 numbered strategies were implemented as distinct, documentable processes that can be verified through records. After four years of Freedom of Information (FOI) requests and structured evidence review, the findings reveal major documentation gaps that prevent verification of enhanced‑monitoring implementation and of delivery of the Plan's enhanced-monitoring commitments.

National Cabinet endorsed the *Australian COVID-19 Vaccination Policy* in November 2020, which established enhanced monitoring commitments as a key safeguard accompanying Australia's COVID-19 vaccine rollout. The central accountability question is whether the TGA can demonstrate, through available documentation, systematic implementation of the enhanced, TGA-led safety monitoring framework. The policy is available here: [Australian COVID-19 Vaccination Policy](https://www.health.gov.au/sites/default/files/documents/2020/12/covid-19-vaccination-australian-covid-19-vaccination-policy.pdf).

> **Central problem**: TGA cannot demonstrate, on the available documentary record, that it systematically implemented the enhanced, TGA-led safety monitoring framework set out in the Cabinet-endorsed Australian COVID-19 Vaccination Policy, raising fundamental questions about regulatory accountability during Australia's largest medical intervention.


## Key Findings

> ### After four years of systematic investigation, this audit finds:
> 
> #### 1. No systematic implementation documentation  
> TGA's OAIC-directed searches in September 2024 across more than 531 TRIM containers identified no implementation records for the February 2021 COVID-19 Vaccine Safety Monitoring Plan, a position confirmed by OAIC Decision [2025] AICmr 54. 
> 
> #### 2. "Day-to-day processes" instead of enhanced monitoring  
> Senate testimony in October 2025 confirmed that implementation of the Plan was never systematically tracked, and that COVID-19 vaccine safety monitoring was managed through routine “day-to-day processes” — TGA’s own characterisation indicating the framework was not operationalised as distinct from routine surveillance, contradicting the enhanced monitoring commitment set out in the Cabinet-endorsed policy and the February 2021 Plan for 68.4 million doses.
> 
> #### 3. Only 16% of Plan outputs have complete implementation documentation  
> Only 3 of 19 audited Plan outputs have complete implementation documentation; 10 are partially documented, and 6 have no documentation identified despite systematic searches.  
> 
> #### 4. Signal investigations lack audit trails  
> TGA investigated 148 safety signals and took 57 regulatory actions (Senate QON 559 subsequently updated the signal count to 150, with 93 signals having no publicly documented decision rationale).
>  
> 
> #### 5. AusVaxSafety integration cannot be demonstrated
> Strategy 2.4 of the Plan explicitly committed to AusVaxSafety active surveillance integration. AusVaxSafety conducted 6.8 million SMS surveys capturing approximately 3 million adverse events and described its program as operating "as part of" the TGA-led national pharmacovigilance plan. No coordination protocols, data integration frameworks, or audit trails showing how these active surveillance findings informed TGA signal detection or regulatory decisions have been located through four years of FOI requests, OAIC-directed searches, or systematic review of published TGA material. TGA's OAIC-directed searches omitted "AusVaxSafety" as a search term entirely — a significant methodological gap given its explicit role in the Plan.
>
> #### 6. Provisional approval verification gap  
> No documentation demonstrates that the Safety Monitoring Plan's enhanced monitoring commitments were verified before provisionally approved COVID-19 vaccines transitioned to full registration, leaving the evidentiary basis for those transitions impossible to independently verify.
>
> #### 7. Detailed conformity assessment: 0% implementation for core monitoring
> ISO 19011 conformity assessment reveals systematic implementation failure: Objective 2 (Signal Detection) achieved 0% full implementation across 8 outputs, Governance achieved 0% across 2 outputs [View detailed output-by-output breakdown](analysis/ISO-19011-conformity-assessment-checklist.md#output-by-output-breakdown) showing evidence basis for all 19 audited Plan outputs.
>
> #### 8. Safety Monitoring Plan did not meet auditability standards
> The February 2021 Plan did not align with ISO 19011:2018 auditability principles or ANAO performance audit standards. It lacked numbered outputs and an implementation framework, conflating strategies with deliverables — making systematic tracking impossible from the outset. Analysis identified approximately 36 discrete outputs across five objectives; the audit maintained a conservative scope of 19 specified outputs for methodological rigour and defensibility. A plan published as a formal Cabinet-endorsed commitment to enhanced monitoring for 68.4 million provisionally approved doses should have been designed to be audited. That the Plan was never structured to support systematic tracking is itself a finding — the absence of an implementation trail cannot be attributed solely to implementation failure when the framework was not designed to be audited.


## The Accountability Standard

This work exists to ensure that future reviews of Australia's COVID-19 regulatory response are grounded in what was demonstrably recorded at the time, not solely in institutional recollection or post-hoc explanation.

As of August 2026, no Commonwealth oversight body has initiated a dedicated performance audit. This raises fundamental questions about the standard of accountability that should apply.


### FOI Compliance vs Governance Requirements

OAIC Decision [2025] AICmr 54 demonstrates an important distinction in regulatory oversight: procedural compliance does not necessarily establish substantive accountability.

TGA's comprehensive search documentation satisfied FOI Act requirements under s24A, demonstrating proper record-keeping of the search process itself. Independent legal analysis confirmed this procedural compliance.

However, what those thorough searches established—that systematic Plan implementation records "cannot be found or do not exist"—raises a separate accountability question: whether the enhanced monitoring framework required for provisional approval was implemented as designed.

Procedural correctness and technical compliance in FOI administration and substantive delivery of Cabinet-endorsed policy commitments are distinct accountability standards, both necessary for transparent governance.

> In a cabinet-approved enhanced monitoring framework under provisional approval governing population-scale medical intervention, monitoring without defined metrics, tracking and records is indistinguishable from no monitoring at all. What cannot be verified cannot be proven to have existed—regardless of assurances provided to Australians by Cabinet and formal testimony given to the Senate by senior TGA officials four years later. 

## The Evidence Base

This finding is based on official determinations, not interpretation:

**TGA's September 2024 submission to OAIC (MR22/00538)** documented searches across more than 531 TRIM containers using eight search terms, locating no records TGA classified as Plan implementation documentation despite reviewing extensive routine pharmacovigilance material. In paragraph 15 of [the Department's formal submission](primary-sources/oaic/MR22-00538/tga-submission-oaic-mr22-00538-sept-2024-redacted.pdf), the Department states that "there is unlikely to be a set of discrete documents evidencing the TGA's preparedness (because no audit of preparedness was undertaken)," while acknowledging in the same passage that documents evidencing changes to procedures or the actual collection and investigation of adverse-event reports could relate to preparedness, in which case "there would likely be a large volume of relevant documents." A TGA search officer's contemporaneous record, in Attachment A, page 29, states: "I have been unable to find any relevant documents in this search. If you have any other suggestions for search terms, I will conduct further searches as necessary." These statements, from formal OAIC proceedings and operational search records, bear on the audit's central finding from within TGA's own documentary record.

**Office of the Australian Information Commissioner (OAIC) Decision [2025] AICmr 54** reviewed this evidence and found the Department took "all reasonable steps" under s24A of the FOI Act, concluding "documents cannot be found or do not exist." Independent legal analysis by Sparke Helmore (11 May 2025) ([case note](reference-documents/sparke-helmore-auq-dhac-foi-case-note.pdf)) confirmed the administrative law finding.

 **Senate testimony (9 October 2025):** TGA senior officials described the Plan's "five key themes" as "essentially describ[ing] our day-to-day processes"—characterising monitoring as routine operations rather than a distinct enhanced framework.

**Senate QON 559 (SQ25-001584) — TGA's Formal Answer to Plan Compliance**: TGA's written answer to the direct question "How has the TGA complied with the COVID-19 Vaccine Safety Monitoring Plan?" — submitted on the parliamentary record in response to follow-up questions arising from the [9 October 2025 Senate hearing](https://www.aph.gov.au/Parliamentary_Business/Hansard/Hansard_Display?bid=committees/estimate/29000/&sid=0003) — describes activities against all five Plan strategies but produces no documentary evidence of systematic implementation. 93 of 150 investigated signals reported in the Senate QON have no publicly documented decision rationale. See [QON 559 Gap Analysis](analysis/tga-senate-qon-559-gap-analysis-2026.md).

**Search Methodology Note:** TGA's OAIC-directed searches (September 2024) employed only 8 generic document-title terms ("Implementation of Plan", "Audit Report"), missing output-specific terminology (signal detection, AusVaxSafety coordination, ICMRA sharing) and pharmacovigilance vocabulary (AEFI escalation, performance metrics, risk management). TGA’s OAIC-directed searches omitted “AusVaxSafety” entirely, despite Strategy 2.4 making it the Plan’s named active-surveillance integration partner. This audit employed 
14 strategic terms targeting specific Plan outputs and pharmacovigilance processes. [See detailed search methodology comparison](analysis/search-methodology-comparison.md)

The documentation gap is established as a matter of official record, confirmed through both administrative law proceedings and parliamentary testimony.

Detailed methodology, evidence hierarchies, and output-by-output assessments are in the [Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf) and [Evidence Matrix](analysis/output-assessment-evidence-matrix.xlsx).

## The Investigation: Four Years of FOI Requests

This audit emerged from a four‑year FOI‑based investigation into TGA’s implementation of its published safety‑monitoring commitments. The investigation revealed a troubling pattern of changing institutional positions.

### Timeline of Contradictions


- **February 2022** - TGA claims requested implementation documents “do not exist” [FOI 3643](primary-sources/foi/foi-3643/foi-3643-decision-letter-redacted.pdf)

- **February 2022** - TGA acknowledges that “ample documentation” exists, but does not identify Plan‑specific implementation records.

- **2022–2023** - TGA organises extensive vaccine‑safety documentation for Information Commissioner review.

- **September 2024** - Under direction from the Office of the Australian Information Commissioner (OAIC reference MR22/00538), TGA searches more than 531 TRIM containers, and demonstrates capability to classify and organise **2,218+ pages** of vaccine‑safety documentation by Safety Plan objectives.

- **11 May 2025** - Sparke Helmore case note provides third-party legal analysis of [2025] AICmr 54, noting TGA's search documentation illustrated "persons who were consulted and undertook searches, date the searches were undertaken, locations searched, search terms used, outcomes of the searches undertaken, [and] reasons as to why no relevant documents have been found." The analysis emphasises maintaining detailed search records as FOI best practice, confirming through independent legal review that comprehensive searches established systematic Plan implementation records "cannot be found or do not exist" as a matter of administrative law.

- **June 2025** - TGA identifies **399 Plan‑aligned documents** across 12 document categories but refuses to process them for citizen access, claiming that classification by Plan objectives requires “subjective interpretation”, despite having successfully classified 2,218+ pages nine months earlier (FOI 25‑0166).

- **9 October 2025** – Senate Community Affairs Legislation Committee  

  TGA officials testify that:
  
  - Plan implementation was **never systematically tracked** by Plan objectives.  
  - Monitoring was managed through “day‑to‑day processes”, not a distinct enhanced framework.  
  - Producing documents by Plan objectives would involve “some difficulty” and a “vast volume of documents”.  
  - 148 safety signals were investigated and 57 regulatory actions taken – yet **no documentation links specific signals to specific actions**.

A second IC review (MR25/01153) challenging TGA’s practical refusal decision (FOI 25-0166, April 2025) was lodged in June 2025. A decision is pending as of June 2026.

All key documentation and evidence is provided in the [primary sources](primary-sources/) folder.

## The Critical Question

If TGA can organise 2,218+ pages by Plan objectives for the Information Commissioner, why can it not provide equivalent documentation to citizens after four years of requests?

Each plausible explanation points to a serious failure in implementation, documentation, or both:

- Enhanced monitoring was not conducted as a structured programme with the required documentation.  
- Records are insufficiently organised to retrieve, despite demonstrated classification capability.  
- Documents were never systematically maintained as required by international pharmacovigilance and public‑sector record‑keeping standards.  
- Verification of the Safety Monitoring Plan's enhanced monitoring commitments was not documented before transitions to full registration.


## What This Audit Found

### Implementation Status by the Numbers

The assessment systematically evaluated all 19 plan outputs against publicly available evidence, using ISO 19011:2018 audit principles and ANAO performance audit standards. [^plan-scope]

**Overall implementation**          

- **16% Fully implemented (3/19 outputs)** – mainly public‑communication activities with clear documentation including publication of more than 150 weekly COVID‑19 vaccine safety reports.
- **53% Partially implemented/undocumented (10/19 outputs)** – activities appear to have occurred, but systematic implementation and governance cannot be verified.  
- **31% Not documented (6/19 outputs)** – no evidence identified in public material or FOI/OAIC processes.

**Detailed breakdown by objective:** [View complete conformity assessment](analysis/ISO-19011-conformity-assessment-checklist.md#output-by-output-breakdown) showing Objective 2 (Signal Detection) at 0% fully implemented across 8 outputs and Governance at 0% documented across 2 outputs.


## Four Critical Documentation Gaps


### Gap 1: Signal Investigation Audit Trail


**What TGA reported**

- 150 safety signals investigated (148 per Senate testimony, 9 October 2025; updated to 150 in Senate QON 559).  
- 57 regulatory or consumer‑information actions taken, e.g. Product Information warnings and safety alerts (Senate testimony, 9 October 2025).

**What is missing**

- No published documentation linking individual signals to specific actions.  
- No documented investigation protocols applied to each signal.  
- No decision‑making criteria explaining why 57 signals led to actions while 93 did not.  
- No signal‑by‑signal audit trails enabling independent scrutiny.

**Why this matters**

International pharmacovigilance standards adopted or referenced by TGA (ICH E2E, CIOMS) require **traceable audit trails** from signal detection through assessment to regulatory decision. Without these trails:

- The enhanced monitoring framework cannot be verified.  
- Compliance with the Plan's enhanced monitoring commitments during the provisional‑approval period cannot be demonstrated.  
- Regulatory decision‑making remains opaque despite significant public‑health implications.
- TGA's FOI refusals for signal investigation documentation—despite Senate testimony confirming 'ample documentation' exists—withhold population-level evidence that could assist treating doctors in forming evidence-based causation opinions for Vaccine Claims Scheme applications. See [Compensation Analysis](analysis/compensation-analysis.md) for details. 


### Gap 2: Enhanced Monitoring Verification at Provisional Approval 


**What was required**

- Enhanced post-market monitoring, as set out in the February 2021 Safety Monitoring Plan, was the stated basis on which provisional approval proceeded. TGA guidance requires documented evidence to support verification decisions before extensions and transition to full registration.

**What was found**

- OAIC‑directed TRIM searches (MR22/00538, September 2024) across **531+ containers** using eight Plan‑aligned search terms identified **zero** documents demonstrating verification that enhanced‑monitoring comitmments were satisfied before Comirnaty (July 2023) or Spikevax (April 2023) transitioned to full registration.  
- Australian Public Assessment Reports (AusPARs) and TGA media releases covering these transitions contain **no evaluation against the Safety Monitoring Plan** and no Plan‑level verification records.
- Third-party verification of this gap is provided by [FOI 5275](primary-sources/foi/foi-5275-redacted.pdf) (August 2024) (secured by this auditor under FOI 26-2581, decided February 2026) where a separate applicant sought monthly incidence data for AusPAR-specified monitoring conditions. TGA responded that such documents "do not exist." This confirms condition-specific incidence data is inaccessible 3.5 years post-approval, consistent with the absence of Strategy 2.3 AIR-denominator implementation documented in this audit.

**Why this matters**

Without documented verification:

- Delivery of the Plan's enhanced-monitoring commitments for 68.4 million doses cannot be confirmed.
- The integrity of the provisional‑approval framework – which relies on enhanced, documented post‑market monitoring – is called into question.


### Gap 3: Enhanced Monitoring Framework Integration


**What operated**

- AusVaxSafety conducted around **6.8 million** vaccine‑safety surveys.  
- TGA investigated **150** safety signals and took **57** regulatory actions.  
- More than **150** weekly COVID‑19 vaccine safety reports were published.

**What is missing**

- Documentation showing systematic integration of these activities into the enhanced monitoring framework defined in the Plan.  
- Coordination protocols or data‑flow documentation linking AusVaxSafety outputs to TGA signal investigations.  
- Evidence that enhanced processes were distinguished from routine “day‑to‑day” pharmacovigilance and tracked against Plan objectives.
- Systematic analysis of 150+ safety reports found zero Plan framework references despite [FOI 4029-03](primary-sources/foi/foi-4029/foi-4029-03.pdf) proving TGA presented Strategy 2.3 methodology to Advisory Committee on Vaccines (September 2021). Complete [FOI 4029 suite](primary-sources/foi/foi-4029) available in reference documents.

**Why this matters**

Provisional approval is designed around **enhanced monitoring** distinct from business‑as‑usual surveillance. If monitoring cannot be distinguished, documented and verified as enhanced, the regulatory safeguard justifying reduced pre‑market evidence is undermined.

### Gap 4: Governance and Performance Measurement


**What was promised**

- The February 2021 Plan referred to review, evaluation and governance.  
- TGA correspondence (February 2022) stated that implementation would be reviewed and lessons identified.

**What was found**

- No documentation of Plan‑level governance mechanisms, oversight structures or performance‑measurement systems.  
- No implementation reviews or evaluations located in public sources, FOI releases or OAIC‑directed searches.  
- TGA’s 2022‑23 and 2023‑24 annual/performance reports contain **no reference to the Plan**, despite 68.4 million provisionally approved doses being administered.

**Why this matters**

Without governance and performance‑measurement records:

- There is no way to verify that enhanced‑monitoring objectives were achieved.  
- Oversight bodies cannot assess whether provisional‑approval conditions were systematically monitored and enforced.


## Public Communications vs Policy Commitments

A critical gap exists between public messaging and formal policy commitments regarding COVID-19 vaccine safety monitoring.

### The Public Message: "No Different"

On **3 February 2021**—the same month TGA published its COVID-19 Vaccine Safety Monitoring Plan—the Department of Health released a video stating:

> "All registered vaccines are closely monitored by the TGA... **COVID-19 vaccines will be no different.**"<sup>[1](#fn1)</sup>

This positioned COVID-19 monitoring as identical to routine surveillance.

### The Policy Commitment: "Enhanced Monitoring"

Formal commitments painted a different picture:

- **National Cabinet** (November 2020): Promised "active and comprehensive" monitoring for provisional approvals
- **Bilateral Agreements** (February 2021): Established governance requirements for safety monitoring and adverse event reporting

The TGA's own planning documents reinforced this commitment:

- **TGA Safety Monitoring Plan** (February 2021): Outlined 17 numbered strategies to "strengthen" and "enhance" routine pharmacovigilance systems


### The Contradiction

If monitoring was 'no different' from routine surveillance, the Safety Plan's 17 enhancement strategies were either:

1. Never implemented (monitoring remained routine despite policy commitments), or

2. Implemented but indistinguishable from routine processes (no operational meaning), or

3. Mere aspirations never operationalised (policy theatre without substance)

All three possibilities point to the same audit finding: enhanced monitoring cannot be verified as systematically implemented.


### Testing the Contradiction: 2022 Direct Inquiries

On **18 and 22 February 2022**, I submitted identical inquiries requesting Safety Plan implementation evidence: progress reports against the 17 strategies, investigation documentation, and governance records.

**TGA Responses** (identical template both dates):
- **Claimed**: Monitoring "enhanced dramatically" and represented "the most intense... ever conducted"
- **Provided**: Routine weekly surveillance reports + a generic covid safety video<sup>[2](#fn2)</sup> "Get vaccine safety information you can trust"
- **Delivered**: Zero Plan-specific implementation documentation

The response pattern was clear: claims of dramatic enhancement, evidence of routine processes.<sup>[3](#fn3)</sup>

### Resolution: 2025 Senate Testimony

**Senate testimony (9 October 2025)** revealed that monitoring consisted of "day-to-day processes" with no systematic tracking against the Safety Plan's 17 strategies. This admission confirms what TGA publicly stated in 2021—that COVID-19 vaccine monitoring was "no different" from routine surveillance—directly contradicting the commitment to enhanced monitoring mandated by National Cabinet and operationalised in the published Plan.

Four years of inquiries produced identical results: assertions of enhancement without documentation of what made the monitoring operationally distinct.

[Full senate testimony analysis](primary-sources/senate-community-affairs-legislation-committee/README.md)

---

**Primary Sources:**

Department of Health, "COVID-19 vaccines – TGA approval process" (3 Feb 2021)<sup>[1](#fn1)</sup>

TGA, "Get vaccine safety information you can trust" (26 Nov 2021)<sup>[2](#fn2)</sup>

---

<a name="fn1">1</a>: https://www.youtube.com/watch?v=XxJ7dnltvtI

<a name="fn2">2</a>: https://www.youtube.com/watch?v=PT4M9fX9sPI

<a name="fn3">3</a>: Detailed analysis: [Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf), pp. 86-87

---


### From "Molecule to Market" to Enhanced Safety Monitoring: The Teaching-Practice Gap

In October 2021, at the peak of provisional approval rollout, senior TGA officials taught Master of Pharmacy students at University of Technology Sydney about COVID-19 vaccine safety monitoring. [See Pharmacovigilance - a regulator's perspective](primary-sources/tga-documents/webinar-presentation-pharmacovigilance-regulators-perspective.pdf)

What they showed:
- Slide 22: Routine PV infrastructure (AEMS, DAEN, daily/weekly analysis, workflow database)
- Slide 23: Safety Plan referenced with aspirational strategies
- Slide 24: Weekly COVID-19 safety reports

What was absent: Operational mechanisms distinguishing COVID-19 monitoring from routine systems. No AusVaxSafety integration, no Plan's 17 strategies, no governance structures, no performance metrics—despite technical training for professionals.

Four years later (October 2025), Senate testimony described the Plan as managed through "day-to-day processes" with no systematic tracking. OAIC searches found no Plan-specific implementation or governance records.

The gap: Teaching materials showed routine pharmacovigilance with Safety Plan referenced aspirationally. Neither teaching materials nor FOI/OAIC processes produced evidence (workplans, governance minutes, KPI tracking, integration records) demonstrating enhanced monitoring existed as a distinct framework—despite being the stated basis on which provisional approval proceeded.


## Official 2021 AEFI Surveillance Report

In 2024, *Communicable Diseases Intelligence* published an annual report on adverse events following COVID‑19 vaccination in 2021, based on data from TGA’s AEMS passive (spontaneous) surveillance system.

**What it shows:**
- Intensive passive monitoring, with over 111,000 COVID‑19 vaccine AEFI reports in 2021 and much higher reporting rates than for non‑COVID‑19 vaccines.
- Detection and investigation of rare adverse events (e.g. myocarditis/pericarditis, thrombosis with thrombocytopenia syndrome), leading to changes in product information, clinical guidance, and weekly public safety reports.

**What it does not show:**
- No mention of the February 2021 **COVID‑19 Vaccine Safety Monitoring Plan** or its 17 strategies.
- No documentation of plan‑level governance or performance tracking against Safety Plan objectives.  
- No evidence of systematic AusVaxSafety–TGA integration frameworks or explicit provisional‑approval verification processes.

This report is consistent with the findings in Phillips et al. (2021) discussed in the next section below: it demonstrates that substantial monitoring activity occurred, but does not provide the Safety Plan‑specific implementation, governance, or verification documentation that this audit assesses.

**Reference:**  

Glover C, et al. (2024). Surveillance of adverse events following immunisation in Australia, COVID‑19 vaccines, 2021. *Communicable Diseases Intelligence*, 48. [doi:10.33321/cdi.2024.48.2](https://doi.org/10.33321/cdi.2024.48.2)

[Full AEFI surveillance report](primary-sources/vaccine-surveillance/cdi-2024-surveillance-aefi-covid-19-2021.pdf)


## Supporting Peer-Reviewed Literature of Systemic Gaps

A peer-reviewed study published in *Vaccine* (September 2021) provides independent validation of identified gaps. Phillips et al. interviewed 17 Australian vaccine safety experts in July–October 2020—**before the COVID-19 vaccine rollout**—and documented significant system limitations.

**Key findings:**

- Data linkage was described as a “big hole” and a “huge omission”, despite being considered “technically quite feasible”.  
- AusVaxSafety-Active and the TGA’s passive system (AEMS) were described as “parallel systems” where notifications and signals could “fall through gaps”.  
- Experts stated that COVID-19 vaccine safety monitoring would require “significant enhancement”, including “systematic approaches to population-level active surveillance”, particularly through data linkage.

These pre-rollout warnings align with TGA Senate testimony (9 October 2025) that monitoring remained “day-to-day processes” and was never systematically tracked against the COVID-19 Vaccine Safety Monitoring Plan. OAIC-directed searches found no documentation showing that the expert-identified gaps in linkage, integration, or population-level active surveillance were addressed.

**The authors’ conclusion:**

> Phillips et al. concluded that implementation of the COVID-19 immunisation program and its safety monitoring arrangements represented an opportunity to strengthen Australia’s vaccine pharmacovigilance system, including by improving integration between active and passive surveillance, developing population-level active surveillance through linked data, and better capturing later-onset AEFI.

**What happened:** The Safety Plan was published (February 2021) but cannot be verified as systematically implemented. On the available record, the “opportunity” identified by the experts to strengthen the system and capture later-onset AEFI was not realised.

**Reference:** Phillips A, et al. (2021). *Vaccine*, 39(40), 5968-5981. [doi:10.1016/j.vaccine.2021.07.059](https://doi.org/10.1016/j.vaccine.2021.07.059)

[Full paper: Phillips et al. (2021)](reference-documents/phillips-2021-vaccine-pharmacovigilance-system.pdf)

## What This Audit Examines: Enhanced Safety Monitoring
  
### Enhanced Monitoring as Defined by the Plan

The COVID-19 Vaccine Safety Monitoring Plan (February 2021) operationalised National Cabinet's commitment to "active and comprehensive" monitoring and was embedded in bilateral agreements as the authoritative framework for provisional approval oversight.

**Status as national policy instrument:**
* Operationalised Cabinet's mandate (November 2020) for vaccines with incomplete pre-market data
* Embedded in bilateral state agreements as the governance framework
* Publicly promised to Australian citizens as the standard for enhanced surveillance

**The Plan's explicit definition:** 17 numbered strategies across five objectives designed to "strengthen the existing vaccine vigilance system"—the operational meaning of enhanced monitoring beyond business-as-usual.

**This audit uses the Plan's own framework as the standard.** When we ask whether "enhanced monitoring" was implemented, we mean: were these specific 17 strategies operationalised with verifiable documentation?


### The Audit Question

The audit question is whether the Plan’s 17 numbered strategies were implemented as distinct, documentable processes. The TGA conducted pharmacovigilance activities during the rollout, investigating 150 safety signals, documenting 57 regulatory actions, and publishing more than 150 weekly safety reports.

The Plan's 17 strategies included:
* Active surveillance through AusVaxSafety integration (Strategy 2.4)
* Systematic collaboration frameworks (Strategy 2.4)
* Integrated analysis of multiple data sources
* Product-specific investigation protocols
* Dedicated governance and performance tracking

For provisionally approved medicines, these strategies were presented as the safeguard justifying accelerated access: earlier public access was granted on the basis of demonstrably stronger post-market safeguards.

Therefore, this audit asks: Were the Plan's 17 numbered strategies operationalised through dedicated protocols and audit trails? Was AusVaxSafety's active surveillance systematically integrated with TGA signal management, as Strategies 2.1 and 2.4 required? Was implementation tracked and governed, or—consistent with later descriptions of "day-to-day processes"—were these strategies **not implemented as distinct, systematically tracked processes with dedicated governance and audit trails**?

### Why This Matters

This question is critical. Approximately 68.4 million COVID-19 vaccine doses (around 91 per cent of the total rollout) were administered under provisional approval by late 2023, which 
relied on enhanced safety monitoring beyond routine surveillance as the compensating safeguard, reflected in TGA's enhanced post-market monitoring framework and guidance. If the additional strategies presented as part of this enhanced monitoring framework and publicly promised in February 2021 cannot be distinguished in the documentary record, then:

* The Plan's enhanced-monitoring commitments cannot be verified as delivered 
* Public assurances of heightened oversight are unsubstantiated
* The integrity of the provisional approval pathway is compromised
* Fundamental accountability is impaired

The audit scope is limited to documented implementation of the 17 enhanced monitoring strategies committed to by the TGA during the provisional approval period and specified in its February 2021 COVID-19 Vaccine Safety Monitoring Plan, together with two additional governance outputs. It examines whether those strategies were implemented with the documentation, governance, and verifiable audit trails necessary for independent accountability.

## The Challenge of Black Box Governance for Private Citizens

This audit begins with a contradiction that defines its entire scope: The TGA promised a verifiable “enhanced” system as the oversight framework underpinning provisional approval. Four years later, it described that system as undocumented 'day-to-day' processes. Our task is to investigate the gap between that promise and that description using the limited tools of a citizen. We confront the fundamental accountability problem of information asymmetry: regulators hold complete knowledge of internal processes while citizens see only outputs. When the TGA announced "enhanced safety monitoring," it created a definitional crisis: where does routine pharmacovigilance end and enhanced monitoring begin?

For private citizens with limited resources, funding, and investigative powers, this creates an impossible research challenge. Yet patterns emerge that demand explanation—even when definitive proof remains beyond citizen reach.

This audit employs transparent methodology: open access, version control, responsiveness to correction, permanent archive, and explicit limitations. It acknowledges inherent uncertainties while demonstrating what can be verified from outside the black box. [Read more: Black Box Governance](reference-documents/black-box-governance.md)

## ANAO Audit History and the Pharmacovigilance Gap

The Australian National Audit Office (ANAO) has examined TGA several times since the mid‑1990s, with reports focused on prescription‑medicine evaluation, the regulation of non‑prescription and complementary medicines, manufacturer compliance and cost‑recovery arrangements. These audits have primarily assessed pre‑market evaluation, regulatory processes, enforcement and financial frameworks, rather than whether specific pharmacovigilance plans were implemented as designed or whether enhanced post‑market commitments were demonstrably delivered.

In 2022–23, the ANAO conducted a performance audit of Australia’s COVID-19 vaccine rollout (Australia’s COVID-19 Vaccine Rollout, Auditor-General Report No. 3 2022–23). The audit examined the governance, planning and implementation of the national rollout, including vaccine acquisition and distribution, eligibility and delivery arrangements, and the TGA’s role in vaccine approval and safety monitoring. Its examination of TGA activities was not an audit of the implementation of the February 2021 COVID-19 Vaccine Safety Monitoring Plan.

Crucially, that audit did **not** examine:

- Whether TGA’s specific pharmacovigilance commitments in the February 2021 COVID‑19 Vaccine Safety Monitoring Plan were implemented as designed.  
- Whether “enhanced” monitoring, distinct from routine surveillance, actually operated in practice.  
- Whether provisional‑approval conditions were verified and documented before vaccines transitioned to full registration.  
- Whether TGA’s records and decision trails met international pharmacovigilance standards (e.g. ICH E2E, CIOMS) for traceable audit trails from signal detection to regulatory action.

As a result, there is currently no independent assurance that the enhanced post‑market safety monitoring promised to Australians – and relied upon to justify provisional approval for 68.4 million doses – was ever implemented and documented to the standard expected of a national regulator.

This citizen audit is intended to help fill that oversight gap by providing:

- A structured, evidence‑based implementation assessment of the February 2021 Safety Monitoring Plan.  
- A clear mapping of documentation gaps around signal management, AusVaxSafety integration, provisional‑approval verification and governance.  
- A concrete evidentiary platform on which ANAO could scope and conduct a dedicated performance audit of TGA’s COVID‑19 vaccine pharmacovigilance system and its compliance with provisional‑approval conditions requiring enhanced post‑market safety monitoring.

Taken together, the scale of provisional use (68.4 million doses), the absence of a demonstrable implementation trail, and the lack of any prior ANAO examination of these specific pharmacovigilance issues provide a strong public‑interest basis for ANAO to initiate a focused performance audit.

## Oversight and Accountability

This assessment has been provided to multiple oversight bodies:

- **Australian Senate** – Senator Malcolm Roberts cited the audit by name in the adjournment debate on 24 March 2026, referencing key findings from the SSRN publication including absence of implementation records and ISO 19011 conformity assessment results. [Read the Senate Analysis](primary-sources/senate-2026-03-24/README.md)
- **Australian National Audit Office (ANAO)** – submitted 27 November and 10 December 2025, requesting a dedicated performance audit of TGA's COVID‑19 vaccine pharmacovigilance implementation and compliance with provisional‑approval conditions. A response was received confirming the request has been passed to the annual audit work program team for consideration. No further feedback is guaranteed; updates are published via the ANAO's annual audit work program each July.
- **Senate Community Affairs Legislation Committee** – provided to key members on 16 December 2025 to inform questioning and oversight; key findings were confirmed in principle through testimony on 9 October 2025. A response was received from the Committee Secretary on 2 March 2026 acknowledging that the committee considered the correspondence and noted the issues raised. No follow-up action has been taken since.
- **Office of the Australian Information Commissioner (OAIC)** – central to reviews MR22/00538 and MR25/01153, and the [2025] AICmr 54 decision. IC review for MR25/01153 still pending.
- **Commonwealth Ombudsman** – complaint submitted 1 April 2025 (ref: 2025‑806374) regarding contradictions in TGA responses and systemic issues in pharmacovigilance governance and FOI administration. No action commenced as of 5 August 2026.

Key correspondence is available in the [correspondence](primary-sources/correspondence/) folder.

For the full chronology of FOI requests, OAIC proceedings, Senate engagement, and oversight body submissions from February 2022 see [Investigation Timeline](TIMELINE.md).

## The Call for Investigation

Australia administered 68.4 million COVID‑19 vaccine doses under provisional approval – the country’s largest deployment of provisionally approved medicines. Provisional approval was justified on the basis that **enhanced, documented post‑market monitoring** would compensate for limited pre‑market data.

After four years of systematic FOI requests and documentary review, TGA has not demonstrated that:

- It systematically implemented the enhanced monitoring framework described in the February 2021 Plan.  
- Enhanced monitoring was distinct from routine “day‑to‑day processes”, as provisional approval requires.  
- It maintained audit trails linking 150 investigated signals to 57 regulatory actions, as international standards envisage.  
- It verified, and documented verification of, the Plan's enhanced-monitoring commitments before 68.4 million doses transitioned to full registration.  
- It established the governance, oversight and performance‑measurement arrangements its own Plan indicated.

The problem is straightforward: **TGA made commitments to Australians about enhanced, documented safety monitoring for COVID-19 vaccines administered to 21.2 million people. It cannot, on the record, show that those commitments were kept.** This gap in demonstrable accountability requires formal, independent investigation and reform of pharmacovigilance and provisional approval frameworks.

## Methodology and Evidence Base

### Assessment Framework

This audit applies systematic evidence based principles consistent with:

- **ISO 19011:2018 – Guidelines for Auditing Management Systems** - [ISO 19011 Management Systems Audit Checklist](analysis/ISO-19011-conformity-assessment-checklist.md)
  - Evidence-based approach (Clause 4 f)
  - Risk-based approach (Clause 4 g)
  - Independence (Clause 4 e) and due professional care (Clause 4 c)
  - Fair presentation of findings and limitations (Clause 4 b)

- **ANAO Performance Audit Process and compliance standards** - [Performance Audit Process](https://www.anao.gov.au/work/insights/performance-audit-process)
  - Assessment against published plans and criteria  
  - Triangulation across multiple sources  
  - Emphasis on accountability and transparency  
  - ISSAI‑aligned

**Regulatory frameworks applied**

- *Therapeutic Goods Act 1989* (provisional approval provisions) and TGA's provisional registration guidance documents
- TGA guidance on provisional approval pathways and Risk Management Plans.  
- Australian Regulatory Guidelines for Prescription Medicines (ARGPM).  
- International pharmacovigilance standards: ICH E2E, CIOMS, EMA GVP Module I.  
- Commonwealth records‑management and performance‑reporting frameworks: PGPA Act 2013, Archives Act 1983.

### Assessment Output Methodology

Each of the 19 Plan outputs (the Plan's 17 strategies plus 2 governance outputs) was evaluated against documentary evidence categorised by a four-tier source-reliability hierarchy, ranking evidence by verifiability, reliability, and evidential authoritativeness:

- **Tier 1 — Primary Statutory Evidence:** FOI decision letters; OAIC submissions and determinations; direct TGA communications.
- **Tier 2 — Primary Documentary Evidence:** Senate Hansard and Questions on Notice; TGA Annual Reports; published TGA safety reports; the COVID-19 Vaccine Safety Monitoring Plan.
- **Tier 3 — Secondary Documentary Evidence:** partner organisation reports; Australian Immunisation Register data; publicly accessible surveillance data.
- **Tier 4 — Tertiary Contextual Evidence:** international regulatory guidance; ICH E2E; CIOMS; comparative regulatory frameworks.

Higher-tier evidence takes precedence in case of conflict, and all findings are anchored in Tier 1 or Tier 2 evidence. This is the same hierarchy applied in Section 9.4 of the [Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf) and the [dataset codebook](analysis/dataset-codebook.md).

### Rating Criteria

"Fully implemented" requires coherent end-to-end documentation showing that required processes, integrations, governance arrangements and outputs were in place and sustained over time.

Partial completion of activities without an implementation trail is rated "partially implemented", not "fully implemented".

**"Not Documented" denotes the absence of locatable documentary evidence; it is not a finding that an activity did not occur.** The label deliberately remains within the documentary register rather than asserting "Not Implemented," which the available evidence cannot establish. Any "Not Documented" classification can be overturned by production of a single document demonstrating the relevant output.

**Search strategy:** This audit employed systematic keyword searches with 14 strategic terms (9 primary, 5 secondary) targeting specific Plan outputs and pharmacovigilance processes, documented in Appendix A.2.2 (pp. 77-78) of the Main Audit Report. In comparison, TGA's OAIC-directed TRIM searches used 8 generic document-title terms without output-specific or pharmacovigilance vocabulary (TGA OAIC Submission, 20 September 2024, pp. 28-32). [Full search methodology comparison](analysis/search-methodology-comparison.md)

## Evidence Sources

All material is publicly available or obtained through lawful FOI processes, enabling independent verification of every finding. Key sources are also provided as PDF files in the reference-documents folder for archival and offline use.

**Australian COVID‑19 Vaccination Policy**  
https://www.health.gov.au/sites/default/files/documents/2020/12/covid-19-vaccination-australian-covid-19-vaccination-policy.pdf 
Commits the Australian Government to active and comprehensive post‑market safety monitoring for COVID‑19 vaccines and assigns adverse event monitoring "via the TGA" through a national COVID‑19 Vaccine Pharmacovigilance Plan.

**TGA COVID‑19 Vaccine Safety Monitoring Plan (February 2021)**  
https://www.tga.gov.au/sites/default/files/covid-19-vaccine-safety-monitoring-plan.pdf     
Sets out 19 specific outputs across 17 numbered strategies as TGA's operational implementation of the enhanced‑monitoring expectation for provisionally approved COVID‑19 vaccines.

**COVID-19 vaccine safety reports**
https://www.tga.gov.au/news/covid-19-vaccine-safety-reports
TGA published approximately 150 COVID-19 vaccine safety reports—weekly from March 2021, then fortnightly through early 2023—detailing DAEN adverse events, safety signals (e.g., myocarditis/TTS), and regulatory actions.

**AusVaxSafety – Active and enhanced vaccine safety surveillance for COVID‑19 vaccines in Australia**
https://www.ausvaxsafety.org.au/active-and-enhanced-vaccine-safety-surveillance-covid-19-vaccines-australia  
Describes AusVaxSafety as operating "as part of the national COVID‑19 Vaccine Pharmacovigilance Plan, led by the TGA and the Australian Government", complementing TGA and state/territory spontaneous reporting systems.

**Australian Public Assessment Reports and related releases**  
Comirnaty AusPAR (transition from provisional to full registration)  
https://www.tga.gov.au/sites/default/files/2023-08/auspar-comirnaty-230807.pdf

**TGA public databases and publications**  
Database of Adverse Event Notifications (DAEN) and published regulatory decisions.

**FOI responses**
   * FOI 3643 (2022) – refusal of an "implementation report" for the COVID‑19 Vaccine Safety Monitoring Plan.
   * FOI 25‑0166 (2025) – 399 Plan‑aligned documents identified across 12 document categories but not processed under practical‑refusal provisions.

**Information Commissioner material**
   * OAIC reviews MR22/00538 and MR25/01153 (directed searches and responses).
   * [2025] AICmr 54 decision ('AUQ' and Department of Health and Aged Care')  
https://www.austlii.edu.au/cgi-bin/viewdoc/au/cases/cth/AICmr/2025/54.html

**Sparke Helmore case note – 'AUQ' and Department of Health and Aged Care [2025] AICmr 54**  
https://www.sparke.com.au/insights/case-note-auq-and-department-of-health-and-aged-care-freedom-of-information/

**Senate Community Affairs Legislation Committee testimony (9 October 2025)**

**Video (timestamped):**  
https://www.youtube.com/watch?v=YLFNBFdICU0&t=9040s (2:30:40–2:37:00)

**Hansard:**  
https://www.aph.gov.au/Parliamentary_Business/Hansard/Hansard_Display?bid=committees/estimate/29000/&sid=0003

**Key testimony:** TGA officials stated Plan implementation was never systematically tracked and monitoring occurred through "day-to-day processes" rather than distinct enhanced framework. Confirmed 148 safety signals investigated and 57 regulatory actions taken (later updated to 150 safety signals in QON 559).

[Full testimony analysis →](primary-sources/senate-community-affairs-legislation-committee/README.md)

## Documentary Evidence of TGA Documentation Capacity


### FOI 5082: TGA Vaccine Pharmacovigilance System  

**Baseline pre-2021 + COVID implementations July–August 2021, released 26 July 2024**

**Source:** FOI 5082 https://www.tga.gov.au/sites/default/files/2024-08/FOI5082.pdf. Signal Investigation Unit (SIU), Pharmacovigilance & Special Access Branch.  

**Link:** https://www.tga.gov.au/sites/default/files/2024-08/FOI5082.pdf

**Note:** Hyperlink from log entry (26 July 2024); PDF accessible via direct/archive links.

**Disclosure Log:** https://www.tga.gov.au/resources/publication/corporate-reports/documents-released-under-section-11c-freedom-information-act-1982-jul-2024-jun-2025

**Archive:** [Download FOI5082.pdf](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/raw/main/primary-sources/foi/foi-5082.pdf) (13.3 MB)

**Summary**

FOI 5082 Request: TGA's internal documents on "COVID-19 vaccine pharmacovigilance"—specifically vaccine safety monitoring systems, signal detection methods, and operational SOPs (baseline pre-2021 + COVID-specific July–August 2021).

**Documents Released**

Internal blueprint documenting routine pharmacovigilance baseline (pre-2021) with COVID-19 signal detection implementation docs (19 July–24 August 2021). Documents routine "spontaneous reporting → assessment → action" framework (AEMS/DAEN/DPAR, VSIG for clusters) predating Safety Plan by 12–24 months. Contextualises Senate testimony characterisation of "day-to-day processes," including staffing/automation (APS5/6 for DPAR/chi-squared, EL1 for MaxSPRT/O/E, 99-100% QLIK/Stata/R).

Post-Plan COVID implementation docs (observed-vs-expected, MaxSPRT, enhanced DPAR frequency/chi-squared comparators) documented without any reference to Safety Plan integration, compliance frameworks, or mapping to Plan's specified strategies. No signal-to-action workflows or comprehensive AusVaxSafety protocols documented. Demonstrates baseline infrastructure and COVID-specific methodological adaptations implemented independently of documented Plan requirements. Does not address post-Plan implementation gaps (FOI 25-0166, MR22/00538 null results).

**Critical evidentiary significance**

FOI 5082 demonstrates TGA's established capacity and practice of detailed pharmacovigilance documentation when systems exist, including documented methodological capacity (e.g., MaxSPRT staffing/automation). Documents support "routine PV existed" and show COVID-specific methodological enhancements were implemented, but contain zero evidence of Safety Plan integration or compliance. The absence of Plan implementation documentation in FOI 5082—combined with null results for Plan-specific requests (FOI 25-0166, MR22/00538)—is consistent with non-implementation rather than non-documentation. Shows baseline "day-to-day processes" existed before Cabinet-endorsed enhanced framework was promised, but fails to demonstrate promised enhancements were ever implemented as documented Plan compliance.

### Evidence Storage and Research Standards

This repository follows open research principles by archiving at-risk primary sources (FOI responses, government documents, OAIC decisions) whilst citing stable institutional sources (peer-reviewed articles, legislation, standards) by reference. This approach aligns with FAIR principles, open access standards, and digital preservation best practices.

**Full documentation:** [Evidence Storage Methodology and Research Standards](audit-governance/evidence-storage.md)

## Limitations and Falsifiability


### Scope

This audit examines documented evidence of implementation against the February 2021 Safety Monitoring Plan. The scope is limited to documentation, records management, and governance processes. Clinical safety outcomes and individual regulatory decisions are outside scope.​​​​​​​​​​​​​​​​

## Meaning of documentation gaps

Absence of documentation does not prove that activities never occurred. It does, however:

- Prevent independent verification of TGA’s assurances about “enhanced” monitoring.  
- Raise questions about transparency, accountability and compliance with international pharmacovigilance standards requiring systematic documentation.  
- Indicate potential non‑compliance with Commonwealth record‑keeping and performance‑reporting obligations.

## Why the gaps are significant

The probability that comprehensive implementation documentation exists but could not be located is low, given:

1. TGA has demonstrated the ability to classify 2,218+ pages of Plan‑aligned material for OAIC (MR22/00538, September 2024).  
2. Senate testimony confirmed that Plan implementation was never systematically tracked and that monitoring was treated as “day‑to‑day processes”.  
3. Multiple FOI requests over four years (FOI 3643, FOI 25‑0166) targeted the same implementation evidence.  
4. Systematic review of publicly available TGA databases, websites, annual reports and AusPARs found no Plan‑level implementation or verification trail.

## Falsifiability

The methodology is explicitly falsifiable: any finding can be disproved by production of contradicting documentation. Corrections and additional evidence are welcomed, and would be incorporated into future versions with transparent version history.

## Alternative explanations for absent records

Three possible explanations exist for the documented gaps:

1. **Records never existed:** The enhanced monitoring framework was not systematically implemented as a tracked, documented process distinct from routine operations. Senate testimony (October 2025) describing monitoring as "day-to-day processes" never systematically tracked supports this explanation.

2. **Records existed but were not retained:** Implementation was documented but records were not preserved in accordance with the Archives Act 1983 and Public Governance, Performance and Accountability Act 2013. This would itself constitute a serious governance failure for a Cabinet-endorsed framework governing 68.4 million provisional doses.

3. **Records exist but have not been produced:** Documentation exists within TGA systems but has not been located or disclosed despite OAIC-directed searches covering more than 531 TRIM containers and 2,218+ pages, multiple FOI requests, and direct parliamentary questioning.

All three explanations represent significant accountability failures. The first indicates a gap between commitment and delivery. The second indicates a breach of Commonwealth records management obligations. The third would indicate a failure of both FOI compliance and parliamentary accountability. The audit's findings and recommendations apply regardless of which explanation proves correct.


## What's in This Repository

### Main Assessment Report

[Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf)

**Implementation Status Assessment Report: TGA COVID‑19 Vaccine Safety Monitoring Plan (March 2026)**

The comprehensive audit report includes:

- Executive summary with key findings and implications.  
- Systematic assessment of all 19 Plan outputs across 17 numbered strategies.  
- Detailed evidence analysis using the four‑tier evidence hierarchy.  
- Provisional‑Approval Lifecycle Verification Gap   
- Legislative framework analysis (*Therapeutic Goods Act* ss 22C, 23AA, 29, and related guidance).  
- Governance and accountability analysis.  
- Structured responses to likely counter‑arguments.  
- Priority reform recommendations.

### Supporting Documentation

- [TGA Senate QON 559 Gap Analysis](analysis/tga-senate-qon-559-gap-analysis-2026.md) – Gap analysis of TGA's formal written answer to Senate Question on Notice 559 (SQ25-001584, October 2025) assessing TGA's stated positions against all five Safety Monitoring Plan strategies and documenting the 93-signal gap derived from TGA's own parliamentary figures.

- [TGA Senate QON SQ13-19 Gap Analysis](analysis/tga-senate-qon-sq13-19-gap-analysis-2026.pdf) – Gap analysis of TGA's responses to seven Senate Questions on Notice (SQ13–19, December 2025) mapping TGA's stated positions against Safety Monitoring Plan outputs, National Cabinet policy commitments, and international pharmacovigilance standards.

- [Compensation Analysis](analysis/compensation-analysis.md) – Analysis of TGA's FOI refusals for signal investigation documentation and implications for Vaccine Claims Scheme causation assessments.

- [FOI Systematic Review](analysis/foi-systematic-review.md) – Systematic review of FOI request patterns, TGA response inconsistencies, and documentary evidence gaps across four years.

- [ISO 19011 Management Systems Audit](analysis/ISO-19011-conformity-assessment-checklist.md) – 
  Independent conformity assessment using ISO 19011:2018 guidelines. Documents 7 major non-conformities and overall NON-CONFORMING rating. Includes [detailed output-by-output breakdown](analysis/ISO-19011-conformity-assessment-checklist.md#output-by-output-breakdown) with 16% conformity rate across 19 Plan outputs, Objective 2 (Signal Detection) at 0% fully implemented and Governance at 0% documented. Complete evidence matrix with methodology and rating criteria available in [Excel format](analysis/output-assessment-evidence-matrix.xlsx).

- [Search Methodology Comparison](analysis/search-methodology-comparison.md) – Systematic comparison of this audit's output-specific search strategy (14 strategic terms) versus TGA's OAIC-directed document-title searches (8 generic terms), documenting gaps in signal detection, AusVaxSafety coordination, ICMRA sharing, and pharmacovigilance terminology. Includes comparison table and gap analysis with full citations to TGA OAIC submission (September 2024, pp. 28-32) and audit methodology (Appendix A.2.2, pp. 77-78).

- [Surveillance Data Analysis](analysis/surveillance-analysis.md) – Systematic analysis of TGA COVID-19 vaccine safety reports (2021-2023) documenting zero Plan framework references across 150+ reports despite [FOI 4029-03](primary-sources/foi/foi-4029/foi-4029-03.pdf) proving TGA presented Strategy 2.3 methodology to Advisory Committee on Vaccines (September 2021). Complete [FOI 4029 suite](primary-sources/foi/foi-4029) available in reference documents. Includes ISO 19011 audit methodology, ANAO performance tracking gaps, and evidence of inadequate OAIC search scope excluding advisory body containers.

- [FOI Analysis and Timeline Documentation](analysis/tga-foi-analysis.pdf) – Detailed FOI/OAIC timeline (2022–2025), pattern analysis of contradictory TGA responses, and comparison of TGA claims versus documented evidence.

- [TGA Safety Plan Audit Summary](analysis/tga-safety-plan-audit.pdf) – Visual executive summary presentation with implementation status dashboard, source reliability hierarchy and key gaps.

- [One-Page Audit Flowchart](analysis/tga-audit-one-page-flowchart.pdf) – One-page visual flowchart of audit methodology, evidence hierarchy, and key findings.

- [Primary Sources](primary-sources/) – FOI responses, OAIC decisions, Senate testimony, Australian Government and TGA policy documents, AusPARs, performance reports, vaccination data, and surveillance materials.

- [Correspondence](primary-sources/correspondence/) – Formal correspondence with oversight bodies including ANAO and Senate Community Affairs Legislation Committee submissions and responses.

- [Reference Documents](reference-documents/) – Supporting analytical and contextual material including peer-reviewed literature, legal case notes, and international pharmacovigilance standards.

- [Open Review Architecture](audit-governance/open-review-architecture.md) – Documents how the audit's public, forkable GitHub architecture functions as a continuous open review mechanism in place of traditional closed peer review.

- [Media Coverage](media-coverage/) – Investigative journalism co‑authored by Paul Rekaris and Dr Julie Sladden on Maryanne Demasi's Substack:  
  - "TGA's vaccine safety black hole: A concerned citizen's four‑year quest for answers"  
    <https://blog.maryannedemasi.com/p/tgas-vaccine-safety-black-hole-a>  
  - "Stairs to nowhere: TGA's vanishing vaccine safety monitoring trail"  
    <https://blog.maryannedemasi.com/p/stairs-to-nowhere-tgas-vanishing>

## Open Access Framework

This work is open access by design: all sources, methods, reasoning, and revisions are publicly available, reusable, and challengeable without restriction.

The audit is disseminated via a green open access pathway<sup>1</sup> with all materials self-archived through GitHub (version control), Zenodo (persistent DOIs), Harvard Dataverse, Mendeley Data, SSRN, SocArXiv, and Arweave (immutable backup)<sup>2</sup>. This ensures:

- Independent verification of all claims
- Reproducible and inspectable research methods
- Permanent public accessibility
- No barriers to scrutiny or reuse

This approach aligns regulatory accountability work with open science principles. All findings are transparent, reproducible, and falsifiable through independent verification.

The audit's open review architecture — public version control, forkability, permanent archiving, and continuous public scrutiny — is documented in the [Open Review Architecture](audit-governance/open-review-architecture.md) page.

**References:**

<sup>1</sup> Suber, P. (2012). *Open Access*. MIT Press. https://cyber.harvard.edu/hoap/Open_Access_(the_book)

<sup>2</sup> Suber, P. *How to make your own work open access*. Harvard Open Access Project. https://cyber.harvard.edu/hoap/How_to_make_your_own_work_open_access

## Licence and Citation

### Licence

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

This work is free to use, share and adapt with appropriate attribution. The open licence is intentional: regulatory‑accountability research should be freely accessible. You are encouraged to build on this methodology, replicate the approach, and use these findings in advocacy, research or oversight activities.

Full license: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Citation

When citing this work, please use:

**Zenodo (primary):**
Rekaris, P. (2026). Documentation Gap Analysis: Implementation Audit of TGA COVID-19 Vaccine Safety Monitoring Plan (Version 1.9.4). Zenodo. https://doi.org/10.5281/zenodo.17731054

**SSRN:**
Rekaris, Paul, Documentation Gap Analysis: Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan (January 12, 2026). Available at SSRN: https://ssrn.com/abstract=6333058 or http://dx.doi.org/10.2139/ssrn.6333058


**BibTeX:**
```bibtex
@misc{rekaris2026tga,
  author = {Rekaris, Paul},
  orcid = {0009-0000-1338-9578},
  title = {Documentation Gap Analysis: Implementation Audit of TGA COVID-19 Vaccine Safety Monitoring Plan},
  month = {August},
  year = {2026},
  version = {1.9.4},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.17731054},
  url = {https://doi.org/10.5281/zenodo.17731054}
}
```

**Zenodo:** [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17731054-blue)](https://doi.org/10.5281/zenodo.17731054)

[CITATION.cff](CITATION.cff)


# DISCLAIMER AND DECLARATION

## Nature of This Audit

This citizen-led assessment is termed an "audit" because it applies systematic audit methodology (ISO 19011:2018, ANAO performance audit principles) to evaluate documented evidence against published commitments. However, it lacks the statutory powers, internal access, and formal appointment of a regulatory audit. All findings are based exclusively on publicly accessible documents, FOI responses, and official testimony. This work cannot compel evidence production or verify internal processes—it can only assess what can be independently verified through available records. The absence of verifiable documentary evidence demonstrating implementation is itself the key accountability finding. This assessment invites formal audit by ANAO with full access to TGA's internal systems and staff.

**Methodological Boundaries:** Consistent with ISO 19011:2018 and ANAO audit principles, findings are presented objectively and conclusions are based strictly on audit evidence. This assessment is limited to evaluating documented evidence of Plan implementation. No opinions are expressed on policy appropriateness, social consequences, or matters beyond audit scope.

## Scope and Intent

This audit assesses documented evidence of Safety Plan implementation against provisional approval commitments, and does not question the competence, good faith, or professional conduct of TGA staff or partner organisations. Staff may have worked diligently within resource constraints, organisational structures, or system limitations beyond their control.

The findings concern systemic documentation, records management, and governance processes—not individual performance or intent. The absence of documentation may reflect organisational capacity issues, competing priorities during emergency response, or records-management system limitations rather than deliberate non-implementation.

This distinction matters: even conscientious work within existing systems can result in documentation gaps that constitute governance concerns requiring independent assessment.

## Scope of Assessment

This assessment evaluates publicly available evidence for implementation of TGA’s COVID-19 Vaccine Safety Monitoring Plan (February 2021) commitments. It does not assess the clinical safety or efficacy of COVID-19 vaccines, nor the appropriateness of individual regulatory decisions. The findings relate to documentation, records management, and governance processes, not clinical or scientific judgements.

Throughout this report, references to enhanced monitoring requirements, commitments and conditions under provisional approval mean those set out in the TGA's February 2021 COVID-19 Vaccine Safety Monitoring Plan. They do not refer to conditions of registration imposed on individual sponsors under the Therapeutic Goods Act 1989, which are a separate instrument and outside this audit's scope. This audit has not sought or reviewed the underlying sponsor documentation on which TGA’s assessment of those conditions is based, and makes no finding as to its availability or completeness.

**Evidence base:** Analysis is based on publicly available documentation, FOI responses, OAIC material, Senate testimony, and official publications. All factual claims are supported by cited sources.

## Regulatory framework and analytical scope

A key challenge in assessing regulatory accountability is the layered nature of the framework within which the TGA operated. The relevant framework comprises the Therapeutic Goods Act 1989 (Cth), associated regulations made under it, legislative instruments, regulatory guidance, government policy commitments and internationally recognised pharmacovigilance standards. These sources differ in legal status and function: the Act and regulations establish statutory or regulatory requirements, while legislative instruments, guidance, policy materials and international standards may establish regulatory requirements, expectations, government commitments or recognised good practice without necessarily creating statutory obligations.

The February 2021 Safety Monitoring Plan should be understood in its national policy context: it operationalised the Australian Government's and National Cabinet's commitment to enhanced COVID-19 vaccine safety monitoring during the period of provisional registration. This national policy status does not, by itself, convert the Plan into a statutory obligation. A failure to demonstrate implementation of a policy commitment is not automatically a statutory breach. However, where that commitment formed part of the governance and assurance framework surrounding provisional regulatory approval, the inability to verify its implementation raises a distinct regulatory accountability question.

This audit does not seek to undertake a comprehensive legal analysis of every obligation arising from each regulatory instrument. Rather, it focuses on whether the enhanced COVID-19 vaccine safety monitoring commitments identified in relevant policy and regulatory materials were implemented and can be verified through available documentary evidence. Accordingly, the analysis distinguishes between legal requirements, regulatory expectations, policy commitments and evidence of implementation. Where this report refers to a monitoring commitment as a legal requirement, that characterisation is supported by a specific statutory or regulatory provision. Where a commitment is described in policy or governance terms, that reflects its actual source and should not be read as asserting a statutory obligation.

The available record does not provide the level of documentary assurance needed to independently verify that a major national commitment was systematically implemented. This does not establish that the underlying monitoring activities did not occur. Rather, it limits the ability of an independent party to determine how the Plan's commitments were implemented, how delivery was monitored and assured, and whether the enhanced-monitoring commitment was fulfilled as intended. This distinction is central to the audit's assessment of documentation, governance and regulatory accountability.

## Peer-Review Status

This work has not yet been formally peer-reviewed or independently verified. It is published to encourage independent verification, peer review, and scrutiny by researchers, citizens, oversight bodies, and other interested parties. The methodology employs recognised audit standards (ISO 19011:2018, ANAO performance audit framework) with documented search protocols and four-tier evidence hierarchy to enable independent verification and formal peer review. Two research papers arising from this audit are currently under peer review at international journals.

### Open Review Architecture

The public GitHub repository functions as an open review mechanism: the complete methodology, evidence base, version history, and analytical decisions are publicly accessible and inspectable. Anyone may fork the repository, raise issues, propose corrections, or independently replicate the findings. This open architecture provides a form of continuous improvement and public scrutiny that traditional closed peer review does not offer — every claim is visible, every source is cited, and every change is documented with rationale.

Corrections and additional evidence are welcomed and would be incorporated into future versions with transparent version history.   

## Accuracy and Good Faith

This analysis is accurate to the best of the author’s knowledge. Given the volume and complexity of material, inadvertent errors in citation or interpretation may occur; corrections are welcomed via public contact channels. The work is conducted in good faith and in the public interest, consistent with principles of open government and citizen-led accountability.

## Living Document

Updates occur as new official documents (e.g., FOI, OAIC material) or substantive feedback become available, with transparent version history via GitHub tags/releases.

## Conflicts of Interest

The author has no financial, professional, or personal conflicts related to this work. No funding was received from pharmaceutical companies, government agencies, advocacy groups, or other interested parties.

## Legal Disclaimer

This independent audit examines institutional processes and documentary evidence related to implementation of government policy and regulatory frameworks, to inform public and parliamentary understanding.

The dataset comprises documentary materials, including government records, FOI responses, parliamentary testimony, and public regulatory publications, obtained through lawful public accountability mechanisms. It does not involve human participants, clinical data, or identifiable personal information, and no ethics approval was required.

References to named individuals reflect standard documentation practices, citing who presented information in their official capacity as identified in public source materials. No attribution of misconduct or deliberate misrepresentation to any person or organisation is intended or should be inferred.

**Copyright:** Use of source materials, including Crown Copyright documents, is for non-commercial research, criticism, review, and public interest analysis pursuant to fair dealing provisions of the Copyright Act 1968 (Cth).

**Corrections:** Feedback identifying inadvertent mischaracterisation of fact, evidence, or position will be promptly reviewed and addressed.

-----

## Contact

For enquiries regarding peer review, methodology, evidence corrections, collaboration, or media enquiries:

**Email:** rekasp@protonmail.com  
**Latest News and Updates:** [@prekas23 on X](https://x.com/prekas23)

**Author ORCID:** [![ORCID](https://img.shields.io/badge/ORCID-0009--0000--1338--9578-green.svg)](https://orcid.org/0009-0000-1338-9578)

-----

## Acknowledgements

This work builds on four years of systematic FOI requests, Information Commissioner reviews and engagement with parliamentary oversight processes. Thanks are due to those who provided guidance on FOI procedures, regulatory frameworks and academic standards for transparency research.

Special thanks to **Dr Julie Sladden** and **Dr Maryanne Demasi** for collaboration on investigative reporting that brought these issues to wider public attention.

-----

## Version History

**Document Version:** 1.9.4   
**Last Updated:** 11 August 2026  
**First Published:** 27 November 2025  
**Archive:** Zenodo DOI current. Bitcoin timestamp verified (block 942725). 

For detailed version history and changelog, see [Version History](audit-governance/version-history.md)

-----

## Permanent Archive

**Full blockchain and archival verification documentation:** [Blockchain and Archival Verification Records](blockchain-and-archival-verification/README.md)

This audit has been permanently archived and cryptographically timestamped:

- **National Library of Australia**: [NED476889S65171](https://nla.gov.au/nla.obj-4238332288) (Legal deposit, [AWA archived](https://webarchive.nla.gov.au/tep/221557), discoverable via [Trove](https://trove.nla.gov.au/))

- **Zenodo Archive:** [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17731054-blue)](https://doi.org/10.5281/zenodo.17731054)  
  Permanent academic archive with CERN backing

- **Harvard Dataverse:** [10.7910/DVN/BDKZQJ](https://doi.org/10.7910/DVN/BDKZQJ)  
  Harvard University research data repository; DOI-registered scholarly dataset archive  

- **SSRN:** [Abstract 6333058](https://ssrn.com/abstract=6333058) | DOI: [10.2139/ssrn.6333058](https://doi.org/10.2139/ssrn.6333058) Academic preprint repository; indexed by Google Scholar

- **Mendeley Data:** [10.17632/y5wmt6f8j9](https://doi.org/10.17632/y5wmt6f8j9) (companion dataset to SSRN preprint)

- **SocArXiv:** [10.31235/osf.io/sb4gz](https://osf.io/preprints/socarxiv/sb4gz) Social science preprint repository

- **Bitcoin Timestamp:** 29 March 2026, 3:29 PM AEDT  
  SHA-256: `eb0cbfc1b582f861b7c103120a491640ee3c1c4f1ac3606c80d0751564610347`    
  Verification Screenshot: [View](blockchain-and-archival-verification/bitcoin-timestamp-verification-2026-03-29.png)

- **Arweave:** [Permanent Storage](https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps)

- **Internet Archive:** [Full Repository (v1.9.3)](https://archive.org/details/tga-covid-19-vaccine-safety-monitoring-audit-v-1.9.3) | [Audit Report PDF](https://archive.org/details/tga-covid-19-vaccine-safety-monitoring-audit-report) | [Web Snapshots](https://web.archive.org/web/*/github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit*)  
 Complete archive and dated snapshots proving public web presence

The archival stack was designed to ensure dissemination, reproducibility, and national permanence.  The rationale is documented in the [Permanent Archive README](blockchain-and-archival-verification/README.md#rationale-for-platform-selection).  


[^plan-scope]: The Plan specifies 17 numbered pharmacovigilance strategies across five objectives. This audit assessed these 17 outputs together with two additional governance outputs: Implementation oversight and Performance measurement—necessary to evaluate implementation effectiveness and organisational performance. These governance elements reflect requirements under the Public Governance, Performance and Accountability Act 2013 s37(2) and are consistent with the definition of audit criteria (ISO 19011:2018 cl 5.5.2) and audit programme objectives (cl 5.2). Total: 19 outputs audited.

---

*This document is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to share and adapt this work with appropriate attribution.*

---

© Copyright 2026 Paul Rekaris
| Licensed under [![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)



[↑ Back to top](#table-of-contents)


