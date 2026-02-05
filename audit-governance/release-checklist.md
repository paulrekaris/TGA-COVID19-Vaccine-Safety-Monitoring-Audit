# Release Checklist

**Use this checklist to execute the release workflow:**

## Phase 1: Content Finalisation ✓
- [ ] Finalised all content changes
- [ ] Updated version number in README
- [ ] Documented changes in VERSION-HISTORY.md
- [ ] Commit all changes with descriptive release message

## Phase 2: Release and Academic Archival
- [ ] Create Git tag: `v__________`
- [ ] Push to GitHub: `git push origin v__________`
- [ ] Create GitHub Release (Title: "Version X.X.X - Brief Description of Major Changes")
- [ ] Upload repository to Zenodo
- [ ] Obtain new DOI from Zenodo: `10.5281/zenodo._______`
- [ ] Update DOI badge in README with new DOI
- [ ] Update VERSION-HISTORY.md archive note to: "Zenodo DOI updated. Blockchain verification pending."
- [ ] Commit archive note update

## Phase 3: Blockchain Verification
- [ ] Generate cryptographic hash of released version
- [ ] Create Bitcoin timestamp via OpenTimestamps
- [ ] Record Bitcoin transaction ID: `___________________________`
- [ ] Upload to Arweave permanent storage
- [ ] Record Arweave transaction ID: `___________________________`
- [ ] Update VERSION-HISTORY.md with blockchain details
- [ ] Update VERSION-HISTORY.md archive note to: "Zenodo DOI and blockchain verification current. Bitcoin timestamp: [tx]. Arweave: [ID]."
- [ ] Update GitHub Release notes with blockchain verification metadata
- [ ] Commit blockchain verification updates

## Post-Release
- [ ] Verify all links work (DOI, GitHub release, archive)
- [ ] Review any workflow/scheduling changes needed
- [ ] Archive completed checklist
