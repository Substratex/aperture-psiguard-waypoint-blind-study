# Front Matter

## Abstract

Long-horizon artificial-intelligence systems can exhibit changes in stability, coordination, role behavior, correction dynamics, tool interaction, and temporal organization that are difficult to characterize from isolated outputs. Longitudinal Computational Dynamics (LCD) treats the evolving computational trajectory as an empirical object and SubstrateX Aperture™ implements a Runtime Evidence architecture for reconstructing, measuring, governing, and preserving such trajectories. The present study is the first paper in the LCD series organized around an independently originated external trajectory and an independently developed comparison system.

This study arose from an experimental collaboration between Arjay Asadi, developer of SubstrateX Aperture™, and Bradley, developer of PsiGuard. PsiGuard and Aperture were developed independently and operate from different architectural and evidentiary assumptions. PsiGuard is treated here as a live prospective stability and intervention system. Aperture is treated as a longitudinal Runtime Evidence Observatory supporting full-horizon retrospective reconstruction and prefix-bounded prospective replay. The systems are not assumed to measure identical constructs, and PsiGuard intervention is not defined as equivalent to any Aperture temporal marker.

The study asks: **Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?** The empirical object is a 275-turn Bradley–Waypoint interaction. A verdict-free blind source was constructed before Aperture computation, preserving source ordering, prompts, responses, role identity, completion state, source-turn coordinates, and provenance while excluding PsiGuard intervention turns, wandering labels, holding/intervened classifications, detector readings, and proprietary detector internals. The qualified blind source contains 275 Bradley/user events and 275 Waypoint/assistant events, producing 550 canonical events. Four assistant events are explicitly incomplete, yielding 271 eligible Waypoint measurements. The final certified run resolves 48 of 48 Method Contracts with no unsupported computational outputs or evidence-horizon violations.

Aperture was evaluated in two modes. First, the complete T1–T275 record was processed retrospectively and frozen before PsiGuard disclosure. The completed trajectory reconstructed staged weakening at source turn T2 and a candidate boundary at T25, but did not confirm formal Basin Exit t*, did not receive an independently supplied observable-failure anchor tf, and therefore did not compute formal lead time. The final regime is Transitional, with a candidate open watch from T25 through T275. Second, the same blind source was replayed independently at every prefix horizon from T1 through T275. T1 was unavailable under the minimum measurement gate; T2–T275 produced 274 of 274 computable prefixes with exact role/event topology, zero future-event leakage, zero ingestion errors, and 48/48 Method Contracts on every computable prefix.

Prospective replay reveals a substantive difference between retrospective reconstruction and horizon-valid issuance. A staged warning appears at T2 under informational-only confidence and remains present thereafter; confidence matures at later horizons. Candidate status is horizon-sensitive, repeatedly withdrawing and reappearing before becoming continuously present only from T168 through T275. Formal t* is temporarily emitted at 32 individual prefix horizons, beginning at T10, but those emissions are subsequently withdrawn as the evidence horizon grows; the completed T275 record retains t*=null. Selected prefix reruns reproduce these states deterministically. These results demonstrate that warning, candidate formation, and formal-boundary issuance have different prefix-validity properties and that retrospective coordinates cannot be treated automatically as contemporaneous warning coordinates.

Before external disclosure, the Aperture result, prospective ledger, evidence identity, machine-readable Runtime Evidence Artifact, Passport, Casefile, Validator, and preservation artifacts were frozen. An identity discrepancy between a prospective harness-local T275 hash and the browser-certified Runtime Evidence identity was discovered and reconciled before disclosure: all 550 events matched exactly in content, role, source turn, source-event ordinal, completion state, and canonical turn, and rebuilding the production semantic identity reproduced the certified hash. The correction was preserved as an audit record rather than silently overwritten.

This Version 0.1 manuscript is a registered pre-unblinding record. PsiGuard coordinates have not been used to alter Aperture computation or interpretation. The cross-system comparison procedure, outcome classes, offset rules, false-alarm analysis, and disagreement categories are prespecified here before disclosure. The final post-unblinding version will add Bradley’s disclosed PsiGuard coordinates through a source-turn join only; Aperture will not be recomputed or retuned for that comparison.

## Research Status and Scope

This manuscript is **Paper VIII** in the Longitudinal Computational Dynamics publication sequence and the first paper in the series centered on a blind external comparative case study rather than a foundational architectural proposition. It builds directly on Papers I–VII: the scientific object and field definition of LCD; the bounded validation architecture; Aperture methods; Runtime Evidence; Computational Behavior Architecture; Evidence-Governed Computation; and Chronodynamics.

The present version is **Version 0.1 — Registered Pre-Unblinding Manuscript**. It records the research question, collaboration, source construction, ingestion qualification, Aperture release, blind-result identity, retrospective findings, prospective replay findings, comparison protocol, classification rules, limitations, and repository plan before Bradley discloses PsiGuard intervention and wandering coordinates. Section 6 is therefore written as a registered post-unblinding analysis plan rather than as completed comparative results. No cross-system convergence claim is made in this version.

This paper does not treat PsiGuard as ground truth and does not treat Aperture as a validated production failure predictor. It does not claim that PsiGuard intervention equals Aperture t_aw, that an early Aperture warning is predictive merely because it occurs early, that temporary prefix t* emissions are stable Basin Exits, or that lead time exists without an independently supplied observable-failure anchor. The study tests whether independently produced evidence exhibits temporal, structural, or operational correspondence on one long-horizon trajectory.

The highest validation level supported by a claim is stated separately. The governed Aperture evidence core has implementation and deterministic support under the frozen source and release. The prospective prefix experiment tests horizon-valid issuance and prefix invariance on this trajectory. Construct correspondence to PsiGuard and prospective performance relative to independently defined external coordinates remain unresolved until unblinding. Independent replication by an unaffiliated implementation remains future work.

## Collaboration and Attribution

The experiment was initiated through collaboration between **Arjay Asadi**, developer of SubstrateX Aperture™, and **Bradley**, developer of PsiGuard. Formal publication attribution for Bradley, including preferred full name, affiliation, system description, and authorship status, is intentionally left for collaborator review before Version 1.0. No proprietary PsiGuard detector internals are required for the study. The comparison requires only the externally disclosed native source-turn coordinates and Bradley’s confirmation of how those coordinates should be interpreted operationally.

The scientific purpose of the collaboration is to preserve independence rather than to harmonize the systems. Aperture was not configured to reproduce PsiGuard labels. PsiGuard was not used to set Aperture thresholds. The systems were allowed to disagree. The study therefore asks whether two independently developed evidentiary systems recover related structure from the same trajectory under a protocol that prevents post-hoc tuning.

## Registered Pre-Unblinding Status

At manuscript freeze:

- the Aperture science release is r.5.7.4;
- the Preserve/Export hotfix is r.5.7.4.1 and changes no science;
- the verdict-free blind source contains 275 native turns and 550 canonical events;
- the blind source SHA-256 is `5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6`;
- the certified browser Runtime Evidence identity is `APERTURE-CER-6753eadcdd506`;
- the certified canonical hash is `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`;
- 271 Waypoint measurements are eligible;
- Method Contract conformance is 48/48 PASS;
- the retrospective and prospective Aperture results are frozen;
- Blind Result Lock v2 records `external_disclosure_received = false`;
- the post-disclosure operation is restricted to source-turn joining and comparison;
- Aperture must not be recomputed or retuned after PsiGuard disclosure for this experiment.

## Contributions

This paper makes nine empirical and methodological contributions.

1. It applies the complete Runtime Evidence lifecycle to an independently originated 275-turn long-horizon AI interaction rather than an internally authored validation fixture.
2. It operationalizes a blind cross-system comparison between Aperture and PsiGuard without assuming construct equivalence or treating either system as ground truth.
3. It separates full-horizon retrospective reconstruction from 275 independent prefix-bounded prospective computations over the same source.
4. It demonstrates a concrete prefix-validity distinction: retrospective candidate formation at T25 coexists with horizon-sensitive candidate issuance that does not remain continuously present until T168.
5. It documents deterministic but non-prefix-invariant formal-boundary behavior: 32 temporary t* emissions occur at individual prefixes and are subsequently withdrawn, while the completed record retains t*=null.
6. It preserves claim refusal as an empirical result: substantial runtime pressure, drift, exposure, and candidate formation do not authorize a final Basin Exit, observable-failure, or formal lead-time claim.
7. It demonstrates the role of evidence identity and auditability by detecting and reconciling a harness-local identity mismatch before external disclosure without changing the canonical event set or scientific findings.
8. It prespecifies temporal, structural, and operational comparison classes before PsiGuard coordinates are revealed, reducing the opportunity for post-hoc interpretation.
9. It defines a reproducible evidence release structure linking the manuscript to the blind source, result lock, prospective ledger, Runtime Evidence Artifact, Passport, Casefile, Validator, forensic report, identity audit, and post-unblinding comparison artifacts.

