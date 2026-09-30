# Behavioral evaluation status

**Status: unrun.** No external evaluation endpoint and model were configured for isolated predictions. No real baseline/core/full responses or grades were manufactured. The ten-task version-2 suite was frozen before semantic source distillation and its SHA-256 is recorded in `acceptance-status.json`. Development and final scenarios are separate. No final evaluation run was consumed.

The intended comparison uses the same model/settings and fresh context for each task and condition: a frozen minimal role prompt, the core alone, and the core with reference access. Reference paths actually retrieved must be recorded. Grade actual saved responses against the criteria after prediction, with conditions hidden where possible. A full-condition pass and a gain over baseline are separate claims; a tie is not evidence of improvement.

The user requested behavioral testing. This release is therefore a structurally validated, editorially reviewed candidate with that acceptance requirement still outstanding. Publication is not represented as completion of independent behavioral acceptance.

## Running the outstanding evaluation

Use the `tools/evaluation_runner.py` and `tools/acceptance_suite.py` workflow from [Books-to-Skill-Refs](https://github.com/ariel-lee-1023/Books-to-Skill-Refs), with an explicitly selected compatible endpoint/model and a persistent run directory. Read that repository's evaluation-runner documentation for the current command schema. Preserve the existing suite and frozen partitions. Record actual predictions, retrieval traces, grades and runtime content hash under this ledger; do not populate `acceptance-results.json` with editorial expectations.

The current runtime content hash is captured by the validation record. Results from a different content hash require a fresh appropriate run. `editorial-review.md` is authoring evidence only and must not be relabeled as model acceptance.
