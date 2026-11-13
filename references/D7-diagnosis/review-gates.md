# D7 · Review Gates

> This file covers: the multi-gate acceptance system before delivery — the pass conditions and gating logic of five gates (layout / separation / hierarchy / legibility / distinctiveness).
> How to use: the final gate check before a concept is locked and at finished-work acceptance; any gate failed means rework — nothing ships sick.

## Definition

Review gates = splitting "deliverable" into five serial gates, each with a binary, decidable pass condition. The gates are a **minimum standard** (award bar), not an excellence standard — passing only guarantees no accident; high scores come from D6/aesthetic-criteria.

## Mechanism

The main cause of acceptance failure is not a standard set too high but standard drift (deciding "is it OK" by feel each time). Serial gates fix "is it OK" into "did it pass this one item", and the gate order follows dependency: checking separation when the layout is wrong is meaningless (everything is recomputed after a re-layout) — so structure first, surface after.

## The five gates

### Gate 1: Layout Gate

Pass conditions (all met):
1. The aspect ratio is decided and matches the subject (D1/aspect-ratio);
2. The composition type is explicit (you can name it) and the subject's placement falls inside the type's criterion band;
3. In a multi-frame sequence, adjacent frames differ in ≥2 dimensions and the same type appears no more than once (a hard rule of sequence).

Typical faults that fail this gate: F01, F28, composition type fighting the aspect ratio.

### Gate 2: Separation Gate

Pass conditions:
1. Subject-background separation holds — at least one of: value difference ≥2 stops / hue difference >90° / defocus separation;
2. No figure-ground three-near (near value + near hue + near saturation);
3. Ground contact holds (shadow / contact surface).

Typical faults: F05, F07, F21.

### Gate 3: Hierarchy Gate

Pass conditions:
1. The strong anchor is unique (or 1 primary and 1 secondary differing by ≥1 step);
2. Element grouping is clear (perceived group count 3–5);
3. Both ends of the tonal range have anchors (a maximum near black / white exists).

Typical faults: F03, F04, F22, F23.

### Gate 4: Legibility Gate

Pass conditions:
1. The thumbnail test passes (still recognizable as "what it is" at thumb size);
2. The squint test passes (the subject's value mass is distinguishable);
3. The edge scan is clean (no half objects / tangency / tangent lines / corner hijack);
4. No key information lost (cut joint / cut face / text out of the safe area);
5. Text elements are readable: the value contrast between text and ground reaches the readable line (dark on light or light on dark, empirical consensus ≥4.5:1).

Typical faults: F15–F19, F26.

### Gate 5: Distinctiveness Gate

Pass conditions:
1. At least one of the position / shot-size / angle axes is explicitly offset (not all default);
2. At least one stateable "bold decision" (one sentence saying "what makes this frame special");
3. For a sequence frame: this frame has an independent job in the sequence (it cannot swap identities with a neighbor).

Typical faults: F28, F30. This gate is the "anti-mediocrity gate" — the first four prevent accidents, this one prevents authorlessness.

## Gating procedure

1. Pass the gates serially: 1 → 2 → 3 → 4 → 5; **do not check later gates before the earlier one passes** (check again after a re-layout).
2. Output per gate: PASS, or FAIL plus the fact (point to the location in the frame).
3. FAIL handling: enter cause-tree to fix the root cause → open a prescription (prescriptions) → repair → **restart from Gate 1** (a structural repair changes everything downstream).
4. All pass = deliverable (with a six-dimension score as a note on "how good it is").

## Quick gate card (30-second version)

| Gate | One-line self-question |
|---|---|
| Layout | What is the type? Which line is the subject on? |
| Separation | What makes the subject float up? |
| Hierarchy | Where do I look first? Second? |
| Legibility | Does it still read at thumb size? |
| Distinctiveness | What is this frame's "author's signature"? |

## Boundaries

- The gates are a general minimum: a movement may add gates (documentary adds a "credibility gate", commercial adds a "code gate") but may not remove them (the five are the floor).
- Conceptual / anti-aesthetic frames: the criteria of Gates 1 and 5 are converted through their declaration system (centering and imbalance may be deliberate decisions) — but the physical-accident lines of Gates 2 / 3 / 4 are not exempt (even the deliberate must be "cleanly deliberate").
- All five gates passed with a low six-dimension score = competent but without a highlight: that is "usable", not "good"; tell the user the level honestly.

## Connections to other files

- Knowledge sources for the gate criteria: D1 (layout / separation), D5 (hierarchy / legibility), D6 (distinctiveness)
- Prescriptions and rework: see prescriptions
- Scoring: see D6/aesthetic-criteria
- The review functions: see modes/function/compare.md, diagnose.md
- The methodological source of the delivery-acceptance idea: see modes/schools/commercial.md (the generalization of quality-gate discipline)