# 1. Introduction

## 1.1 The long-horizon observability problem

Artificial-intelligence evaluation commonly centers on outputs, tasks, episodes, or aggregate scores. Those objects are useful but incomplete when behavior develops over extended interaction. A model may remain locally competent while its role organization, response structure, correction dynamics, tool use, or stability changes gradually. A final answer can conceal formation. A benchmark score can conceal temporal path dependence. A short-horizon monitor can detect immediate conditions without preserving the longitudinal evidence needed to reconstruct how those conditions emerged.

Longitudinal Computational Dynamics addresses this gap by treating the computational trajectory itself as an empirical object. The object is not a hidden cognitive state. It is the observable and computationally reconstructed development of behavior across a qualified runtime record. The trajectory may include messages, tool calls, role transitions, corrections, recurrences, contradictions, explicit state changes, and other source-bound events. The scientific problem is to reconstruct that record without inventing evidence, measure declared properties of its development, preserve uncertainty and missingness, and prevent later presentations from making claims stronger than the source and methods permit.

The practical difficulty is that long-horizon systems create two different but easily conflated questions. The first is retrospective: given the completed trajectory, what structure can be reconstructed from the full record? The second is prospective: at a particular evidence horizon, what could the system legitimately have emitted using only evidence available by that point? A retrospective marker may identify an early formation coordinate only after later evidence makes the pattern legible. Treating that reconstructed coordinate as if it were an online warning would backdate knowledge.

Paper VII formalized this distinction through historical and prospective replay. The present study applies it to an external trajectory. The goal is not merely to show that Aperture can draw a worldline after the fact. The goal is to determine which findings survive prefix-bounded replay and then compare those frozen findings with a separate live stability system that was developed independently.

## 1.2 Why independent systems matter

A single implementation can test internal conformance, deterministic replay, and self-consistency. It cannot by itself establish that a measured construct corresponds to an independently observed phenomenon. Several Aperture instruments agreeing over the same Current Evidence Run demonstrate internal congruence, not external validity. Similarly, a detector matching labels that were used to tune it demonstrates little about generalization.

Independent systems create a more demanding test. If two systems with different methods, vocabularies, architectures, and operating objectives identify related structure in the same trajectory without exchanging labels in advance, their correspondence may provide convergent evidence. If they disagree, that disagreement can expose construct differences, sensitivity differences, evidence-threshold differences, or weaknesses in one or both systems. Either outcome is scientifically useful if the comparison is protected against post-hoc retuning.

The present experiment therefore preserves non-equivalence. PsiGuard intervention is not defined as Aperture t_aw. A PsiGuard wandering label is not defined as an Aperture regime. An Aperture Basin Exit is not presumed to be what triggers PsiGuard intervention. Instead, the systems are compared at three levels: temporal correspondence, structural correspondence, and operational correspondence.

## 1.3 Aperture and PsiGuard

SubstrateX Aperture™ is the principal reference implementation of Runtime Evidence Infrastructure within the LCD research program. It ingests heterogeneous operational records, constructs a source-bound Canonical Runtime, computes registered measurement telemetry, forms a Current Evidence Run, projects bounded instrument findings, applies Runtime Evidence Authority and Evidence-Governed Computation, issues a Runtime Evidence Passport when certification conditions are satisfied, and preserves the result as portable artifacts.

PsiGuard is an independently developed system created by Bradley for live stability/control observation of the same Waypoint interaction. For this study, PsiGuard is characterized only by what is necessary to establish the experimental comparison: it operated contemporaneously with the trajectory, it produced intervention and wandering coordinates, and those coordinates were withheld from Aperture until the Aperture results were frozen. The study does not infer or reverse-engineer PsiGuard's proprietary detector logic.

The systems therefore approach the same trajectory from different evidentiary positions. PsiGuard is treated as a live prospective operational system. Aperture is tested both retrospectively and through prefix-bounded replay. The comparison is not designed to prove one system correct by the other. It is designed to test whether independently produced evidence converges in time or structure and, where it does not, to make the disagreement inspectable.

## 1.4 Experimental collaboration

The collaboration began from a substantive scientific challenge: retrospective reconstruction is not equivalent to online warning. Bradley's live PsiGuard environment created an unusual opportunity to test that distinction against an interaction that had not been authored to satisfy Aperture's expectations. Rather than ask Bradley for his intervention numbers first, the protocol required Aperture to qualify the source, compute the full trajectory, replay every prefix, and lock its results before disclosure.

This sequencing changes the evidentiary character of the collaboration. Bradley is not merely providing a dataset after the fact, and Aperture is not being tuned to reproduce his labels. The two systems bring separate histories and separate operating assumptions to one preserved trajectory. The collaboration becomes a controlled comparison of independent observational systems.

## 1.5 Research question and registered hypotheses

The governing research question is:

**Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?**

The following hypotheses are registered before PsiGuard coordinate disclosure.

**H1 — Temporal correspondence.** At least some PsiGuard intervention or wandering coordinates will fall within or near Aperture prospective regions characterized by elevated warning, candidate formation, pressure, drift, or related bounded findings.

**H2 — Prospective/retrospective divergence.** Aperture's full-horizon retrospective formation coordinates will not be identical to the first horizons at which equivalent states are prospectively supportable. Later evidence will alter the admissibility or persistence of some earlier interpretations.

**H3 — Horizon sensitivity.** Candidate and formal-boundary states will show greater sensitivity to the evidence horizon than the broad staged-warning state.

**H4 — Non-equivalent semantics.** Some apparent temporal matches will not constitute construct matches because PsiGuard intervention and Aperture markers represent different operational decisions or evidence classes.

**H5 — Informative disagreement.** At least one comparison case will be better described as partial, offset, retrospective-only, Aperture-only, PsiGuard-only, or structurally divergent than as a binary match/mismatch.

No hypothesis authorizes post-hoc movement of Aperture coordinates after disclosure. Any external comparison is performed against the frozen prospective ledger and retrospective record.

# 2. Scientific and Architectural Background

## 2.1 Longitudinal Computational Dynamics

Longitudinal Computational Dynamics studies the organization of observable computational behavior across extended runtime. Its empirical object, Longitudinal Computational Behavior, is represented through evidence-bound trajectories rather than assumed hidden mental states. Paper I defines the contribution as an integration of canonical runtime formation, worldlines, behavioral telemetry, stability and drift measures, temporal markers, governed instruments, evidence identity, and preservation around the longitudinal computational trajectory as a measurable evidence-bearing object.

The framework does not claim that a worldline is an extracted internal path through model cognition. It is a reconstruction over qualified operational evidence. A source may be incomplete, asymmetric, or role-ambiguous. Canonicalization therefore has an evidentiary boundary: structure may be normalized, but missing facts cannot be invented. This boundary was operationally important in the present experiment because an early generic parsing path distorted the event topology. The experiment did not accept scientific results until source and role preservation were repaired and independently audited.

## 2.2 Runtime Evidence

Runtime Evidence is the source-bound evidentiary substrate through which longitudinal behavior is reconstructed and examined. The core lifecycle used in this study is:

**Qualified Source → Canonical Runtime → Current Evidence Run → Runtime Evidence Record → Bounded Findings → Certified Runtime Evidence Record → Runtime Evidence Passport + Evidence Seal → Preservation Artifact**

Each transition has a distinct responsibility. Qualification establishes what source was supplied and what transformations are authorized. Canonicalization provides stable event identity and coordinate relationships. Measurement forms telemetry under registered methods. The Current Evidence Run binds active evidence identity. Instruments consume the shared evidence substrate through claim-bounded projections. Runtime Evidence Authority evaluates whether the record is certifiable. The Passport and Seal bind identity, formation, integrity, and claim boundary. Preservation keeps the resulting object inspectable beyond the interface session.

This architecture matters for external validation because comparison must not overwrite the evidence it is evaluating. Expected outcomes and external labels are test context, not evidence input. The Runtime Evidence Record must exist independently before comparison.

## 2.3 Evidence-Governed Computation

Evidence-Governed Computation governs the relationship:

**evidence → method → admissible claim → presentation → preservation**

Its purpose is not to certify objective truth. It limits what a computational system may legitimately claim from the evidence and methods available to it. An instrument may project drift, pressure, temporal structure, or role dynamics, but the projection cannot silently strengthen a candidate marker into a confirmed boundary. Missingness cannot become a negative finding. A source-supplied coordinate cannot be replaced by a display coordinate without disclosure. A preservation artifact cannot claim greater authority than the certified record from which it derives.

