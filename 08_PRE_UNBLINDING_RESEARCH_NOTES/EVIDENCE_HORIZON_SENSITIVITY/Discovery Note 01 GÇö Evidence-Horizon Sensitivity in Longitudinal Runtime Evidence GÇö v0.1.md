# Discovery Note 01 — Evidence-Horizon Sensitivity in Longitudinal Runtime Evidence

## A Pre-Unblinding Analysis of Claim Persistence, Withdrawal, Re-entry, and Coordinate Revision Across 275 Prospective Evidence Horizons

**Internal Technical Study · Version 0.1 · 19 October 2026**  
**Author:** Arjay Asadi  
**Affiliation:** SubstrateX® Longitudinal Labs  
**Research program:** Longitudinal Computational Dynamics® · Runtime Evidence · Evidence-Governed Computation™ · Chronodynamics  

---

## Abstract

A prospective prefix replay of the Waypoint T1–T275 trajectory exposed a methodological phenomenon that is not visible from a completed retrospective reconstruction alone. Aperture was recomputed independently at every native source-turn horizon, with no future-event leakage and with the external PsiGuard intervention/wandering coordinates withheld. The replay showed that some claims were highly stable under growing evidence while others were repeatedly issued, withdrawn, relocated, and reissued. The staged weakening coordinate `t_aw=T2` was invariant at every computable horizon after T2. By contrast, candidate-boundary status appeared at T2, withdrew and re-entered repeatedly, and became status-persistent only at T168; even after status persistence, its reconstructed coordinate continued to change. Most strikingly, formal `t*` was issued at 32 prefix horizons across 30 issuance episodes, withdrawn 30 times, and absent in the completed T275 record. Selected-prefix repeats reproduced these states deterministically.

This study names the phenomenon **Evidence-Horizon Sensitivity**: the degree to which an evidence-authorized finding, marker, regime, coordinate, or claim changes as the admissible evidence horizon expands. Its complement is **Horizon Invariance**. The central methodological conclusion is that deterministic replay at a fixed horizon does not imply longitudinal claim stability under later admissible evidence. The note proposes a set of horizon-stability metrics, separates status invariance from coordinate invariance, introduces a provisional Horizon Non-Monotonicity Principle, and recommends preserving claim revision lineage as part of Runtime Evidence. The result is intentionally bounded to one trajectory and remains pre-unblinding with respect to PsiGuard.

## Research Status and Claim Boundary

This is an internal discovery record, not a numbered foundational paper and not a claim of general validity. It documents a phenomenon discovered in one independently originated long-horizon trajectory before disclosure of the external system's comparison coordinates. It establishes that the phenomenon exists in this Aperture replay under the frozen implementation and source conditions. It does not establish prevalence across models, source families, or tasks; calibrated predictive validity; causal interpretation; or universal behavior of longitudinal evidence systems.

The study therefore distinguishes three levels:

1. **Observed in this run:** claim status and coordinates can be horizon-sensitive.
2. **Methodological implication:** prospective validation should test revision behavior, not issuance alone.
3. **General scientific proposition:** requires multi-case replication and remains open.

## 1. Discovery Context

The Waypoint/PsiGuard experiment was designed to distinguish completed-trajectory reconstruction from prefix-bounded prospective issuance. A verdict-free source preserved 275 native exchanges and was replayed as 275 independent evidence horizons: `T1`, `T1–T2`, ..., `T1–T275`. T1 was correctly unavailable because only one eligible measurement existed. T2–T275 produced 274 computable prefixes. Every computable prefix passed 48/48 Method Contracts, no future event entered an earlier prefix, coordinate audits passed, and no PsiGuard verdict or intervention coordinate was used as Aperture evidence.

The completed retrospective record resolves staged weakening at T2 and a candidate boundary at T25, while formal `t*` is not confirmed and observable failure `tf` is not supplied. The prefix replay revealed that these terminal statements conceal very different revision histories.

### 1.1 Discovery statement

