# Gayer–Shy (2016) Tying Welfare Correction

## Target paper

Amit Gayer and Oz Shy (2016), “A Welfare Evaluation of Tying Strategies,” Research in Economics 70(4), 623–637.

## Project purpose

Derive exact consumer-surplus and welfare crossing conditions under mixed tying, replace rounded/numerical threshold statements with certified roots, and restate the corrected welfare ranking and endpoint correspondence.

## Current status

**Stage 0 — Evidence Freeze / independent re-verification.**

No publication-facing correction theorem is frozen yet. The master audit findings are transferred only as hypotheses/evidence to be independently reconstructed in this repository.

## Starting evidence

- Master audit provenance: `ryotamatsuki/ozshypapers — audits/welfare_evaluation_tying_strategies_2016_final.md`
- Source status: Complete article-form mathematical source inspected in the master audit; final VOR provenance should be re-frozen in this repository.
- Initial signal: The transferred audit found that Result 12(a)’s low-cost consumer-surplus ranking is false on an open interval and identified corrected crossing values.

## Repository policy

1. Re-derive all publication-facing claims from the original model rather than copying the master-audit conclusion.
2. Separate source transcription, derivation, counterexample, corrected theorem, and downstream implications.
3. Treat local FOCs as insufficient when regime changes, clipping, entry/exit, or boundary actions are feasible.
4. Preserve exact equality and boundary cases in the equilibrium correspondence.
5. Numerical and symbolic checks support but do not replace analytical proof.
6. Do not draft a submission claim until the Version-of-Record lineage and prior-disclosure search are frozen.
7. Keep the master audit repository as provenance; this repository becomes canonical only for publication-facing development after Stage 0 passes.

## Planned structure

```text
README.md
PROJECT_STATUS.md
PROVENANCE.md
CLAIM_BOUNDARY.md
EVIDENCE_MAP.md
docs/
  STAGE_00_EVIDENCE_FREEZE.md
derivations/
code/
results/
sources/
manuscript/
submission/
```

## Immediate next step

Complete `docs/STAGE_00_EVIDENCE_FREEZE.md`: freeze the exact source/version, independently reproduce the transferred discrepancy, run a fresh prior-disclosure search, and decide whether the project passes into theorem/proposition development.

