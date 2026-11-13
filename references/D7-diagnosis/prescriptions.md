# D7 · Prescriptions

> This file covers: the two-level grading of repair prescriptions (adjustment / restructure), the standard prescription format, the criteria for choosing a prescription, and single-variable iteration with the other variables fixed.
> How to use: the format and proportion of a prescription after diagnosis — preventing minor faults from being treated with a major operation, and major faults from getting only a dab of ointment.

## Definition

A prescription = a frame-modification plan aimed at a located root cause. Two levels:
- **Adjustment**: keep the compositional structure, tune parameters (position, value, negative space, cropping).
- **Restructure**: change the composition type / viewpoint / aspect ratio — a structural do-over.

## Mechanism

The criterion for grading a prescription is **the level of the root cause**: a parameter-level root cause (position slightly off, value within one stop) → adjustment; a structural-level root cause (wrong composition type, unsuitable aspect ratio, viewpoint with the opposite semantics) → restructure. The cost of mis-grading is asymmetric: restructuring when only an adjustment was needed = overturning everything for nothing and introducing new problems; adjusting when restructuring was needed = treating the symptom, not the cause (it never quite gets fixed).

## Criteria

### Adjustment vs restructure selection table

| Root-cause level | Typical faults | Level |
|---|---|---|
| Element parameters | F02 weak subject, F11 lopsided, F15 wrong first fixation | Adjustment |
| Framing parameters | F12 blocked look, F19 joint cut, F08 overcrowded | Adjustment (move frame or subject) |
| Light and color parameters | F20 / F21 / F22 / F24 | Adjustment (reset light and color, composition untouched) |
| Wrong composition type | F01 still flat after repeated offsets (the subject wanted symmetry but was offset) | Restructure (change the type) |
| Wrong spatial structure | F06 flat (a whole layer missing), F05 repeated figure-ground merges | Restructure after one failed adjustment |
| Wrong viewpoint or aspect ratio | Angle semantics inverted, aspect ratio fighting the composition | Restructure |
| Sequence-level faults | F30 drift, repeated look across frames | Restructure (at the sequence-plan level) |

General rule: **one failed adjustment of the same fault → escalate to restructure** (adjustment is not an infinite knob).

### Standard prescription format (four parts per prescription)

1. **Action**: what to change (move X to Y / darken Z / add a foreground anchor) — executable, no adjectives.
2. **Reason**: which criterion or mechanism it answers (one sentence).
3. **Expectation**: what should change in the frame afterwards.
4. **Verification**: which test or criterion confirms it (D5/tests or a review-gates item).

Example prescription (adjustment):
> Action: move the key light from dead front to 45° front-side; ratio 1:1 → 4:1.
> Reason: F21 flat light; volume needs direction plus ratio.
> Expectation: the face gains a light side and a dark side; a shadow beside the nose becomes visible.
> Verification: squint test — the face's value mass splits into two grades.

Example prescription (restructure):
> Action: abandon centered symmetry; use a thirds offset plus frame within a frame (subject inside a window frame); change the viewpoint from eye level to a 15° low angle.
> Reason: the subject is "a gaze in distress"; symmetry's ceremonial semantics contradict the intent (a composition-type-level root cause).
> Expectation: a voyeuristic feel plus psychological pressure appears.
> Verification: step 2 subject identification plus the emotional-delivery criterion.

### Single-variable iteration (discipline when there are many changes)

Change one variable at a time (position, or light, or color, or cropping…), confirm its effect, then change the next — after parallel changes nothing can be attributed (you cannot tell which change did the work). When several prescriptions run concurrently, order them "structural first" and execute one by one.

### Prescription packaging protocol (multiple faults at once)

1. List every fault name and root cause;
2. Layer them: structural (composition type / viewpoint / aspect ratio / layering) first, parametric (light / color / cropping) after;
3. Choose only one restructure plan at the structural level (do not hand the user several to assemble);
4. Within each layer, order by the single-variable discipline;
5. Output one unified verification checklist.

## Boundaries

- Prescriptions are decided by the root cause, not by the user's mood (when the user says "delete it all and start over" while the root cause is only adjustment-level, offer the adjustment plan first and explain why restructure is unnecessary — the naming right is the user's, the advising right is VKI's).
- Restructuring is not failure: an early restructure is cheaper than repeated adjustments.
- Keep the number of prescriptions restrained: ≤5 per pass (rule of thumb); more than that means localization has not converged — go back to cause-tree and re-assign the branch.

## Connections to other files

- Localization: see cause-tree, fault-library
- The frame-reading flow: see protocol
- Knowledge sources for prescriptions: the D1–D6 files
- Verification criteria: see D5/tests, review-gates
- The diagnose function flow: see modes/function/diagnose.md
