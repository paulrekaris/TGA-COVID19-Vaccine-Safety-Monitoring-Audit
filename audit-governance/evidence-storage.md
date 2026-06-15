# Evidence Storage Methodology and Research Standards

[![ISO 15489-1:2016](https://img.shields.io/badge/ISO-15489--1%3A2016-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/62542.html) [![Open Access](https://img.shields.io/badge/Open%20Access-MIT%20Press%202012-E67E22?labelColor=E67E22&style=flat-square)](https://cyber.harvard.edu/hoap/Open_Access_(the_book)) [![FAIR Principles](https://img.shields.io/badge/FAIR-Data%20Principles-000000?labelColor=000000&style=flat-square)](https://doi.org/10.1038/sdata.2016.18) [![DPC](https://img.shields.io/badge/DPC-Digital%20Preservation%20Handbook-1A7A4A?labelColor=1A7A4A&style=flat-square)](https://www.dpconline.org/handbook)

## Overview

This document explains the approach used to manage evidence sources in this audit, distinguishing between materials archived locally and those cited by reference through stable institutional sources.

---

## Source Storage Approach

This repository follows open research principles by archiving primary sources central to the audit's findings while citing publicly accessible supporting materials by reference.

## Repository Folder Structure

**Primary sources** contains original government and regulatory documents obtained through FOI processes, official proceedings, or direct government publication — material that constitutes the evidentiary record of the audit. 

**Reference documents** contains supporting analytical and contextual material including peer-reviewed literature, legal case notes, and international standards cited in the audit methodology. 

Some documents serve both functions; classification reflects their primary role in the audit. This classification aligns with ISO 15489-1:2016 principles distinguishing records that constitute evidence of activities (primary sources) from supporting reference material (reference documents).

### Archived Locally

- FOI responses and decisions (including OAIC MR22/00538 and AICmr 54) (risk of URL changes/removal)
- TGA policy documents and guidance (version control)
- Senate testimony transcripts (completeness)
- OAIC decisions (permanent record)
- International standards (ISO, ICH, CIOMS) (freely available; ICH E2E and CIOMS VIII archived locally)

All locally archived materials are additionally protected through:
- Bitcoin timestamping (cryptographic proof of existence)
- Arweave permanent storage (censorship-resistant archiving)
- Internet Archive snapshots (web presence verification)
- Zenodo DOI archiving (academic permanence)

### Cited by Reference

- Peer-reviewed journal articles (stable DOIs)
- Legislation and acts (official government sources)
- International standards (ISO) (purchasable/library accessible)
- Methodology frameworks (Open Access, OSINT, ANAO) (stable institutional URLs)

This approach balances repository size constraints with research reproducibility, ensuring core evidence remains accessible and independently re-checkable while maintaining verifiable citations to supporting materials.

---

## Research Standards

This approach aligns with established research transparency and data management principles:

### FAIR Principles (Findable, Accessible, Interoperable, Reusable)

Data and evidence should be findable through persistent identifiers, accessible for verification, interoperable across systems, and reusable by others. This audit archives core evidentiary documents to ensure permanent accessibility whilst citing stable institutional sources that meet FAIR criteria. Persistent identifiers (Zenodo DOI, GitHub tags, and stable legislative URLs) are used to support long-term findability and verification.

**Reference:** Wilkinson, M. D., et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data*, 3, 160018. https://doi.org/10.1038/sdata.2016.18

### Open Access and Reproducibility

Open access research requires that sources be freely available for independent verification. Suber (2012) emphasises that open access removes barriers to knowledge by ensuring research materials are "digital, online, free of charge, and free of most copyright and licensing restrictions." This audit implements green open access by self-archiving primary sources whilst citing publicly accessible supporting materials.

**Reference:** Suber, P. (2012). *Open Access*. MIT Press. Chapter 3: Policies. https://mitpress.mit.edu/9780262517638/open-access/

### Digital Preservation

Standard digital preservation principles recognise that government websites and official documents are at risk of removal, modification, or link decay. The Digital Preservation Coalition emphasises the importance of archiving at-risk materials to ensure long-term accessibility and authenticity. This audit archives FOI responses, government documents, and regulatory decisions subject to these risks, whilst citing peer-reviewed literature and legislation through permanent institutional sources.

This audit implements multiple preservation layers including blockchain verification (Bitcoin, Arweave), web archival services (Internet Archive), and academic repositories (Zenodo) to ensure evidence remains accessible and tamper-evident.

**Reference:** Whyte, A., & Tedds, J. (2011). *Making the Case for Research Data Management*. Digital Curation Centre. https://www.dcc.ac.uk/resources/briefing-papers/making-case-rdm

### Data Management Best Practices

Standard data management principles distinguish between materials requiring local archiving (at-risk or version-controlled sources) and those reliably available through stable institutional repositories. This selective archiving approach follows open science principles whilst managing repository scope.

**Reference:** Research Data Alliance. (2020). *Data Management Planning*. https://www.rd-alliance.org/

---

## Implementation Notes

- Core evidentiary documents (FOI responses, TGA decisions, senate testimony) are stored in this repository to ensure permanent accessibility regardless of government website changes

- Supporting materials (journal articles, standards, frameworks) are cited through stable DOIs and institutional URLs that provide reliable long-term access

- This selective archiving approach follows open science principles while managing repository scope

- All archived materials include metadata (date archived, source URL where applicable) to support verification and citation

---

**Document Version:** 1.0  
**Last Updated:** 21 March 2026 
**Licence:** CC BY 4.0
