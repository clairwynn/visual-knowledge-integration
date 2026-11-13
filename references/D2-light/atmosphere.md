# D2 · Atmosphere and Volumetric Light

> This file covers: volumetric light / the Tyndall effect, fog and haze used for depth, the optical side of atmospheric perspective, and the difference between motivated and ambient light.
> How to use: consult when "air, beams, fog, atmospheric depth" are wanted; to keep atmospheric elements from turning into a cheap filter.

## Definition

Atmosphere and volume = making light visible inside a medium (fog, dust, water vapour, smoke): light beams (volumetric light / Tyndall effect), haze, and aerial haze. They turn "air" into a layer of the picture.

## Mechanism

Scattering by the medium makes the light path itself visible (the beam) and attenuates distant objects (fog = natural atmospheric perspective, see D1/depth-layering). Atmospheric elements therefore hit three targets at once: (1) they draw invisible light (a volumetric shaft is "the shape of light"); (2) they add a gradient to depth (farther is hazier and grayer); (3) they emotionalize (sacred / mysterious / dusk / polluted, depending on medium and color temperature).

## Criteria

### Conditions under which volumetric light holds

1. **There must be a blocker**: a beam is the path revealed after light is cut by objects (tree crowns, window mullions, gaps in clouds, a crowd) — a full-screen glow with no blocker does not hold.
2. **There must be a medium**: a beam in perfectly clear air is an implausibility; the scene must carry visual hints of fog, dust, water vapour, or smoke.
3. **There must be one direction**: the beam direction equals the light-source direction and is consistent across the frame; beams in several directions = a no-key-light accident.
4. **Intensity must be restrained**: the beam is the eye of the picture, not the main dish — 10–20% of the frame (rule of thumb); "holy light" covering the whole frame is cheap (one of the AI-slop signatures, see D6/ai-defaults).

### Three uses of fog

| Use | Operation | Effect |
|---|---|---|
| Depth fog | Attenuate the far layer (value rises, contrast drops, hue drifts gray-blue), keep the near layer | Spatial depth +1 (aerial haze) |
| Mood fog | An even thin fog over the whole frame | Quiet, uncertain, a memory feel |
| Purifying fog | Fog darkens background detail, leaving only silhouette grading | Minimal silhouette, solitude |

### Medium × color-temperature emotion table (rules of thumb)

| Medium | Color temperature | Emotion |
|---|---|---|
| Morning mist | A transition from cool blue to warm gold | Hope, waking |
| Dust (indoors, backlit) | Warm gold | Time, old objects, classroom or warehouse |
| Water vapour (bathroom / kitchen) | Neutral | Life, intimacy |
| Smoke | Warm orange or cool cyan | Danger, aftermath of war, narrative residue |
| Night fog plus cool light | Blue-cyan | Solitude, suspense |

### Motivated light versus ambient light

- **Motivated**: the scene contains an identifiable source (window, lamp, fire) and the beam comes from there — the source of legitimacy in a realistic system.
- **Ambient (unmotivated but intentional)**: atmosphere lighting with no clear source (dream, memory, stylization) — legitimate but requires a stylistic declaration; abused inside a realistic frame it becomes an implausibility.

## Boundaries

- Atmospheric elements eat contrast: information density in a foggy frame naturally drops, so separate the subject by value difference and position instead (do not count on defocus in fog — deep DoF in fog only makes it foggier and flatter).
- Night scene plus volumetric light plus wet-ground reflection is the "premium night" trio, but all three at once easily overloads — the subject must still be unique (one source, one protagonist).
- The line between a sacred beam and a "cheap holy light" is restraint (share) and motive (whether the source has a place in the scene).

## Counterexamples

- Counterexample 1: three parallel beams in a cloudless sunny frame — no medium, no blocker, the beams float. Fix: add trees, a window, or smoke and dust, or remove the beams.
- Counterexample 2: in a foggy frame the distance is sharper and more saturated than the foreground — atmospheric inversion (see the counterexample in depth-layering).
- Counterexample 3: beams entering the same room from two directions — a double-key accident. Fix: keep one, demote the other to ambient bounce.

## Connections to other files

- The structural side of atmospheric perspective: see D1/depth-layering
- The beam as a visual path: see D1/visual-path (a band of light is an implicit leading line)
- Volumetric light used in low key: see tonality
- AI-slop criteria for overloaded holy light: see D6/ai-defaults
- Atmospheric narrative of light: see modes/schools/cinematic-director.md, eastern-painting.md (fog as negative space)
