# Beyond the Light Barrier scientific-integrity review

November 8, 2026

Public edition. Private references and unpublished details have been omitted.

Six published-version reviews completed, one earlier review reconciled to the published version, and one review remains partial because the underlying benchmark evidence was unavailable.

## Monitor and version verification

- **Monitor health passed.** The November 8 heartbeat was 7:33:06 AM Central (8:33:06 AM Eastern). The manifest listed 56 monitored articles and eight pending entries. Service, schema version, counts, timestamps, paths, and unique queue identities validated.
- Manifest generated at `2026-11-08T13:33:06.838Z`. Connected GitHub returned manifest blob `424e643d2cea4f648044859aaee201651e0a104b` on the initial read and again at `2026-11-08 15:37:04 UTC`. [Manifest](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/changes.json)
- All eight exact paths returned complete article bodies. ID, title, canonical URL, timestamps, provenance identifiers, file SHA-256, HTML SHA-256, text SHA-256, and Git blob hashes were checked. The HTML hashes matched the exact monitor fingerprints.
- Review recorded at `2026-11-08T15:38:13Z`. The companion file `BTLB-review-ledger-2026-11-08.jsonl` carries the same findings with one record per article ID and fingerprint.

## Scope and continuity

- Article integrity review covered the full hashed HTML and extracted text, equations, cited sources, evidence classifications, figure captions and alt text. Blogger-hosted image pixels are external to the hashed snapshot and were outside this review. The article reviews do not confer Category 8 or Category 9 evidence.
- All eight posts attribute their figures as AI-generated or AI-assisted conceptual illustrations. The site-level disclosure identifies OpenAI ChatGPT and human accountability for publication. The exact model versions and article-by-article extent of text or reasoning assistance are unspecified in the snapshots. The image attributions and project disclosure support the review of labeling. They do not establish which model produced an individual image or passage.
- Raw Blogger API HTML hashes in provenance are recorded source claims. The exported HTML hashes independently match all monitor fingerprints. For #17–#19 the recorded source HTML hash differs from the exported fingerprint and the provenance records a feed jump-break offset. The upstream raw bytes are outside this GitHub verification.
- The accompanying JSON Lines file records this review run for later reconciliation. Daily automation access was outside the scope of this review.
- The review used the BTLB Research Method and supporting project records to check evidence scope, traceability, falsifiability, reproducibility, preservation of negative findings, and figure attribution. [Research Method](https://www.beyond-the-light-barrier.com/p/research-method.html) · [AI & Research Disclosure](https://www.beyond-the-light-barrier.com/p/ai-research-disclosure.html)


## Article dispositions

| Article | Published | Review state | Assessment |
| --- | --- | --- | --- |
| [Research Explained #17](https://www.beyond-the-light-barrier.com/2026/10/research-explained-17-how-would-we-know.html) | 2026-10-31 | Reconciled | Pass with recommendation |
| [Research Explained #18](https://www.beyond-the-light-barrier.com/2026/11/research-explained-18-can-two-observers.html) | 2026-11-01 | Complete | Pass |
| [Research Explained #19](https://www.beyond-the-light-barrier.com/2026/11/research-explained-19-how-would-we-know.html) | 2026-11-02 | Complete | Pass with recommendation |
| [Research Explained #20](https://www.beyond-the-light-barrier.com/2026/11/research-explained-20-can-light-pulse.html) | 2026-11-03 | Complete | Pass |
| [Research Explained #21](https://www.beyond-the-light-barrier.com/2026/11/research-explained-21-when-simulation.html) | 2026-11-04 | Complete | Pass with recommendation |
| [Research Explained #22](https://www.beyond-the-light-barrier.com/2026/11/research-explained-22-what-would-it.html) | 2026-11-05 | Partial | Article scope supported, benchmark unverified |
| [Research Journal #32](https://www.beyond-the-light-barrier.com/2026/11/research-journal-32-three-architectures.html) | 2026-11-06 | Complete | Pass |
| [Research Journal #33](https://www.beyond-the-light-barrier.com/2026/11/research-journal-33-when-architecture.html) | 2026-11-07 | Complete | Pass with recommendation |

## Review notes

The unfinished November 1–7 work was evaluated in publication order. The earlier #17 assessment was handled as a version reconciliation.

### Article #18 · Research Explained #18 -- Can Two Observers Disagree About Whether a Signal Traveled Faster Than Light?

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-321546500909680694`
- Fingerprint `34c46c063828b66a250ac08dd5cc241de8bbd30e03cf09389f49ce78467060a2`
- Snapshot path `articles/321546500909680694/34c46c063828b66a250ac08dd5cc241de8bbd30e03cf09389f49ce78467060a2.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/321546500909680694/34c46c063828b66a250ac08dd5cc241de8bbd30e03cf09389f49ce78467060a2.json)
- Git blob `4a4c8bf031dda4cf7e3addad2e3eab86c22976a1`
- File SHA-256 `7f4746f51bea97e653b074392b8532737fe93c8115527174c6e34d24cfdda445`
- Text SHA-256 `2d602ed42ca7bc3be0538e71cac39a6b02a5c72113970007d796eb5a4f6d4b8d`

**Prior assessment.** PARTIAL in the daily review. November 8 history names this exact fingerprint and the same GitHub blob. The pre-publication checklist also records a same-workflow arithmetic check.

**Reconciliation.** Continued the exact published review. The normalized nonfigure text and external links of the earlier draft match apart from the figure publication note. Independently recomputed both examples and checked all six external references against author copies or publisher records.

- For Δt = 1 s, Δx = 2 light-seconds and v = 0.8c, γ = 5/3 gives Δt′ = −1 s and Δx′ = 2 light-seconds. The invariant interval is −3 light-seconds squared in both frames and the zero-time threshold is 0.5c. Spacelike classification is invariant and the coordinate time order can reverse.
- With u = 4c in each sender’s frame, the outbound interception is at t = 5/4 s, x = 1 light-second. Bob receives at t′ = 3/4 s, replies immediately, and Alice receives at t′ = 15/16 s, corresponding to t = 9/16 = 0.5625 s. Both transmitter-frame legs are future-directed under the stipulated rule. The resulting influence loop depends on controllability, both directions, and the specified dynamics. The article properly separates it from a metric closed timelike curve.
- The published sources support synchronization, the conditional antitelephone, the wormhole time-machine scenario, speculative warp geometry, Everett’s modified causal-loop construction, and Hawking’s conjecture at the level cited. The project references substantiate the dated evidence ceilings and the scanned WC null result. Teaching derivations are Category 6. The caption discloses the AI illustration and distinguishes its return-path schematic from the worked calculation.

**Limits.** Some APS articles were inspected at publisher-abstract level. Their role is to identify and support the bounded historical or theoretical claims. The calculations are given in full in the article and checked separately. No physical FTL model is established.

[Einstein’s special relativity paper](https://fourmilab.ch/etexts/einstein/specrel/www/) · [Benford, Book and Newcomb](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.2.263) · [Morris, Thorne and Yurtsever](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.61.1446) · [Alcubierre’s author preprint](https://arxiv.org/abs/gr-qc/0009013) · [Everett on warp-drive causality](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.53.7365) · [Hawking on chronology protection](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.46.603)

### Article #19 · Research Explained #19 -- How Would We Know a Message Really Came Through a Spacetime Shortcut?

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-2076332398344806775`
- Fingerprint `bccfe8dba39c2a8276cd560785114a0ac2d8eb1c65041b560ac083cbbde8f5bd`
- Snapshot path `articles/2076332398344806775/bccfe8dba39c2a8276cd560785114a0ac2d8eb1c65041b560ac083cbbde8f5bd.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/2076332398344806775/bccfe8dba39c2a8276cd560785114a0ac2d8eb1c65041b560ac083cbbde8f5bd.json)
- Git blob `7d9720b2ec092a116e610176e2106e7a97b59136`
- File SHA-256 `43e5c10aaf70c8211950623d078d2b716f2d5e3ba84c7abf0a6950543a2b37ee`
- Text SHA-256 `544e93e68001b4f91e39df823bc0a4f0e577a9cc18ff9710efdda3150b2faddf`

**Prior assessment.** Daily scientific review unfinished. Project publication history reports an editorial integrity review before publication, without a matching reviewed artifact or monitor fingerprint in the records examined.

**Reconciliation.** Preserved the editorial history and completed the published-version review keyed to the verified November 2 snapshot.

- At the SI value of c, 300,000 m in vacuum takes 1.0006922856 ms. Subtracting the assumed 0.900 ms gives 100.6922856 μs, appropriately summarized as approximately 101 μs. The example clock equation has consistent time units and signs for the stated convention. A receiver-clock offset of roughly −101 μs can imitate the result. The illustrative ratios to 200 μs and 1 μs standard uncertainties are about 0.50 and 101.
- The article separates message identity, calibrated timing, a discrepancy with a defined reference model, and evidence discriminating among physical mechanisms. Unpredictable challenges, blind trials, independent timing checks, leakage controls, and retention of ambiguous trials make the proposal testable. The metrology and relativity references support their assigned roles. The project records support the evidence limits described in the article. The timing calculation is Category 6 and the prospective architecture is Category 5. Figure attribution explicitly identifies AI generation.
- For any eventual protocol, define the earliest permitted challenge-dependent emission and decision times, a false-alarm and missed-detection rule, a surveyed and synchronized reference path, and a covariance-aware uncertainty budget. These are details for the proposed experiment rather than revisions to the teaching arithmetic.

**Limits.** Invented timings and uncertainty values are reproducible arithmetic. No apparatus data, measured covariance, or route-specific prediction exists in this article.

[BIPM SI Brochure](https://www.bipm.org/en/publications/si-brochure) · [BIPM time metrology](https://www.bipm.org/en/time-metrology) · [JCGM 100:2008 measurement uncertainty guide](https://doi.org/10.59161/JCGM100-2008E) · [Einstein’s synchronization treatment](https://fourmilab.ch/etexts/einstein/specrel/www/)

### Article #20 · Research Explained #20 — Can a Light Pulse Arrive Early Without Sending a Message Faster Than Light?

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-3697806019943294304`
- Fingerprint `dd757207e76406da9ebefb0688e64fa359e077548eb4370d4d4d9731842e2dc9`
- Snapshot path `articles/3697806019943294304/dd757207e76406da9ebefb0688e64fa359e077548eb4370d4d4d9731842e2dc9.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/3697806019943294304/dd757207e76406da9ebefb0688e64fa359e077548eb4370d4d4d9731842e2dc9.json)
- Git blob `5091dfe3290fd4696b462b15a759137e7604e6cd`
- File SHA-256 `8e6863eab8abc24c098c3d4ea8dc2c96ea67c181cf861d0881a2468ad513d515`
- Text SHA-256 `39f8000b70b37e5f9c93f440bc657a3822df86acb3c566ef3090f424403e20e3`

**Prior assessment.** Daily review unfinished. Local draft history records primary-source research, arithmetic checks, and AI figure preparation.

**Reconciliation.** Matched the local draft’s nonfigure scientific body and external citation links to the published snapshot. Finished the external-source review against the published version.

- The bibliography correctly identifies Stenner, Gauthier and Neifeld, including Neifeld’s initials M. A., and the citation dates, titles and publication details align with the inspected records.
- The 3.00 m example gives 10.0 ns at the stated approximation to c, 3.75×10⁸ m/s for the 8.0 ns peak-marker interval, about 1.3c as printed, and 2.0 ns advance. The example models timing markers and declares its assumed fixed-delay correction.
- Dogariu et al. support negative group velocity and small waveform distortion in a gain-assisted medium. Stenner et al. measured a detection time slightly longer than for the vacuum reference under their encoding and receiver procedure. Kuzmich et al. found subluminal operational signal speeds for the modeled conditions using an optical signal-to-noise criterion. The article keeps peak motion distinct from causal information, and labels external optical experiments, Category 6 teaching math, and future BTLB tests separately. Figure 1 discloses OpenAI image generation.

**Limits.** The Nature publisher page restricted direct access. The paper’s reproduced first page and the research group’s own description supported the attributed result. The article provides a fully specified example and a prospective receiver test. The exact image-generation model version is unspecified.

[Dogariu, Kuzmich and Wang author preprint](https://arxiv.org/abs/physics/0012060) · [Stenner, Gauthier and Neifeld paper, first page in the issue PDF](https://www2.mps.mpg.de/homes/solanki/publikationen/j157.pdf) · [Duke research group’s information velocity page](https://physics.duke.edu/information-velocity-research) · [Kuzmich et al. author preprint](https://arxiv.org/abs/physics/0101068)

### Article #21 · Research Explained #21 -- When a Simulation Works, What Have We Actually Proven?

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-1879593111044956659`
- Fingerprint `dda77b2739dd09ac98818549cf92f00a509ad42ade06f5a49dcd1de9d06973ab`
- Snapshot path `articles/1879593111044956659/dda77b2739dd09ac98818549cf92f00a509ad42ade06f5a49dcd1de9d06973ab.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/1879593111044956659/dda77b2739dd09ac98818549cf92f00a509ad42ade06f5a49dcd1de9d06973ab.json)
- Git blob `d2e324c758f2c41e0655dce5e2e7da9cd5ace87a`
- File SHA-256 `04abb04b1e2799e052cbf32a6c7fdfc392d0161171673aec28092822cae31d7f`
- Text SHA-256 `6e9cca3dc0621d83ba38cfd2e34da30d963be3fd0ac295c805cdcd93024a0970`

**Prior assessment.** Daily review unfinished. No exact prior review was found.

**Reconciliation.** Completed a review of the exact November 4 snapshot.

- The central distinction holds among code execution, numerical verification against mathematics, and testing predictions against the physical world. Cross-platform execution is useful evidence of repeatability and portability. Shared assumptions and implementation errors can survive agreement. The platform example is hypothetical and the article provides no new numerical calculation to reproduce.
- The project records support the internally checked WC-MGT-1 result and the distinction between internal verification and Category 8. The WD discussion correctly treats stress-energy, energy conditions, stability, causality, and formation as separate constraints. It preserves the value of scoped negative results and identifies an observable, uncertainty budget, and controls as prerequisites for physical tests. The illustration discloses AI generation.
- Distinguish the terminology explicitly in the bibliography or prose. The National Academies uses computational reproducibility for obtaining consistent results with the same inputs, methods, code and conditions, and replicability for separate studies with their own data. BTLB Category 8 uses its own meaningfully independent reproduction standard. Labeling both usages would remove an ambiguity without changing the scientific conclusion.

**Limits.** Review covers the article’s account of project results. WC-MGT-1 was not rerun and no Category 8 result is claimed.

[National Academies definitions and recommendations](https://www.nationalacademies.org/read/25303/chapter/2) · [BTLB public reproduction and verification package index](https://www.beyond-the-light-barrier.com/p/reproduction-verification-packages.html)

### Article #22 · Research Explained #22 -- What Would It Take to Detect a Tiny Distortion in Spacetime?

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-4274054251979338495`
- Fingerprint `026a486e54c81c13776b86edd7a6581dc3ace19d1755d409df2ce8387e53aa33`
- Snapshot path `articles/4274054251979338495/026a486e54c81c13776b86edd7a6581dc3ace19d1755d409df2ce8387e53aa33.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/4274054251979338495/026a486e54c81c13776b86edd7a6581dc3ace19d1755d409df2ce8387e53aa33.json)
- Git blob `e63fc3a9f7ab0b1615f0ed5caa396fb62fe1feda`
- File SHA-256 `b53e35c675269f4a1ca2cda1952c97cb34d4b27fda663e7660aaa3f2fbfb7699`
- Text SHA-256 `96021a5f724ecad55f3a3d691b6fa392efa065214ded458a04a3bb319f0e1c3b`

**Prior assessment.** Initial monitor PASS with a recommendation to publish a sanitized reproducibility package. The historical assessment did not identify the exact fingerprint.

**Reconciliation.** Preserved the initial PASS as historical. Verified and reviewed the exact published snapshot and checked the reported values and the scope of the negative result against project records.

- The project summary agrees with the published NP-2C values of about 1.10×10⁻¹⁶ rad and 8.06×10⁻²⁷ m. Using T = 0.05 s and a representative two-photon Raman effective wavevector 4π/(780 nm), Δφ/(k_eff T²) gives about 2.74×10⁻²¹ m/s². This independently checks the scale conversion under that assumption. It does not establish the modeled phase or the full pulse-sequence response.
- The article correctly confines the sensitivity gate failure and retirement to the historical NP-2C design. The 5–14× NP-2G screening range agrees with the project summary and is a material-limited calculation with assumptions. The article preserves conventional backgrounds, source-synchronous systematics and the need for rotation-reversal controls and a complete observable model. Gravity Probe B supports Earth-orbit frame dragging and the atom-interferometry review is instrumentation background. Neither source establishes the laboratory rotor signal. The AI figure is labeled conceptual.
- Retain the reproducibility recommendation. A sanitized frozen NP-2C package would need the geometry and rotor/atom parameters, governing equations and detector transfer, configuration, method/code, reference output and tolerances. NP-2D needs the sensitivity comparison and detector response assumptions. NP-2G needs material inputs, constraints and the screening calculation.

**Limits.** Original benchmark inputs and the full NP-2D through NP-2G calculation and sensitivity artifacts were not located in the inspected sources or the public package index. Summary corroboration and the scale conversion are complete. Regeneration of the central phase/displacement and independent verification of the gate and screening remain blocked.

[Gravity Probe B primary paper](https://arxiv.org/abs/1105.3456) · [Bongs et al. review DOI](https://doi.org/10.1038/s42254-019-0117-4) · [Bongs et al. author correction](https://research.birmingham.ac.uk/en/publications/author-correction-taking-atom-interferometric-quantum-sensors-fro/) · [BTLB public reproduction and verification package index](https://www.beyond-the-light-barrier.com/p/reproduction-verification-packages.html)

### Article #32 · Research Journal #32 — Three Architectures, No Predetermined Winner

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-117840139236241411`
- Fingerprint `1a0893ec3f1959c6958937b71a5f917012a6cb7166b2a45bc78f47df94f9b77d`
- Snapshot path `articles/117840139236241411/1a0893ec3f1959c6958937b71a5f917012a6cb7166b2a45bc78f47df94f9b77d.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/117840139236241411/1a0893ec3f1959c6958937b71a5f917012a6cb7166b2a45bc78f47df94f9b77d.json)
- Git blob `a282d183749bf2c6d74d81341a7ecc8a7bce4d88`
- File SHA-256 `4e2bc829964ca4345c809fc07d5d7976d084582f13bd1bc3d4b6a0780749e2f1`
- Text SHA-256 `9770766ef91fc838fd7b91377b2e78e5ce56665b1f7d13adef9227469220114a`

**Prior assessment.** Monitor blocked on full text at this exact fingerprint. Separate read-only architecture-provenance work verified the local records before this review.

**Reconciliation.** Resolved the access blocker using the verified snapshot. Reused the earlier provenance work and checked the central published claims against the committed records.

- The October 29 diagnostic gives 24 criteria, 72 candidate rows and 12 noncompensable scoped gates. The candidate descriptions and risks track the diagnostic. The gate count refers to the comparison framework and conveys no gate passes or ranking. The October 30 owner record makes ARCH-003 a reversible development direction and leaves adequacy, acceptance, freeze and implementation authorization open at that checkpoint.
- The local closure record and tag establish eight open findings. Its 64 FAIL observations are repetitions and variants supporting the findings. The article accurately distinguishes a scoped comparison from a decision and preserves unresolved alternatives and corrective obligations. This is a Category 5 engineering record. There is no new physics equation, simulation or measurement claim. Figure 1 is identified as an AI-assisted conceptual comparison.

**Limits.** Local committed records support the article’s documentary claims. The comparison was not rerun and remote preservation was not independently checked. The article explicitly bounds these claims.

[Public Journal #31 chronology](https://www.beyond-the-light-barrier.com/2026/10/research-journal-31-closing.html)

### Article #33 · Research Journal #33 — When an Architecture Is Accepted but Not Yet Built

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-3654156281980371013`
- Fingerprint `4898154010139e1b8c0e418b475f14b2eb53a8f986b42f3c92c88c6a5bd7e3bb`
- Snapshot path `articles/3654156281980371013/4898154010139e1b8c0e418b475f14b2eb53a8f986b42f3c92c88c6a5bd7e3bb.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/3654156281980371013/4898154010139e1b8c0e418b475f14b2eb53a8f986b42f3c92c88c6a5bd7e3bb.json)
- Git blob `6e1dc73abcdacd00c4af5d9a1533be3cbdc0f20b`
- File SHA-256 `5930f607b3f7ff8f44ceff6e2f352438ba8b06ef1d9a4ca423afc927b6a87946`
- Text SHA-256 `2766ad68a4cbdb950d894b233874c4c0cd3ffee93bdfb7762c04da329e925aef`

**Prior assessment.** Preliminary PASS with verification limitations at this exact fingerprint and blob in the November 8 daily review.

**Reconciliation.** Continued the preliminary review using the project records and checked the scope of the test and requirements claims.

- The October 31 crosswalk identifies proposed treatments for eight open findings. A later October 31 owner record supports bounded adequacy and acceptance to proceed toward detailed design. The November 2 freeze establishes four common responsibilities and six invariants under change control. The article keeps selection, acceptance, freeze, implementation, corrective verification and scientific validation separate.
- The freeze record reports 12 design tests, an assessment against requirements R1–R59, and zero direct contradictions in the bounded conceptual audit. These counts and qualifications are traceable to the freeze. The article reports them with the appropriate Category 5 boundary. The full working record is unavailable in that package and the audit outcomes remain unreplicated.
- Retain the prior recommendation for a sanitized requirements-to-design-test crosswalk with scope, rationale, uncovered cases and historical finding IDs if published. Figure 1 is disclosed as AI-assisted and conceptual. The discussion of scientific authority correctly distinguishes AI assistance and artifact integrity from evidentiary authority.

**Limits.** The documentary review is complete at the article’s stated scope. The preservation record explicitly lacks the complete underlying Design Test 1–12 and R1–R59 working record. No audit re-performance or remote preservation check was performed.

### Article #17 · Research Explained #17 — How Would We Know Where a Signal Actually Went? — Tracing Light Through Curved Spacetime

- Blogger ID `tag:blogger.com,1999:blog-5793283855177519383.post-8040246204219982292`
- Fingerprint `ff2d4478114160615ec299a802a8bdd4d89fdc76ec13c2a1d8a74fb4e50c5f30`
- Snapshot path `articles/8040246204219982292/ff2d4478114160615ec299a802a8bdd4d89fdc76ec13c2a1d8a74fb4e50c5f30.json`. [Exact GitHub snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/d18b09094dac77ab78efbf8036f5067233eb5ced/articles/8040246204219982292/ff2d4478114160615ec299a802a8bdd4d89fdc76ec13c2a1d8a74fb4e50c5f30.json)
- Git blob `34560df0c8fe57197e094352473f9ebf81f55470`
- File SHA-256 `aaca28fa222cf5a30dc22feb72345e47dabdd5ba402d5630a6585a24ee164208`
- Text SHA-256 `71dad560010ac59aeda11a232afa876b4045acb0c9099fc80295a7ff4a02a14b`

**Prior assessment.** Monitor PASS with recommendation, provisional as to version. A separate October 31 author self-review preserved a hashed pre-publication HTML draft.

**Reconciliation.** Reconciled the local reviewed draft to the exact published snapshot by comparing normalized nonfigure text and external citation destinations. Differences were removal of the opening title/date block, substitution of the conceptual figure for its placeholder, and the corresponding publication note. The draft and snapshot have different raw hashes. Carried forward the reviewed scientific body and checked the publication changes.

- The null constraint and the affine geodesic equation serve different purposes. The (−,+,+,+) convention, connection indices and units, weak-field deflection 4GM/(c²b), and first-order one-way Shapiro expression are consistent within the stated domains. The moving receiver example follows from ct = L + vt. Use of the physical phase wavevector for observed frequency avoids dependence on arbitrary affine normalization.
- The quasar delay is an observational example and Cassini measured a radio-frequency signature associated with changing light time. Multiple candidate paths and nonunique inference are kept distinct from tracking a photon. The proposed moving-endpoint ray suite is a prospective workflow. The project records support the bounded Category 7 description and retention of the WC-MGT-1 null result.
- For the proposed workflow, give the proposed ray tests stable benchmark identifiers and, once run, freeze metric and endpoint inputs, solver tolerances, null residuals, and failed connections. The figure caption explicitly discloses AI generation and its conceptual role.

**Limits.** Some original citations were available as author manuscripts or publisher abstracts. The carried-forward author review and this reconciliation are article checks. The proposed ray suite remains prospective.

[Carroll’s general relativity lectures](https://arxiv.org/abs/gr-qc/9712019) · [Kundić et al. on the observed lens delay](https://arxiv.org/abs/astro-ph/9610162) · [Ashby and Bertotti on light time](https://arxiv.org/abs/0912.2705) · [Cassini radio-link measurement](https://www.nature.com/articles/nature01997) · [Perlick’s exact lens equation](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.69.064017)

## Acknowledgment status

**ACKNOWLEDGMENT_BLOCKED.** No inspected supported mechanism was available that atomically compares the expected fingerprint with the authoritative Google Apps Script queue and acknowledges only that version. Manifest read-back remained at the same blob with all eight entries pending. The daily schedule and automation instructions were preserved.

These article ID and fingerprint pairs are candidates for acknowledgment only after a supported mechanism is inspected and a fresh manifest still matches the pair. The #22 fingerprint is excluded while benchmark evidence remains blocked.

| Article | Blogger post ID | Exact fingerprint |
| --- | --- | --- |
| #17 | `8040246204219982292` | `ff2d4478114160615ec299a802a8bdd4d89fdc76ec13c2a1d8a74fb4e50c5f30` |
| #18 | `321546500909680694` | `34c46c063828b66a250ac08dd5cc241de8bbd30e03cf09389f49ce78467060a2` |
| #19 | `2076332398344806775` | `bccfe8dba39c2a8276cd560785114a0ac2d8eb1c65041b560ac083cbbde8f5bd` |
| #20 | `3697806019943294304` | `dd757207e76406da9ebefb0688e64fa359e077548eb4370d4d4d9731842e2dc9` |
| #21 | `1879593111044956659` | `dda77b2739dd09ac98818549cf92f00a509ad42ade06f5a49dcd1de9d06973ab` |
| #32 | `117840139236241411` | `1a0893ec3f1959c6958937b71a5f917012a6cb7166b2a45bc78f47df94f9b77d` |
| #33 | `3654156281980371013` | `4898154010139e1b8c0e418b475f14b2eb53a8f986b42f3c92c88c6a5bd7e3bb` |
