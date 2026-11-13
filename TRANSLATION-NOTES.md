# Translation Notes

This repository ships two editions of the same knowledge base:

- **Root** — English, the default edition.
- **`zh/`** — the Chinese original, preserved unchanged, with an identical file tree, identical section numbering, and identical quantitative criteria.

## Principles used for the English edition

1. **Structure preserved.** Every section, table row, numbered item, and bullet has a counterpart. Nothing is merged, dropped, or added.
2. **Numbers preserved.** Ratios, percentages, stop counts, angles, ranges, and fault or card identifiers are copied exactly — 62/38, 60–80%, 2:1–8:1, 30–60°, ≥2 stops, F01–F31, and so on. A numeral written as a word in prose (e.g. "12 design schools") is still the same number.
3. **Terminology fixed.** One concept maps to one English term across all 87 files. The table below lists the settled terms and the variants to avoid.
4. **Template slots preserved.** Chinese template brackets became square brackets; the number, order, and meaning of slots are unchanged.
5. **Style.** Professional written English — declarative criteria, no colloquialisms, no added commentary, no external citations.
6. **No source-language residue.** The English files contain no Chinese characters. Cross-references point to the English file names, which are the same as the Chinese ones.

## Settled terminology

| Use | Do not use |
|---|---|
| aspect ratio | frame ratio, image ratio |
| safe area | safety zone, margin zone |
| rule of thirds | third rule, thirds rule |
| power points | force points, energy points |
| negative space | blank space, white space (except where "blank" is used deliberately for textureless emptiness) |
| textured negative space | textured blank, textured emptiness |
| visual path | sight line, eye route |
| leading line | guide line, leading curve |
| visual weight | visual mass, optical weight |
| figure-ground | figure/ground relation, subject-background |
| depth layering | layering depth, plane stacking |
| atmospheric perspective | aerial view, air perspective |
| frame within a frame | inner frame composition, nested frame |
| edge intrusion | edge cutting, border invasion |
| tangent merge | tangency, bad merge |
| joint cut | joint cropping, joint cut-off |
| shot size | shot scale, framing size |
| camera position | camera placement, viewpoint position |
| focal length | lens length, focal distance |
| depth of field | DoF range, focus depth |
| tonality | tone, tonal quality |
| high key / low key | high brightness / low brightness |
| lighting ratio | light ratio, contrast ratio |
| catchlight | eye light, eye sparkle |
| palette | color scheme, color set (use "palette" when it is the fixed pre-decided set) |
| color cast | color shift, tint overlay |
| cause tree | cause chart, reason tree |
| review protocol | review process, inspection procedure |
| fault pattern | fault type, error pattern |
| prescription | remedy, fix (use "prescription" for the leveled repair instruction) |
| review gates | pass threshold, acceptance gate |
| one-variable-at-a-time | single variable iteration, one change at a time |
| experience tier | experience level, user profile |
| hard routing | forced routing, mandatory dispatch |
| iron rules | hard rules, non-negotiable rules (both render the same concept; keep one per file) |
| median composition | average composition, default composition |
| AI-slop | AI flavor, AI look |
| controlled imperfection | deliberate flaw, planned imperfection |
| authenticity | realism, credibility |
| style DNA | style genome, style signature |
| movement card | school card, style card |
| translation playbook | conversion playbook, mapping guide |
| confusables | confusing pairs, look-alikes |

## Structural correspondences

- `SKILL.md`, `README.md`, `indexes/`, `modes/`, `references/`, `evals/` exist in both editions with the same relative paths.
- In-file cross-references (e.g. "see D5/visual-weight") are unchanged, so a reader can jump between editions by swapping the root prefix for `zh/`.
- `movement-library/` keeps its card identifiers and card count (421) in both editions.

## Maintenance

When a change is made to the English edition, mirror it in `zh/` only if the change is substantive; typographical fixes need not be mirrored. When a new term is introduced, add it to the table above in the same commit, so the one-term-one-translation rule stays enforceable.
