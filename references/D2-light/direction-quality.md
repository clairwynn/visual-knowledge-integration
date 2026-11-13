# D2 · Direction and Quality Semantics

> This file covers: the deeper semantics of direction × quality combinations, the realism function of 45-degree directional light, how light position works with the frame's momentum, and the motivated-light check.
> How to use: after light-fundamentals has fixed the basic direction, use this file to refine the semantic combination; to verify that "the light is saying what the frame wants to say".

## Definition

Direction and quality are not merely physical parameters but semantic units: viewers hold stable emotional associations about "where the light comes from and whether it is hard or soft". This file gives the semantics matrix of direction × quality and the realism criteria.

## Mechanism

Direction determines the "writing direction" of shadow — shadow is light's handwriting, and the emotion of that handwriting is decoded unconsciously (a side-light cut = conflict; a hidden face in backlight = mystery). Quality determines the brushstroke (hard = woodcut, soft = watercolor). Direction writes "relation" (who is bright and who is dark = who is strong and who is weak); quality writes "texture" (whether the world is hard or tender).

## Criteria

### Direction × quality semantics matrix

| Combination | Semantics | Typical frame |
|---|---|---|
| 45-degree side-front + soft | Natural, reliable, everyday | Lifestyle portrait, food |
| 45-degree side-front + hard | Resolute, realistic, sculptural | Corporate portrait, architectural detail |
| Side 90 degrees + hard | Conflict, judgment, division | Character portrayal, suspense |
| Side 90 degrees + soft | Melancholy, transition, dusk feel | Literary mood pieces |
| Backlight + hard | Silhouette, declaration of outline | Sunset silhouette, portrait from behind |
| Backlight + soft (hazed) | Sacred, misty, memory | Window light, morning mist, backlit hair |
| Top light + hard | Oppressive, exposed, noon cruelty | Narratives of hardship, interrogating feel |
| Top light + soft | Neutral, everyday | Street photography, office scenes |
| Bottom light + hard | Aberrant, horrific | Reserved for horror |
| Wraparound light (no directional sense) | Flat, no information | Only usable on e-commerce white backgrounds |

### The realism function of 45-degree directional light (rules of thumb)

45-degree side-front light is called the "realism default": (1) it gives three value bands at once — lit side, shadow side, transition zone — so volume is complete; (2) shadow length is natural (neither exaggerated nor absent); (3) it matches the remembered experience of the classical studio and of everyday window light — the viewer finds it "true but not dull". It is the safe starting point for realism-oriented frames; the risk of dullness is managed through ratio and setting.

### Light position and momentum working together

- A diagonal momentum running to the right, with light coming from the left: shadows extend rightward, the same direction as the momentum, momentum compounding momentum.
- Light coming against the momentum: counter-momentum light creates a sense of resistance (walking into the wind) — an advanced move that requires clear intent.
- Side light and the frame's axis: a true side light "cuts" the frame into a bright and a dark half, usable when the composition is a half-split (division narrative: bright world / dark world); avoid side light when the narrative is not about division.

### Motivated-light check

Every light source in the frame should have a "source" findable within the scene (window, lamp, fire, sky), or at least not contradict the scene (a shaft of top light in a dark night with no source = implausible unless it is a stylistic declaration). Criteria:
1. The key light's direction has a source in the scene;
2. Color temperature matches that source (window light bluish-white, lamps warm, fire orange);
3. Shadow direction is consistent across the whole frame (multiple shadows in multiple directions = no-key-light accident, see D6/ai-defaults).

## Boundaries

- The semantics matrix is a statistical association, not a law: a specific cultural context or narrative may invert it (e.g. shooting horror with soft light, a "gentle trap") — inversion must be deliberate.
- A night scene with complex ambient light (a neon street) may carry multiple sources and multiple color temperatures, but the "single key light" principle holds: whoever lights the subject has the say.
- Hard light is not "bad quality": hard and soft are equals, and the only question is fit.

## Counterexamples

- Counterexample 1: a quiet early-morning frame paired with noon top light and hard shadows — the temporal semantics collide. Fix: a low-angle warm side light with long shadows.
- Counterexample 2: the person's shadow falls to the left while the cup on the table casts to the right — shadow directions are inconsistent across the frame (a no-key-light accident). Fix: fix one key-light direction and unify every shadow.
- Counterexample 3: a backlit portrait wanting facial detail with no fill source at all — neither a silhouette declaration nor acceptable, just a dead-black face. Fix: rotate to 45 degrees, or add ambient bounce (snow, white wall, reflector semantics).

## Connections to other files

- The basic four variables: see light-fundamentals
- The five portrait lighting patterns: see portrait-lighting
- Motivated light and volumetric light in scene: see atmosphere
- Shadow-direction consistency and AI-slop: see D6/ai-defaults
- Narrative use of light: see modes/schools/cinematic-director.md, documentary.md