The present experiment provides a concrete test of this discipline. The completed run exhibits substantial pressure, drift, failure exposure, candidate formation, and multiple temporary formal-boundary emissions under prefix replay. Yet the final certified record refuses Basin Exit because the governing persistence and evidence conditions are not satisfied at the completed horizon. It also refuses formal lead time because tf was not independently supplied. The refusal is itself an observable system behavior and part of the empirical result.

## 2.4 Chronodynamics and evidence horizons

Chronodynamics supplies the specialized temporal layer within LCD. It distinguishes wall-clock time, source order, canonical event order, frame order, dependency order where available, and symbolic-time measures derived through declared methods. A claim must identify which coordinate it uses. In the present study, external comparison is performed primarily in Bradley's native source-turn coordinate because that is the coordinate shared by the blind source and the withheld PsiGuard disclosures.

Historical and prospective replay are evidentially distinct. Historical replay can use the completed trajectory to reconstruct earlier structure, provided the result is labeled retrospective. Prospective replay advances the evidence horizon one position at a time and records only what the system can support at that horizon. A scrubber moving through a fully computed run is not a substitute for prospective replay, because the underlying frame may have been computed with future evidence.

The concept of prefix invariance follows directly. A marker is prefix-invariant if its status remains stable as later admissible evidence is added under the same governing rules. A marker that appears and disappears across prefixes is horizon-sensitive. The present experiment makes this property observable for warning, candidate, and formal-boundary states.

## 2.5 Validation hierarchy

The LCD validation program separates levels that answer different scientific questions.

| Level | Question | Evidence required | Claim permitted |
|---|---|---|---|
| V0 — Formal | Are constructs, clocks, units, and claim rules coherent? | specification review, examples, counterexamples | the construct is defined |
| V1 — Implementation | Does code implement the registered contract? | unit tests, schema tests, code-to-contract trace | the implementation conforms to the contract |
| V2 — Deterministic | Do identical inputs and profiles reproduce authoritative outputs? | repeated runs, hashes, tolerance reports, replay | the computation is reproducible under stated conditions |
| V3 — Construct / calibration | Do signals track independently annotated or manipulated structure? | labeled corpora, controlled perturbations, ablations, calibration | the measure has supported construct meaning within the studied scope |
| V4 — Prospective | Do prefix-valid outputs anticipate independently defined outcomes? | held-out runs, prospective replay or live issuance, independent outcomes, false-alarm analysis | measured prospective performance within the tested scope |
| V5 — Independent replication | Can independent investigators reproduce the method and findings? | external implementation or execution, preserved materials, discrepancy report | independent replication support |

This paper must not allow one layer's validation status to transfer automatically to another. The evidence core can have V2 support while an individual temporal marker lacks V3 calibration. A prefix replay can test V4 conditions on one trajectory without establishing general prospective validity. Cross-system correspondence, if observed after unblinding, may contribute external construct evidence but will remain bounded to the study design and source.

# 3. Systems Under Comparison

## 3.1 SubstrateX Aperture™

The frozen scientific implementation used for this study is SubstrateX Aperture r.5.7.4. Release r.5.7.4.1 is a Preserve/Export UI-readiness hotfix that does not alter science. Aperture functions as a Runtime Evidence Observatory rather than a monolithic detector. It contains source qualification and canonicalization, measurement authority, temporal reconstruction, regime and marker logic, Runtime Evidence Authority, a Method Contract registry, a Runtime Evidence Passport, preservation/export surfaces, and multiple bounded instruments.

For this study, the most important architectural property is that the instruments are consumers of one certified evidence substrate. Seismo, Chronos, Drift, Pressure, Bridge, Noesis, Scope, Dynamics, and Interferometer may expose different bounded projections, but they do not create separate histories and may not overwrite the governing temporal authority. This allows visually complex diagnostic surfaces to remain subordinate to a common evidence identity.

Aperture's final certified run contains 550 canonical events and 271 eligible Waypoint measurements. Four assistant events are explicitly incomplete and remain unavailable for measurement rather than being imputed. The Method Contract registry resolves 48 of 48 contracts with no unsupported outputs or evidence-horizon violations. Certification produces Runtime Evidence Record `APERTURE-CER-6753eadcdd506` under canonical hash `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`.

## 3.2 PsiGuard

PsiGuard is an independently developed live stability/control system created by Bradley. Its internal proprietary detector logic is outside the evidentiary requirements of this paper and is not inferred. The study requires only the following externally reviewable facts, subject to Bradley's confirmation before Version 1.0:

- PsiGuard operated contemporaneously with the Waypoint trajectory;
- it produced intervention coordinates and wandering coordinates in the native source-turn domain;
- those coordinates were not supplied to Aperture before Aperture's results were frozen;
- the coordinates can be disclosed after the blind lock and joined to the frozen Aperture record without recomputation.

A more detailed architectural description may be included in Version 1.0 only with Bradley's review and approval. The study deliberately avoids claims about PsiGuard constructs that Bradley has not authorized.

## 3.3 Non-equivalence of constructs

The comparison is designed around related evidence, not identity of constructs.

| PsiGuard object | Aperture object | Comparison rule |
|---|---|---|
| intervention | prospective warning / candidate / bounded instrument state | compare temporal region and operational posture; do not define as equal |
| wandering | drift, role pressure, regime state, candidate formation | compare structural interpretation and timing |
| live action | prefix-valid Aperture state | principal prospective comparison |
| later retrospective interpretation | full-horizon Aperture reconstruction | compare separately from live issuance |
| proprietary detector score | Aperture telemetry | no direct metric equivalence assumed |

Three comparison dimensions are therefore prespecified.

**Temporal correspondence** asks whether the systems react within the same source-turn region.

**Structural correspondence** asks whether the systems appear to characterize related forms of instability or organization.

**Operational correspondence** asks whether the evidence leads to intervention, warning, continued observation, candidate status, or no supported action.

A temporal match without structural correspondence is not treated as full convergence. Likewise, structural similarity separated by a large temporal offset is not treated as exact temporal agreement.

## 3.4 Shared trajectory, separate authorities

Both systems observe the same underlying interaction, but their evidence authorities remain separate. PsiGuard's intervention coordinate remains a PsiGuard observation. Aperture's t_aw, t_candidate, t*, regime, and instrument findings remain Aperture objects. The post-unblinding comparison creates a third object: a comparison record that references both systems without rewriting either.

This separation prevents circular validation. PsiGuard cannot become the hidden label input that causes Aperture to reproduce PsiGuard. Aperture cannot redefine PsiGuard's actions in its own ontology. The scientific question concerns correspondence among independently formed records.

# 4. Experimental Design

## 4.1 Source trajectory

The source is a continuous long-horizon Bradley–Waypoint interaction containing 275 native source turns. The original environment included PsiGuard classifications and intervention context, but those annotations were excluded from the Aperture blind compute source. The source is unusual in length and continuity relative to short benchmark episodes and therefore provides a useful stress test for longitudinal evidence formation.

The blind computational source represents each native exchange as two events: Bradley as user and Waypoint as assistant. The complete source therefore contains 550 canonicalizable events. Four Waypoint responses are explicitly interrupted before completion. Those events remain part of the canonical history but are not treated as telemetry-bearing measurements, yielding 271 eligible Waypoint measurements.

## 4.2 Blind-source construction

The blind source preserves only information available without PsiGuard verdicts:

- native source-turn number;
- source ordering;
- Bradley prompt;
- full Waypoint response where supplied;
- user/assistant role identity;
- source actor identity;
- completion state;
- source provenance metadata.

The source excludes:

- holding labels;
- wandering labels;
- intervention labels;
- withheld classifications;
- PsiGuard detector readings;
- intervention coordinates supplied for comparison;
- proprietary detector internals;
- post-hoc narratives that explain expected outcomes.

Before compute, the blind source was hashed and preserved. The SHA-256 value is `5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6`.

## 4.3 Ingestion qualification

Ingestion was treated as Phase 0 rather than as a convenience step. An earlier generic operational-log path could claim the transcript before the role-aware transcript path, producing a malformed 323-frame runtime from the earlier T1–T150 source. Additional testing showed that speaker-like labels embedded within assistant content could also be misinterpreted as event boundaries.

No scientific result was accepted while those defects remained. The ingestion layer was repaired so that recognized roles alone open role boundaries, unknown label-like lines remain content when they occur inside active events, declared source-specific role maps are preserved without hard-coding the benchmark into the global ontology, and an independent line-by-line fidelity audit compares the canonical projection against the raw source.

The T1–T150 acceptance case then produced exactly 300 canonical events, 150 source turns, 148 eligible assistant measurements, two incomplete assistant events, zero pseudo-roles, zero continuation splits, and transcript/JSONL semantic identity. The same role-preserving strategy was extended to the T1–T275 blind source, producing 550 canonical events with 275 Bradley/user and 275 Waypoint/assistant events and four explicitly incomplete assistant measurements.

