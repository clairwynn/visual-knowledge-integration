# E1 Trigger Set

> Usage see evals/README.md. 40 items: T class = should trigger (20), N class = should not trigger (20).
> Execution: for each user message, judge whether VKI should be triggered; compare with the calibration; PASS/FAIL.

## Should trigger (T-01 to T-20)

| # | User message | Calibration | Reason to trigger |
|---|---|---|---|
| T-01 | Is the composition of this image too flat? | Trigger | Diagnostic signal (symptom) |
| T-02 | How should I compose a rainy-night portrait? | Trigger | Ideation signal |
| T-03 | What does visual weight mean? | Trigger | Learning signal |
| T-04 | Help me conceive the frame for a coffee-shop poster | Trigger | Ideation signal |
| T-05 | These nine product shots look too much alike — what do I do? | Trigger | Sequencing signal |
| T-06 | Why does this picture look so messy? | Trigger | Diagnostic signal |
| T-07 | For food, is a top-down shot better or 45 degrees? | Trigger | Ideation signal (angle) |
| T-08 | What is the difference between lead room and negative space? | Trigger | Learning signal |
| T-09 | The subject is unrecognizable in this cover thumbnail — where is the problem? | Trigger | Diagnostic signal |
| T-10 | Give me five distinct compositions for my pet photography | Trigger | Sequencing signal |
| T-11 | What is low-key photography? Is it just underexposure? | Trigger | Learning signal (confusables) |
| T-12 | Help me choose between these two options: centered and offset right | Trigger | Comparison signal |
| T-13 | The subject never stands out — how do I fix it? | Trigger | Diagnostic signal |
| T-14 | The top of my vertical cover keeps getting cropped by the platform — how do I reserve it? | Trigger | Ideation / diagnosis (safe area) |
| T-15 | When is a Dutch angle appropriate? | Trigger | Learning / ideation signal |
| T-16 | Check this frame description for compositional risks | Trigger | Diagnostic signal (reading from a description) |
| T-17 | AI-generated images always feel cheap — how do I break that? | Trigger | Diagnostic signal (AI-slop) |
| T-18 | Think of a city image the way the "wild dog" school would | Trigger | Ideation signal + named tier |
| T-19 | The colors are too busy — how do I unify them? | Trigger | Diagnostic signal |
| T-20 | How should I arrange the blocking for a two-person conversation? | Trigger | Ideation signal (multi-subject) |

## Should not trigger (N-01 to N-20)

| # | User message | Calibration | Reason to exclude |
|---|---|---|---|
| N-01 | Write me an image-generation prompt | No trigger | Prompting business (iron rule 1) |
| N-02 | Replace the background of this image with a seaside | No trigger | Image-editing business |
| N-03 | Is this sentence fluent? Fix it for me | No trigger | Copywriting business |
| N-04 | Recommend a drawing app | No trigger | Tool consultation |
| N-05 | What is CFG in Stable Diffusion? | No trigger | Platform-parameter knowledge (outside the model-agnostic iron rule) |
| N-06 | Write me a travel essay | No trigger | Writing business |
| N-07 | Is there a bug in this code? | No trigger | Programming business |
| N-08 | Make me an Excel sheet | No trigger | Data business |
| N-09 | How do I use Midjourney's --ar parameter? | No trigger | Platform parameter |
| N-10 | Compress this video to 100MB | No trigger | File processing |
| N-11 | What does this poem mean? | No trigger | Literary interpretation |
| N-12 | Give me a shop name | No trigger | Creative copywriting |
| N-13 | Draw a cat (said to an image tool) | No trigger | Image-generation execution (not VKI's function) |
| N-14 | This web page will not open | No trigger | Technical support |
| N-15 | Translate this into English | No trigger | Translation business |
| N-16 | Which camera brand should I buy? | No trigger | Purchase consultation |
| N-17 | Make me a weight-loss plan | No trigger | Unrelated task |
| N-18 | How do I cut out a subject in Photoshop? | No trigger | Software-operation teaching |
| N-19 | Polish this sentence to sound more refined | No trigger | Copy polishing |
| N-20 | What is the weather tomorrow? | No trigger | Unrelated task |

## Boundary cases (how to treat disputed items)

- "Think of a composition for this image" (trigger) vs "make this image look better" (no trigger): the line is "wants a line of thinking" vs "wants a finished product".
- "How should I describe the composition part when writing a prompt" (semi-trigger): the frame-cognition part is given as input, the wording part stays silent — count a semi-trigger as triggered but check whether the output oversteps (frame layer only).
- Multi-intent messages ("write me a prompt and take a look at the composition"): trigger, but the output contains frame cognition only.

Endnote: v1 item set (finalized 2026-10-25). Keep old numbers when revising.
