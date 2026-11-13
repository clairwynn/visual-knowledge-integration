# D2 · Light Fundamentals: The Four Variables

> This file covers: the matrix semantics of light's four variables — direction, quality, ratio, color temperature — and the framework of "light serves composition".
> How to use: any frame's light design passes through the four variables first, with an explicit choice for each; portrait-specific lighting setups are in portrait-lighting.

## Definition

A beam of light is fully described by four independent variables: **direction** (where it comes from), **quality** (hard or soft), **ratio** (how many stops between light and shadow), and **color temperature** (cooler or warmer). The light feel of a frame is the compound of the four choices made.

## Mechanism

Light plays three roles in composition: (1) **modelling** — direction determines shadow shape, and shadow is the source of three-dimensionality; (2) **separation** — the value difference between subject and background is the strongest separation device (perceived earlier than defocus); (3) **directing attention** — the brightest area and the area of highest contrast are frequent first landing points (see D5/attention). Light is therefore not atmospheric decoration but a compositional tool: once the composition type is fixed, use light to reinforce it.

## Criteria

### Variable one: direction

| Direction | Semantics | Compositional function |
|---|---|---|
| Front light (from the camera side) | Flat, honest, no privacy | Reduces shadow, flattens; beware that it erases volume |
| 45-degree side-front | Natural, the standard position for volume | The default for modelling; the source of realism |
| Side light (90°) | Dramatic, cutting, texture enlarged | A light-dark border across a face or object = strong modelling; best with a dark background |
| Backlight | Outline, silhouette, sacred or mysterious | Rim separation of the subject; in silhouette the subject becomes a declaration of shape |
| Top light | Oppressive, noon, interrogating | Heavy eye-socket shadow; use with care when flattering a portrait |
| Bottom light | Horrific, aberrant | Rarely used; its appearance is a dramatic declaration |
| Window light / single-side natural light | Quiet, lived-in, painterly | The default choice for single-source narrative |

### Variable two: quality (hard versus soft)

- **Hard light** (a small, distant source: noon sun, bare bulb): sharp shadow edges, enlarged texture, a sense of conflict. Criterion: the shadow has a clear boundary.
- **Soft light** (a large, close source: overcast sky, big window, softbox): feathered shadows, softened texture, approachability. Criterion: the shadow boundary is a gradient.
- Practice with source size and distance: a large close source = soft transition; a small distant source = hard specular highlight. Want soft: bring the source closer and make it larger; want hard: move it farther and make it smaller.
- **Inverse-square in practice**: double the distance and illuminance falls to one quarter (2 stops darker) — a close lamp falls off fast (soft highlight transition, shadows sinking quickly), a distant lamp falls off slowly (harder, more specular highlights). Moving the lamp changes contrast: this is the lever for adjusting contrast without touching the layout.
- Composition linkage: hard light strengthens lines and structure (pair with diagonal or architecture); soft light strengthens form and atmosphere (pair with portrait or still life).

### Variable three: ratio (brightness difference between key and shadow)

| Ratio | Stops | Emotion | Use |
|---|---|---|---|
| 1:1 | 0 stops | Flat, candid | ID-photo feel, e-commerce white background |
| 2:1 | 1 stop | Soft and open | Lifestyle, approachable commercial |
| 4:1 | 2 stops | Editorial texture (the sweet spot) | Magazine portrait, brand film |
| 8:1 | 3 stops | Chiaroscuro, dramatic | Low-key fashion, suspense |
| 16:1+ | 4 stops+ | Film noir, mysterious | Very dark narrative |

Each additional stop is one grade of contrast; the ratio is "the quantitative lever of emotion".

### Variable four: color temperature

| Color temperature | Reading | Common scene |
|---|---|---|
| 2000–3000K (warm) | Candle / tungsten, intimate, nostalgic | Dinner, lamplight, dusk |
| 4000–5000K (neutral) | Morning, everyday | Lifestyle, office |
| 5500–6500K (daylight / cool) | Fresh, clinical | Daylight outdoors, tech feel |
| 7000K+ (blue hour) | Night, cold, solitary | Blue hour, moonlight, refrigerated feel |

- Mixed color temperature (warm window light plus cool night) = the frame carries its own layering and sense of time, a common recipe for sophistication (cool-warm zoning narrative in D3/emotion).
- One dominant color temperature per frame; mixed light must have a clear hierarchy.

### Decision order of the four variables

1. First fix **light's role in the narrative** (who is lit, who hides in shadow) — this is a composition decision.
- 2. Then direction (which way shadows fall, whether subject and background can be separated).
- 3. Then quality (the texture requirement).
- 4. Then ratio (emotional intensity).
- 5. Last, color temperature (the time and emotional undertone).

## Boundaries

- "Beautiful light" is not "right light": direction and ratio must serve the compositional intent (separate whom, hide whom, point at whom), otherwise it is only decoration.
- A multi-source frame still needs exactly one key light; several sources with no key = no shadow and no volume (one of the AI-slop signatures, see D6/ai-defaults).
- In a backlit frame with no fill on the subject, facial information goes to zero — that is a silhouette declaration, not a mistake; if both face and backlight are wanted, reflected surfaces or ambient bounce must supply the fill (a realism constraint).

## Counterexamples

- Counterexample 1: subject and environment share the same brightness, the same direction, and no shadow — flat light blurs into one field and separation rests entirely on defocus. Fix: add a 45-degree side light to build volume, or darken the background to open the ratio.
- Counterexample 2: a gentle mood wanted but noon top light used — dead black under the brow and nose, and the portrait reads harsh. Fix: switch to a large soft source (window / overcast).
- Counterexample 3: three or four lamps each lighting on its own — no key light, volume collapses. Fix: appoint one key light and demote the rest to rim or ambient.

## Connections to other files

- Specific angles of the five classic portrait setups: see portrait-lighting
- Value layering and tonality (high / low key): see tonality
- Semantics of direction and quality developed further: see direction-quality
- Cool-warm and emotional color: see D3/emotion
- Light as a school's language: see modes/schools/cinematic-director.md
