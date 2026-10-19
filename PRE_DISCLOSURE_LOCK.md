# Pre-Disclosure Repository Lock

**Status:** `FROZEN_PRE_DISCLOSURE`  
**Freeze date:** 2026-10-19  
**PsiGuard disclosure received at freeze:** **NO**

This file records the authoritative identifiers for the public pre-disclosure repository snapshot of the Aperture × PsiGuard / Waypoint T1–T275 experiment.

## Aperture releases

- Science release: `r.5.7.4`
- Science build SHA-256: `921ece3edfb031ffb43035d526f8b4aacbfc118b0858ddc17590dc392747e0fb`
- Preserve/Export release: `r.5.7.4.1`
- Export build SHA-256: `a7bdec193eabc0f8901be243fd701d5575a5b9a67fa7dd7b574a39e83ae47a49`
- Export hotfix changed science: **false**

## Blind source

- File: `06_BLIND_SOURCE/PsiGuard_T1-T275_BLIND_APERTURE.jsonl`
- SHA-256: `5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6`
- Native source turns: **275**
- Canonical events: **550**
- PsiGuard annotations used in Aperture computation: **false**

## Certified Runtime Evidence identity

- Run ID: `APERTURE-CER-6753eadcdd506`
- Passport ID: `APERTURE-CER-6753eadcdd506`
- Canonical hash: `6753eadcdd5067e0262658efd7ea29d3aa72c599c59a33313f61bac51b2dcedd`
- Identity contract: `semantic_canonical_evidence`
- Canonicalization version: `2.0`
- Eligible measurements: **271**
- Method Contracts: **48 / 48 PASS**

## Frozen retrospective result

- Regime: `Transitional`
- staged weakening / `t_aw`: `T2`
- candidate boundary: `T25`
- formal `t*`: `null / not confirmed`
- observable failure `tf`: `null / not supplied`
- formal Δt: `unavailable`
- recovery: `not observed`
- candidate watch: `T25 → T275 / 250 source turns`

## Frozen prospective result

- Prefix horizons: **275**
- Computed prefixes: **274**
- Expected unavailable prefix: `T1`
- First staged warning: `T2`, informational-only
- Warning interval: `T2 → T275`
- Candidate first issuance: `T2`
- Candidate persistent issuance: `T168`
- Temporary formal `t*` active at: **32 horizons**
- Terminal T275 formal `t*`: `null`
- Future-event leakage: **0**

## Blind Result Lock v2

- File: `02_LOCK/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json`
- Lock fingerprint: `98b73b68af8f731ac163b9993d984399d339f429a07ef919fed4e874cd770525`
- File SHA-256: `ee7885909849ed6073e001071e7e3cd2c8a1178efeacae50eb2055b5e2a37384`

## Identity reconciliation

The earlier harness-local T275 identity `f906ca496e167...` was reconciled before disclosure against the browser-certified record. The two event spines matched **550/550** on content, role, source turn, source-event ordinal, completion state, and canonical turn. The production semantic identity reproduced `6753eadcdd506...` exactly. The original lock is retained under `05_IDENTITY_AUDIT/` as a superseded audit record.

## Publication rule

This pre-disclosure snapshot must not be rewritten after PsiGuard coordinates are received.

Post-disclosure materials must be published as a new commit and preferably a new signed/annotated tag or GitHub Release. The historical commit and release representing this snapshot must remain reachable.

Recommended tag:

`pre-disclosure-v0.1`

Recommended next tag after unblinding:

`post-disclosure-v0.1`