> **A longitudinal claim can be deterministic at a given evidence horizon yet fail to remain invariant as the admissible evidence horizon expands.**

This is not equivalent to software nondeterminism. Repeated selected prefixes reproduced the same state. The variability appears when the admissible evidence horizon itself changes.

## 2. Definitions

Let `H_k` denote the admissible evidence horizon containing source evidence through native turn `k`. Let a governed claim `C(H_k)` contain at least: status, claim coordinate, claim class, confidence, method version, and evidence basis.

### 2.1 Evidence-Horizon Sensitivity

**Evidence-Horizon Sensitivity (EHS)** is the degree to which `C(H_k)` changes as `H_k` expands to later admissible horizons while the earlier source history remains unchanged.

A claim may be sensitive in several distinct ways:

- **status sensitivity:** issued versus inactive/withdrawn;
- **coordinate sensitivity:** the claim remains present but its assigned source/canonical coordinate changes;
- **claim-class sensitivity:** candidate, confirmed, unavailable, or other authority class changes;
- **confidence sensitivity:** evidentiary confidence strengthens or weakens;
- **regime sensitivity:** the governing regime classification changes.

### 2.2 Horizon Invariance

A finding is **horizon-invariant** over a declared interval when later admissible evidence does not alter the declared component of the finding except through an explicitly permitted revision rule. Horizon invariance must therefore name what is invariant: status, coordinate, claim class, confidence, or a complete claim object.

### 2.3 Prefix validity is not horizon stability

A claim can be validly issued at `H_k` using only evidence available at `H_k` and still be withdrawn at `H_(k+1)`. Prefix validity answers whether the claim was admissible *then*. Horizon stability asks whether the claim survives additional admissible evidence. They are different validation properties.

## 3. Experimental Basis

| Property | Frozen value |
|---|---:|
| Native source turns | 275 |
| Prefix horizons | 275 |
| Computable prefixes | 274 |
| Terminal canonical events | 550 |
| Terminal eligible measurements | 271 |
| Method Contracts | 48 / 48 PASS |
| Future-event leakage | 0 |
| PsiGuard annotations used | No |
| Browser-certified run | `APERTURE-CER-6753eadcdd506` |
| Terminal retrospective regime | Transitional |
| Terminal retrospective `t_aw` | T2 |
| Terminal retrospective candidate | T25 |
| Terminal formal `t*` | null / not confirmed |
| Terminal `tf` | null / not supplied |

The prospective ledger was frozen before PsiGuard coordinate disclosure. An identity-bookkeeping discrepancy between the prefix harness terminal hash and the browser-certified run was subsequently reconciled event-by-event before disclosure; all 550 canonical events matched on content, role, source turn, source-event ordinal, completion state, and canonical order. The scientific prefix rows were not recomputed or modified.

## 4. Empirical Findings

### 4.1 Weakening / staged warning: horizon-invariant after T2

The staged warning first becomes available at T2 and remains active for all 274 computable horizons from T2 through T275. The reconstructed weakening coordinate is T2 in every computable prefix.

- First issuance horizon: **T2**
- Persistent issuance horizon: **T2**
- Persistence lag: **0 turns**
- Active horizons: **274 / 274 after first issuance**
- Horizon Stability Ratio: **100.0%**
- Withdrawals: **0**
- Re-entries after first issuance: **0**
- Unique reconstructed `t_aw` coordinates: **1 (T2)**

This is the clearest example in the run of both status invariance and coordinate invariance.

### 4.2 Candidate boundary: status persistence emerges late

Candidate-boundary status first appears at T2 but is not monotonic. The observed issuance intervals are:

T2–T5; T10; T12–T17; T20–T68; T71; T77; T93; T109; T118; T122–T126; T143; T157; T161; T168–T275

The candidate becomes continuously present only from **T168 through T275**.

