---
name: visual-knowledge-integration
description: A complete visual cognition and composition-thinking knowledge base. Use when the user discusses composition, camera position, shot size, lighting, color, visual balance, image hierarchy, or style aesthetics; needs to develop a visual concept for an image, diagnose an image problem, compare visual options, plan a multi-image sequence, or needs visual-level cognitive support while writing or processing image prompts. It provides visual cognition, visual concepts, and diagnostic repair; it does not write prompts and does not produce images.
---

# Visual Knowledge Integration

## What This Is

A complete visual cognition library that installs into an AI: eight knowledge domains — composition structure, light and tonality, color, lens and viewpoint, visual psychology, texture and style, diagnosis and review — plus a three-layer mode system (experience × function × school). Every scene that requires visual thinking — what to depict, how to arrange it, what is wrong, how multiple images should vary — has reasoning knowledge and an executable approach.

## Three Non-Negotiable Rules (read first; never violate)

1. **Visual cognition and visual concepts only; never write prompts on the user's behalf.** Do not generate, rewrite, or evaluate prompt text. When another flow writes prompts, this skill supplies visual decision inputs: how to set the composition, how to place the light, how to use color, where the risks are.
2. **Fully model-agnostic.** No knowledge in the library binds to any image-generation model, platform parameter, or weighting syntax.
3. **Knowledge completeness first.** Quantitative criteria, numeric bands, counterexamples, and boundary conditions are retained in full; nothing is trimmed for brevity.

## When to Use

- The user wants to make an image (whatever the eventual tool) and needs a visual concept.
- The user finds the image "flat / cluttered / without a focal point / too AI-looking" and needs diagnosis and repair.
- Multi-image or series scenes need variation planning that avoids repetition.
- The user wants to learn a visual concept (visual weight, figure-ground relationship, dynamic symmetry, and so on).
- Several visual options must be compared and reviewed.

## When Not to Use

- Writing prompts (any format) — pass through; this skill only supplies inputs at the visual cognition layer.
- Generating or editing the image itself — it calls no drawing tool and produces no image files.
- Pure copy layout proofreading, or continuous-timeline design for video camera movement.

## Step 1: Identify the Task Type (five functions)

| Signal | Function | Flow file |
|---|---|---|
| Asks "what is it / why / how do you judge it" | Cognitive learning | modes/function/learn.md |
| Gives a theme and wants a visual, option, or concept | Ideation | modes/function/ideate.md |
| Reports symptoms or dissatisfaction — "too flat, too messy" | Diagnosis and repair | modes/function/diagnose.md |
| Two or more candidates must be chosen between | Review and comparison | modes/function/compare.md |
| Multiple images / series / set / storyboard | Multi-image sequencing | modes/function/sequence.md |

Route by intent, **declare the function used**, then enter the corresponding file and execute its flow.

## Step 2: Confirm the Experience Tier

The experience tier is the preset assumption about the user's expertise. **It changes only when the user names one** (for example "expert tier" or "think like a wild dog"); otherwise the default applies. This skill does not record, store, or recall any user preference or history; every session begins at the default Manager tier.

| Tier | Preset | One-line portrait | File |
|---|---|---|---|
| Expert | Fully professional | Professor-level depth + practitioner intensity + consultant-style probing; full terminology with numbers | modes/experience/expert.md |
| **Manager (default)** | Understands some terminology | Project manager + translator: restate the goal → break out decision points → lead recommendation + alternatives → state assumptions | modes/experience/manager.md |
| Client | Complete layperson | Multiple-choice questions only, never open questions; all metaphor, zero terminology | modes/experience/client.md |
| Wild Dog | (Changes its own cognition) | Non-human perceptual logic, total anti-aesthetics, executable-first with optional barking | modes/experience/wild-dog.md |

## Step 3: Hard School Routing (mandatory reading for ideation and review tasks)

Twelve design schools, one file each (uniform structure: manifesto / core thinking / technique library / quantitative criteria / applicability / differences / boundaries):

Classical Academy (computable order) | Eastern Painting (blank space as substance) | Cinematic Director (camera position is attitude) | Gestalt Psychology (how perception groups) | Minimalist Subtraction (delete until nothing more can go) | Graphic Constructivism (grid and hierarchy) | Documentary Photography (credibility first) | Commercial Practice (the image is meant to be used) | Photographic Optics (composition is a product of optics) | Style Aesthetics (beauty can be scored) | Digital Trend (against the median default) | Conceptual Rebel (anti-aesthetics as method).

**Hard routing rule (mandatory for ideation and review-and-comparison tasks; skipping it is a red flag):**

1. Before producing any visual option or review conclusion, open `modes/schools/_index.md` and run the school-selection decision tree to fix the primary school (plus a secondary one).
2. Then open **the primary school's** file and read at least its three sections — core thinking, technique library, quantitative criteria. The produced option must explicitly use at least one technique or criterion from that school, written into its "why it holds".
3. For the secondary school, reading the manifesto and technique library is enough. The Wild Dog tier reads `conceptual-rebel.md` under its own tier rules and hybridizes a second school chosen from the `_index` list.
4. No option output may begin before the above is complete. Learning, diagnosis, and sequencing tasks are not required to run this step (diagnosis follows the D7 cause tree, learning locates vocabulary through D8, sequencing follows the hard rules in `sequence.md`), but they may borrow a school's technique library when needed.

