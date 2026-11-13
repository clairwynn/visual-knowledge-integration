# Evaluation Protocol (Evals README · dormant zone)

> This directory holds VKI's evaluation assets, **dormant by default**. The trigger phrases exist only in this file; they do not appear in SKILL.md or in any other file.

## Activation mechanism (the only switch)

- **Activation phrase: "VKI eval"**; alias: "run a visual eval".
- Activation condition: one of the above phrases appears in the user's message.
- Behaviour after activation: VKI declares "entering evaluation mode" → executes E1 → E2 → E3 in order according to this protocol → outputs the overall evaluation report.
- When not activated: no path reference to this directory and no reference to the phrases may appear in SKILL.md, modes, references, or indexes; no evaluation may be mentioned or run spontaneously during long conversations (dormancy acceptance in the last section).

> Locale note: trigger phrases are language-bound. This English edition defines the English phrases above; the Chinese source edition defines the equivalent Chinese phrases, and the same protocol applies to both.

## General evaluation rules

1. Per-item output: item number + PASS/FAIL (or the list of assertions hit) + evidence (the quoted sentence from the answer).
2. Each of the three evaluations reports its pass rate; the overall report aggregates: pass rate per category + invalid-assertion candidates (assertions that always PASS = no discrimination) + high-variance items (unstable across retests) + localization of weak knowledge domains.
3. Evaluation results serve two purposes: tuning the SKILL.md description trigger words; repairing weak entries in the knowledge base.
4. Zero-source item statements: no external project name, link, or number may appear in any item — items are self-contained.
5. Evaluation runs "without external tools, pure conversation"; when a real image-generation / image-reading environment is available, an image version of the items may be extended (registered separately).

## E1 Trigger evaluation (trigger-set.md)

Verifies the precision and recall of the description's trigger words. Item set: 40 messages (20 should trigger / 20 should not). Execution: for each item judge "should VKI be triggered", compare with the calibrated answer, PASS/FAIL. Pass line ≥90%.

## E2 Composition-cognition assertions (cognition-assertions.md)

Verifies whether the knowledge changes how a frame is thought about. 30 scenarios, each with 3–5 key assertions. Execution: give the scenario → generate a complete answer → check each assertion for a hit (quoting the answer as evidence). Scoring: assertions hit / total assertions. Pass line ≥80%. Assertions with a consistently high hit rate (three consecutive full-PASS rounds) are marked "invalid-assertion candidates" and may be replaced with sharper versions.

## E3 Weak-composition diagnosis accuracy (diagnosis-accuracy.md)

20 standardized symptom items, each calibrated with a root cause (or root-cause group) plus the suggested prescription level (adjustment / restructure). Execution: VKI runs the diagnose function and outputs → compared against the calibration: root-cause hit = full score; direction right but level wrong (same branch, different root cause) = half score; different branch = 0. Additional metric: the over-restructure rate (a restructure-level prescription issued where the calibration says adjustment). Pass line: accuracy ≥75% and over-restructure rate ≤10%.

## Dormancy acceptance (for W8-4)

1. Full-package scan: "VKI eval", "run a visual eval", and any evals/ path reference must not appear in SKILL.md, modes/, references/, or indexes/ (except in this file).
2. Behavioural acceptance: across ≥20 rounds of mixed conversation without the trigger phrase (including composition / diagnosis / learning tasks), VKI must not mention evaluation spontaneously and must not suggest "running an evaluation".

## Maintenance

- Item revision records go in the endnote of each item-set file; replaced invalid assertions keep their old item numbers (T-xx / S-xx / D-xx are never reused).
- After any major knowledge-base change (new domain / restructured movements), rerun a full evaluation round.
