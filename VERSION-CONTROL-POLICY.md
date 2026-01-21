# Version Control Policy

## Purpose
This audit maintains detailed version history reflecting quality management, records management, and research transparency standards applied to regulatory accountability investigation.

## Guiding Standards

**ISO 19011:2018 - Auditing Management Systems**
- **Continuous improvement** (Principle 7): Documentation of corrections, enhancements, and evidence additions through iterative refinement as FOI responses, OAIC submissions, Senate testimony, and peer collaboration reveal new evidence.

**ISO 15489-1:2016 - Records Management**
- **Transparency**: All version changes publicly visible—every FOI response, OAIC submission update, and methodology refinement documented and traceable.
- **Integrity**: Records protected against unauthorised alteration through Git version control and blockchain timestamping, ensuring the audit trail cannot be retrospectively modified.
- **Accountability**: Clear responsibility for version changes with documented rationale—corrections, evidence additions, and analytical refinements explicitly identified.
- **Availability**: Complete version history retrievable through GitHub and permanent archives (Zenodo, Arweave, blockchain), enabling independent verification by oversight bodies.

**Open Access Principles**
- **Free accessibility**: All versions publicly available without paywalls or restrictions, enabling OAIC, Ombudsman, ANAO, Parliament, and peer reviewers to access the complete evidence base [Suber, 2012](https://cyber.harvard.edu/hoap/Open_Access_(the_book)).
- **Reusability**: Content licensed under CC BY 4.0 enabling adaptation and reuse with attribution by researchers, oversight bodies, and FOI applicants.
- **Persistent identifiers**: Zenodo DOIs ensure permanent citability for regulatory proceedings, academic citation, and parliamentary reference.
- **Version transparency**: Full evolution of findings visible—showing how TGA FOI responses, OAIC reviews, and Senate testimony shaped analysis over four years.

See also: [Open Access Framework](README.md#open-access-framework) in main README.

**Open Source Intelligence (OSINT) Methodology**
- **Systematic collection**: Structured evidence gathering from FOI releases, OAIC submissions, Senate Hansard, TGA publications, and official databases following IC tradecraft standards [ODNI, 2024](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf).
- **Source verification**: Cross-referencing TGA statements across FOI responses, OAIC submissions, Senate testimony, and published reports to identify contradictions per OSINT evolution principles [Glassman & Kang, 2012](https://doi.org/10.1016/j.chb.2011.11.014).
- **Transparent documentation**: Complete search methodology documented—FOI request scope, OAIC-directed searches, disclosure log analysis—following IC sourcing requirements [ODNI, 2024](https://www.dni.gov/files/documents/ICD/ICS-206-01.pdf).
- **Replicability**: Evidence collection process structured to enable oversight bodies to independently verify findings using identical FOI/OAIC/Senate sources.

**Research Integrity Standards**
- **Reproducibility**: Detailed changelogs document how findings evolved as TGA responses contradicted earlier positions—enabling reviewers to trace analytical development.
- **Falsifiability**: Version history creates an immutable record of claims at each point—TGA can disprove findings by producing contradicting documentation.
- **Intellectual honesty**: Corrections openly acknowledged rather than silently fixed—arithmetic errors, citation corrections, and analytical refinements explicitly documented.

## Implementation

This audit employs comprehensive version control combining records management standards with OSINT investigative methodology:

- **Git version control**: Every FOI response incorporation, OAIC submission update, and methodology refinement tracked with descriptive commit messages.
- **Version numbering**: Major increments (e.g., 1.8, 1.9) mark significant evidence additions (new FOI releases, OAIC decisions, Senate testimony); minor increments mark corrections.
- **Structured changelogs**: Human-readable history documenting what changed (new evidence), why it changed (FOI response, OAIC finding), and what remained unchanged (core findings).
- **OSINT documentation**: FOI request methodology, OAIC search scope analysis, disclosure log sweep, and source verification processes documented in Appendix A of **[Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf)** for independent replication.
- **Permanent archiving**: Zenodo DOI and blockchain timestamping ensure version history survives potential GitHub removal or institutional pressure.
- **Version-agnostic filenames**: Documents use stable filenames with version control through Git tags—enabling persistent citation in OAIC submissions, Ombudsman complaints, and Senate references.

**See:** [Complete Version History](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/blob/main/VERSION-HISTORY.md)

## Rationale

Regulatory accountability research faces inherent information asymmetry—TGA controls internal records while citizens rely on disclosed material subject to FOI redactions, practical refusals, and contradictory institutional positions.

This audit applies transparency and records management standards to its own methodology, modelling the accountability expected of public institutions, while employing OSINT principles to systematically gather and verify TGA's publicly available statements.

Detailed version control combined with OSINT documentation serves multiple accountability purposes:

1. **Documents evolution**: Shows how findings developed as TGA positions shifted—initial FOI refusals (2022), OAIC-directed comprehensive searches (September 2024), subsequent practical refusal (June 2025), and Senate testimony confirming no systematic tracking (October 2025).
2. **Prevents retrospective revision**: Creates an immutable record preventing silent correction of claims if TGA later produces contradicting documentation—all prior versions remain accessible.
3. **Demonstrates rigour**: Shows systematic, evidence-based OSINT methodology rather than predetermined conclusions—findings emerged from documented contradictions in TGA's own statements.
4. **Enables verification**: Allows ANAO, OAIC, Ombudsman, Parliament, and peer reviewers to examine both analytical development and independently replicate FOI/Senate/OAIC evidence gathering.
5. **Builds trust**: Transparent error correction demonstrates intellectual honesty—documented OSINT methodology enables oversight bodies to verify investigative approach meets IC standards.

Version history combined with OSINT documentation enables accountability infrastructure—proving claims evolved through systematic evidence gathering from TGA's own statements while meeting international standards for records integrity, audit quality, and intelligence community investigative methodology.

## References

International Standards:
- ISO 19011:2018 - Guidelines for auditing management systems. [International Organization for Standardization](https://www.iso.org/standard/70017.html).
- ISO 15489-1:2016 - Information and documentation — Records management — Part 1: Concepts and principles. [International Organization for Standardization](https://www.iso.org/standard/62542.html).

Open Access:
- Suber, P. (2012). *Open Access*. MIT Press. Chapter 10: Self-Help. <https://cyber.harvard.edu/hoap/Open_Access_(the_book)>
- Suber, P. (n.d.). How to make your own work open access. Harvard Open Access Project. <https://cyber.harvard.edu/hoap/How_to_make_your_own_work_open_access>

OSINT Methodology:
- Office of the Director of National Intelligence. (2024). *The IC OSINT Strategy 2024-2026*. <https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf>
- Office of the Director of National Intelligence. (2024). *ICS 206-01: Sourcing Requirements for Disseminated Analytic Products (Publicly Available Information, Commercially Available Information, and Open Source Intelligence)*. <https://www.dni.gov/files/documents/ICD/ICS-206-01.pdf>
- Glassman, M., & Kang, M. J. (2012). Intelligence in the internet age: The emergence and evolution of Open Source Intelligence (OSINT). *Computers in Human Behavior*, 28(2), 673–682. <https://doi.org/10.1016/j.chb.2011.11.014>

Version Control Best Practices:
- Vandervalk, O. (2017). Keep a Changelog. <https://keepachangelog.com/>

Research Transparency:
- Nosek, B. A., et al. (2015). Promoting an open research culture. *Science*, 348(6242), 1422–1425. <https://doi.org/10.1126/science.aab2374>
- Munafò, M. R., et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*, 1(0021). <https://doi.org/10.1038/s41562-016-0021>
