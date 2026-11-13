# E3 Weak-Composition Diagnosis Set (Diagnosis Accuracy)

> Usage see evals/README.md. 20 standardized symptom items (constructed in reverse from D7/fault-library), each calibrated with: root cause (or root-cause group) plus the suggested prescription level.
> Scoring: root-cause hit = 1.0; same branch, different root cause (right direction, wrong level) = 0.5; different branch = 0. Additional: over-restructure rate (calibrated as adjustment but issued as restructure) ≤10%.

| # | Symptom description (item statement) | Calibrated root cause (fault-library number / branch) | Suggested level |
|---|---|---|---|
| D-01 | The figure stands dead center, perfectly symmetrical, and the frame has no life at all. | F01 dead center (A branch: unclear subject / default placement) | Adjustment |
| D-02 | The subject is large, yet the eye always lands first on a lamp in the upper right corner. | F15 wrong first fixation (A branch: stronger distractor anchor) | Adjustment |
| D-03 | Two figures of equal size and equal brightness — you cannot tell who the protagonist is. | F03 dual anchor (B branch: weight order collapsed) | Adjustment |
| D-04 | Seven or eight things crowd together in the frame; you cannot tell who belongs with whom. | F04 scattered plus failed grouping (B/D branches) | Adjustment |
| D-05 | A person in white stands before a white wall; the contour is unreadable. | F05 figure-ground merge (E branch: missing value / color separation) | Adjustment |
| D-06 | No background, no foreground — the picture looks like a sticker. | F06 flat (E branch: two-layer structure) | Adjustment (add a foreground anchor); restructure after a second failure |
| D-07 | The vase seems to float in mid-air, with no shadow. | F07 floating (C branch: missing ground contact) | Adjustment |
| D-08 | The frame is packed full, with not a bit of emptiness. | F08 overcrowded (B branch: density out of control) | Adjustment (subtraction) |
| D-09 | A large field of flat color in the background, the subject shrunk into a corner — so empty it feels alarming. | F09 dead empty (negative space with no texture and no direction) | Adjustment |
| D-10 | A large dark title block above, everything empty below — the frame sinks. | F10 top-heavy (C branch) | Adjustment |
| D-11 | The left half is a dark building, the right only a small branch — it looks crooked. | F11 lopsided (C branch: weight difference unbalancing) | Adjustment |
| D-12 | The figure gazes to the left, but the frame edge is right there — it feels stifled. | F12 blocked look (lead room in the wrong direction) | Adjustment |
| D-13 | The path line is cut halfway by a utility pole; you do not know where to look. | F13 broken path (D branch) | Adjustment |
| D-14 | A light band runs from the left of the frame out through the right edge; the eye follows it out of the picture. | F14 leading out (D branch: no anchor at the end) | Adjustment |
| D-15 | Half a chair protrudes into the right edge of the frame; you cannot tell what it is for. | F16 edge intruder (F branch) | Adjustment |
| D-16 | A lamp post appears to "grow" out of the figure's head, fused to it. | F17 tangent merge (F branch) | Adjustment |
| D-17 | A full-body shot is cut through the middle of the calf; the figure seems to sink into the ground. | F19 joint cut (F branch) | Adjustment |
| D-18 | Every object's shadow points a different way, as if shot at different times. | F20 / F27 no key light / shadow conflict (light-color branch) | Adjustment |
| D-19 | The whole photograph is gray and hazy, with no black and no white — very flat. | F22 no anchors (both ends of the tonal range missing) | Adjustment |
| D-20 | Four vivid colors — orange, green, purple, red — split the frame equally and fight each other. | F23 color clash (G branch: no harmony, no proportion) | Adjustment; restructure the palette after repeated failure |

## Scoring details

1. **Root-cause judgment**: the root cause the answer identifies, if in the same branch and level as the calibration = 1.0; same branch, different root cause = 0.5; different branch = 0; for items with multiple root causes, hitting the main one counts as a hit.
2. **Prescription level**: the level actually issued equals the calibrated level → compliant; calibrated adjustment but issued as restructure → counted once as "over-restructure" (even if the root cause is right).
3. **Evidence requirement**: a diagnosis must include a location in the frame ("the X in the lower right"); a diagnosis without evidence caps that item at 0.5.
4. **Trap items**: D-06 / D-19 / D-20 allow an "escalate after adjustment fails" path — adjusting first within one session is not over-restructure; issuing restructure directly without arguing a "structural-level root cause" is.
5. Pass line: mean score ≥0.75 and over-restructure rate ≤2/20 (=10%, consistent with the README protocol and these scoring details).

## High-frequency misdiagnosis reference (item-design basis, marking reference)

| Symptom keyword | Easily misdiagnosed as | Correct branch |
|---|---|---|
| "Messy" | A path problem (D branch) | May be B (hierarchy) / C (balance) — must be tested |
| "Flat" | A tonal problem | May be A (unclear subject) / wrong composition type |
| "Fake" | A texture problem | May be perspective / shadow conflict (the physics layer) |
| "Crowded" | A density problem | May be a wrong aspect-ratio choice (structural) |

Endnote: v1 item set (finalized 2026-10-25, all constructed in reverse from the fault library). Keep old numbers when revising.