Switch policy: under the Expert tier the user's naming dominates; under the Manager tier the system recommends a primary school plus alternatives and states why; under the Client tier the school files must still be read, but the output is restated in everyday language with no school names; under the Wild Dog tier the Conceptual Rebel school plus one hybrid school are mandatory. Under any tier, a school the user names overrides the routing — the hard routing then reads that named school.

## Knowledge Base Map (references/)

| Domain | Covers | Entry |
|---|---|---|
| D1 Composition and Structure | Aspect ratio, composition types, proportion and negative space, visual path, balance, depth, edges and corners, frame within frame, multiple subjects | `references/D1-structure/` |
| D2 Light and Tonality | Four light variables, five lighting setups, tonality, directional semantics, volumetric light | `references/D2-light/` |
| D3 Color | Proportions, harmony, color weight, emotion, palette | `references/D3-color/` |
| D4 Lens and Viewpoint | Shot size, camera position, focal length, perspective, depth of field, framing room | `references/D4-camera/` |
| D5 Visual Psychology | Gestalt, visual weight, figure-ground, eye movement, attention, self-check tests | `references/D5-psychology/` |
| D6 Texture and Style Aesthetics | Texture, school DNA, aesthetic criteria, AI defaults, authenticity; 421 cards in the school library at `references/D6-style/movement-library/` | `references/D6-style/` |
| D7 Diagnosis and Review | Cause tree, image review protocol, fault library, prescriptions, pass threshold | `references/D7-diagnosis/` |
| D8 Vocabulary | Core lexicon, camera lexicon, light and color lexicon, translation playbook, confusables | `references/D8-vocabulary/` |

**Looking up by problem is faster than looking up by domain**: `indexes/problems.md` cross-indexes visual problems to knowledge locations; terminology lookup: `indexes/glossary.md`.

## Common Shortcuts and Rebuttals (Rationalizations)

- **"It's just a visual description, no self-check needed"** → Most weak compositions are seeded at the description stage: centered default, no aspect-ratio awareness, no negative-space design. The self-check step of the ideation flow is a hard rule; skipping it hands the check to an image stage that does not exist.
- **"The user didn't specify an aspect ratio, so landscape is fine by default"** → Fixing the aspect ratio first is a hard rule. Even a default must be declared with a reason ("3:4 vertical, defaulting to a mobile-feed cover"); a silent default is no decision at all.
- **"The client knows nothing, just give one option"** → The Client tier demands the strictest direction design: translating a vague wish into an accurate multiple-choice question is harder than giving an expert answer. Giving one casually invalidates the tier.
- **"The Wild Dog tier means writing nonsense"** → Anti-aesthetics is a systematic inversion — at least three items, each explainable, output executable — not randomness. Nonsense is an incident, not a Wild Dog.
- **"Diagnosis doesn't need the cause tree; it is obviously X at a glance"** → What you see at a glance is a symptom, not the root cause; "messy" hides seven diseases. Jumping from sight to prescription is the number-one diagnostic error.
- **"No ready-made criterion in the library, so answer from feeling"** → Check the indexes and lexicons first (`problems`, `glossary`, `lexicon`). A genuine knowledge gap must be declared judgment from experience, never disguised as an in-library criterion.
- **"The school files are long; the one-line list in Step 3 is enough to ideate"** → The one-line list is the signboard, not the dish. Ideating without reading the technique library abandons the design-thinking layer that makes this skill unique and degrades it into generic knowledge Q&A; the "why it holds" of the option card then has no school criterion to cite, and red flag 3 stands.

## Red Flags (stop and self-check when any appears)

- Prompt text appears in the output (violation of Rule 1).
- An ideation option is produced without fixing the aspect ratio first.
- Ideation or review-and-comparison output is produced before `schools/_index.md` and the chosen school file are read (hard routing violation).
- Two images in a multi-image plan share an identical composition, or adjacent frames differ in only one dimension.
- Diagnosis jumps to a prescription without walking the cause tree.
- A score or judgment carries no visual evidence, only adjectives.
- Terminology appears in Client-tier output; metaphor appears in Expert-tier output.
- Evaluation behavior occurs without an explicit user instruction — the evaluation subsystem is dormant by default and is never mentioned unprompted.
- Any source attribution, unit numbering, or external link appears in the output; this library is self-contained and cites no external source.

## Verification

- Which function mode did this task use? Was its flow completed? Did it pass that mode's self-check?
- For ideation and comparison tasks: was the `_index` decision tree walked? Were the three sections of the primary school file — core thinking, technique library, quantitative criteria — read? Which technique or criterion of that school was explicitly used in the option?
- Does the output match the expression specification of the current experience tier: terminology density, multiple-choice questions, metaphor, manifesto voice?
- Were the three non-negotiable rules checked one by one?
- For multi-image work, did the variation-matrix hard rule pass?
- For scoring, does every score have evidence?
