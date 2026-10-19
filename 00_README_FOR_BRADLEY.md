# Aperture × PsiGuard — Blind Pre-Disclosure Audit Repository

**Experiment:** Waypoint T1–T275 blind retrospective + prospective prefix validation  
**Status:** FROZEN BEFORE PSIGUARD COORDINATE DISCLOSURE  
**Aperture science release:** r.5.7.4  
**Aperture Preserve/Export hotfix:** r.5.7.4.1 — no science changes

Bradley,

This repository contains the frozen Aperture side of the comparison. The short summary records our interpretation; the raw source, prospective ledger, certified evidence exports, identity audit, and visual projections are included so you can inspect the same run independently before disclosing where PsiGuard intervened.

Nothing here requires acceptance of our interpretation on trust.

## Certified run identity

- Run / Passport: `APERTURE-CER-6753eadcdd506`
- Canonical hash: `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`
- Native source turns: 275
- Canonical events: 550
- Bradley/user events: 275
- Waypoint/assistant events: 275
- Eligible measurements: 271
- Explicit incomplete assistant events: 4
- Method Contracts: 48 / 48 PASS
- PsiGuard intervention/wandering annotations used by Aperture: **none**

## Recommended review order

1. `01_EXPERIMENT_SUMMARY_OVERVIEW.md`
2. `02_LOCK/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json`
3. `04_FULL_APERTURE_EXPORTS/aperture-runtime_passport-APERTURE-CER-6753eadcdd506.json`
4. `04_FULL_APERTURE_EXPORTS/aperture-evidence_artifact-APERTURE-CER-6753eadcdd506.json`
5. `04_FULL_APERTURE_EXPORTS/aperture-validator-APERTURE-CER-6753eadcdd506.json`
6. `04_FULL_APERTURE_EXPORTS/full-forensic-report-APERTURE-CER-6753eadcdd506.json`
7. `03_PROSPECTIVE/APERTURE_T1-T275_PROSPECTIVE_PREFIX_LEDGER_FINAL_FROZEN.csv`
8. `05_IDENTITY_AUDIT/`
9. `06_BLIND_SOURCE/`
10. `07_VISUAL_APPENDIX/`
11. `08_PRE_UNBLINDING_RESEARCH_NOTES/` for the registered Paper VIII manuscript and the separate Evidence-Horizon Sensitivity discovery record.

If you want to ignore every summary we wrote and inspect the run independently, begin with items 3–9.

## Frozen Aperture result

Retrospective full-horizon result:

- staged weakening / `t_aw`: **T2**
- candidate boundary: **T25**
- formal `t*`: **null / not confirmed**
- observable failure `tf`: **null / not supplied**
- formal Δt: **unavailable**
- final regime: **Transitional**
- candidate watch: **T25 → T275 / 250 source turns**

Prospective prefix result:

- T1 unavailable as expected with one eligible measurement;
- T2–T275: 274/274 computable;
- staged warning available from T2, initially informational-only;
- candidate state is horizon-sensitive and becomes continuously present from T168;
- temporary formal `t*` appears at 32 individual prefixes and is later withdrawn;
- completed T275 record retains `t*=null`.

The pre-disclosure prefix sweep also exposed **Evidence-Horizon Sensitivity**: deterministic claims at a particular horizon need not remain invariant as admissible evidence grows. The discovery record is preserved separately under `08_PRE_UNBLINDING_RESEARCH_NOTES/EVIDENCE_HORIZON_SENSITIVITY/` and was created before PsiGuard coordinate disclosure.

## Identity audit

The original Phase-3 harness lock used a local `f906ca...` identity. Before disclosure, the 550-event harness and browser-certified spines were compared event-by-event and matched exactly on content, role, source turn, ordinal, completion state, and canonical order. Production identity recomputation reproduced `6753eadc...`; the original v1 lock is therefore retained under `05_IDENTITY_AUDIT/` and explicitly marked **SUPERSEDED**, while v2 is authoritative.

No scientific finding or prospective row was changed during this reconciliation.

## What we need from PsiGuard next

See `09_REQUESTED_PSIGUARD_DISCLOSURE.md`.

After disclosure, Aperture will not be recomputed. The next operation is a source-turn join only.

## Integrity

`MANIFEST_SHA256.txt` contains SHA-256 hashes for every file in this repository. `REPOSITORY_STATUS.json` records the frozen handoff state.
