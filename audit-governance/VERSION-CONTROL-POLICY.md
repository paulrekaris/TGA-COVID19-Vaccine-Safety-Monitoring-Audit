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

See also: [Open Access Framework](README.md#open-access-framework)

**Open Source Intelligence (OSINT) Methodology**
- **Systematic collection**: Structured evidence gathering from FOI releases, OAIC submissions, Senate Hansard, TGA publications, and official databases following IC tradecraft standards [ODNI, 2024](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf).
- **Source verification**: Cross-referencing TGA statements across FOI responses, OAIC submissions, Senate testimony, and published reports to identify contradictions per OSINT evolution principles [Glassman & Kang, 2012](https://doi.org/10.1016/j.chb.2011.11.014).
- **Transparent documentation**: Complete search methodology documented—FOI request scope, OAIC-directed searches, disclosure log analysis—following IC sourcing requirements [ODNI, 2024](https://www.dni.gov/files/documents/ICD/ICS-206-01.pdf) and professional OSINT standards [OSINT Foundation, 2024](https://www.osintfoundation.com/osint/Standards.asp).
- **Replicability**: Evidence collection process structured to enable oversight bodies to independently verify findings using identical FOI/OAIC/Senate sources, following professional OSINT standards [OSINT Foundation, 2024](https://www.osintfoundation.com/osint/Standards.asp).

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

**See:** [Complete Version History](VERSION-HISTORY.md)

## Release Workflow

This audit follows a structured release process ensuring blockchain verification integrity while maintaining version control transparency:

### Version Numbering Scheme

**Semantic Versioning Adapted for Audit Context⁶:**
- **Major versions (X.0.0)**: Fundamental methodology changes or scope revisions
- **Minor versions (1.X.0)**: Content updates including new FOI evidence, analytical enhancements, or findings refinements
- **Patch versions (1.9.X)**: Metadata updates including blockchain verification, archival confirmation, or technical corrections without content changes

### Standard Release Process

Following ISO 15489-1:2016 records management principles² and OSINT documentation standards⁸,⁹,¹⁰, releases follow this workflow:

**Phase 1: Content Release (Minor Version)**
1. Finalise all content changes (new FOI evidence, analytical updates, methodology refinements)
2. Update version number and date in README
3. Document changes in VERSION-HISTORY.md following Keep a Changelog principles⁷
4. Commit changes to Git with descriptive message
5. Create Git tag (e.g., `v1.10`)
6. Push to GitHub and create GitHub Release¹¹

**Phase 2: Blockchain Verification (Patch Version)**
1. Generate cryptographic hash of released version
2. Create Bitcoin blockchain timestamp via OpenTimestamps (OP_RETURN transaction)¹³,¹⁴
3. Upload to Arweave permanent storage network¹⁵
4. Record verification transaction IDs
5. Update VERSION-HISTORY.md with blockchain verification details
6. Create patch version tag (e.g., `v1.10.1`)
7. Document verification completion

**Phase 3: Academic Archival**
1. Upload content release to Zenodo (minor versions only, not patches)
2. Zenodo concept DOI automatically captures all versions¹⁶
3. No repository updates required (uses persistent "all versions" DOI)

### Rationale for Post-Release Verification

Blockchain verification occurs *after* content release rather than before to solve the cryptographic integrity problem:

- **Authenticity principle²**: Including blockchain hashes *within* the version being hashed would alter the hash itself, creating circular dependency
- **ISO 15489-1:2016 compliance²**: Separating content releases from verification metadata maintains record authenticity—the content version remains immutable while verification proves its existence at a point in time
- **OSINT standards⁹,¹⁰**: Verification metadata documents *when* evidence was fixed, not *what* evidence contains—this separation ensures independent verification of investigative findings
- **Audit trail transparency¹²**: Two-phase release (content → verification) creates clear evidence sequence: findings documented, then cryptographically proven to exist at that time

This workflow ensures version integrity while maintaining separation between substantive findings (content releases) and provenance documentation (verification patches), following records management best practices for accountability infrastructure¹⁷.

### Implementation in Practice

**Example workflow for v1.10 release:**
```
v1.10 (Content Release)
├─ New FOI evidence added
├─ Analysis updated  
├─ Git tagged and released
└─ Documented in VERSION-HISTORY.md

v1.10.1 (Verification Patch)
├─ Bitcoin timestamp recorded¹³,¹⁴ (tx: OP_RETURN abc123...)
├─ Arweave storage confirmed¹⁵
├─ Verification details added to VERSION-HISTORY.md
└─ No content changes from v1.10

v1.10 uploaded to Zenodo
└─ Concept DOI includes both v1.10 and v1.10.1
```

This structured approach ensures every release has cryptographic proof of existence while maintaining clean separation between substantive updates and archival metadata, enabling independent verification by oversight bodies following IC OSINT verification standards⁸,⁹.

## Rationale

Regulatory accountability research faces inherent information asymmetry—TGA controls internal records whilst citizens rely on disclosed material subject to FOI redactions, practical refusals, and contradictory institutional positions.

This audit applies transparency and records management standards to its own methodology, modelling the accountability expected of public institutions, whilst employing OSINT principles to systematically gather and verify TGA's publicly available statements.

Detailed version control combined with OSINT documentation serves multiple accountability purposes:

1. **Documents evolution**: Shows how findings developed as TGA positions shifted—initial FOI refusals (2022), OAIC-directed comprehensive searches (September 2024), subsequent practical refusal (June 2025), and Senate testimony confirming no systematic tracking (October 2025).
2. **Prevents retrospective revision**: Creates an immutable record preventing silent correction of claims if TGA later produces contradicting documentation—all prior versions remain accessible.
3. **Demonstrates rigour**: Shows systematic, evidence-based OSINT methodology rather than predetermined conclusions—findings emerged from documented contradictions in TGA's own statements.
4. **Enables verification**: Allows ANAO, OAIC, Ombudsman, Parliament, and peer reviewers to examine both analytical development and independently replicate FOI/Senate/OAIC evidence gathering.
5. **Builds trust**: Transparent error correction demonstrates intellectual honesty—documented OSINT methodology enables oversight bodies to verify investigative approach meets IC standards.

Version history combined with OSINT documentation enables accountability infrastructure—proving claims evolved through systematic evidence gathering from TGA's own statements whilst meeting international standards for records integrity, audit quality, and intelligence community investigative methodology.

## References

**International Standards:**

1. ISO 19011:2018 - Guidelines for auditing management systems. [International Organization for Standardization](https://www.iso.org/standard/70017.html).

2. ISO 15489-1:2016 - Information and documentation — Records management — Part 1: Concepts and principles. [International Organization for Standardization](https://www.iso.org/standard/62542.html).

**Open Access:**

3. Suber, P. (2012). *Open Access*. MIT Press. Chapter 10: Self-Help. <https://cyber.harvard.edu/hoap/Open_Access_(the_book)>

4. Suber, P. (n.d.). How to make your own work open access. Harvard Open Access Project. <https://cyber.harvard.edu/hoap/How_to_make_your_own_work_open_access>

**OSINT Methodology:**

5. Glassman, M., & Kang, M. J. (2012). Intelligence in the internet age: The emergence and evolution of Open Source Intelligence (OSINT). *Computers in Human Behavior*, 28(2), 673–682. <https://doi.org/10.1016/j.chb.2011.11.014>

6. Keep a Changelog. <https://keepachangelog.com/>

7. Preston-Werner, T. (2013). Semantic Versioning 2.0.0. <https://semver.org/spec/v2.0.0.html>

8. Office of the Director of National Intelligence. (2024). *The IC OSINT Strategy 2024-2026*. <https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf>

9. Office of the Director of National Intelligence. (2024). *Intelligent Community Directive, 206: Sourcing Requirements for Disseminated Analytic Products. Technical Amendment <https://www.dni.gov/files/documents/ICD/ICD-206.pdf>

10. OSINT Foundation. (2024). *Principles for OSINT Professionals*. <https://www.osintfoundation.com/osint/Standards.asp>

**Version Control and Release Management:**

11. GitHub. (2024). Managing releases in a repository. GitHub Docs. <https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository>

12. GitHub. (2024). Reviewing the audit log for your organisation. GitHub Docs. <https://docs.github.com/en/organizations/keeping-your-organization-secure/managing-security-settings-for-your-organization/reviewing-the-audit-log-for-your-organization>

**Blockchain Verification and Archival:**

13. OpenTimestamps. (2024). OpenTimestamps client documentation. <https://github.com/opentimestamps/opentimestamps-client>

14. Nakamoto, S. (2008). *Bitcoin: A Peer-to-Peer Electronic Cash System*. <https://bitcoin.org/bitcoin.pdf>

15. Williams, S. (2018). *Arweave Yellow Paper*. <https://www.arweave.org/yellow-paper.pdf>

16. Zenodo Support. (n.d.). What is DOI versioning? <https://support.zenodo.org/help/en-gb/1-upload-deposit/97-what-is-doi-versioning>

**Records Management:**

17. National Archives of Australia. (n.d.). *Digital Recordkeeping: Guidelines for Creating, Managing...* (aligned ISO 15489). <https://mayaarbinaginting.weebly.com/uploads/1/0/6/1/10612501/digital_recordkeeping.pdf>

**Research Transparency:**

18. Nosek, B. A., et al. (2015). Promoting an open research culture. *Science*, 348(6242), 1422–1425. <https://doi.org/10.1126/science.aab2374>

19. Munafò, M. R., et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*, 1(0021). <https://doi.org/10.1038/s41562-016-0021>
