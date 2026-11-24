# Research Journal #38 exact-version integrity review

Recorded November 24, 2026 from the completed Work verification in Blog Integrity Review (`6b005c39-3e34-83ea-87ad-edc755831d22`).

- Scientific integrity **PASS** for the captured edition. Pinned records support the September 21, 2026 internal software-verification milestone.
- Public evidence package **PASS with a metadata finding**. Release-candidate wording remains in the public package.
- Historical run-record completeness **PROVISIONAL**. Full original output for the exact closure gates and the 851-test Windows run was unavailable. The aggregate outcomes are documented. Archival closure remains unestablished.
- **Category 8 independent reproduction was not established.**

## Exact version and recording checks

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-5821337656101333159`
- Fingerprint `0086a06e49e2e05b696c7397ba62bff28542bb134ffcfd4a1d7c612dd9a0bebe`
- Blogger update `2026-11-23T14:16:09.665-06:00`
- Manifest commit `f9fb69d6d03fb019a26668d9eedb0372cbb19292`, blob `35697deb54438ddf7a2d337b708287dc757bbf01`, 70 monitored articles and 1 pending. Last successful check `2026-11-24T13:33:08.061Z`.
- Snapshot commit `09ae9c9ba537d20873ee05d7d2cf30ba61128dec`, blob `3b4723160d84768b39fa6e13bd01c78c81379ff5`.
- Raw snapshot SHA-256 `6144718283933fe6fd0e94fa8825f2a113af7b10690fa5b475a1dbfff5f344a7` (34,879 bytes).
- Stored HTML SHA-256 equals the fingerprint (17,955 bytes). Stored text SHA-256 `d719b15aab059aec43f1a62d3c7015a3012505837600fea41e0e0a5884cd37da` (14,670 bytes).

Recording read back both GitHub files at their pinned commits, recomputed Git blob IDs and SHA-256 values, opened the published article, and compared the live single-post feed ID, title and update with the manifest. The decoded feed HTML matches the stored HTML byte for byte. Recording also rechecked the preserved public ZIP SHA-256 and its three payload checksums, fetched all eight pinned sources and verified their SHA-256 and GitHub blob IDs, and matched all 21 excerpts to the pinned lines.

[Published article](https://www.beyond-the-light-barrier.com/2026/11/research-journal-38-how-we-verified.html) · [Single-post feed](https://www.beyond-the-light-barrier.com/feeds/posts/default/5821337656101333159?alt=json)

### Pinned BTLB-SIM records

GitHub confirms that candidate `6aebff55f650ada7e59be7852aa3e534ca81ad49` is an ancestor of merge `4543b1fa12b05865c226557f0cf70fffdf6fa97a`. The intervening comparison reports changes only to three architecture documents. The gate runner and classification code have identical blobs at both pins. The acceptance record was committed at 2:34:19 p.m. CDT, and the AR-1.7 scope freeze followed at 2:54:40 p.m., 20 minutes 21 seconds later. [Candidate-to-merge comparison](https://github.com/markkoehn0/btlb-sim/compare/6aebff55f650ada7e59be7852aa3e534ca81ad49...4543b1fa12b05865c226557f0cf70fffdf6fa97a) · [Acceptance record](https://github.com/markkoehn0/btlb-sim/commit/2e3af1d33012c15110d470f3619eafc5ecf2f982) · [AR-1.7 scope freeze](https://github.com/markkoehn0/btlb-sim/commit/51e6d4cfe1e5b906b0691df006205160a4184f5d)

| Recorded run                                                       | Passed | Failed | Skipped             | Deselected |
| ------------------------------------------------------------------ | ------ | ------ | ------------------- | ---------- |
| Candidate, macOS 26.6.2 ARM64, CPython 3.12.14, 16.96 s            | 688    | 0      | 0                   | 1          |
| Candidate, native Windows 11 25H2 AMD64, CPython 3.12.10, 136.42 s | 679    | 0      | 9                   | 1          |
| Merge, macOS 26.6.2 ARM64, CPython 3.12.14, pytest 9.1.1           | 688    | 0      | 0 by reconciliation | 1          |
| Earlier historical-inclusive Windows suite, 851 collected          | 733    | 109    | 9                   | —          |

The nine candidate Windows skips reconcile with the pinned test code. Two exercise historical storage writes with the directory-sync limitation, and seven compare against historical WC V1 execution with its text-mode hash defect. The separately deselected test checks historical host-native path spelling. That deselection is outside the 688 selected tests. The Windows evidence belongs to the candidate, and merged-main acceptance includes a macOS rerun. [Verification profile](https://github.com/markkoehn0/btlb-sim/blob/2e3af1d33012c15110d470f3619eafc5ecf2f982/docs/architecture/CROSS-PLATFORM-VERIFICATION-PROFILE.md) · [Pinned test classification](https://github.com/markkoehn0/btlb-sim/blob/6aebff55f650ada7e59be7852aa3e534ca81ad49/architecture/check_verification_profile.py)

- **CP-001B — portable storage.** The owner-supplied Windows baseline recorded 592 passes and 77 failures across 669 tests, with historical directory synchronization a principal failure family. An early successor checkout exposed a separate Git line-ending problem. After enforcing canonical LF, the corrected Windows Store 2:0 suite reported 48 passes and two skips, and Engine V2 reported 56 passes, both with zero failures. The preserved macOS log records 828 passes in 23.49 s for an earlier full suite. [CP-001B record](https://github.com/markkoehn0/btlb-sim/blob/4543b1fa12b05865c226557f0cf70fffdf6fa97a/docs/architecture/CP-001B.md) · [Earlier macOS log](https://github.com/markkoehn0/btlb-sim/blob/4543b1fa12b05865c226557f0cf70fffdf6fa97a/docs/architecture/CP-001B-checks/full.txt)
- **CP-002 — frozen byte identity.** The successor checks raw bytes before decoding. The initial targeted Windows attempt recorded one pass and eight failures when successor tests invoked historical V1. The revised suite recorded 16 passes on macOS and nine passes plus seven intentional skips on Windows. The record reports that six frozen reference cases matched exactly and WC-PO-1.7C-V1 retained Category 7. [CP-002 record](https://github.com/markkoehn0/btlb-sim/blob/4543b1fa12b05865c226557f0cf70fffdf6fa97a/docs/architecture/CP-002.md)
- **CP-003 — persistent paths.** Execution 2:1 uses repository-relative paths with forward slashes. The record preserves the initial Windows discovery result of 38 passes and one failure and the later 109 failures in the historical-inclusive suite. It associates those 109 failures principally with legacy storage, frozen-specification hashing, and persistent-path behavior. The available evidence supports that aggregate classification. [CP-003 record](https://github.com/markkoehn0/btlb-sim/blob/4543b1fa12b05865c226557f0cf70fffdf6fa97a/docs/architecture/CP-003.md)

The merged acceptance record reports archive verifier passes for **VAPE-1-R1, 10 cases and 98 content-addressed objects**, and **WC-PO-1.7C-V1, 725 immutable objects**, plus passes for the import-boundary and lexical-neutrality guards. The later AR-1.7 inspection supplies separate raw gate output showing 688 passes, one deselection and 18.70 s, along with separate archive verifier outputs. Those logs belong to the later inspection. The historical closure counts come from contemporaneous aggregate records. The connected GitHub workflow query returned no pull-request-triggered runs for either exact commit. [Merged acceptance details](https://github.com/markkoehn0/btlb-sim/blob/2e3af1d33012c15110d470f3619eafc5ecf2f982/docs/architecture/CROSS-PLATFORM-VERIFICATION-PROFILE.md#merged-main-acceptance-verification) · [Later inspection logs](https://github.com/markkoehn0/btlb-sim/tree/51e6d4cfe1e5b906b0691df006205160a4184f5d/docs/architecture/AR-1.7/inspection)

### Public evidence package

The completed Work verification opened the exact link embedded in the snapshot using Chrome Incognito and downloaded the four-file folder without signing in. The ZIP passed its integrity check. `SHA256SUMS` covered exactly `EXCERPTS.md`, `MANIFEST.json`, and `README.md`, and all three digests matched. The checksum file itself was outside its declared coverage. All **eight** manifest source files matched independently computed SHA-256 digests and Git blob IDs at their pinned refs. All **21** excerpt blocks matched the declared source lines verbatim. [Public OneDrive supplement](https://1drv.ms/f/c/a4e777e93c8824b2/IgAxeR7Q1RG_QbC39Px7m7NMARlkxq7NV0IYaBURTA0fH-4?e=4czBuC)



The downloaded ZIP has SHA-256 `5bff70e4633abd964df650071494cc27da9992fe325eae81341f0105a05e390b`. The package README and excerpts still say “Release candidate,” and the manifest says “Sanitized candidate pending explicit release approval.” That wording conflicts with the package’s observed public availability. It does not affect the verified bytes or their correspondence to the pinned records.



The scientific PASS covers internal software verification in the recorded macOS and Windows environments. Native Linux, arbitrary filesystems, Windows directory-entry crash durability, and physical power-loss durability are outside the verified scope. Category 6 analytic benchmarks and Category 7 numerical results retain their classifications. This review verified records and package bytes. It did not rerun the historical gates or archive verifiers, independently reproduce the science, or establish physical experimental evidence.
