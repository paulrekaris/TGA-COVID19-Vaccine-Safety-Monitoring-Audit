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
- **Free accessibility**: All versions publicly available without paywalls or restrictions (Suber, 2012).
- **Reusability**: Content licensed under CC BY 4.0 enabling adaptation and reuse with attribution.
- **Persistent identifiers**: Zenodo DOIs ensure permanent citability and discoverability.
- **Version transparency**: Full evolution of findings visible through open repositories rather than static publications.

See also: [Open Access Framework](../README.md#open-access-framework) in main README.

**Open Source Intelligence (OSINT) Methodology**
- **Systematic collection**: Structured evidence gathering from publicly available sources following established investigative protocols.
- **Source verification**: Cross-referencing multiple independent sources to validate claims and identify contradictions.
- **Transparent documentation**: Complete search methodology and source identification documented for independent replication.
- **Replicability**: Evidence collection process structured to enable others to verify findings using identical methods.

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

1. **Documents evolution**: Shows how findings developed as new evidence emerged through systematic OSINT collection, FOI processes, parliamentary testimony, and ongoing research, analysis and collaboration with experts
2. **Prevents retrospective revision**: Creates immutable record of claims and their supporting evidence at each point in time
3. **Demonstrates rigour**: Shows systematic, evidence-based OSINT methodology rather than predetermined conclusions
4. **Enables verification**: Allows oversight bodies (ANAO, OAIC, Ombudsman, Parliament) and peer reviewers to examine both the audit's development and independently replicate the evidence gathering process
5. **Builds trust**: Transparent correction of errors demonstrates intellectual honesty and good faith; documented OSINT methodology enables independent verification of investigative approach

Version history combined with OSINT documentation enables accountability infrastructure—proving claims evolved through systematic evidence gathering while meeting international standards for records integrity, audit quality, and investigative methodology.

### References

**International Standards:**
- ISO 19011:2018 - Guidelines for auditing management systems. International Organization for Standardization.
- ISO 15489-1:2016 - Information and documentation — Records management — Part 1: Concepts and principles. International Organization for Standardization.

**Open Access:**
- Suber, P. (2012). *Open Access*. MIT Press. Chapter 10: Self-Help. https://cyber.harvard.edu/hoap/Open_Access_(the_book)
- Suber, P. How to make your own work open access. Harvard Open Access Project. https://cyber.harvard.edu/hoap/How_to_make_your_own_work_open_access

**OSINT Methodology:**
- Williams, M. (2024). The Importance of OSINT Investigative Strategy. OSINT.uk. https://www.osint.uk/content/the-importance-of-osint-investigative-strategy

**Version Control Best Practices:**
- Vandervalk, O. (2017). Keep a Changelog. https://keepachangelog.com/

**Research Transparency:**
- Nosek, B. A., et al. (2015). Promoting an open research culture. *Science*, 348(6242), 1422-1425. https://doi.org/10.1126/science.aab2374
- Munafò, M. R., et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*, 1(0021). https://doi.org/10.1038/s41562-016-0021
