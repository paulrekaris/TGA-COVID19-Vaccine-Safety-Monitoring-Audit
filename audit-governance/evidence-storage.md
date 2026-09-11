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

Some documents serve both functions; classification reflects their primary role in the audit. This classification is consistent with ISO 15489-1:2016 principles concerning records as evidence of activities, while distinguishing primary-source evidence from supporting reference material for the purposes of this audit.

### Archived Locally

* FOI responses and decisions (including OAIC MR22/00538 and AICmr 54) (risk of URL changes/removal)
* TGA policy documents and guidance (version control)
* Senate testimony transcripts (completeness)
* OAIC decisions (authoritative public record)
* International pharmacovigilance standards and guidance, including ICH E2E and CIOMS VIII where archived locally

All locally archived materials are additionally protected through:

* Bitcoin timestamping (cryptographic proof of existence)
* Arweave permanent storage (censorship-resistant archiving)
* Internet Archive snapshots (web presence verification)
* Zenodo DOI archiving (persistent scholarly preservation)

### Cited by Reference

* Peer-reviewed journal articles (stable DOIs)
* Legislation and Acts (official government sources)
* International standards (ISO) (purchasable/library accessible)
* Methodology frameworks (Open Access, OSINT, ANAO) (stable institutional URLs)

This approach balances repository size constraints with research reproducibility, ensuring core evidence remains accessible and independently re-checkable while maintaining verifiable citations to supporting materials.

---

## Research Standards

This approach aligns with established research transparency and data management principles:

### FAIR Principles (Findable, Accessible, Interoperable, Reusable)

Data and evidence should be findable through persistent identifiers, accessible for verification, interoperable across systems, and reusable by others. This audit archives core evidentiary documents to support long-term accessibility whilst citing stable institutional sources that support FAIR-aligned access and verification. Persistent identifiers (including Zenodo DOIs), together with GitHub version tags and stable institutional URLs, support long-term findability and verification.

**Reference:** Wilkinson, M. D., et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data*, 3, 160018. https://doi.org/10.1038/sdata.2016.18

### Open Access and Reproducibility

Suber (2012) describes open access literature as "digital, online, free of charge, and free of most copyright and licensing restrictions." This audit supports open verification by making its own research outputs openly available and, where legally and practically appropriate, preserving primary-source materials relied upon in the analysis.

**Reference:** Suber, P. (2012). *Open Access*. MIT Press. Chapter 3: Policies. https://mitpress.mit.edu/9780262517638/open-access/

### Digital Preservation

Standard digital preservation principles recognise that government websites and official documents are at risk of removal, modification, or link decay. The Digital Preservation Coalition emphasises the importance of preserving at-risk digital materials to support long-term accessibility and authenticity. This audit archives FOI responses, government documents, and regulatory decisions subject to these risks, whilst citing peer-reviewed literature and legislation through stable institutional sources.

This audit implements multiple preservation layers including cryptographic verification and preservation mechanisms (Bitcoin timestamping and Arweave), web archival services (Internet Archive), and academic repositories (Zenodo) to support long-term evidence accessibility and make retrospective alteration detectable.

**References:**
Digital Preservation Coalition. *Digital Preservation Handbook*. https://www.dpconline.org/handbook
Whyte, A., & Tedds, J. (2011). *Making the Case for Research Data Management*. Digital Curation Centre. https://www.dcc.ac.uk/resources/briefing-papers/making-case-rdm

### Data Management Best Practices

Standard data management principles support the appropriate preservation and management of research materials according to their characteristics, value, accessibility, and preservation requirements. This selective archiving approach applies those principles while managing repository scope.

**Reference:** Research Data Alliance. https://www.rd-alliance.org/

---

## Implementation Notes

* Core evidentiary documents (FOI responses, TGA decisions, Senate testimony) are stored in this repository to support long-term accessibility regardless of government website changes

* Supporting materials (journal articles, standards, frameworks) are cited through stable DOIs and institutional URLs that support reliable long-term access

* This selective archiving approach follows open research principles while managing repository scope

* Archived materials are accompanied by metadata (date archived, source URL where applicable) to support verification and citation

---

**Document Version:** 1.0       
**Last Updated:** 11 September 2026          

**Licence:** CC BY 4.0
