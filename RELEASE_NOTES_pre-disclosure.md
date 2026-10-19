# Pre-Disclosure Blind Study — Waypoint T1–T275

**Git tag:** `pre-disclosure-v0.1`  
**Release title:** `Pre-Disclosure Blind Study — Waypoint T1–T275`  
**Repository status:** `FROZEN_PRE_DISCLOSURE`  
**Freeze date:** 2026-10-19  
**PsiGuard coordinate disclosure received at freeze:** **NO**

## Purpose

This release freezes the Aperture side of the blind comparative study involving **SubstrateX Aperture™** and **PsiGuard** on the same Waypoint T1–T275 long-horizon trajectory before PsiGuard intervention and wandering coordinates are disclosed.

The governing experimental question is:

> **Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?**

## Frozen Aperture identity

- Science release: `r.5.7.4`
- Science build SHA-256: `921ece3edfb031ffb43035d526f8b4aacbfc118b0858ddc17590dc392747e0fb`
- Preserve/Export release: `r.5.7.4.1`
- Export build SHA-256: `a7bdec193eabc0f8901be243fd701d5575a5b9a67fa7dd7b574a39e83ae47a49`
- Certified Run / Passport: `APERTURE-CER-6753eadcdd506`
- Certified canonical hash: `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`
- Blind source SHA-256: `5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6`

## Frozen topology

- 275 native source turns
- 550 canonical events
- 275 Bradley/user events
- 275 Waypoint/assistant events
- 271 eligible Waypoint measurements
- 4 explicitly incomplete assistant events
- 48 / 48 Method Contracts PASS
- zero future-event leakage in the prospective sweep

## Frozen retrospective result

- Final regime: `Transitional`
- staged weakening / `t_aw`: `T2`
- candidate boundary: `T25`
- formal `t*`: `null / not confirmed`
- observable failure `tf`: `null / not supplied`
- formal Δt: `unavailable`
- recovery: `not observed`
- candidate watch: `T25 → T275 / 250 source turns`

## Frozen prospective result

Aperture was independently recomputed at every admissible evidence horizon:

`T1`, `T1–T2`, `T1–T3`, …, `T1–T275`.

- Prefix horizons: 275
- Computed prefixes: 274
- Expected unavailable prefix: `T1`
- First staged warning: `T2`, informational-only
- Warning interval: `T2 → T275`
- Candidate first issuance: `T2`
- Candidate persistent issuance: `T168`
- Temporary formal `t*` active at: 32 horizons
- Terminal T275 formal `t*`: `null`

The prospective sweep also exposed **Evidence-Horizon Sensitivity**: some longitudinal claims remained stable as the admissible horizon expanded, while others were issued, withdrawn, relocated, or reissued.

## Blind Result Lock

- Authoritative lock: `02_LOCK/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json`
- Lock fingerprint: `98b73b68af8f731ac163b9993d984399d339f429a07ef919fed4e874cd770525`
- Lock file SHA-256: `ee7885909849ed6073e001071e7e3cd2c8a1178efeacae50eb2055b5e2a37384`

## Included research records

This snapshot includes, among other records:

- the blind T1–T275 source;
- the certified Runtime Evidence Artifact and Runtime Evidence Passport;
- full Casefile, Validator, forensic, preservation, and Evidence Commons exports;
- all 275 prospective prefix states;
- determinism and engineering-acceptance records;
- the browser-versus-harness identity reconciliation;
- selected Aperture visual evidence surfaces;
- **Paper VIII — Blind Comparative Validation of Long-Horizon Runtime Stability** (Version 0.1, pre-unblinding);
- **Discovery Note 01 — Evidence-Horizon Sensitivity in Longitudinal Runtime Evidence** (Version 0.1, pre-unblinding).

## What this release does not establish

This release does **not** claim that:

- PsiGuard intervention is equivalent to Aperture `t_aw`;
- T2 is a validated predictive detection point;
- a temporary prefix `t*` is a stable Basin Exit;
- formal lead time exists without an independently supplied `tf`;
- agreement between Aperture and PsiGuard has already been demonstrated;
- the findings generalize beyond this trajectory.

Those questions are reserved for the post-disclosure comparison.

## Post-disclosure rule

This pre-disclosure release must remain historically reachable and must not be rewritten after PsiGuard coordinates are received.

After disclosure:

1. Aperture must not be recomputed or retuned for this comparison.
2. PsiGuard coordinates are joined by native `source_turn` only.
3. Post-disclosure materials must be published in a new commit and preferably under a new tag/release such as `post-disclosure-v0.1`.
4. The pre-disclosure lock, source, prospective ledger, hashes, and artifacts remain unchanged.

## Integrity and rights

See:

- `PRE_DISCLOSURE_LOCK.md`
- `MANIFEST_SHA256.txt`
- `REPOSITORY_STATUS.json`
- `LICENSE.md`
- `CITATION.cff`

The repository is released for non-commercial research, scientific evaluation, reproducibility review, critique, education, and scholarly discussion under the terms of the SubstrateX Research Evaluation License. It is **not** an open-source software release and grants no commercial implementation rights.