- First issuance horizon: **T2**
- Persistent issuance horizon: **T168**
- Persistence lag: **166 turns**
- Active horizons after first issuance: **181 / 274**
- Horizon Stability Ratio: **66.1%**
- Issuance episodes: **14**
- Withdrawals: **13**
- Re-entries after first issuance: **13**

This means a reader of only the final retrospective candidate T25 would miss the claim's substantial issuance/withdrawal history.

### 4.3 Status persistence does not imply coordinate invariance

Even after candidate status becomes persistent at T168, its reconstructed coordinate remains sensitive. Across all candidate-positive horizons, Aperture assigns **30 distinct candidate coordinates** and performs **61 coordinate revisions** between successive candidate-positive observations. Only **70 of 181 candidate-positive horizons (38.7%)** use the terminal retrospective coordinate T25.

From T168 through T275, candidate status is continuously present, yet the coordinate still spans **13 distinct source-turn values** with **37 revisions**. Only **38 of 108 horizons (35.2%)** carry the eventual terminal coordinate T25.

Therefore at least two forms of persistence must be separated:

1. **status persistence** — the marker remains active;
2. **coordinate persistence** — the marker remains anchored to the same coordinate.

### 4.4 Formal `t*`: deterministic issuance with terminal withdrawal

Formal `t*` is active at **32 horizons** across **30 issuance episodes**:

T10, T20, T21, T22, T25, T44, T56, T62, T71, T77, T87, T93, T109, T118, T126, T143, T157, T161, T168, T170, T187, T196, T205, T212, T215, T220, T226, T229, T235, T237, T245, T258

The episodes are:

T10; T20–T22; T25; T44; T56; T62; T71; T77; T87; T93; T109; T118; T126; T143; T157; T161; T168; T170; T187; T196; T205; T212; T215; T220; T226; T229; T235; T237; T245; T258

- First issuance horizon: **T10**
- Persistent issuance horizon: **none**
- Active horizons after first issuance: **32 / 266**
- Horizon Stability Ratio: **12.0%**
- Withdrawals: **30**
- Re-entries after first issuance: **29**
- Unique `t*` coordinates: **30**
- Terminal T275 `t*`: **null / not confirmed**

Selected-prefix deterministic repeats reproduced the formal states exactly. The phenomenon is therefore not adequately described as execution noise. At a fixed horizon, the decision is reproducible; across horizons, the authorized conclusion changes.

### 4.5 Regime classification is also horizon-sensitive

Among the 274 computable prefixes, the terminal Transitional regime appears at 207 horizons (75.5%), Stable at 33 (12.0%), and Collapse at 34 (12.4%). The prospective series contains **109 regime runs and 108 regime transitions**.

The terminal regime therefore summarizes the completed horizon; it does not represent a regime label that was stable throughout prospective replay.

## 5. Proposed Horizon-Stability Metrics

### 5.1 First Issuance Horizon

`H_first(C)` is the earliest admissible horizon at which claim `C` is issued.

### 5.2 Persistent Issuance Horizon

`H_persist(C)` is the earliest horizon after which the claim remains issued through the terminal observed horizon. It is undefined when no such horizon exists.

### 5.3 Persistence Lag

`L_p(C) = H_persist(C) - H_first(C)`

A large persistence lag distinguishes early sensitivity from durable support.

### 5.4 Horizon Stability Ratio

For horizons beginning at first issuance:

`HSR(C) = active horizons / horizons from H_first through terminal horizon`

In this run:

| Claim | H_first | H_persist | Persistence lag | HSR | Withdrawals | Re-entries |
|---|---:|---:|---:|---:|---:|---:|
| Warning / weakening | T2 | T2 | 0 | 100.0% | 0 | 0 |
| Candidate boundary | T2 | T168 | 166 | 66.1% | 13 | 13 |
| Formal `t*` | T10 | — | — | 12.0% | 30 | 29 |

### 5.5 Coordinate Revision Count

`CRC(C)` counts changes in the claim's coordinate across successive horizons where the claim is active. Candidate `CRC=61` in this run; formal `t*` changes coordinate 29 times across its 32 active horizons.

