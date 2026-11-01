# Release Workflow Checklist

[![ISO 19011:2018](https://img.shields.io/badge/ISO-19011%3A2018-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/70017.html) [![ISO 15489-1:2016](https://img.shields.io/badge/ISO-15489--1%3A2016-CC0000?labelColor=CC0000&style=flat-square)](https://www.iso.org/standard/62542.html) [![Semantic Versioning](https://img.shields.io/badge/Semver-2.0.0-000000?labelColor=000000&style=flat-square)](https://semver.org/) [![Zenodo](https://img.shields.io/badge/Zenodo-Best%20Practice-blue?style=flat-square)](https://help.zenodo.org/)  [![GitHub](https://img.shields.io/badge/GitHub-Release%20Management-000000?labelColor=000000&style=flat-square)](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository) 

## Phase 1: Content Finalisation (Always Required)
- [ ] Finalise all content changes
- [ ] Search the repo for the old version number to catch anything missed
- [ ] Update the version and the planned release date in:
  - [ ] `README.md`: version badge, "(Version ...)" citation, BibTeX `version =`, "Document Version"
  - [ ] `CITATION.cff`: `version:` and `date-released:`
  - [ ] `PUBLICATIONS.md`: BibTeX `version =`
  - [ ] `docs/index.md`: front matter `version:` and the footer
  - [ ] `docs/index.html`: the footer
  - [ ] `docs/llms.txt`: the `Version:` line
  - [ ] `analysis/dataset-codebook.md`: "(v...)" in the opening text and in the "as at" sentence
- [ ] Update dates: `docs/metadata.md` (`date_modified`), `docs/sitemap.xml` (`lastmod`), and the "Last Updated" lines in `README.md` and `FAQ.md`
- [ ] In `version-history.md`, replace "Unreleased" in the heading and contents entry with the release date and update "Last updated". Leave the compare link at `HEAD` until the tag exists
- [ ] Decide whether `NEWS.md` gets a release entry now or after the FOI decision
- [ ] Draft the GitHub release notes and the Zenodo version notes
- [ ] Document changes in version-history.md
- [ ] Update archive notes in version-history.md and README to: "Zenodo DOI current. Blockchain and Arweave verification pending."
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
- [ ] Verify new version appears under Concept DOI on Zenodo: `10.5281/zenodo.17731054`
- [ ] In `version-history.md`, change the compare link to `previous...new` now that the tag exists
- [ ] Record the version-specific Zenodo DOI

---

## Phase 3: Blockchain Verification (When Required)

**Apply to:** 
- Major evidentiary milestones
- Before critical submissions (OAIC, Ombudsman, Senate)
- Annual archival snapshots
- When permanent cryptographic proof is strategically valuable

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
- [ ] Update version-history.md with blockchain details
- [ ] Update the archive note in both version-history.md and the `README.md` "Archive:" line to: "Zenodo DOI current. Bitcoin timestamp: [tx]. Arweave: [ID]."
- [ ] Upload the ZIP to the Internet Archive as `tga-covid-19-vaccine-safety-monitoring-audit-v-<version>`
- [ ] Update the Internet Archive links in `FAQ.md` (two places) and `README.md`
- [ ] Lodge the report PDF with NLA National edeposit and record the deposit ID
- [ ] Add the new version's entry to `blockchain-and-archival-verification/README.md` and check whether the previous version's entry is missing
- [ ] Regenerate the permanent archive records PDF with the new NED ID, Zenodo version DOI and dates
- [ ] Update the "Permanent record" entries on `docs/index.html` and `docs/index.md`
- [ ] Re-capture the repo in Software Heritage
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

**Semantic Versioning Convention (adapted for audit context):**
- **MAJOR (X.0.0):** Fundamental restructure or major evidentiary additions
- **MINOR (X.Y.0):** Substantive content changes (new evidence, analysis, documents)
- **PATCH (X.Y.Z):** Minor corrections, clarifications, metadata updates

---

## References and Standards

This workflow checklist aligns with the following frameworks:

**ISO 19011:2018 - Guidelines for auditing management systems**
- https://www.iso.org/standard/70017.html
- Phase 1 supports Clause 6.5 (preparing and distributing the audit report); Phase 4 provides post-release quality assurance and verification.

**ISO 15489-1:2016 — Information and documentation — Records management**: Workflow aligns with ISO 15489-1:2016 via structured creation, controls, metadata, long-term preservation (Zenodo, blockchain), and Git version control for reproducible audit trails.
- https://www.iso.org/standard/62542.html

**Semantic Versioning 2.0.0**
- https://semver.org/
- Provides the MAJOR.MINOR.PATCH adapted for this repository

**Zenodo Best Practices**
- Main documentation: https://help.zenodo.org/
- GitHub integration: https://support.zenodo.org/help/en-gb/24-github-integration
- Citation guidance: https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content
- Phase 2 implements Zenodo's concept DOI and version-specific DOI guidance

**Data Versioning and Reproducibility**
- Research Data Alliance: https://zenodo.org/records/3772870 (Data Versioning Principles)
- Phase 3 blockchain verification supports cryptographic verification

---

**Last Updated:** 1 November 2026
