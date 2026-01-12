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

**Research Integrity Standards**
- **Reproducibility**: Detailed changelogs enable others to understand precisely what changed and why.
- **Falsifiability**: Version history creates permanent record that cannot be quietly altered—any revision attempt is publicly visible.
- **Intellectual honesty**: Corrections (e.g., arithmetic errors) openly acknowledged rather than silently fixed.

### Implementation

This audit employs comprehensive version control practices:

- **Git version control**: Every change tracked with descriptive commit messages
- **Version numbering**: Major version increments (1.8, 1.9) distinguish significant evidence additions from minor corrections
- **Structured changelogs**: Human-readable version history documenting what changed, why it changed, and what remained unchanged
- **Permanent archiving**: Zenodo DOI and blockchain timestamping ensure version history cannot be erased or retrospectively altered
- **Version-agnostic filenames**: Documents use stable filenames (e.g., `TGA-Audit-Report.pdf`) with version control managed through Git tags and releases

### Rationale

Institutional accountability research faces inherent power asymmetry—regulators control internal records while citizens rely on disclosed material. This audit applies transparency and records management standards to its own methodology, modelling the accountability expected of public institutions.

Detailed version control serves multiple purposes:

1. **Documents evolution**: Shows how findings developed as new evidence emerged through FOI processes
2. **Prevents retrospective revision**: Creates immutable record of claims and their supporting evidence at each point in time
3. **Demonstrates rigour**: Shows systematic, evidence-based methodology rather than predetermined conclusions
4. **Enables verification**: Allows oversight bodies (ANAO, OAIC, Parliament) and peer reviewers to examine the audit's development
5. **Builds trust**: Transparent correction of errors demonstrates intellectual honesty and good faith

Version history enables accountability infrastructure—proving claims evolved through systematic evidence gathering while meeting international standards for records integrity and audit quality.

### References

**International Standards:**
- ISO 19011:2018 - Guidelines for auditing management systems. International Organization for Standardization.
- ISO 15489-1:2016 - Information and documentation — Records management — Part 1: Concepts and principles. International Organization for Standardization.

**Version Control Best Practices:**
- Vandervalk, O. (2017). Keep a Changelog. https://keepachangelog.com/

**Research Transparency:**
- Nosek, B. A., et al. (2015). Promoting an open research culture. *Science*, 348(6242), 1422-1425. https://doi.org/10.1126/science.aab2374
- Munafò, M. R., et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*, 1(0021). https://doi.org/10.1038/s41562-016-0021