### 5.6 Terminal Coordinate Agreement Ratio

Conditional on claim presence, this measures the fraction of active horizons whose coordinate equals the terminal retrospective coordinate. For candidate boundary, the ratio is **38.7%** across all candidate-positive horizons and **35.2%** even after candidate status becomes persistent at T168.

These metrics are descriptive proposals for follow-up study; they are not yet standardized measures.

## 6. Provisional Horizon Non-Monotonicity Principle

The observations motivate the following provisional principle:

> **Additional evidence does not necessarily strengthen an existing longitudinal claim. New admissible evidence may preserve, strengthen, weaken, relocate, withdraw, or reissue a previously admissible finding.**

This principle is intentionally provisional. The Waypoint trajectory demonstrates existence in one case; it does not establish prevalence or universality.

The practical consequence is important: an evidence system should not assume that confidence or claim authority grows monotonically merely because the evidence horizon grows. Longitudinal evidence can correct earlier interpretations.

## 7. Implications for Evidence-Governed Computation

### 7.1 Revision is part of the evidence object

A final claim state alone can erase scientifically meaningful history. If a boundary was issued, withdrawn, reissued, and ultimately rejected, preservation of only the terminal rejection hides the actual behavior of the evidence system.

Runtime Evidence should therefore be capable of preserving claim revision lineage, including:

- claim identity;
- first issuance horizon;
- each status transition;
- claim coordinate at each issuance;
- confidence/evidence state;
- withdrawal horizon and reason where available;
- re-entry;
- terminal status;
- method and authority versions.

A companion proposed JSON schema is included with this study.

### 7.2 Prospective evaluation needs more than onset accuracy

A detector can appear impressive if evaluation records only its earliest positive horizon. That is insufficient when the signal later withdraws repeatedly. Prospective evaluation should therefore report persistence, withdrawal, re-entry, coordinate revision, terminal agreement, and false-alarm behavior in addition to first issuance.

### 7.3 Evidence refusal remains meaningful

The completed T275 record rejects a formal Basin Exit despite multiple earlier formal `t*` emissions. This terminal refusal should not erase the earlier emissions, and the earlier emissions should not be promoted into a final success. Both are part of the governed evidence history.

## 8. Implications for Chronodynamics

Chronodynamics already separates historical reconstruction from prospective replay. Evidence-Horizon Sensitivity adds a second distinction: **prospective admissibility at one horizon versus persistence under later horizons**.

A robust temporal analysis should therefore make at least three questions explicit:

1. What can be reconstructed from the completed trajectory?
2. What could be issued using only evidence available at horizon `H_k`?
3. How stable is that issued claim as admissible evidence expands beyond `H_k`?

The third question is the specific object of this discovery note.

## 9. Validation Consequences

The observation suggests a cross-cutting validation dimension: **Horizon Stability / Revision Consistency**. It does not replace existing validation levels. Instead it asks whether a prospective claim behaves coherently under evidence growth.

Future studies should examine:

- withdrawal frequency;
- time to persistent issuance;
- coordinate drift;
- confidence monotonicity/non-monotonicity;
- sensitivity near thresholds;
- dependence on persistence/hysteresis rules;
- stable and negative-control behavior;
- whether revision semantics match the governing Method Contract.

## 10. Follow-Up Study Design

The next study should repeat the prefix experiment across stable controls, transitions, recoveries, failure-confirmed runs, open-watch cases, and different source/model families. Each case should use frozen methods and exact prefix slicing. Claims should be analyzed separately for weakening, candidate boundary, formal `t*`, regime, Drift, Pressure, Failure Exposure, dominant finding, and recovery.

The included replication protocol defines the required fields, controls, metrics, falsification conditions, and promotion criteria.

## 11. Relationship to the Waypoint–PsiGuard Comparative Study

