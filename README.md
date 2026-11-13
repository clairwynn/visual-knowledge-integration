# Visual Knowledge Integration

A complete visual cognition library for AI: **composition and structure, light and tonality, color, lens and viewpoint, visual psychology, texture and style, diagnosis and review** — eight knowledge domains, plus a three-layer mode system (experience × function × school).

Every scene that requires visual thinking — what to depict, how to arrange it, what is wrong, how a series should vary — has reasoning knowledge and an executable approach.

The English edition is the default in this repository. The Chinese original is preserved under [`zh/`](zh/).

## Three Non-Negotiable Rules

1. **Visual cognition and visual concepts only; never write prompts on the user's behalf.** Do not generate, rewrite, or evaluate prompt text. When another flow writes prompts, this library supplies visual decision inputs: how to set the composition, how to place the light, how to use color, where the risks are.
2. **Fully model-agnostic.** No knowledge in the library binds to any image-generation model, platform parameter, or weighting syntax.
3. **Knowledge completeness first.** Quantitative criteria, numeric bands, counterexamples, and boundary conditions are retained in full; nothing is trimmed for brevity.

## When to Use

- Making an image (whatever the eventual tool) and needing a visual concept.
- An image feels "flat / cluttered / without a focal point / too AI-looking" and needs diagnosis and repair.
- Multi-image or series scenes need variation planning that avoids repetition.
- Learning a visual concept: visual weight, figure-ground relationship, dynamic symmetry, and so on.
- Comparing and reviewing several visual options.

## When Not to Use

- Writing prompts in any format — this library only supplies inputs at the visual cognition layer.
- Generating or editing the image itself — it calls no drawing tool and produces no image files.
- Pure copy layout proofreading, or continuous-timeline design for video camera movement.

## Repository Layout

```
SKILL.md                      Entry file: skill metadata, routing rules, red flags
evals/                        Trigger set and self-evaluation: cognition assertions, diagnosis accuracy
indexes/                      Cross-indexes: problems.md (problem → knowledge), glossary.md (terminology)
modes/                        Three-layer mode system
  function/                   Five functional flows: learn, ideate, diagnose, compare, sequence
  experience/                 Four experience tiers: expert, manager (default), client, wild-dog
  schools/                    12 design schools plus the _index selection decision tree
references/                   Eight knowledge domains
  D1-structure/               Composition and structure: aspect ratio, composition types, proportion and negative space, visual path, balance, depth, edges, frame within frame, multiple subjects
  D2-light/                   Light and tonality: four light variables, five lighting setups, tonality, directional semantics, volumetric light
  D3-color/                   Color: proportions, harmony, color weight, emotion, palette
  D4-camera/                  Lens and viewpoint: shot size, camera position, focal length, perspective, depth of field, framing room
  D5-psychology/              Visual psychology: gestalt, visual weight, figure-ground, eye movement, attention, self-check tests
  D6-style/                   Texture and style aesthetics: texture, school DNA, aesthetic criteria, AI defaults, authenticity
    movement-library/         421 school cards (painting, photography, design, subculture, and more)
  D7-diagnosis/               Diagnosis and review: cause tree, image review protocol, fault library, prescriptions, pass threshold
  D8-vocabulary/              Vocabulary: core lexicon, camera lexicon, light and color lexicon, translation playbook, confusables
zh/                           Chinese original edition, identical structure to the root
```

## How to Use

This repository is an **Agent Skill**: `SKILL.md` carries the `name` / `description` metadata and is the single entry point. Place the whole directory into the skills directory of the AI client in use — for example `<skills-root>/visual-knowledge-integration/`. The AI then matches it automatically on composition, lighting, color, style, and diagnosis tasks, and follows the routing rules in `SKILL.md` to read files under `modes/` and `references/`.

A single task usually needs only a few files: fix the function and experience tier through Steps 1 and 2 of `SKILL.md`, then read the matching flow file and domain file as needed. Ideation and review tasks additionally run the hard school routing.

## Core Flow

1. **Identify the task type (five functions)** — learn, ideate, diagnose, compare, sequence; route by intent and then declare the function used.
2. **Confirm the experience tier** — expert, manager (default), client, wild dog; changed only when the user names one.
3. **Hard school routing (mandatory for ideation and review)** — run the decision tree in `modes/schools/_index.md` to fix the primary school, read that school's core thinking, technique library, and quantitative criteria, then explicitly cite one of its techniques or criteria in the option.

## Notes

- The knowledge base is self-contained, cites no external sources, and is written as an English edition alongside the preserved Chinese original in `zh/`.
- All criteria address visual cognition; none involves parameters or syntax of any specific image-generation model.
- File paths, section numbering, and the structure of the knowledge domains are identical between the English root and `zh/`, so either edition can be read against the other.
