# D1 · Aspect Ratio

> This file covers: the logic of choosing an aspect ratio, the aspect-ratio-to-subject mapping, the matching of aspect ratio to composition type, and the cropping safe area.
> How to use: the **first step** of any frame task — check this file to fix the aspect ratio, then move to composition-type selection (see composition-types). Until the aspect ratio is settled, no other composition decision should be opened.

## Definition

Aspect ratio = the width-to-height proportion and orientation of the frame, the first skeleton of the image. It decides how content extends, how the eye travels, and how the subject breathes; it exists before composition type, camera position, light, and color.

**Aspect ratio first (hard rule)**: every frame decision begins with the aspect ratio. Composition designed while the ratio's role is still unclear will be forced to collapse at the final step.

## Mechanism

The aspect ratio is "the shape of the viewfinder". It presets three kinds of information:

1. **Direction of extension**: a horizontal frame channels attention left-right (environment, juxtaposition, movement); a vertical frame channels it up-down (depth, height, single subject); a square frame gathers toward the center (contemplation, symmetry).
2. **Breathing room**: the same content naturally gains more top-bottom space in a vertical frame and more left-right extension in a horizontal one — which directly changes the negative-space structure (see spatial-allocation).
3. **Viewing context**: the aspect ratio is often derived backwards from the viewing medium (phone portrait screen, cinema screen, square card); the medium is the ratio's first constraint.

## Criteria

### Common aspect-ratio roles

| Ratio | Orientation | Good at | Typical subjects |
|---|---|---|---|
| 1:1 | Square | Centered symmetry, still life, headshots, pattern | Social cards, product shots, icons |
| 4:3 / 3:2 | Horizontal | General environmental narrative, landscape, two-person dialogue | Photography, illustration scenes |
| 16:9 | Wide horizontal | Cinematic feel, panorama, multi-figure juxtaposition | Film frames, banner covers |
| 21:9 | Ultra-wide | Epic panorama, horizontal lines, solitude | Film-poster interiors, desktop wallpapers |
| 3:4 / 2:3 | Vertical | Full-body portrait, vertical leading (towers / trees / stairs) | Posters, covers, portraits |
| 9:16 | Tall vertical | Mobile full screen, single-subject close-up, depth | Short-video frames, phone wallpapers, story cards |

### Subject × aspect ratio mapping (rules of thumb)

| Subject | First choice | Second choice | Reason |
|---|---|---|---|
| Single full-body portrait | 2:3 / 3:4 | 9:16 | Vertical room for the figure plus space under the feet |
| Facial close-up | 1:1 / 4:5 | 3:4 | A face holds its steadiest tension in a square frame |
| Landscape panorama | 16:9 / 21:9 | 3:2 | Horizontal extension carries the horizon |
| Architecture / towers | 2:3 | 9:16 | Vertical emphasis on height |
| Food shot from above | 1:1 / 4:5 | 3:4 | Tabletop geometry is isomorphic with a square frame |
| Two-person dialogue | 3:2 / 16:9 | 4:3 | Horizontal room for the confrontation or exchange axis |
| Multiple objects laid flat | 1:1 / 4:3 | — | Grid layout needs a regular border |
| Product hero shot | 1:1 | 3:4 | Platform convention plus centered focus |

### Aspect ratio and composition-type matching

- Vertical frame plus a horizontal composition type (panorama laid across) = mutual conflict; large dead areas on both sides.
- Horizontal frame plus a strongly vertical composition type (a single tower standing) = the tower is cut by the frame or dead space opens on both sides; switch to vertical or convert to a horizontal group.
- The square frame suits best: centered symmetry, sun-disc, pattern repetition, a single still object.
- The ultra-wide frame inherently demands leading lines (road / river / band of light) to thread left and right together, or it becomes two images.

## Cropping safe area

- **Central safe area**: when downstream cropping cannot be predicted (platform auto-crop, multi-size delivery), keep the subject's key information and any text inside the central 60–80%, and treat the outer 10–20% as a sacrifice band.
- **Bottom avoidance band**: for frames aimed at video frames or comment-overlay contexts, keep roughly the bottom 15–20% (rule of thumb) free of key visual elements, reserved for subtitles and interface.
- **Headroom**: leave 5–10% buffer at the top of a vertical portrait to survive platform top-cropping (details in D4/framing-room).

## Boundaries

- When the aspect ratio is hard-constrained by the medium (platform-mandated size), design freedom shifts to composition type and spatial allocation; in that case use the ratio's "role" fully rather than fighting it.
- In a vertical frame avoid composing with horizontal thinking (panorama laid across, "wide" language); the same in reverse — a mismatch between the frame and the language's direction is the hidden root cause of a frame that "feels wrong".
- 1:1 is not the universal "nothing lost either way" answer: when directional narrative is needed it satisfies neither side.

## Counterexamples

- Counterexample 1: a single tall tree centered in a 16:9 horizontal frame — the left and right halves become decorative emptiness and the subject hangs isolated. Fix: switch to 2:3 vertical so the tree fills the height, or offset the tree in the horizontal frame and extend the horizon.
- Counterexample 2: a group portrait crammed into a 9:16 phone wallpaper — faces shrink beyond recognition. Multiple figures need a horizontal frame, or a change to one figure plus an implied crowd.
- Counterexample 3: a cover image with the title placed in the top 10% — platform cropping eats it. Fix: bring it into the central safe area.

## Connections to other files

- After the ratio is fixed → composition-type selection: see composition-types-1/2
- Spatial allocation and negative space inside the ratio: see spatial-allocation
- Framing buffers inside the ratio (headroom / lead room): see D4/framing-room
- Aspect-ratio consistency across an image sequence: see modes/function/sequence.md
- Review check of the bottom avoidance band: see D7/fault-library (edge-accident family)