This history is included because source fidelity is part of the scientific method. A longitudinal detector cannot be validated on an event topology that it parsed incorrectly. The correction therefore precedes, rather than follows, acceptance of the science.

## 4.4 Full retrospective reconstruction

The complete T1–T275 blind source was computed once under the frozen Aperture science release. This run asks:

**Given the completed trajectory, what longitudinal structure does Aperture reconstruct from the full evidence record?**

The retrospective run was preserved through the Runtime Evidence lifecycle. The final certified record contains stable source and canonical coordinates, 271 eligible measurements, Method Contract PASS, an issued Runtime Evidence Passport, final temporal authority, instrument findings, a Casefile, a Validator result, a full forensic report, and preservation bundles.

The run was frozen before PsiGuard coordinate disclosure. Retrospective findings are explicitly marked as retrospective where later evidence contributes to support. They are not described as evidence that Aperture could necessarily have warned at the reconstructed historical coordinate.

## 4.5 Prospective prefix replay

The decisive prospective experiment recomputed the same source independently at every native source-turn horizon:

**T1, T1–T2, T1–T3, …, T1–T275.**

Each prefix terminates after the complete Bradley–Waypoint exchange for its final source turn. No source event beyond the prefix boundary is admitted. Each prefix is computed independently rather than incrementally inheriting hidden state from a previous prefix. This design makes the admissible evidence horizon explicit and prevents later turns from silently influencing earlier prospective states.

The prospective ledger records, at minimum:

- terminal source turn;
- prefix source hash;
- canonical event count;
- eligible measurement count;
- compute status;
- confidence state;
- current regime;
- staged-warning support;
- candidate support;
- formal-boundary support;
- reconstructed t_aw, t_candidate, and t* where applicable;
- tf and formal Δt availability;
- Method Contract status and count;
- unsupported-output count;
- evidence-horizon violations;
- prefix canonical identity;
- future-leakage audit;
- coordinate-audit status.

The prospective issuance coordinate is the prefix horizon at which a state is supportable, not an earlier coordinate reconstructed within that prefix. If a T40 computation reconstructs weakening at T25, that does not convert the prospective warning coordinate into T25. The prospective fact is that the T40 evidence horizon supported a finding that referred retrospectively to T25.

## 4.6 Engineering acceptance of the prefix experiment

The eight-horizon engineering acceptance sweep used T1, T2, T25, T50, T100, T150, T200, and T275 before the full sweep. Acceptance required exact source slicing, role preservation, completion-state preservation, zero future leakage, stable coordinates, Method Contract conformance, and reproduction of the final full-horizon scientific state.

The complete prospective sweep then produced:

- 275/275 evaluated prefix horizons;
- T1 unavailable as expected because only one eligible measurement exists and Aperture requires at least two;
- T2–T275: 274/274 computable;
- exact role/event topology: PASS;
- future-event leakage: 0;
- coordinate audits: PASS;
- ingestion errors: 0;
- Method Contracts: 48/48 on every computable prefix;
- unsupported outputs: 0;
- evidence-horizon violations: 0.

## 4.7 Blind result lock

After the prospective sweep, the Aperture result was frozen before PsiGuard disclosure. The Blind Result Lock records the science release, export release, source hash, certified retrospective identity, retrospective coordinates, prospective warning behavior, candidate intervals, formal-boundary emissions, determinism checks, ledger hashes, and a declaration that PsiGuard annotations were not used.

The governing post-lock rule is simple: **after Bradley discloses PsiGuard coordinates, Aperture is not recomputed or retuned for this comparison.** The external coordinates are joined to the frozen source-turn domain and evaluated against the already preserved Aperture results.

## 4.8 Identity reconciliation before disclosure

During preparation of the reviewer package, a discrepancy was discovered between the T275 identity retained by the prospective harness and the identity certified by the browser Runtime Evidence Artifact. The harness retained `f906ca496e167...`, whereas the production certified record carried `6753eadcdd506...`.

The discrepancy was investigated before external disclosure. The frozen blind JSONL and browser-certified canonical event spine were compared event-by-event across all 550 events on the fields most relevant to evidence identity:

- content;
- role;
- source turn;
- source-event ordinal;
- completion state;
- canonical turn.

All 550 events matched on all six dimensions. Total mismatches were zero. Rebuilding the production semantic canonical identity using the terminal r.5.7.4 identity contract reproduced `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd` exactly. The discrepancy was therefore classified as a harness-local identity-derivation/bookkeeping mismatch rather than a difference in source, canonical events, measurements, or scientific findings.

The original lock was preserved for audit. Blind Result Lock v2 carries the production-certified identity. No prospective ledger row was changed, no detector was rerun, and no scientific coordinate was altered. This episode is reported because evidence identity is part of the experiment rather than an implementation detail to be hidden.

## 4.9 Registered PsiGuard disclosure procedure

After this Version 0.1 manuscript is frozen, Bradley will be asked to disclose only the information required for comparison:

- PsiGuard intervention turns in the native T1–T275 coordinate system;
- PsiGuard wandering turns in the same coordinate system;
- optional operational clarification of those labels, if Bradley chooses to provide it.

The disclosure should be preserved as a dated machine-readable record. No detector internals are required. Any later descriptive material from Bradley is treated as explanatory context, not as Aperture evidence.

## 4.10 Registered post-disclosure comparison rules

The comparison is performed by source-turn join only. Each PsiGuard coordinate is joined to:

- the frozen Aperture prefix state at that source turn;
- the frozen retrospective state for the completed run;
- nearby Aperture state transitions needed to measure temporal offset;
- relevant bounded instrument findings where interpretation is supported.

Comparison outcomes are classified into the following registered classes.

| Class | Definition | Interpretation boundary |
|---|---|---|
| Prospective convergence | PsiGuard action occurs in the same or prespecified neighboring region as an Aperture prefix-valid warning/candidate/related bounded state | strongest cross-system agreement, not proof of identical construct |
| Temporal offset | both systems identify related development but at different turns | quantify signed offset; investigate threshold/sensitivity differences |
| Retrospective-only correspondence | completed Aperture record reconstructs relevant earlier structure, but prefix replay could not support it contemporaneously | evidence for reconstruction, not live-detection success |
| Aperture-only state | Aperture emits a prospective state without corresponding PsiGuard action in the comparison window | candidate false alarm, construct difference, or sensitivity difference |
| PsiGuard-only action | PsiGuard intervenes or marks wandering without a supported Aperture prospective state | candidate miss, construct difference, or operational threshold difference |
| Structural disagreement | both systems react in a similar region but characterize the development differently | analyze semantics rather than force binary agreement |
| Inadmissible comparison | missing source alignment, ambiguous label meaning, unavailable evidence, or mismatched coordinate domain prevents valid comparison | excluded from performance claims |

The principal offset quantity is defined in native source turns. For a PsiGuard coordinate T_p and the nearest semantically comparable Aperture prospective issuance T_a:

**offset = T_p − T_a**

Positive values mean Aperture issued earlier under the chosen pairing; negative values mean PsiGuard acted earlier. Offsets are not computed for pairs lacking a defensible semantic relationship.

## 4.11 Anti-contamination controls

The following controls are frozen before disclosure:

- no PsiGuard intervention/wandering coordinate was used to tune ingestion, telemetry, thresholds, regimes, markers, instruments, confidence gates, or claims;
- expected outcomes remain outside Aperture computation;
- external labels cannot rewrite the source, canonical runtime, telemetry, markers, findings, Passport, Seal, or evidence identity;
- prospective state is read from the frozen prefix ledger rather than regenerated after disclosure;
- retrospective coordinates remain labeled retrospective;
- temporary prefix t* emissions remain issued-and-withdrawn horizon states and cannot be promoted after the fact;
- absent tf remains absent unless independently supplied as an external outcome anchor;
- any identity or packaging correction must preserve an audit trail and cannot silently alter scientific results.

# 5. Pre-Disclosure Aperture Results

## 5.1 Certified source topology and evidence formation

The final blind source contains 275 native exchanges: 275 Bradley/user events and 275 Waypoint/assistant events. Aperture constructs 550 canonical events. Four Waypoint assistant events are explicitly incomplete and measurement-ineligible, leaving 271 eligible measurements. The final Method Contract Authority reports 48 registered contracts, 48 complete contracts, zero unsupported outputs, zero unresolved contracts, zero undeclared thresholds, zero undeclared evidence horizons, and zero measurement-horizon violations.

The certified Runtime Evidence identity is `APERTURE-CER-6753eadcdd506`. The canonical hash is `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`. The Runtime Evidence Passport is issued with Method Contract conformance PASS. The preservation Validator reports the required evidence stages aligned and the manifest valid.

