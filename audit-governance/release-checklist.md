# Release Workflow Checklist


## Phase 1: Content Finalisation (Always Required)
- [ ] Finalise all content changes
- [ ] Update version number and date in README and CITATIONS
- [ ] Document changes in VERSION-HISTORY.md
- [ ] Update archive notes in VERSION-HISTORY.md and README to: "Zenodo DOI current. Blockchain and Arweave verification pending."
- [ ] Review and test:
  - [ ] Run automated checks (CI status green, if applicable)
  - [ ] Verify all links work
  - [ ] Check formatting in key documents
  - [ ] Ensure no placeholder text remains
- [ ] Commit: `"vX.X.X: Prepare release notes"`
- [ ] Push to main

---

## Phase 2: Release and Academic Archival
- [ ] Create Git tag: `v__________`
- [ ] Push to GitHub: `git push origin v__________`
- [ ] Create GitHub Release with appropriate title (triggers Zenodo upload automatically)
- [ ] Verify new version appears under Concept DOI on Zenodo: `10.5281/zenodo._______`

---

## Phase 3: Blockchain Verification (When Required)

**Apply to:** 
- Major evidentiary milestones
- Before critical submissions (OAIC, Ombudsman, Senate)
- Annual archival snapshots
- When permanent immutable proof is strategically valuable

**Skip for:** Routine documentation updates, minor corrections

### Blockchain Steps:
- [ ] Download repository ZIP from GitHub release
- [ ] Get commit hash: `git rev-parse HEAD`
- [ ] Generate SHA-256 hash of ZIP file
- [ ] Create Bitcoin timestamp via OpenTimestamps
- [ ] Record Bitcoin transaction ID: `___________________________`
- [ ] Upload ZIP to Arweave permanent storage
- [ ] Record Arweave transaction ID: `___________________________`
- [ ] Verify Arweave transaction is retrievable via public gateway (e.g., arweave.net)

### Documentation Updates:
- [ ] Update blockchain verification README.md in `/blockchain-and-archival-verification/` folder
- [ ] Upload Bitcoin timestamp verification PNG to `/blockchain-and-archival-verification/`
- [ ] Upload permanent archive records PDF to `/blockchain-and-archival-verification/`
- [ ] Update VERSION-HISTORY.md with blockchain details
- [ ] Update VERSION-HISTORY.md archive note to: "Zenodo DOI current. Bitcoin timestamp: [tx]. Arweave: [ID]."
- [ ] Update GitHub Release notes with blockchain verification metadata
- [ ] Commit: `"vX.X.X: Add blockchain verification"`
- [ ] Push blockchain verification updates

---

## Phase 4: Post-Release Verification (Always Required)
- [ ] Verify all links work (DOI, GitHub release, archive URLs)
- [ ] Check GitHub Pages deployment succeeded
- [ ] Test that release is accessible and properly formatted
- [ ] Review any workflow improvements needed for next release
- [ ] Archive completed checklist with release notes

---

## Release Guide

**What type of release is this?**

| Release Type | Phases Required | Example | Typical Triggers |
|--------------|-----------------|---------|------------------|
| **Minor content update** | 1, 2, 4 | Documentation clarifications | Routine updates, typo fixes |
| **Major content release** | 1, 2, 4 | New evidence, analysis, submissions | Significant FOI responses, new analysis |
| **Evidentiary milestone** | 1, 2, 3, 4 | Before legal proceedings, major submissions | Pre-OAIC/Ombudsman submission, Senate inquiry |
| **Metadata/verification only** | 1, 2, 4 | Adding blockchain timestamps to existing release | Post-hoc verification needs |

---

**Semantic Versioning Convention:**
- **MAJOR (X.0.0):** Fundamental restructure or major evidentiary additions
- **MINOR (X.Y.0):** Substantive content changes (new evidence, analysis, documents)
- **PATCH (X.Y.Z):** Minor corrections, clarifications, metadata updates

---

## References and Standards

This workflow checklist aligns with the following frameworks:

**ISO 19011:2018 - Guidelines for auditing management systems**
- https://www.iso.org/standard/70017.html
- Phases 1 & 4 implement Clause 6.5 (audit report preparation) and Clause 6.7 (follow-up activities)

**ISOISO 15489-1:2016 — Information and documentation — Records management**: Workflow aligns with ISO 15489-1:2016 via structured creation, controls, metadata, permanent disposition (Zenodo, blockchain), and Git version control for reproducible audit trails.

**Semantic Versioning 2.0.0**
- https://semver.org/
- Defines MAJOR.MINOR.PATCH increment rules applied in this repository

**Zenodo Best Practices**
- Main documentation: https://help.zenodo.org/
- GitHub integration: https://support.zenodo.org/help/en-gb/24-github-integration
- Citation guidance: https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content
- Phase 2 implements Zenodo's concept DOI and version-specific DOI guidance

**Data Versioning and Reproducibility**
- Research Data Alliance: https://zenodo.org/records/3772870 (Data Versioning Principles)
- Phase 3 blockchain verification supports cryptographic reproducibility

---

**Last Updated:** 2026-02-07
