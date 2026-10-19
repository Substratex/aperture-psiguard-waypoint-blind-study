# Experiment Summary & Overview

## Experimental question

**Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?**

This is a comparison of related evidence, not an assumption of detector equivalence:

- **PsiGuard:** live stability/control system operating prospectively.
- **Aperture:** longitudinal Runtime Evidence system supporting both retrospective reconstruction and prefix-bounded prospective analysis.

## Experimental controls

The Aperture result was frozen **before PsiGuard coordinate disclosure**.

Aperture did not receive as evidence inputs:

- intervention turns,
- wandering labels,
- holding/intervened classifications,
- PsiGuard detector readings,
- withheld/proprietary detector internals.

The blind computational source preserves only source ordering, Bradley prompts, Waypoint responses, roles, completion state, native source-turn coordinates, and provenance.

## Source / topology

| Item | Frozen value |
|---|---:|
| Native source turns | 275 |
| Canonical events | 550 |
| User / Bradley events | 275 |
| Assistant / Waypoint events | 275 |
| Eligible Waypoint measurements | 271 |
| Explicit incomplete assistant events | 4 |
| Method Contracts | 48 / 48 PASS |
| Certified run / Passport | `APERTURE-CER-6753eadcdd506` |
| Certified canonical hash | `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd` |

## Retrospective reconstruction

The completed T1–T275 trajectory supports:

| Evidence coordinate | Result |
|---|---|
| `t_aw` / staged weakening | **T2** |
| candidate boundary | **T25** |
| formal `t*` | **null / not confirmed** |
| observable failure `tf` | **null / not supplied** |
| formal Δt | **unavailable** |
| recovery | **not observed** |
| final regime | **Transitional** |
| candidate watch | **T25 → T275 / 250 turns** |

The retrospective finding is intentionally bounded: **candidate formation is observed, but Basin Exit is not confirmed.**

## Prospective prefix experiment

The same blind source was replayed independently at every evidence horizon:

`T1`, `T1–T2`, `T1–T3`, ... `T1–T275`.

Each prefix contained no future event beyond its terminal source turn.

Engineering acceptance:

- 275/275 prefix horizons evaluated;
- T1 expected unavailable because fewer than two telemetry-bearing turns exist;
- T2–T275: 274/274 computed;
- exact role/event topology PASS;
- future leakage: 0;
- coordinate audits PASS;
- ingestion errors: 0;
- 48/48 Method Contracts on each computable prefix;
- unsupported outputs: 0;
- evidence-horizon violations: 0.

### Prospective warning

The first staged warning appears at **T2**, but at **informational-only** confidence. It remains present through T275.

Confidence milestones for that already-present warning:

- T2 — informational only
- T8 — low confidence
- T18 — medium confidence
- T40 — high confidence

This makes the warning highly sensitive on this trajectory; it should not be interpreted as a standalone discriminative detector onset.

### Prospective candidate behavior

Candidate status is horizon-sensitive:

- first appears at **T2**;
- repeatedly withdraws and reappears;
- becomes continuously present only from **T168 through T275**.

The completed retrospective reconstruction nevertheless places the candidate boundary at **T25**. This is direct evidence that retrospective coordinate reconstruction and prospective issuance are different questions.

### Formal `t*` behavior

A temporary formal `t*` first appears at **T10** and is emitted at 32 individual prefix horizons. These states are deterministic on repeated selected-prefix runs, but they are subsequently withdrawn as the evidence horizon grows.

The completed T275 record has:

- `t* = null`
- `t_star_confirmed = false`

Therefore the 32 prefix emissions are retained as **temporary issued-and-withdrawn horizon states**, not as a stable Basin Exit claim.

No `tf` was independently supplied, so formal lead time is unavailable throughout.

## Identity reconciliation before disclosure

The prospective harness initially retained a local T275 identity `f906ca496e167...`, while the browser-certified Runtime Evidence Artifact carried `6753eadcdd506...`.

Before PsiGuard disclosure, the two records were reconciled event-by-event:

- 550/550 content matches;
- 550/550 roles match;
- 550/550 source-turn coordinates match;
- 550/550 source-event ordinals match;
- 550/550 completion states match;
- 550/550 canonical-turn coordinates match.

Total mismatches: **0**.

Rebuilding the production semantic canonical identity reproduces `6753eadcdd506...` exactly. The discrepancy was therefore classified as a **harness identity-derivation/bookkeeping mismatch**, not a difference in source, canonical events, measurements, or scientific findings.

The original lock is retained for audit; Blind Result Lock v2 carries the certified browser identity. The prefix ledger itself remains immutable.

## Interpretation boundaries

This package does **not** claim:

- that PsiGuard intervention equals Aperture `t_aw`;
- that T2 constitutes validated predictive detection;
- that any temporary prefix `t*` is a stable Basin Exit;
- that formal lead time exists without independently supplied `tf`;
- that agreement with PsiGuard has already been demonstrated.

Those questions are intentionally reserved for post-disclosure comparison.

## Post-disclosure operation

After Bradley supplies intervention and wandering turns, the next operation is a **join only** by native `source_turn`.

Aperture will not be recomputed or tuned.

The comparison will distinguish:

1. prospective convergence;
2. temporal offset;
3. retrospective-only correspondence;
4. Aperture-only warning;
5. PsiGuard-only intervention;
6. structural disagreement.

This preserves the test as an external comparison rather than turning it into a post-hoc detector-fitting exercise.