These properties matter because the comparison is not performed against a screenshot or narrative summary. It is performed against a preserved evidence family whose source, canonical, measurement, temporal, authority, and preservation identities are inspectable.

## 5.2 Retrospective reconstruction

The completed T1–T275 trajectory supports the following frozen retrospective state.

| Evidence object | Frozen result |
|---|---|
| staged weakening / t_aw | T2 |
| candidate boundary | T25 |
| formal t* | null / not confirmed |
| observable failure tf | null / not supplied |
| formal Δt | unavailable |
| recovery | not observed |
| final regime | Transitional |
| candidate watch | T25 → T275 / 250 source turns |

The result is intentionally bounded. The full run reconstructs early weakening and sustained candidate formation, but it does not satisfy the governing conditions required to confirm Basin Exit. No observable-failure anchor is independently supplied, so formal lead time cannot be computed. Later instrument surfaces may describe high pressure, elevated drift, or critical exposure, but those projections do not override final temporal authority.

## 5.3 Prospective staged warning

The first staged warning is available at T2, the first computable prefix. At T2 the production confidence state is **informational only**. The warning then remains present at every computable horizon through T275.

Confidence milestones for the already-present warning are:

| Prefix horizon | Confidence state | Interpretation |
|---|---|---|
| T2 | informational only | earliest supportable staged warning under minimum evidence |
| T8 | low confidence | confidence maturation, not a new warning onset |
| T18 | medium confidence | confidence maturation |
| T40 | high confidence | confidence maturation |

This behavior makes the warning highly sensitive on this trajectory but not independently discriminative. Because it remains on continuously after T2, its utility cannot be evaluated from onset timing alone. The post-unblinding analysis must therefore consider false-alarm burden, persistence, and whether PsiGuard actions cluster around later structural changes rather than merely asking whether a warning existed.

## 5.4 Prospective candidate behavior

Candidate status is substantially more horizon-sensitive than the broad warning state. It first appears at T2, but repeatedly withdraws and reappears as the evidence horizon grows. The candidate state becomes continuously present only from T168 through T275.

This is an important divergence from the completed retrospective record, which reconstructs the candidate boundary at T25. The two facts answer different questions:

- **Retrospective T25**: using the completed trajectory, Aperture identifies T25 as the candidate formation coordinate.
- **Prospective continuous candidate from T168**: under prefix-bounded evidence, candidate status does not remain continuously established until much later.

Therefore the retrospective candidate coordinate cannot be described as if Aperture had maintained a stable candidate call from T25 onward in real time.

## 5.5 Formal t* and prefix invariance

The strongest prospective finding is that formal t* is deterministic at individual horizons but not prefix-invariant across the growing record.

A temporary formal t* first appears at T10. Across all 275 prefix horizons, formal t* is emitted at 32 horizons:

**T10, T20, T21, T22, T25, T44, T56, T62, T71, T77, T87, T93, T109, T118, T126, T143, T157, T161, T168, T170, T187, T196, T205, T212, T215, T220, T226, T229, T235, T237, T245, T258.**

These emissions are subsequently withdrawn as later evidence enters the admissible horizon. At T275, formal t* is null and `t_star_confirmed = false`.

Selected independent prefix reruns at T2, T10, T20, T25, T69, T126, T168, T196, T245, and T275 reproduce the same state/identity comparisons exactly. The flicker is therefore not treated as execution noise. It is evidence that the present formal-boundary decision is horizon-sensitive under this trajectory.

The experiment preserves these emissions as **issued-and-withdrawn prospective states**. They are not promoted into a stable Basin Exit claim. Their relationship to PsiGuard intervention is reserved for post-unblinding comparison.

## 5.6 Formal lead time remains unavailable

No independently supplied observable-failure anchor tf is present in the Aperture blind evidence. Consequently, formal Δt remains unavailable in both retrospective and prospective analysis. Candidate formation, warning onset, high failure exposure, or temporary prefix t* cannot substitute for tf.

This refusal is methodologically important. A system can appear more impressive by manufacturing lead time from any early warning and later adverse-looking behavior. The current evidence authority prevents that substitution. A formal lead-time claim requires the declared temporal anchors under the governing method.

## 5.7 Final regime and open watch

The completed run ends in a Transitional regime. The candidate watch remains open from T25 through T275, covering 250 native source turns. Recovery is not observed, but neither is a final Basin Exit or supplied observable failure.

This state is neither a stable-normal conclusion nor a confirmed-failure conclusion. It is a bounded open trajectory with persistent candidate evidence. That intermediate evidentiary posture is important for the external comparison because PsiGuard may have acted within periods that Aperture ultimately preserved as open candidate formation rather than as a terminal failure state.

## 5.8 Instrument projections

The instrument layer renders multiple bounded views over the same certified evidence identity. Representative surfaces expose stability, drift, pressure, continuity, basin proximity, temporal organization, operational translation, failure exposure, role/tool dynamics, and related evidence. These surfaces are useful for structural comparison but do not independently authorize stronger marker claims.

Selected final-run projections include high Basin Pressure, elevated drift, critical composite failure exposure, and Tool-Loop Pressure as a primary bounded finding. The exact numerical projection should be interpreted within the relevant instrument contract rather than as a universal probability of failure. The final temporal authority remains decisive for formal t*, tf, and Δt status.

## 5.9 Evidence refusal as a result

The completed run demonstrates a property that is easy to overlook: Aperture is capable of refusing a stronger claim despite substantial adverse-looking evidence. The user interface contains dramatic pressure, drift, boundary, and exposure visualizations. Yet the certified authority says candidate, not confirmed Basin Exit; open watch, not formal failure interval; tf unavailable; lead time not computable.

That refusal is a practical test of Evidence-Governed Computation. The architecture is not only a measurement engine. It is also a constraint system that separates observations, computations, candidate states, confirmed markers, external anchors, and prohibited interpretations.

# 6. Registered Post-Unblinding Cross-System Analysis

## 6.1 Status of this section

**Reserved by protocol.** At Version 0.1 freeze, PsiGuard intervention and wandering coordinates have not been disclosed to Aperture analysis. This section defines the exact structure into which those coordinates will be inserted after Bradley provides them. Numerical convergence rates, offsets, and disagreement counts are intentionally absent.

Version 1.0 will complete this section without recomputing Aperture.

## 6.2 PsiGuard disclosure record

The final paper will record:

- disclosure timestamp;
- Bradley's preferred formal attribution;
- the disclosed intervention coordinates;
- the disclosed wandering coordinates;
- any label definitions Bradley authorizes for publication;
- a SHA-256 fingerprint of the disclosure file;
- confirmation that disclosure occurred after the Aperture Blind Result Lock and Version 0.1 manuscript freeze.

## 6.3 Temporal correspondence

For each disclosed PsiGuard coordinate, the comparison will identify the frozen Aperture state at that exact source turn and, where meaningful, the nearest semantically comparable prospective Aperture state transition. Results will distinguish exact-turn coincidence from neighborhood-level correspondence.

No single tolerance window is assumed to establish scientific equivalence. Any neighborhood threshold used for summary statistics will be declared explicitly and reported alongside exact offsets.

## 6.4 Prospective convergence

A case will be classified as prospective convergence when PsiGuard acts within a region in which Aperture, using only prefix-valid evidence, already carries a semantically relevant warning, candidate, regime, or bounded instrument state. The analysis will state which Aperture object supports the classification rather than treating all warnings as interchangeable.

Because Aperture warning is continuously present after T2, convergence cannot be claimed merely because a PsiGuard action occurs while warning is true. Stronger prospective convergence will require additional structural specificity, such as candidate status, a local state transition, pressure/drift formation, or another registered comparison dimension.

## 6.5 Temporal offset

Where both systems identify semantically related structure but at different turns, the signed source-turn offset will be reported. The paper will report the pair selection rule, exact coordinates, absolute offset, and sign interpretation.

Offsets may reveal sensitivity differences, action thresholds, persistence requirements, or evidentiary asymmetry. They are not automatically interpreted as one system being better or earlier in a predictive sense.

## 6.6 Retrospective-only correspondence

A case will be classified as retrospective-only when the completed Aperture record reconstructs relevant structure in the same region, but the corresponding prefix state did not support the finding at that time. This category is central to the paper because it distinguishes the scientific value of reconstruction from the operational value of live detection.

A retrospective-only match is explicitly **not** counted as a prospective detection success.

## 6.7 Aperture-only and PsiGuard-only cases

Aperture-only states may reflect false alarms, higher sensitivity, broader constructs, or evidence that PsiGuard did not operationalize. PsiGuard-only actions may reflect Aperture misses, different constructs, a higher-level control rule, or evidence unavailable to Aperture.

