# Blockchain and Archival Verification Records

This audit is protected by multiple verification and archival methods including version control/reproducibility (GitHub), blockchain-based cryptographic verification (Bitcoin, Arweave), web archival services (Internet Archive Wayback Machine, direct upload, NLA Legal deposit + Australian Web Archive), and academic repositories (Zenodo, Harvard Dataverse, SSRN, SocArXiv, Mendeley Data).

[![Permanent Archive](https://img.shields.io/static/v1?label=Permanent+Archive&message=Multi+Layer+Verification&color=2D6F4D&labelColor=512B58)](permanent-archive-records-2026-08-19.pdf) [![NLA](https://img.shields.io/static/v1?label=NLA&message=Web+Archive&color=2D6F4D&labelColor=512B58)](https://webarchive.nla.gov.au/tep/221557) [![National Library of Australia](https://img.shields.io/badge/National%20Library%20of%20Australia-Collection%20Development%20Policy-000000?labelColor=000000&style=flat-square)](https://www.library.gov.au/visit/about-us/corporate-information/collection-policies-and-plans/collection-development-policy)

[![ISO 19011:2018](https://img.shields.io/badge/ISO-19011%3A2018-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/70017.html) [![ISO 15489-1:2016](https://img.shields.io/badge/ISO-15489--1%3A2016-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/62542.html) [![ISO 14721:2025](https://img.shields.io/badge/ISO-14721%3A2025-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/87471.html) [![LOCKSS](https://img.shields.io/badge/LOCKSS-Lots%20of%20Copies%20Keep%20Stuff%20Safe-8C1515?labelColor=8C1515&style=flat-square)](https://www.lockss.org/) 

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17731054-blue)](https://doi.org/10.5281/zenodo.17731054) [![Harvard Dataverse](https://img.shields.io/badge/Harvard%20Dataverse-10.7910%2FDVN%2FBDKZQJ-A51C30?labelColor=A51C30)](https://doi.org/10.7910/DVN/BDKZQJ) [![SSRN](https://img.shields.io/badge/SSRN-6333058-0a4d8c?labelColor=0a4d8c)](https://ssrn.com/abstract=6333058) [![SocArXiv](https://img.shields.io/badge/SocArXiv-10.31235%2Fosf.io%2Fsb4gz-C0392B?labelColor=C0392B)](https://osf.io/preprints/socarxiv/sb4gz) [![Mendeley Data](https://img.shields.io/badge/Mendeley%20Data-10.17632%2Fy5wmt6f8j9-000000?labelColor=000000&color=000000)](https://doi.org/10.17632/y5wmt6f8j9) 

[![Bitcoin Timestamp](https://img.shields.io/badge/Bitcoin%20Timestamp-29%20Mar%202026-F7931A?labelColor=000000&logo=bitcoin)](bitcoin-timestamp-verification-2026-03-29.png) [![Bitcoin Block Explorer](https://img.shields.io/badge/Bitcoin-Block%20942725-F7931A?labelColor=000000&logo=bitcoin)](https://mempool.space/block/00000000000000000001835be8e30d6d83c3b4296f06ee5d8fcdc9d0aafd3e4a) [![Arweave verify](https://img.shields.io/badge/Arweave-Verify%20on--chain-FF4E42)](https://viewblock.io/arweave/tx/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps) [![Arweave retrieve](https://img.shields.io/badge/Arweave-Retrieve%20files-000000)](https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps) [![Internet Archive](https://img.shields.io/badge/Internet%20Archive-Full%20Repository-black?logo=internetarchive&logoColor=white)](https://archive.org/details/tga-covid-19-vaccine-safety-monitoring-audit-v-1.9.4)

## Research Infrastructure Architecture

| Function | Purpose | Mechanism | Question Answered |
|---|---|---|---|
| Scholarly dissemination | Discoverability and academic reach | SSRN, SocArXiv | Can it be found and read? |
| Research data preservation | Long-term access to evidence | Harvard Dataverse, Mendeley Data | Is the evidence independently accessible? |
| Citable archival record | Stable scholarly citation | Zenodo DOI | Can it be precisely cited? |
| Reproducibility and version control  | Transparency and independent replication, and version history | GitHub | Can the methodology be traced and replicated? |
| Long-term preservation | Protection against loss or suppression | NLA, Internet Archive | Will it survive platform failure? |
| Cryptographic verification | Proof of existence and integrity | Bitcoin OpenTimestamps, Arweave | Did it exist at a specific point in time? |
| Independent scholarly scrutiny | Evaluation by subject-matter experts | Journal peer review | Is the work sufficiently rigorous? |


## Table of Contents

- [Rationale for Platform Selection](#rationale-for-platform-selection)
- [National Library of Australia – National edeposit (NED)](#national-library-of-australia--national-edeposit-ned)
- [National Library of Australia – Australian Web Archive (AWA)](#national-library-of-australia--australian-web-archive-awa)
- [Zenodo Archive](#zenodo-archive)
- [Harvard Dataverse – Harvard University Research Data Repository](#harvard-dataverse--harvard-university-research-data-repository)
- [SSRN – Social Science Research Network](#ssrn--social-science-research-network)
- [SocArXiv – OSF Preprints (Social Sciences)](#socarxiv--osf-preprints-social-sciences)
- [Bitcoin Timestamp (OpenTimestamps)](#bitcoin-timestamp-opentimestamps)
- [Arweave Permanent Storage](#arweave-permanent-storage)
- [Internet Archive (Wayback Machine)](#internet-archive-wayback-machine)
- [Internet Archive – Direct Upload](#internet-archive--direct-upload)
- [Combined Verification](#combined-verification)


## Rationale for Platform Selection

Archival platforms were selected across three functional categories to prevent a single point of failure and to ensure dissemination, reproducibility, and national permanence. Together they form a multi-layer stack that meets academic ards while providing forensic-grade audit verification appropriate for critical regulatory accountability research — and maximum amplification of findings.

The multi-layer approach follows the LOCKSS principle ("Lots of Copies Keep Stuff Safe") — the established digital preservation ard that no single archive, platform, or jurisdiction should be a single point of failure for material of enduring public significance.

**Dissemination and Reach**
- **SSRN**: World's largest social science preprint repository; maximises reach across policy, law, and public administration communities
- **SocArXiv/OSF**: Primary open-access preprint repository for social science; registerd by ORCID; hosted by the Center for Open Science

**Reproducibility and Archiving**
- **Zenodo**: CERN-backed permanent archive; assigns versioned DOIs enabling precise academic citation; concept DOI captures all versions
- **Harvard Dataverse**: Harvard University research data repository; DOI-registered scholarly dataset archive supporting long-term preservation, discoverability, citation, and reproducibility
- **GitHub**: Live repository hosting complete methodology, evidence, and data for independent replication
- **Mendeley Data**: Elsevier dataset repository powered by Digital Commons Data; DOI-supported, archived in perpetuity by DANS (Dutch national research data repository, Royal Netherlands Academy of Arts and Sciences); FAIR data principles; companion dataset to SSRN preprint

**National Permanence and Decentralised Verification**
- **National Library of Australia (AWA)**: Legal deposit confirming heritage preservation as a significant Australian policy publication
- **Internet Archive**: International web preservation via direct upload and Wayback Machine snapshots
- **Arweave**: Permanent decentralised blockchain storage; cryptographically immutable
- **Bitcoin timestamp**: OpenTimestamps OP_RETURN transaction; immutable proof-of-existence on the world's most secure blockchain

The blockchain and decentralised storage layers provide tamper-proof verification aligned with OSINT methodology, ISO 19011 evidence chain requirements, and ISO 15489-1:2016 records management principles — ensuring findings remain permanently accessible and independently verifiable regardless of institutional pressure or platform failure.

---

## National Library of Australia – National edeposit (NED)

**Deposit ID:** NED484448        
**NLA Reference ID:** NED476889S65171                
**Deposit Date:** 19 August 2026, 1:49 PM AEST  
**Title:** Documentation Gap Analysis: Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan – August 2026, v1.9.4  
**Version:** v1.9.4  
**Year of publication:** 2026  
**File:** documentation-gap-analysis-audit-report-v1_9_4.pdf  
**Publisher:** Paul Rekaris  
**Access conditions:** Openly on the internet  

**Previous deposit**  
**Deposit ID:** NED477153  
**NLA Reference ID:** NED477153P1133159  
**Deposit Date:** 14 July 2026, 10:16 AM AEST  
**Version:** v1.9.3 (16 June 2026)  
**File:** documentation-tga-covid19-vaccine-safety-monitoring-audit-rekaris-2026.pdf  
**Size:** 1.1 MB  
**Status:** Available via Trove

### Significance

National edeposit fulfills Commonwealth digital legal deposit requirements. Registered with the National Library of Australia, ensuring permanent preservation as part of Australia's official national collection.

### Access

**Direct Link:** https://nla.gov.au/nla.obj-4238332288 (Multi-part monograph)   
**Trove Discovery:** https://trove.nla.gov.au/  

---

## National Library of Australia – Australian Web Archive (AWA)

**Archive ID:** 20260205171443  
**NLA Reference:** Australian Web Archive (AWA) selective capture  
**Archive Date:** 5 February 2026, 5:14 PM AEDT  
**Title:** TGA COVID-19 Vaccine Safety Monitoring Audit  
**Target:** https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit  
**Status:** Publicly accessible via webarchive.nla.gov.au and Trove

### Significance

AWA is a selective web archive operated by the National Library of Australia. The NLA selects content according to collection policies and priorities for material of national relevance and significance. Selection for AWA archiving represents an independent institutional assessment that this audit has ongoing research and documentary value as part of Australia's national information heritage. Archival capture ensures long-term public access to the evidence, methodology, and findings independent of third-party platforms.

### Access

**Direct Link:** https://webarchive.nla.gov.au/awa/20260204014956/https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/     
**Trove Discovery:** https://trove.nla.gov.au/  

---

## Zenodo Archive

**DOI:** 10.5281/zenodo.17731054 (all versions)   
**Version:** v1.9.5         
**Date:** 7 September 2026       
**Title:** Documentation Gap Analysis: Implementation Audit of TGA COVID-19 Vaccine Safety Monitoring Plan     
**Author:** Paul Rekaris     
**Licence:** CC BY 4.0     
**Status:** PUBLISHED — Publicly Accessible     
**Registered:** ORCID   

### Significance

Zenodo is a general-purpose open research repository operated by CERN and developed under the European OpenAIRE programme. It provides DOI-backed permanent archiving for research outputs of all kinds. The repository is linked directly to GitHub, enabling automatic archiving of each release with a versioned DOI. As the primary citable identifier for this audit, the Zenodo DOI ensures permanent, stable academic referencing independent of any single platform. CERN backing provides institutional credibility and long-term preservation guarantees. Each major release receives its own versioned DOI, enabling precise citation of specific versions, while a permanent concept DOI (10.5281/zenodo.17731054) links all versions and always resolves to the latest release.

### Access

**Direct Link:** https://doi.org/10.5281/zenodo.17731054

---

## Harvard Dataverse – Harvard University Research Data Repository

**DOI:** 10.7910/DVN/BDKZQJ  
**Published:** 12 May 2026  
**Title:** TGA COVID-19 Vaccine Safety Monitoring Plan — Implementation and Governance Evidence Dataset (2021–2026)  
**Author:** Paul Rekaris  
**Licence:** CC BY 4.0  
**Status:** PUBLISHED — Publicly Accessible  
**Persistent Identifier Provider:** DataCite  
**Indexed:** DOI-registered scholarly repository infrastructure

### Significance

Harvard Dataverse is a major scholarly research data repository operated by Harvard University. It provides DOI-backed archival preservation, citation infrastructure, metadata indexing, and long-term public access for research datasets. Publication in Harvard Dataverse supports transparency, reproducibility, discoverability, and independent verification of the audit evidence base. The repository forms part of the project’s multi-layer preservation architecture built around the LOCKSS principle (“Lots of Copies Keep Stuff Safe”), ensuring that the underlying implementation and governance dataset remains permanently accessible independent of any single platform or jurisdiction.

### Access

**Direct Link:** https://doi.org/10.7910/DVN/BDKZQJ

----

## SSRN – Social Science Research Network

**Submission Date:** January 12, 2026  
**Posted Date:** March 2026  
**Abstract ID:** 6333058  
**Title:** Documentation Gap Analysis: Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan  
**Author:** Paul Rekaris  
**DOI:** 10.2139/ssrn.6333058  
**Companion Dataset** (Mendeley Data): 10.17632/y5wmt6f8j9  
**Licence:** CC BY 4.0  
**Status:** POSTED — Publicly Accessible

### Significance

SSRN is the world's largest preprint repository for social science, law, economics, and public policy research, owned by Elsevier and registered by ORCID. Listing ensures the audit appears in academic search results globally and is discoverable by researchers, parliamentary staff, legal practitioners, and journalists using academic search tools. The audit sits within the policy and governance research domain rather than medical preprint classification. Both SSRN and Mendeley Data are Elsevier platforms, providing discoverability within the same academic ecosystem and a direct preprint-to-dataset link.

### Access
**Direct Link:** https://ssrn.com/abstract=6333058  
**DOI:** https://doi.org/10.2139/ssrn.6333058   
**Companion Dataset (Mendeley Data):** https://data.mendeley.com/datasets/y5wmt6f8j9

---

## SocArXiv – OSF Preprints (Social Sciences)

**Submission Date:** 16 March 2026     
**Accepted Date:** 17 March 2026     
**Preprint DOI:** 10.31235/osf.io/sb4gz_v4
**Direct Link:** https://doi.org/10.31235/osf.io/sb4gz
**Title:** Documentation Gap Analysis: Independent Audit of TGA COVID-19 Vaccine Safety Monitoring Plan     
**Author:** Paul Rekaris  
**Licence:** CC BY 4.0  
**Status:** ACCEPTED — Publicly Accessible and Searchable  
**Registered:** ORCID

### Significance

SocArXiv is an open access preprint platform for the social sciences operated by the Center for Open Science and hosted at the University of Maryland. Pre-moderation by academic volunteers ensures minimum scholarly ards before acceptance. Acceptance ensures the audit is discoverable by social science researchers, policy analysts, and open science practitioners using OSF and ORCID. The audit was accepted following pre-moderation on 17 March 2026, confirming the work meets scholarly ards for social science and policy research.

### Access

**Direct Link:** https://doi.org/10.31235/osf.io/sb4gz_v3     
**Supplemental Materials:** https://osf.io/jvqyt

---

## Bitcoin Timestamp (OpenTimestamps)

### Version 1.9.2
**Date:** 29 March 2026 AEDT  
**Time:** 3:29 PM AEDT  
**Bitcoin Block:** 942725  
**Block Hash:** [00000000000000000001835be8e30d6d83c3b4296f06ee5d8fcdc9d0aafd3e4a](https://mempool.space/block/00000000000000000001835be8e30d6d83c3b4296f06ee5d8fcdc9d0aafd3e4a)  
**SHA-256:** `eb0cbfc1b582f861b7c103120a491640ee3c1c4f1ac3606c80d0751564610347`  
**Status:** VERIFIED — Bitcoin Attestation Confirmed  
**Proof File:** [TGA-COVID19-Vaccine-Safety-Monitoring-Audit-v1.9.2.zip.ots](TGA-COVID19-Vaccine-Safety-Monitoring-Audit-v1.9.2.zip.ots)  
**Verification Screenshot:** [View](bitcoin-timestamp-verification-2026-03-29.png)

### Significance
Bitcoin blockchain timestamps provide cryptographically immutable proof that this audit existed in its verified form at a specific point in time. Unlike institutional archives, the record can only be altered through consensus of the entire distributed network — making it particularly appropriate for regulatory accountability research where institutional pressure on evidence is a documented risk.

### Verification 
1. Download the [.ots proof file](TGA-COVID19-Vaccine-Safety-Monitoring-Audit-v1.9.2.zip.ots) above
2. Download the matching ZIP from Arweave:  
   https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps   
3. Go to https://opentimestamps.org   
4. First drop the `.ots` file, then drop the ZIP file   
5. The tool will confirm: "Bitcoin block 942725 attests existence as of 2026-03-29 AEDT"   

---
## Arweave Permanent Storage   
### Deposited Version: v1.9.2   
**Upload / Confirmation Date:** 27 March 2026, 9:55 AM AEDT   
**Transaction ID:** `TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps`   
**File:** TGA-COVID19-Vaccine-Safety-Monitoring-Audit-v1.9.2.zip   
**Size:** 64.44 MB   
**Status:** CONFIRMED — permanent and publicly retrievable   

Retrieve via [turbo-gateway](https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps) or [arweave.net](https://arweave.net/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps). 

Verify on-chain: [ViewBlock](https://viewblock.io/arweave/tx/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps)

Transaction independently verified via ViewBlock explorer ([screenshot](arweave-transaction-verification-2026-03-29.png)) on 29 March 2026 (block 1,884,750; 1,468 confirmations as at that date).

### Significance   
Arweave provides permanent, immutable storage of the complete audit archive. The file cannot be altered, removed, or taken down. Transactions are verified on the Arweave blockchain and stored permanently across the distributed network.

### Access   
**Current Version (v1.9.2)**      
**Direct Link:** https://turbo-gateway.com/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps  
**Status Verification:** https://viewblock.io/arweave/tx/TNVdy5y__FCWRvXA1pBTQQ-kEBJfG-SOdb7JEmnbeps  

---

## Internet Archive (Wayback Machine)

**Latest Snapshot:** 15 June 2026  
**Archive URL:** https://web.archive.org/web/20260615104416/https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit

### Significance

Internet Archive preserves dated snapshots of this repository's public web presence, providing legally-recognised evidence that content was publicly accessible at specific points in time. This complements blockchain verification by proving not just that files existed (Bitcoin/Arweave) but that they were publicly visible on the web.

### Access

**View All Snapshots:** https://web.archive.org/web/*/github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit*

### Verification

To view historical snapshots:
1. Visit the archive URL above
2. Select any dated snapshot to view repository as it appeared
3. Confirms content was publicly accessible on specific dates
4. Provides independent third-party evidence of temporal evolution

---

## Internet Archive – Direct Upload

### Current Version (v1.9.4) — Full Repository     
**Upload Date:** 2026-08-19 02:31 UTC   
**Identifier:** tga-covid-19-vaccine-safety-monitoring-audit-v-1.9.4     
**File:** TGA-COVID19-Vaccine-Safety-Monitoring-Audit-v1.9.4.zip       
**Licence:** CC BY 4.0       
**Status:** UPLOADED - Publicly Accessible  

**Direct Link:** https://archive.org/details/tga-covid-19-vaccine-safety-monitoring-audit-v-1.9.4  

### Current Version (v1.9.4) — Audit Report PDF    
**Upload Date:** 2026-08-19 02:41 UTC    
**Identifier:** tga-covid-19-vaccine-safety-monitoring-audit-report_20260819      
**File:** tga-covid19-vaccine-safety-monitoring-audit-report.pdf       
**Licence:** CC BY 4.0         
**Status:** UPLOADED - Publicly Accessible   

**Direct Link:** https://archive.org/details/documentation-gap-analysis-audit-report_20260819

---

## Combined Verification

This audit is protected by multiple independent verification methods:

- **National Library of Australia:** Official Australian Government archive with legal deposit registration and selective historical web archiving (AWA)
- **Zenodo:** DOI-backed permanent academic archive: 10.5281/zenodo.17731054
- **Harvard Dataverse:** Harvard University research data repository supporting long-term preservation, citation, and reproducibility: https://doi.org/10.7910/DVN/BDKZQJ  
- **SSRN:** Academic preprint repository; registered by ORCID: https://ssrn.com/abstract=6333058  
- **Mendeley Data:** Companion dataset repository; Elsevier ecosystem; long-term archiving by DANS: https://data.mendeley.com/datasets/y5wmt6f8j9  
- **SocArXiv – OSF Preprints (Social Sciences):** Social science preprint repository; registered by ORCID: https://doi.org/10.31235/osf.io/sb4gz_v4  
- **Bitcoin:** Cryptographic timestamp proving existence on 29 March 2026 (block 942725)
- **Arweave:** Permanent storage ensuring file accessibility forever
- **Internet Archive:** Web presence verification with dated snapshots
- **GitHub:** Public version control with complete history

**Dataset Paper:** The companion dataset paper and evidence matrix are separately archived at Zenodo (10.5281/zenodo.20175557) and SSRN (10.2139/ssrn.6610438).  

Full deposit records are maintained in [permanent-archive-records](permanent-archive-records-2026-08-19.pdf).

### Preservation Standard

[![ISO 14721:2025](https://img.shields.io/badge/ISO-14721%3A2025-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/87471.html)

The multi-layer archival architecture aligns with ISO 14721:2025 — Open Archival Information System (OAIS) reference model, the international standard for long-term digital preservation. OAIS defines the framework for ingest, archival storage, data management, access, and preservation planning. The independent preservation layers documented above implement OAIS principles of multi-copy redundancy, designated-community access, and long-term availability independent of any single platform.

https://www.iso.org/standard/87471.html

The repository supports long-term preservation and reproducibility consistent with the Australian Code for the Responsible Conduct of Research (2018). The evidence base draws together FOI materials, OAIC proceedings, parliamentary records, and related documentation accumulated over several years that would be difficult to reconstruct in equivalent form.

https://www.nhmrc.gov.au/about-us/publications/australian-code-responsible-conduct-research-2018

Together, the technical preservation layers ensure the audit cannot be suppressed, altered, backdated, or disappeared.

[↑ Back to top](#table-of-contents)

**Last updated:** 7 September 2026
