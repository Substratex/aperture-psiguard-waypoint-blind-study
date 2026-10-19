# Aperture T1–T275 Prospective Prefix Test — Phase 3 Report

**Status:** COMPLETE / BLIND RESULT LOCKED  
**Aperture:** r.5.7.4  
**Blind source SHA-256:** `5a66a0300bd6cfca74e0c0ff022944b1ec39eaa5f3ad254ac2aed7cc9a87f3e6`  
**Full-run canonical hash:** `f906ca496e167b8f67487804023a3ed536c3780d9376faca4044836ca34184e0`  
**Full-run Passport / Run ID:** `APERTURE-CER-f906ca496e167`  
**Final prospective ledger SHA-256:** `1e4e701d676ba69ffc4ad67bb6ad4c56df07f2abab0dc1d7490f084689392f9a`  
**Blind Result Lock fingerprint:** `cae2ee0f595013731c4289456f0440e351d3573b8857ead61bd416c77fec09bb`

## Engineering acceptance

- 275 native source-turn prefixes evaluated independently.
- T1 is correctly unavailable: one eligible telemetry measurement is below Aperture's minimum of two.
- T2–T275: 274/274 computable.
- Exact role/event topology: PASS.
- Future-event leakage: 0.
- Coordinate audits: PASS.
- Ingestion errors: 0.
- Method Contracts: 48/48 on every computable prefix.
- Unsupported outputs: 0.
- Evidence-horizon violations: 0.
- T275 reproduces the frozen full-run identity and final temporal authority.

## Prospective findings

### Warning

The first staged warning is available at **T2** and remains present at every computable horizon through T275. T2 is production confidence **informational only**. Because the same warning stays on continuously, first warning coordinates at later confidence tiers are descriptive confidence milestones rather than independent detector onsets:

- T2 — informational only
- T8 — low confidence
- T18 — medium confidence
- T40 — high confidence

This makes the warning state highly sensitive but not discriminative within this trajectory.

### Candidate boundary

The first candidate state appears at **T2**, but candidate status repeatedly withdraws and reappears. It becomes continuously present from **T168 through T275**. The completed retrospective record reconstructs **candidate T25**. Therefore the candidate marker is not prefix-invariant.

### Formal t* / Basin Exit

A temporary formal t* first appears at **T10**. Across the 275 prefixes, formal t* is emitted at **32 horizons** and subsequently withdrawn; the completed T275 run has **t*=null**. The issuance turns are:

T10, T20, T21, T22, T25, T44, T56, T62, T71, T77, T87, T93, T109, T118, T126, T143, T157, T161, T168, T170, T187, T196, T205, T212, T215, T220, T226, T229, T235, T237, T245, T258

These temporary prefix emissions are deterministic in repeated runs at selected horizons, so they are not execution noise. They demonstrate that the current formal boundary decision is **not prefix-invariant**. They are therefore preserved as issued-and-withdrawn prospective states and are not promoted to a stable Basin Exit claim.

No observable failure `tf` was supplied, so formal prospective Δt remains unavailable.

## Determinism

Independent repeats were run at T2, T10, T20, T25, T69, T126, T168, T196, T245 and T275. All repeated state/identity comparisons matched exactly.

## Scientific interpretation before unblinding

This phase does not support a claim that Aperture is already a calibrated online boundary detector. It does support a stronger methodological conclusion: the prospective replay exposes which retrospective structures are stable under growing evidence and which are horizon-sensitive. Warning is continuously available after the minimum evidence gate; candidate state is intermittent before becoming sustained late in the run; formal t* flickers and is absent at the completed horizon.

This distinction is frozen **before PsiGuard disclosure**. No PsiGuard verdict, intervention coordinate, wandering coordinate, or annotation was used in any prefix computation.

## Next step

Send the Blind Result Lock to Bradley, then receive his PsiGuard intervention/wandering coordinates. The post-unblinding operation is a source-turn join only. Aperture must not be recomputed or retuned for this comparison.
