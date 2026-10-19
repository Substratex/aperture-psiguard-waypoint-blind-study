# Evidence-Horizon Sensitivity Replication Protocol — v0.1

**Status:** Internal / proposed multi-case follow-up  
**Origin:** Discovery Note 01, 2026-10-19  

## Purpose

Test whether Evidence-Horizon Sensitivity generalizes beyond the Waypoint T1–T275 trajectory and characterize which claim families are horizon-invariant, status-stable but coordinate-sensitive, or persistently non-monotonic under expanding admissible evidence.

## Frozen principle under test

> Deterministic issuance at a fixed evidence horizon does not imply persistence under later admissible evidence.

## Study matrix

Use multiple trajectory classes:

- stable controls;
- transitional cases;
- recovery cases;
- independently anchored failure-confirmed cases;
- long open-watch cases;
- multiple models and source families.

For each case, run every admissible prefix independently from a frozen source and frozen Aperture release. No state may carry from prefix k to prefix k+1.

## Claim families

At minimum record:

- weakening / `t_aw`;
- candidate boundary;
- formal `t*`;
- regime;
- Drift state;
- Pressure state;
- Failure Exposure state;
- dominant finding;
- recovery / re-entry state.

## Required per-prefix fields

- source horizon;
- source-prefix hash;
- canonical hash;
- run ID;
- eligible measurement count;
- Method Contract status;
- claim status;
- claim coordinate;
- confidence;
- regime;
- evidence/missingness state;
- no-future-leakage audit.

## Metrics

For each claim C:

- **First Issuance Horizon** `H_first`;
- **Persistent Issuance Horizon** `H_persist`;
- **Persistence Lag** `L_p = H_persist - H_first`;
- **Horizon Stability Ratio** `HSR`;
- **Withdrawal Count** `W`;
- **Re-entry Count** `R`;
- **Coordinate Revision Count** `CRC`;
- **Terminal Status Agreement**;
- **Terminal Coordinate Agreement Ratio**, conditional on claim presence.

Status persistence and coordinate persistence must be reported separately.

## Controls

1. Same frozen source and implementation versions across repeats.
2. Exact prefix truncation; no future source event or annotation.
3. Independent recomputation of selected horizons for deterministic replay.
4. Negative/stable controls to estimate baseline claim flicker.
5. External outcome labels remain outside active computation until comparison.
6. Preserve all withdrawals and re-entries; do not collapse to terminal state only.

## Falsification / weakening conditions

The generalized hypothesis is weakened if horizon sensitivity is unique to one source, disappears under independently implemented replay, is caused by source slicing defects, or is eliminated by correcting an implementation inconsistency rather than by a scientifically declared revision rule.

## Promotion criterion

Do not elevate Evidence-Horizon Sensitivity to a general foundational claim until the effect is characterized across multiple trajectory classes and source families, with deterministic replay and at least one independently anchored comparison set.
