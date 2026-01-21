## Version Control Policy

### Purpose
This audit maintains detailed version history reflecting quality management, records management, and research transparency standards.

### Guiding Standards

**ISO 19011:2018 - Auditing Management Systems**
- **Continuous improvement** (Principle 7): Documentation of corrections, enhancements, and evidence additions through iterative refinement based on new evidence and feedback.

**ISO 15489-1:2016 - Records Management**
- **Transparency**: Records processes documented and available for scrutiny—every version change publicly visible.
- **Integrity**: Records protected against unauthorised alteration through Git version control and blockchain timestamping.
- **Accountability**: Clear responsibility for version changes with documented rationale.
- **Availability**: Complete version history retrievable and understandable through GitHub and permanent archives.

**Open Access Principles**
- **Free accessibility**: All versions publicly available without paywalls or restrictions [Suber (2012)](https://cyber.harvard.edu/hoap/Open_Access_(the_book)).
- **Reusability**: Content licensed under CC BY 4.0 enabling adaptation and reuse with attribution.
- **Persistent identifiers**: Zenodo DOIs ensure permanent citability and discoverability.
- **Version transparency**: Full evolution of findings visible through open repositories rather than static publications.

See also: [Open Access Framework](README.md#open-access-framework) in main README.

**Open Source Intelligence (OSINT) Methodology**
- **Systematic collection**: Structured evidence gathering from publicly available sources following IC tradecraft standards [ODNI, 2024](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf).
- **Source verification**: Cross-referencing multiple independent sources to validate claims per OSINT evolution principles [Glassman & Kang, 2012](https://doi.org/10.1016/j.chb.2011.11.014).
- **Transparent documentation**: Complete search methodology documented following professional standards [OSINT Foundation, 2024](https://www.osintfoundation.com/osint/Standards.asp).
- **Replicability**: Evidence process structured for replication using established protocols.

**Research Integrity Standards**
- **Reproducibility**: Detailed changelogs enable others to understand precisely what changed and why.
- **Falsifiability**: Version history creates permanent record that cannot be quietly altered—any revision attempt is publicly visible.
- **Intellectual honesty**: Corrections (e.g., arithmetic errors) openly acknowledged rather than silently fixed.

### Implementation

This audit employs comprehensive version control practices combining records management standards with OSINT investigative methodology:

- **Git version control**: Every change tracked with descriptive commit messages
- **Version numbering**: Major version increments (1.8, 1.9) distinguish significant evidence additions from minor corrections
- **Structured changelogs**: Human-readable version history documenting what changed, why it changed, and what remained unchanged
- **OSINT documentation**: Search methodology, source identification, and evidence verification processes documented in Appendix A in **[Main Audit Report](analysis/documentation-gap-analysis-audit-report.pdf)** for independent replication
- **Permanent archiving**: Zenodo DOI and blockchain timestamping ensure version history cannot be erased or retrospectively altered
- **Version-agnostic filenames**: Documents use stable filenames (e.g., `documentation-gap-analysis-audit-report.pdf`) with version control managed through Git tags and releases

**See:** [Complete Version History](https://github.com/paulrekaris/TGA-COVID19-Vaccine-Safety-Monitoring-Audit/blob/main/VERSION-HISTORY.md)

### Rationale

Institutional accountability research faces inherent power asymmetry—regulators control internal records while citizens rely on disclosed material. This audit applies transparency and records management standards to its own methodology, modelling the accountability expected of public institutions, while employing Open Source Intelligence principles to systematically gather and verify publicly available evidence.

Detailed version control combined with OSINT methodology serves multiple purposes:

1. **Documents evolution**: Shows how findings developed as new evidence emerged through systematic OSINT collection, FOI processes, parliamentary testimony, and ongoing research analysis and collaboration with experts
2. **Prevents retrospective revision**: Creates immutable record of claims and their supporting evidence at each point in time
3. **Demonstrates rigour**: Shows systematic, evidence-based OSINT methodology rather than predetermined conclusions
4. **Enables verification**: Allows oversight bodies (ANAO, OAIC, Ombudsman, Parliament) and peer reviewers to examine both the audit's development and independently replicate the evidence gathering process
5. **Builds trust**: Transparent correction of errors demonstrates intellectual honesty and good faith; documented OSINT methodology enables independent verification of investigative approach

Version history combined with OSINT documentation enables accountability infrastructure—proving claims evolved through systematic evidence gathering while meeting international standards for records integrity, audit quality, and investigative methodology.

### References

**International Standards:**
- ISO 19011:2018 - Guidelines for auditing management systems. [International Organization for Standardization](https://www.iso.org/standard/70017.html).
- ISO 15489-1:2016 - Information and documentation — Records management — Part 1: Concepts and principles. [International Organization for Standardization](https://www.iso.org/standard/62542.html).

**Open Access:**
- Suber, P. (2012). *Open Access*. MIT Press. Chapter 10: Self-Help. [https://cyber.harvard.edu/hoap/Open_Access_(the_book)](https://cyber.harvard.edu/hoap/Open_Access_(the_book))
- Suber, P. How to make your own work open access. [Harvard Open Access Project](https://cyber.harvard.edu/hoap/How_to_make_your_own_work_open_access).

**OSINT Methodology:**
- Office of the Director of National Intelligence. (2024). *The IC OSINT Strategy 2024-2026*. [https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf)
- Glassman, M., & Kang, M. J. (2012). Intelligence in the internet age: The emergence and evolution of Open Source Intelligence (OSINT). *Computers in Human Behavior*, 28(2), 673-682. [https://doi.org/10.1016/j.chb.2011.11.014](https://doi.org/10.1016/j.chb.2011.11.014)
- OSINT Foundation. (2024). *Principles for OSINT Professionals*. [https://www.osintfoundation.com/osint/Standards.asp](https://www.osintfoundation.com/osint/Standards.asp)

**Version Control Best Practices:**
- Vandervalk, O. (2017). [Keep a Changelog](https://keepachangelog.com/).

**Research Transparency:**
- Nosek, B. A., et al. (2015). Promoting an open research culture. *Science*, 348(6242), 1422-1425. [https://doi.org/10.1126/science.aab2374](https://doi.org/10.1126/science.aab2374)
- Munafò, M. R., et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*, 1(0021). [https://doi.org/10.1038/s41562-016-0021](https://doi.org/10.1038/s41562-016-0021)
