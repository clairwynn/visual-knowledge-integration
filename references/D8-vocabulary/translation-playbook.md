# D8 · Translation Playbook

> This file covers: the two-way correspondence between structured visual semantics (regions / proportions / coordinates / layers / key-value) and visual concepts — translating "engineered description" into "frame cognition", and "frame intent" into "structured expression".
> How to use: when a structured frame description appears (zones / coordinates / proportions / grids), translate it into compositional cognition; or organize a composition plan into a structured checklist for downstream.

## Definition

Structured visual semantics = a language that describes frame layout in computable terms (regions, proportions, coordinates, layers); visual concept language = the disciplinary language of composition type / camera position / negative space. The two languages describe the same frame; this playbook is the bilingual dictionary.

## Mechanism

Structured language is precise but semantically mute ("put the subject in the lower left 30%" does not say why); visual language is semantic but imprecise ("offset composition" cannot land on a pixel). The value of translation: structure guarantees reproducibility and verifiability, visual language guarantees reasonableness and evaluability — a composition plan travels back and forth between the two languages, each taking what it is good at.

## Translation correspondences

### Aspect ratio and coordinates

| Structured expression | Visual translation |
|---|---|
| Vertical 2:3 / 3:4 / 9:16 | Full-body portrait family of aspect ratios (the duty table in D1/aspect-ratio) |
| Horizontal 16:9 / 21:9 | Cinematic / panoramic family |
| Square 1:1 | Centered symmetry / still-life family |
| Frame center (0.5, 0.5) | Dead center (the default placement, requires a declared reason) |
| (0.33, 0.33) / (0.67, 0.33) / (0.33, 0.67) / (0.67, 0.67) | Thirds power points |
| The (0.382, 0.618) family | Golden-section placement (62/38) |
| x=0.1 edge band | The edge zone (the four-check focus band in edges) |
| The central 60–80% region | The safe area (the cropping fallback) |

### Proportion and negative space

| Structured expression | Visual translation |
|---|---|
| Subject area 40–50% | The normal band for a medium / full-shot subject |
| Proportion ≤35% | The negative-space composition domain |
| Proportion ≥70% | The filled / close-up domain |
| Negative space 50% | The 50/50 standoff grade |
| Negative space 70% | The 30/70 breathing grade |
| Negative space ≥85% | The 10/90 isolated-sublime grade |
| A "gradient / texture / mist" specified in the empty zone | Textured negative space (a hard spec) |

### Regions and grids

| Structured expression | Visual translation |
|---|---|
| Left-right split (50/50 vertical division) | Two-subject standoff layout |
| 1/3–2/3 vertical division | Two-subject primary-secondary layout |
| Three horizontal bands (top / middle / bottom) | Sky-subject-ground three bands (the classic landscape band) |
| Row × column grid (r×c) | Row-column zoning / pattern repetition / tiled array |
| Ordered layering from far to near | Three-layer depth plus occlusion order |
| Bounding boxes non-overlapping with spacing ≥ threshold | Multi-subject zone allocation plus anti-merge spacing |
| Bounding boxes partially overlapping with declared front-back | Layered occlusion (making the foreground / background relation explicit) |
| Anchored to the same surface y value | Shared-surface ground contact (preventing floating) |

### Layers and key-value

| Structured expression | Visual translation |
|---|---|
| The key order of primary / secondary keys | The visual weight order (first fixation → secondary anchor) |
| "Required field / optional field" | Required / optional composition decision axes (aspect ratio required, focal length optional) |
| Constraint form ("must not / must") | Quality gates (no cluttered background / must touch the ground) |
| Numeric bandwidth (min–max) | Criterion bandwidth (the empirical range of a proportion / ratio) |
| Version iteration (v1 → v2 changes one field) | Single-variable iteration with the others fixed |
| Validator (field compliance check) | The review-gate check |

### Reverse translation (visual plan → structured checklist)

When a composition plan is handed downstream (or used for sequence planning), translate it into a seven-field checklist:
1. canvas: aspect ratio and orientation
2. subject: the subject and its share (position plus percentage)
3. layout: composition type plus power-point placement (coordinate band)
4. space: negative-space proportion plus texture
5. camera: shot size plus angle plus focal length
6. light: key direction plus quality plus ratio plus color temperature
7. constraints: quality gates (ground contact / counting / safe area / prohibitions)

The seven fields mirror the frame-reading protocol: every structured field can be verified in reverse by the six-step reading.

## Translation discipline

1. **No semantic loss**: after translation the meaning is equivalent (the structured version must be able to restore the compositional intent, and vice versa); a translation that keeps only numbers and drops "why" fails.
2. **Precise, not invented**: precision without basis in the visual language ("lands at 0.618" when it is really an empirical band) is downgraded to a bandwidth statement.
3. **Judge in both languages**: at acceptance, the structured fields run the gates (binary) and the visual criteria run the protocol (six steps) — it passes only when both pass.
4. **Intent redundancy**: important compositional intent is guaranteed by multiple expressions (visual language and structured fields written together, synonymous statements side by side) — the mapping from a single word to a frame varies on the implementation side, and double writing reduces intent loss (rule of thumb).

## Connections to other files

- Knowledge sources for the two languages: D1–D4 (visual), D7/review-gates (judgment)
- Field semantics in detail: D1/spatial-allocation (proportion), multi-subject (regions), D4 (camera)
- Assembly formulas: the assembly discipline in camera-lexicon, light-color-lexicon