The paper will report such cases rather than exclude them to improve apparent agreement.

## 6.8 Structural disagreement

Structural disagreement occurs when the systems react in the same temporal region but describe materially different phenomena. For example, PsiGuard may classify a condition as wandering while Aperture emphasizes Tool-Loop Pressure, role pressure, drift, or candidate boundary formation.

These cases may be more scientifically informative than exact label matches because they expose how the systems partition the trajectory.

## 6.9 Wandering analysis

PsiGuard wandering coordinates will be joined separately from intervention coordinates. The analysis will inspect Aperture regime, drift, role/tool dynamics, pressure, candidate status, and other bounded findings at and around those turns. Wandering is not assumed to equal drift; the purpose is to test whether the independently defined phenomena show structural or temporal relationship.

## 6.10 Persistent warning and false-alarm burden

Because Aperture's staged warning remains continuously present from T2, prospective utility cannot be summarized by sensitivity alone. The final analysis will report the persistence of warning relative to the number and distribution of PsiGuard actions and will avoid describing a continuously active warning as a sequence of successful detections.

The paper will therefore distinguish:

- warning availability;
- warning confidence maturation;
- candidate issuance;
- formal-boundary issuance;
- sustained candidate intervals;
- local bounded instrument changes;
- external PsiGuard actions.

This decomposition is necessary for any meaningful false-alarm or operational-utility interpretation.

## 6.11 Post-unblinding integrity rule

No Aperture science object may be recomputed for the primary comparison after disclosure. Corrections limited to packaging, typography, repository organization, or clearly documented clerical transcription are permitted only if they do not alter scientific content and remain auditable.

Any desire to improve Aperture after seeing PsiGuard becomes a new experiment requiring a new version, new lock, and separate evaluation.

# 7. Discussion

## 7.1 From architectural proposition to empirical machinery

Papers I–VII establish a scientific and architectural program: Longitudinal Computational Dynamics as the field, Longitudinal Computational Behavior as the empirical object, Runtime Evidence as the evidentiary substrate, Evidence-Governed Computation as the claim discipline, Chronodynamics as the temporal specialization, and Aperture as the reference implementation.

The Waypoint–PsiGuard experiment changes the status of that program in a specific but important way. Aperture is no longer being evaluated only on internally authored scenarios or architectural demonstrations. It has processed an independently originated, long-horizon interaction; preserved its roles and incomplete events; constructed a 550-event canonical runtime; formed 271 eligible measurements under 48 complete Method Contracts; issued a certified evidence identity; reconstructed a worldline; replayed 275 evidence horizons; exposed non-prefix-invariant marker behavior; refused unsupported formal claims; and preserved a machine-readable artifact family for external inspection.

In that bounded sense, **Aperture has crossed from architectural proposition into working empirical machinery.** The phrase does not mean that every metric is scientifically validated. It means the architecture can now be used to conduct an empirical experiment whose source, methods, claims, evidence horizons, identities, and discrepancies are preserved for challenge.

## 7.2 Prospective detection and retrospective reconstruction are different scientific objects

The experiment already establishes one major methodological result before any PsiGuard coordinate is known: retrospective and prospective temporal claims diverge materially on the same trajectory.

The completed record reconstructs a candidate boundary at T25. Prospective candidate status, however, is intermittent and does not remain continuously present until T168. Formal t* appears at 32 individual prefixes and then disappears, while the final record refuses t* entirely. These are not minor implementation details. They demonstrate that later evidence can change the admissibility of a marker and that a historical coordinate cannot be interpreted automatically as a contemporaneous warning.

This distinction should generalize as a methodological requirement even if the particular thresholds do not. Any long-horizon system that claims early warning from historical traces should distinguish the earliest coordinate that can be reconstructed from a completed trajectory from the earliest horizon at which the warning could actually have been issued without future evidence.

## 7.3 Prefix invariance becomes a validation target

The formal-boundary flicker observed here suggests that prefix invariance should be treated as an explicit validation property rather than an incidental characteristic. A deterministic decision at a single horizon can still be unstable under the addition of later evidence. Determinism asks whether the same prefix reproduces the same result; prefix invariance asks whether the meaning remains stable as the evidence horizon expands.

Those are different properties. The present t* behavior passes selected-horizon deterministic replay but fails prefix invariance on this trajectory. This does not automatically invalidate the boundary construct. It identifies a concrete target for method refinement, persistence design, calibration, and future validation.

## 7.4 Evidence refusal is scientifically informative

Aperture's final refusal to confirm Basin Exit is important precisely because the trajectory contains substantial evidence that could tempt overclaiming. High pressure, elevated drift, critical failure exposure, temporal stress, long candidate formation, and repeated temporary t* emissions could be narratively assembled into a failure story. The governing authority does not permit that assembly to become a formal claim when persistence, hysteresis, or external anchors are not satisfied.

This behavior is central to the value proposition of Runtime Evidence Infrastructure. An observatory should not merely generate measurements. It should preserve the difference between observation, computation, candidate, confirmation, external supply, and unavailable state.

## 7.5 What cross-system convergence would mean

If post-unblinding comparison reveals meaningful alignment, the appropriate interpretation is **cross-system convergent evidence within this trajectory**. Such correspondence would be stronger than Aperture agreeing with its own fixtures because PsiGuard was developed independently and its coordinates were withheld.

Even strong convergence would not prove objective truth, universal validity, or identical constructs. It would show that independently formed observational systems identify related temporal or structural regions under a protected comparison protocol. That result could motivate broader multi-trajectory and cross-system studies.

## 7.6 What disagreement would mean

Disagreement is not a failed experiment. If PsiGuard intervenes where Aperture sees no supported prospective instability, the result may expose an Aperture miss, a PsiGuard-specific construct, or evidence asymmetry. If Aperture warns broadly where PsiGuard remains in holding posture, the result may expose an Aperture false-alarm problem or a deliberately more conservative PsiGuard action threshold. If both react but characterize the region differently, the disagreement may illuminate construct boundaries.

The value of the current design is that these cases cannot be erased by tuning after disclosure. The disagreement remains evidence.

## 7.7 External validity remains open

One trajectory cannot establish transport across models, domains, organizations, or source types. The present study should therefore be interpreted as an external comparative case study, not as a population-level benchmark. Its strongest contribution is methodological and evidentiary: it demonstrates a protocol by which a Runtime Evidence system can be blind-tested against an independent live system without collapsing retrospective and prospective claims.

Future work should replicate the protocol across additional trajectories, include negative controls and stable runs, quantify false-alarm burden, introduce independently anchored outcomes where ethical and available, and invite unaffiliated investigators to reproduce the evidence pipeline.

## 7.8 Implications for Runtime Evidence Infrastructure

The experiment also illustrates why Runtime Evidence Infrastructure is broader than visualization. The reviewer package contains the source, canonical record, prospective ledger, Passport, Casefile, Validator, forensic report, preservation bundles, identity reconciliation, and immutable hashes. A reviewer can ignore the user interface and inspect the evidence directly. The UI then becomes a bounded projection over a preserved record rather than the sole location where the claim exists.

That architecture matters for accountability. Long-horizon systems will increasingly operate across sessions, tools, workflows, agents, and institutions. If evidence exists only as transient dashboards or narrative summaries, later challenge becomes difficult. A preserved Runtime Evidence object allows a finding to remain inspectable after the original session and allows external comparisons to be performed without rewriting the underlying computation.

# 8. Limitations and Threats to Validity

## 8.1 Single-trajectory design

The study analyzes one 275-turn interaction. No prevalence, generalization, or model-wide predictive claim follows from one trajectory. The source is valuable because it is long-horizon and independently originated, not because it is statistically representative.

## 8.2 Single external comparison system

PsiGuard provides one independent system. Agreement between two systems is stronger than self-agreement but remains insufficient to establish construct validity generally. Additional systems and human or operational anchors would strengthen triangulation.

## 8.3 PsiGuard coordinates are not ground-truth failure anchors

An intervention is an action produced under PsiGuard's operational policy. It is not automatically an independently verified failure event. Wandering is likewise a PsiGuard construct whose relationship to Aperture drift or regime state must be examined rather than assumed.

## 8.4 Proprietary external method

PsiGuard's internal detector logic may remain proprietary. This limits mechanism-level comparison and independent replication of PsiGuard. The study can still test coordinate-level correspondence if the disclosure object and label semantics are sufficiently clear, but any claim must respect this boundary.

## 8.5 Aperture warning sensitivity

Aperture's staged warning is present from T2 onward and therefore has limited discriminative value within this single trajectory. Post-unblinding analysis must not inflate apparent sensitivity by treating every later external action as a new warning success.

