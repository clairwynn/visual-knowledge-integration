# D6 · AI Defaults

> This file covers: the evidence for the "median composition" tendency in generative images, the AI-slop feature list, and the cause and systematic breaking method for each feature.
> How to use: steer around the defaults at concept time (prevention); check item by item against the list when diagnosing "too much AI feel" (treatment).

## Definition

AI defaults = the statistical median frame a generative model tends to produce with no explicit instruction: centered subject, eye level, medium shot, frontal light, deep DoF, perfect symmetry, even detail. AI-slop = the "authorless" look that appears when defaults stack with over-smoothing.

## Mechanism

What a model learns from a mass of images is "the average composition" — and the average is exactly the opposite of composition (zero tension, zero stance). Without intervention the frame slides automatically to the median: centered, flat light, no depth, sharp everywhere. **An explicit composition instruction is therefore itself a de-slopping device**: any explicit compositional decision (offset / side light / shallow DoF / layering) pulls the frame away from the median.

## Criteria

### AI-slop feature list (for diagnosis, check item by item)

| # | Feature | Cause | Breaking method |
|---|---|---|---|
| 1 | Centered passport shot (dead center plus symmetry) | Median composition | Thirds / offset plus directional negative space (D1) |
| 2 | Flat light with no key (shadow directions confused or absent) | Multiple sources averaged out | Fix one key light plus ratio ≥2 stops (D2) |
| 3 | Deep DoF (sharp everywhere) | No DoF instruction | Specify shallow or deep DoF and the reason (D4/dof) |
| 4 | Plastic skin / porcelain surfaces | Over-smoothing | Controlled imperfection (pores / fine hair / scratches, see authenticity) |
| 5 | Over-perfect symmetry and placement | Posed bias in the data | Deliberate asymmetry / slight tilt / staggered objects (D1) |
| 6 | Gray flat contrast (no black, no white) | Mid-value averaging | Add anchors at both ends (high/low key design, D2/tonality) |
| 7 | Even detail density (background as sharp as the subject) | No layering instruction | Three-layer depth plus background de-emphasis (D1/depth-layering) |
| 8 | Floating objects (no contact shadow, no anchoring) | Weak physical consistency | Shared surface plus contact shadow (D1/multi-subject) |
| 9 | Full-screen holy light / even glow | An over-broad "atmosphere" instruction | One-directional volumetric light plus motivated source (D2/atmosphere) |
| 10 | Small limb or object errors (extra fingers, vague structure) | Detail averaged out | Reduce the element count per frame; count explicitly (D1/multi-subject) |
| 11 | Templated light (the same "golden hour orange" for everyone) | A fashionable style word | Fix light by narrative (direction / ratio / color temperature each with a reason) |
| 12 | Mute frame (nobody knows where the light comes from) | No motivated source | Make the source identifiable (D2/direction-quality) |

### Median-composition evidence (research conclusion, consensus statement)

Observational studies of generative image sets report: with no composition instruction, subject positions cluster markedly near the frame center, shot sizes cluster in the medium range, and viewpoints cluster at eye level — the three together form "median composition". The reverse inference: **an explicit offset on any one axis** (position / shot size / angle) significantly increases the distance from the median; offsetting all three makes the frame "have an author".

### Prevention protocol (run at concept time)

1. Position axis: the subject is not centered (unless centering is the declaration);
2. Viewpoint axis: not eye level, or eye level with a strong reason;
3. Shot-size axis: an explicit grade (not hovering in the "in-between");
4. Light: one key light plus ratio plus directional semantics;
5. Layers: a declared three-layer depth;
6. Imperfection: at least one "real imperfection" (see authenticity).

## Boundaries

- Centered symmetry, eye level, and deep DoF are all legitimate choices — AI-slop is decided not by "having used them" but by "having defaulted to them with no reason". A declarative centering (gravity, ritual) is not slop at all; it is a strong stance.
- The feature list is a dedicated diagnosis for generative images; for real photographs only items 1 / 2 / 5 / 6 apply (the rest are specific to the generation mechanism).
- Priority of methods: prevention (avoid at concept time) > repair (check item by item after generation).

## Counterexamples

- Counterexample 1: a single sentence — "a beautiful woman in a garden" — every axis defaulted, producing median composition. Fix: add decisions on the five axes of position / shot size / angle / light / layers.
- Counterexample 2: to de-slop, inverting every feature at once (tilt + overexposure + strange color all at once) — from one authorless stance to another (chaos). Fix: offset 2–3 axes deliberately and keep the rest conventional.
- Counterexample 3: killing a "centered symmetrical religious image" as AI-slop — a declarative centering is one of the highest compositional forms. The criterion is "is there a reason".

## Connections to other files

- The operational files for each breaking method: the corresponding D1 / D2 / D4 files
- Controlled imperfection and authenticity: see authenticity
- The digital-trend school (de-slopping as a school): see modes/schools/digital-trend.md
- Integration into the diagnostic protocol: see D7/cause-tree
