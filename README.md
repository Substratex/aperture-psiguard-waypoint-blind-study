# Aperture × PsiGuard — Waypoint T1–T275 Blind Comparative Study

**Repository status:** FROZEN PRE-DISCLOSURE SNAPSHOT  
**Aperture science release:** `r.5.7.4`  
**Aperture Preserve/Export release:** `r.5.7.4.1` — no science changes  
**Certified run / Passport:** `APERTURE-CER-6753eadcdd506`  
**Certified canonical hash:** `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`

This repository preserves the pre-disclosure Aperture side of a blind comparative study involving **SubstrateX Aperture™** and **PsiGuard** on the same long-horizon Waypoint trajectory.

The governing experimental question is:

> **Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?**

## Why this repository exists

The purpose of this repository is to make the Aperture result inspectable **before** PsiGuard intervention/wandering coordinates are disclosed. It contains the blind source, frozen retrospective Runtime Evidence Record, all 275 prospective prefix states, certification and preservation artifacts, identity reconciliation, selected visual evidence surfaces, and pre-unblinding research notes.

Nothing in this repository asks a reviewer to trust a narrative summary. The underlying machine-readable evidence family is included so the run can be independently inspected.

## Blindness / anti-contamination statement

At the time of this frozen snapshot, Aperture had **not** received as evidence inputs:

- PsiGuard intervention turns;
- PsiGuard wandering turns;
- holding/intervened classifications;
- PsiGuard detector readings;
- withheld/proprietary detector internals.

After disclosure, Aperture is not to be recomputed or retuned for this comparison. The post-disclosure operation is a **join by native `source_turn` only**. Any post-disclosure material must be added in a new commit/tag/release and must not overwrite this pre-disclosure snapshot.

## Frozen topology

| Item | Frozen value |
|---|---:|
| Native source turns | 275 |
| Canonical events | 550 |
| Bradley/user events | 275 |
| Waypoint/assistant events | 275 |
| Eligible Waypoint measurements | 271 |
| Explicit incomplete assistant events | 4 |
| Method Contracts | 48 / 48 PASS |
| Final regime | Transitional |
| Retrospective weakening / `t_aw` | T2 |
| Retrospective candidate boundary | T25 |
| Formal `t*` | null / not confirmed |
| Observable failure `tf` | null / not supplied |
| Formal Δt | unavailable |
| Candidate watch | T25 → T275 / 250 source turns |

## Prospective replay

The same blind source was independently recomputed at every evidence horizon:

`T1`, `T1–T2`, `T1–T3`, …, `T1–T275`.

The prospective record preserves what Aperture could support at each prefix without future events. It also exposed **Evidence-Horizon Sensitivity**: some claims remain stable as evidence grows, while others are issued, withdrawn, relocated, or reissued under later admissible evidence.

## Recommended review order

1. [`01_EXPERIMENT_SUMMARY_OVERVIEW.md`](01_EXPERIMENT_SUMMARY_OVERVIEW.md)
2. [`02_LOCK/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json`](02_LOCK/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json)
3. [`04_FULL_APERTURE_EXPORTS/aperture-runtime_passport-APERTURE-CER-6753eadcdd506.json`](04_FULL_APERTURE_EXPORTS/aperture-runtime_passport-APERTURE-CER-6753eadcdd506.json)
4. [`04_FULL_APERTURE_EXPORTS/aperture-evidence_artifact-APERTURE-CER-6753eadcdd506.json`](04_FULL_APERTURE_EXPORTS/aperture-evidence_artifact-APERTURE-CER-6753eadcdd506.json)
5. [`04_FULL_APERTURE_EXPORTS/aperture-validator-APERTURE-CER-6753eadcdd506.json`](04_FULL_APERTURE_EXPORTS/aperture-validator-APERTURE-CER-6753eadcdd506.json)
6. [`04_FULL_APERTURE_EXPORTS/full-forensic-report-APERTURE-CER-6753eadcdd506.json`](04_FULL_APERTURE_EXPORTS/full-forensic-report-APERTURE-CER-6753eadcdd506.json)
7. [`03_PROSPECTIVE/APERTURE_T1-T275_PROSPECTIVE_PREFIX_LEDGER_FINAL_FROZEN.csv`](03_PROSPECTIVE/APERTURE_T1-T275_PROSPECTIVE_PREFIX_LEDGER_FINAL_FROZEN.csv)
8. [`05_IDENTITY_AUDIT/`](05_IDENTITY_AUDIT/)
9. [`06_BLIND_SOURCE/`](06_BLIND_SOURCE/)
10. [`08_PRE_UNBLINDING_RESEARCH_NOTES/`](08_PRE_UNBLINDING_RESEARCH_NOTES/)

For the full handoff guide written specifically for Bradley, see [`00_README_FOR_BRADLEY.md`](00_README_FOR_BRADLEY.md).

## Research records included

The repository includes:

- the complete claim-revision and prospective prefix ledgers;
- the browser-vs-harness identity reconciliation record;
- the complete fresh Aperture export family.

## What this repository does not establish

This pre-disclosure repository does **not** claim that:

- PsiGuard intervention equals Aperture `t_aw`;
- T2 is already a validated predictive detection point;
- a temporary prefix `t*` is a stable Basin Exit;
- formal lead time exists without an independently supplied `tf`;
- agreement between Aperture and PsiGuard has already been demonstrated;
- the results generalize beyond this trajectory.

Those questions are reserved for the post-disclosure comparison.

## Integrity

The repository contains [`MANIFEST_SHA256.txt`](MANIFEST_SHA256.txt), which records SHA-256 hashes for the frozen package contents. The authoritative pre-disclosure identity and release hashes are also recorded in [`PRE_DISCLOSURE_LOCK.md`](PRE_DISCLOSURE_LOCK.md).

## Citation

See [`CITATION.cff`](CITATION.cff).

## License and rights

See [`LICENSE.md`](LICENSE.md). This repository is released for non-commercial research, scientific evaluation, critique, education, and scholarly discussion under the terms stated there. It is **not an open-source software release** and grants no commercial implementation rights.

## Collaboration

This study arose from an experimental collaboration between **Arjay Asadi / SubstrateX®**, developer of SubstrateX Aperture™, and **Bradley Carter**, developer of PsiGuard. The two systems were developed independently and are not assumed to measure identical constructs.

---

**SubstrateX® — Longitudinal Labs — Instrumenting Intelligence in Motion™** 