## 8.6 Formal-boundary horizon sensitivity

The 32 temporary t* emissions reveal a weakness or at least an unresolved property in current formal-boundary behavior. The paper reports this result rather than suppressing it. Future versions of the method may require revised persistence, hysteresis, or calibration, but such revisions are outside the frozen experiment.

## 8.7 No independently supplied tf

The source does not supply an independently anchored observable-failure coordinate to Aperture. Therefore formal lead time cannot be validated in this study. PsiGuard interventions cannot be substituted automatically for tf.

## 8.8 Source completeness

The experiment can only analyze what the supplied record preserves. Missing tool internals, omitted environmental events, provider truncation, or unrecorded context can affect interpretation. Canonicalization cannot recover absent facts without adding a separate external evidence source.

## 8.9 Measurement and construct validity

The experiment demonstrates implementation, deterministic replay, prospective horizon discipline, and the ability to compare against an independent system. It does not establish construct validity for every instrument or signal. Each measure retains the validation level supported by its own evidence.

## 8.10 No V5 independent replication

The complete evidence family is preserved for external inspection, but an unaffiliated investigator has not yet independently implemented or reproduced the method. Version 1.0 should state any external review performed by Bradley separately from independent implementation replication.

# 9. Reproducibility, Evidence Release, and Repository

## 9.1 Evidence package

The pre-disclosure reviewer package contains enough material for an external reviewer to inspect the Aperture side of the experiment without relying on the authors' summary. The package includes:

- experiment summary and overview;
- Blind Result Lock v2;
- frozen prospective prefix ledger;
- prospective summary;
- certified Runtime Evidence Artifact;
- Runtime Evidence Passport;
- full Casefile;
- human-readable report;
- diagnostic snapshot;
- technical appendices;
- preservation Validator;
- full forensic report;
- Aperture evidence bundle;
- Evidence Commons bundle;
- identity reconciliation record and report;
- original superseded lock retained for audit;
- verdict-free blind JSONL;
- raw immutable source representation;
- SHA-256 manifest.

The raw export family is preserved as unmodified browser exports, renamed only for review order.

## 9.2 Repository structure

The intended public research repository will use the following structure:

```text
paper-viii/
  README.md
  manuscript/
    Paper_VIII_pre_unblinding.docx
    Paper_VIII_pre_unblinding.pdf
    Paper_VIII_final.docx
    Paper_VIII_final.pdf

  protocol/
    proposed_test_protocol.md
    registered_analysis_plan.json

  source/
    blind_source.jsonl
    source_manifest.json
    source_map.json

  aperture/
    blind_result_lock_v2.json
    prospective_prefix_ledger.csv
    runtime_evidence_artifact.json
    runtime_evidence_passport.json
    validator.json
    full_casefile.json

  identity_audit/
    reconciliation.json
    reconciliation_report.md

  psiguard/
    disclosed_coordinates.json
    disclosure_manifest.json

  comparison/
    post_unblinding_comparison.json
    comparison_table.csv

  figures/
    selected_runtime_evidence_views/

  hashes/
    SHA256SUMS
```

**Repository URL:** reserved for Version 1.0 publication after collaborator review and authorization of the PsiGuard disclosure materials. No URL is invented in this pre-unblinding manuscript.

## 9.3 Versioning discipline

Version 0.1 is the registered pre-unblinding manuscript. It should be hashed and committed before PsiGuard coordinate disclosure. Version 1.0 will add the disclosed comparison results, collaborator-approved PsiGuard description, final authorship/attribution, repository URL, and post-unblinding Discussion additions.

The Version 1.0 manuscript should preserve the Version 0.1 artifact rather than overwrite it. The manuscript history becomes part of the anti-contamination evidence.

## 9.4 Data and collaboration release boundary

The Aperture evidence package can be released by SubstrateX subject to its research-use terms. PsiGuard coordinates, system descriptions, screenshots, or proprietary materials should be published only with Bradley's approval. The repository should therefore separate Aperture-owned materials from collaborator-controlled disclosure objects.

# 10. Conclusion

This study establishes a transition in the LCD research program from internal architecture and controlled validation toward blind external comparative evaluation. Aperture successfully transformed an independently originated 275-turn interaction into a qualified, canonicalized, measured, certified, instrumented, and preservable Runtime Evidence object. The complete run contains 550 canonical events and 271 eligible measurements under 48 complete Method Contracts, and it remains traceable to a frozen blind source.

The retrospective reconstruction identifies staged weakening at T2 and candidate formation at T25 while refusing final Basin Exit, observable failure, and formal lead time. The prospective prefix experiment reveals that those retrospective coordinates cannot be interpreted naively as live detections. Warning is available early but broadly persistent; candidate status is intermittent before becoming sustained much later; formal t* appears deterministically at 32 individual horizons but is not prefix-invariant and is absent from the completed record.

These findings matter independently of the forthcoming PsiGuard comparison. They demonstrate that prospective replay can expose evidentiary properties invisible in a full-horizon reconstruction and that evidence governance can preserve a weaker final claim despite visually and numerically strong adverse projections. They also identify prefix invariance as a concrete validation target for future temporal methods.

The decisive next question is external. PsiGuard was developed independently, operated live, and produced withheld intervention and wandering coordinates. The Aperture result, prospective ledger, comparison rules, and manuscript have been frozen before those coordinates are introduced. When Bradley discloses them, the systems will be compared by source-turn join only, with no Aperture recomputation.

If the systems converge, the result will constitute cross-system convergent evidence within this trajectory, not universal validation. If they diverge, the disagreement will remain equally important because it will reveal differences that were protected from post-hoc tuning. In either case, the experiment demonstrates a reproducible way to move from architectural proposition toward empirically challengeable Runtime Evidence science.

# References

Allen, J. F. (1983). Maintaining knowledge about temporal intervals. Communications of the ACM, 26(11), 832–843. DOI 10.1145/182.358434.

Asadi, A. (2026a). Longitudinal Computational Dynamics: Foundations of Computational Organization Across Extended Runtime. Version 1.0. Longitudinal Computational Dynamics Series, Paper I. SubstrateX®.

Asadi, A. (2026b). Validating Longitudinal Computational Dynamics: Deterministic Runtime Evidence and Discrimination of Computational Regime Transitions. Version 1.0. Longitudinal Computational Dynamics Series, Paper II. SubstrateX®.

Asadi, A. (2026c). Aperture Methods: Runtime Reconstruction, Evidence Formation, and Scientific Instrumentation in SubstrateX Aperture™. Version 1.0. Longitudinal Computational Dynamics Series, Paper III. SubstrateX®.

Asadi, A. (2026d). Foundations of Runtime Evidence: Source-Bound, Deterministic, and Claim-Governed Reconstruction of Longitudinal Computational Behavior. Version 1.0. Longitudinal Computational Dynamics Series, Paper IV. SubstrateX®.

Asadi, A. (2026e). Computational Behavior Architecture: Canonical Representation, Temporal Structure, and Evidence-Bound Reconstruction of Longitudinal Computational Behavior. Version 1.0. Longitudinal Computational Dynamics Series, Paper V. SubstrateX®.

Asadi, A. (2026f). Foundations of Evidence-Governed Computation: Evidence Authority, Claim Admissibility, and Bounded Computational Projection. Version 1.0. Longitudinal Computational Dynamics Series, Paper VI. SubstrateX®.

Asadi, A. (2026g). Foundations of Chronodynamics: Symbolic Time, Temporal Authority, and Prospective Validity in Longitudinal Computational Systems. Version 1.0. Longitudinal Computational Dynamics Series, Paper VII. SubstrateX®.

Asadi, A. (2026h). Worldline and Regime Standard (WRS). RFC 1.0 Draft. SubstrateX®.

Asadi, A. (2026i). Runtime Evidence Standard (RES). RFC 1.0 Draft. SubstrateX®.

Asadi, A. (2026j). Evidence Commons Standard (ECS). RFC 1.0 Draft. SubstrateX®.

Asadi, A. (2026k). Evidence-Governed Computation for the Web: An Executable Reference Architecture for Evidence-Bound Web Software. SubstrateX EGC Web™ Technical Paper I. Version 1.0. SubstrateX®.

Lamport, L. (1978). Time, clocks, and the ordering of events in a distributed system. Communications of the ACM, 21(7), 558–565. DOI 10.1145/359545.359563.

National Institute of Standards and Technology. (2023). Artificial Intelligence Risk Management Framework (AI RMF 1.0). DOI 10.6028/NIST.AI.100-1.

OpenTelemetry Project. (n.d.). Logs data model.

Rundgren, A., Jordan, B., & Erdtman, S. (2020). RFC 8785: JSON Canonicalization Scheme (JCS). Internet Engineering Task Force. DOI 10.17487/RFC8785.