Paper VIII should retain Evidence-Horizon Sensitivity as a major pre-disclosure finding, but the phenomenon should not depend on the post-unblinding outcome. It was discovered before PsiGuard coordinates were available and should remain analytically separate from whether the two systems later converge or disagree.

A suitable statement for Paper VIII is:

> The prospective replay unexpectedly revealed substantial Evidence-Horizon Sensitivity in formal boundary issuance, motivating a separate analysis of claim persistence, coordinate revision, and withdrawal under expanding evidence.

## 12. Limitations

This internal study has important limitations. It analyzes one long-horizon trajectory and one implementation. Some horizon-sensitive behavior may reflect declared threshold/hysteresis design rather than a general property of longitudinal evidence. The study does not yet separate desirable evidence revision from over-sensitive marker logic, estimate population rates, compare alternative threshold regimes, or test independent implementations. PsiGuard coordinates remain undisclosed and are not used here.

The formal `t*` flicker should therefore be treated simultaneously as (a) evidence of horizon sensitivity and (b) a potential target for later method review after the blind comparative experiment is completed. It must not be silently repaired before unblinding.

## 13. Conclusion

The Waypoint T1–T275 prospective replay revealed a distinction that is not visible from endpoint reconstruction alone. Aperture's weakening coordinate was completely horizon-invariant after T2. Candidate-boundary status was intermittent before becoming persistent at T168, while its coordinate continued to revise even after status persistence. Formal `t*` was deterministically issued at 32 horizons but never achieved persistent issuance and was absent from the completed record.

These observations establish, within this run, that **deterministic issuance and horizon invariance are separate properties**. They also show that claim status persistence and coordinate persistence must be analyzed separately. The result motivates Evidence-Horizon Sensitivity as a distinct methodological object, Horizon Invariance as its complement, and claim revision lineage as a preservation requirement for prospective Runtime Evidence.

The discovery remains intentionally bounded and pre-unblinding. Its next scientific test is replication across multiple trajectory classes and independent outcome contexts.

## References and Internal Evidence Basis

1. Asadi, A. (2026). *Longitudinal Computational Dynamics: Foundations of Computational Organization Across Extended Runtime*. Longitudinal Computational Dynamics Series, Paper I. SubstrateX®.
2. Asadi, A. (2026). *Validating Longitudinal Computational Dynamics: Deterministic Runtime Evidence and Discrimination*. Longitudinal Computational Dynamics Series, Paper II. SubstrateX®.
3. Asadi, A. (2026). *Foundations of Evidence-Governed Computation*. Longitudinal Computational Dynamics Series, Paper VI. SubstrateX®.
4. Asadi, A. (2026). *Foundations of Chronodynamics*. Longitudinal Computational Dynamics Series, Paper VII. SubstrateX®.
5. `APERTURE_T1-T275_PROSPECTIVE_PREFIX_LEDGER_FINAL.csv` — frozen 275-prefix prospective ledger.
6. `APERTURE_T1-T275_PHASE3_PROSPECTIVE_PREFIX_REPORT.md` — pre-unblinding Phase 3 report.
7. `APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json` — reconciled pre-disclosure lock.
8. `APERTURE_T1-T275_IDENTITY_RECONCILIATION.json` — browser/harness identity reconciliation.

## Appendix A — Formal `t*` issuance horizons

T10, T20, T21, T22, T25, T44, T56, T62, T71, T77, T87, T93, T109, T118, T126, T143, T157, T161, T168, T170, T187, T196, T205, T212, T215, T220, T226, T229, T235, T237, T245, T258

## Appendix B — Candidate issuance intervals

T2–T5; T10; T12–T17; T20–T68; T71; T77; T93; T109; T118; T122–T126; T143; T157; T161; T168–T275

## Appendix C — Companion Materials

This discovery package includes:

- machine-readable horizon-sensitivity metrics;
- full enriched claim revision ledger;
- transition-only claim revision ledger;
- proposed claim revision lineage JSON schema;
- multi-case replication protocol;
- frozen discovery record;
- three derived figures;
- SHA-256 manifest.