van der Aalst, W. M. P. (2016). Process Mining: Data Science in Action (2nd ed.). Springer. DOI 10.1007/978-3-662-49851-4.

World Wide Web Consortium. (2013). PROV-O: The PROV Ontology.

**Experimental material.** Bradley–Waypoint T1–T275 long-horizon interaction and PsiGuard comparison record, supplied through research collaboration with Bradley, developer of PsiGuard. Formal bibliographic attribution and public-release terms pending collaborator review.

# Appendix A — Frozen Evidence and Identity Registry

| Item | Frozen value |
|---|---|
| Manuscript status | Version 0.1 — Registered Pre-Unblinding |
| Aperture science release | r.5.7.4 |
| Preserve/Export hotfix | r.5.7.4.1 — no science change |
| Blind source | PsiGuard_T1-T275_BLIND_APERTURE.jsonl |
| Blind source SHA-256 | 5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6 |
| Native source turns | 275 |
| Canonical events | 550 |
| Bradley/user events | 275 |
| Waypoint/assistant events | 275 |
| Explicit incomplete assistant events | 4 |
| Eligible Waypoint measurements | 271 |
| Method Contracts | 48 / 48 PASS |
| Certified run / Passport | APERTURE-CER-6753eadcdd506 |
| Certified canonical hash | 6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd |
| Retrospective t_aw | T2 |
| Retrospective candidate | T25 |
| Formal t* | null / not confirmed |
| tf | null / not supplied |
| Formal Δt | unavailable |
| Final regime | Transitional |
| Candidate watch | T25 → T275 / 250 source turns |
| External PsiGuard disclosure received at lock | false |

# Appendix B — Prospective Prefix Milestones

## B.1 Confidence milestones

| Horizon | State |
|---|---|
| T1 | unavailable — one eligible measurement |
| T2 | first staged warning; informational-only confidence |
| T8 | warning persists; low confidence |
| T18 | warning persists; medium confidence |
| T40 | warning persists; high confidence |
| T168 | candidate state begins continuous presence through T275 |
| T275 | Transitional; candidate present; formal t*=null |

## B.2 Temporary formal t* issuance horizons

T10, T20, T21, T22, T25, T44, T56, T62, T71, T77, T87, T93, T109, T118, T126, T143, T157, T161, T168, T170, T187, T196, T205, T212, T215, T220, T226, T229, T235, T237, T245, T258.

These are preserved as temporary issued-and-withdrawn prefix states. They are not a stable Basin Exit series.

## B.3 Deterministic repeat horizons

Independent repeats were performed at T2, T10, T20, T25, T69, T126, T168, T196, T245, and T275. The repeated state/identity comparisons matched exactly for the tested horizons.

# Appendix C — Registered Comparison Classification Record

A post-unblinding comparison row should minimally contain:

- native Bradley source turn;
- PsiGuard disclosed state/action;
- Aperture prospective warning state;
- Aperture prospective candidate state;
- Aperture prospective formal-boundary state;
- Aperture prospective regime;
- selected bounded structural findings where relevant;
- Aperture retrospective formation state;
- nearest semantically comparable prospective issuance coordinate;
- signed temporal offset where admissible;
- classification: prospective convergence, temporal offset, retrospective-only, Aperture-only, PsiGuard-only, structural disagreement, or inadmissible;
- analyst note constrained to the frozen evidence objects;
- source and artifact references.

# Appendix D — Evidence Package Inventory

The full pre-disclosure audit package provides the following review order.

1. Experiment Summary & Overview — concise statement of question, controls, and findings.
2. Blind Result Lock v2 — authoritative pre-disclosure declaration.
3. Runtime Evidence Passport — certified identity and claim boundary.
4. Runtime Evidence Artifact — primary machine-readable evidence object.
5. Validator — preservation, identity, and conformance status.
6. Full Forensic Report — broad inspection surface.
7. Prospective Prefix Ledger — all 275 evidence-horizon states.
8. Identity Audit — f906→6753 reconciliation and audit record.
9. Blind Source — verdict-free computational source and raw immutable source representation.
10. Aperture Evidence Bundle and Evidence Commons Bundle — preservation-level package objects.

A reviewer may ignore all narrative summaries and begin directly with items 3–10.

# Appendix E — Selected Runtime Evidence Views

The following figures are visual projections of the same frozen certified Runtime Evidence Record, `APERTURE-CER-6753eadcdd506`. They are included to make the machine-readable evidence family easier to inspect. The underlying Artifact, Passport, Casefile, Validator, forensic reports, prospective ledger, and preservation bundles remain authoritative.

![Figure E1 — Runtime Evidence Passport](/mnt/data/Image 01 — Runtime Evidence Passport.png)

**Figure E1. Runtime Evidence Passport.** The issued Passport binds the reconstructed interaction to one certified evidence identity covering 550 canonical frames and 271 eligible telemetry measurements. It records a Transitional final formation posture, High pressure, and Tool-Loop Pressure as the primary bounded finding while preserving the formal lead-time refusal.

![Figure E2 — Worldline Formation and Certified Frame Path](/mnt/data/Image 02 — Runtime Evidence Brief.png)

**Figure E2. Worldline Formation and Certified Frame Path.** The simplified formation view resolves Stable → Weakening at T2 → Candidate Boundary at T25 while leaving Basin Exit unresolved and Failure unsupplied. The lower frame path exposes the source-bound evidence events supporting the formation.

![Figure E3 — Seismo Runtime Field / Worldline](/mnt/data/Image 03 — Seismo Runtime Field  Worldline.png)

**Figure E3. Seismo Runtime Field / Worldline.** Seismo projects the certified run as a frame-indexed worldline combining stability, drift, pressure, continuity, basin proximity, and recovery posture while retaining the governing temporal constraints: T2 weakening, T25 candidate, t* not confirmed, and tf not supplied.

![Figure E4 — Worldline Reconstruction](/mnt/data/Image 05 — Worldline Reconstruction.png)

**Figure E4. Worldline Reconstruction.** The canonical/measurement alignment transforms the originally flat conversation into a 550-event longitudinal trajectory joined to 271 measurements while preserving explicit unmeasured gaps rather than silently filling them.

![Figure E5 — Benchmark Bridge / Operational Risk Translation](/mnt/data/Image 06 —  Operational Risk Translation.png)

**Figure E5. Benchmark Bridge / Operational Risk Translation.** The Bridge translates Runtime Evidence into an operational interpretation layer while explicitly refusing an official benchmark score, prospective forecast, deployment authority, or formal Δt claim.

![Figure E6 — Chronos Temporal Evidence Map](/mnt/data/Image 07 — Chronos Temporal Evidence Map.png)

**Figure E6. Chronos Temporal Evidence Map.** Chronos exposes frame-indexed temporal evidence together with temporal viscosity, compression, echo-time gradient, shear, curvature, and evidence-supported continuation postures. These are evidence-derived temporal projections, not calibrated future probabilities.

![Figure E7 — Pressure / Energetics](/mnt/data/Image 08 — Ξ Pressure.png)

**Figure E7. Pressure / Energetics.** Pressure decomposes observable runtime pressure into boundary, correction, Tool-I/O, temporal, and related contributions. The adjacent synthetic field is a deterministic diagnostic adjunct and is not presented as literal physical energy or hidden model mechanics.

![Figure E8 — Failure Exposure / Cognitive Cartography](/mnt/data/Image 09 — Failure Exposure.png)

**Figure E8. Failure Exposure / Cognitive Cartography.** Composite Failure Exposure is decomposed across observable channels. High exposure remains distinct from observed failure: the certified record retains no confirmed t*, no supplied tf, and no formal lead-time claim.

![Figure E9 — Drift Engine](/mnt/data/Image 10 — Drift Engine.png)

**Figure E9. Drift Engine.** Drift projects runtime displacement relative to observable anchors and attractor-like structures while remaining explicitly bounded to runtime evidence rather than hidden state, intent, consciousness, or internal causality.

# Appendix F — Post-Unblinding Completion Fields

Version 1.0 will add the following fields without altering the Version 0.1 record:

- Bradley's preferred formal name and affiliation;
- approved PsiGuard system description;
- authorship or collaboration attribution approved by Bradley;
- disclosure timestamp and disclosure artifact hash;
- intervention-turn list;
- wandering-turn list;
- exact source-turn join table;
- comparison outcome counts;
- temporal offset distribution where admissible;
- prospective convergence cases;
- retrospective-only cases;
- Aperture-only cases;
- PsiGuard-only cases;
- structural disagreements;
- persistent-warning / false-alarm analysis;
- post-unblinding Discussion additions;
- public repository URL;
- final Version 1.0 manuscript hash.

No Aperture recomputation is permitted for the primary comparison after disclosure.
