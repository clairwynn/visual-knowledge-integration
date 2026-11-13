# D6 · Style and Movement Lineage (Art Movements DNA)

> This file covers: the "DNA cards" of the major visual movements (the three-piece set of composition / light and color / texture, plus emotion, failure points, and typical color values); the rules for mixing styles and arbitrating conflicts; the seven-layer deconstruction method; and the disambiguation of style concepts.
> How to use: look up a DNA card when the user names a style (or when a style recommendation is needed); when mixing, split the layers and arbitrate by the rules; when analysing "why does this look like movement X", use the seven-layer deconstruction.

## Definition

Style-movement lineage = the historical classification of visual languages. A movement's frame features can be split into multiple DNA layers: **composition habits, light-and-color recipes, texture and brushwork** (the three operational layers), plus **emotion** (the intent layer) and **failure points** (the opposite of what that style is most often done wrong as). Style = the consistency of the DNA layers; the typical color values (hex) can be taken directly as palette anchors for D3/palette-strategy.

## Mechanism

"Style" is not an adjective but a parameter set: saying "Impressionism" means fragmented brushwork + outdoor light and color + everyday subjects holding at the same time. A "neither-here-nor-there" look usually comes from the DNA layers being borrowed from different movements. The correct posture for choosing a style: pick the movement → inherit its multiple DNA layers → fine-tune a single layer as needed (never tune several layers at once). **Giving only a style name almost guarantees a mediocre result** — a style must land on the light-color and medium layers to be truly defined (empirical finding: the lighting layer matters more to the final texture than the style label itself).

## Style DNA cards · quick reference (12 common movements)

| Movement | Composition DNA | Light and color DNA | Texture / brushwork DNA |
|---|---|---|---|
| Classical academy | Thirds / golden / triangle; layered depth in history painting | Chiaroscuro, brown-gold warm key, idealized light | Smooth glazing, invisible brushwork |
| Impressionism | Cropped viewfinder framing (photographic crop), high viewpoint | Outdoor natural light, violet shadows, complementary vibration | Fragmented brushwork, impasto, dissolving edges |
| Expressionism | Distorted space, tilted and exaggerated perspective | Subjective color (anti-natural color), strong contrast | Coarse brushwork, scraping |
| Surrealism | Precise realistic framework plus irrational insertion | Staged cold light, long shadows | Photographic smoothness (classic) or fine oil |
| Minimalism | Large negative space, single subject, geometry | Monochrome or achromatic fields, even light | Flat paint, traceless surface |
| Bauhaus / Constructivism | Geometric division, diagonal momentum, grid | Red-yellow-blue primaries plus black and white, flat light | Flat color blocks, hard edges |
| Silicon Valley flat (digital) | Grid cards, centered hierarchy | High value, low saturation plus one accent | No gradients, hard edges, no texture |
| Film noir | Diagonal division, frame within a frame, Dutch angle | High ratio, single hard source, venetian-blind shadows | Heavy grain, deep black |
| Vaporwave / synthwave | Centered symmetry, grid horizon | Neon pink and cyan, gradient sky | Deliberately cheap 3D texture, scanlines |
| Ink wash / literati painting | Negative-space composition, one-corner emphasis, scattered points | Ink in five tones, very limited color | Bone-method brushwork, paper absorbing ink |
| Ukiyo-e | Flat outline, cropped high viewpoint, diagonal wave patterns | Flat color blocks, limited color plates | Line drawing plus flat fill, wood grain |
| Digital photorealism | The full photographic composition set (D1 / D4 in this library) | Physically correct light, by subject | Micro-imperfection (skin texture / lens flaws) |

## Extended DNA cards (six dimensions plus failure points plus typical color values)

Each card below is an empirical distillation of the movement-card corpus: one line → three DNA layers → emotion → typical color values → **failure point** (the thing this style is most often done wrong as). Failure points are the custom check items when re-creating or mixing.

**The full corpus**: 421 movement cards (including 274 hand-drawn styles) are programmatically collected under the same framework in movement-library/ (divided into 9 card files by corpus category; the index is movement-library/_index.md) — the extended cards in this section are the curated layer: for a style task, check the curated cards first, then the full corpus.

### Baroque (1600–1750, Europe)

Treat light as the protagonist and use dramatic chiaroscuro and momentum to build an emotional climax.
- **Composition**: diagonal or S-shaped momentum; the frame is "in the middle of happening"; figures are cut off by the frame edge and the viewer is pulled into the scene
- **Light and color**: a single strong source from outside the frame splits a large devouring darkness (chiaroscuro pushed to a dark-dominant extreme); asphalt black and deep brown ground, with warm gold, deep crimson, and Prussian blue accents; high contrast, low saturation
- **Texture**: loose, visibly fat brushwork; bravura passages of velvet, brocade, and marble
- **Emotion**: dramatic, impassioned, sensual, oppressive
- **Color anchors**: `#1A1512` `#6B4423` `#C9A227` `#8E1B1B` `#1F3A5F` `#E8DCC0`
- **Failure point**: multiple light sources kill the Baroque feel instantly (there must be one single directional key light); over-saturation slides into fantasy illustration; writing only "dark" is not enough — the specific structure "one source devouring the darkness" is required

### Wabi-sabi (1400–present, Japan)

Beauty in the flawed and the impermanent: cracks, rust, asymmetry, and an object worn by use.
- **Composition**: minimal, asymmetrical, large negative space, a single object centered or set to one side
- **Light and color**: soft natural side light stressing the relief of the grain, leaving deep quiet shadows (no drama); extremely low-saturation earth colors — gray-brown, moss green, rust, faded off-white
- **Texture**: the material is the brushwork — clay grain, wood grain, rust patches, cracks; kintsugi (repairing cracks with gold, making the scar the highlight)
- **Emotion**: still, lonely, humble, the gentleness of time
- **Color anchors**: `#8A7A6A` `#6B7A5A` `#A8432A` `#D9CFC0` `#C9A227` `#3A3632`
- **Failure point**: the frame made brand-new and glossy (the weathered / worn / asymmetrical "imperfection" must be kept); degenerating into an ordinary still life (missing the trace language of time's erosion)

### Fauvism (1905–1908, France)

Set color free from description: grass may be red, a face may be green.
- **Composition**: flattened, decorative arrangement; space pushed and pulled by warm and cool color blocks rather than perspective
- **Light and color**: no traditional modelling — value is entirely replaced by color intensity; very high-purity large blocks collide directly (vermilion / cobalt / emerald / orange-yellow)
- **Texture**: broad, decisive visible brushwork, impasto in pure color, leaving the canvas white showing
- **Emotion**: joy, intensity, a sensory explosion, vitality
- **Color anchors**: `#D62828` `#1F5FD6` `#2E9B5B` `#F2A93B` `#8B3FA0` `#F2EDE4`
- **Failure point**: given modelling in light and shade (adding "three-dimensionality" to a pure-color frame is an anti-style error); insufficient purity (pure color squeezed straight out without mixing is the baseline)

### Art Nouveau (1890–1910, Europe)

Decoration of whiplash lines and organic curves: the source of poster aesthetics.
- **Composition**: the central subject enclosed by decorative rings or arches (a natural frame within a frame), vertical poster proportions
- **Light and color**: flattened, almost no volumetric light; separated by color blocks and lines; soft decorative colors — sage green, mustard yellow, dark gold, mauve, peacock blue
- **Texture**: flat color blocks plus decorative contour lines of varying weight; a lithographic print feel
- **Emotion**: elegant, elaborate, sensual, the mystery of nature
- **Failure point**: confused with Art Deco — **Art Nouveau is organic curves, Art Deco is geometric straight lines** (they must be kept apart); lacking the print-medium feel it degenerates into an ordinary pretty illustration

### Pop Art (1955–1970, Britain and the United States)

Appropriating mass-media imagery: the mechanical reproduction of screen printing, satirizing consumer society while embracing it.
- **Composition**: repeating grids (the same image arranged over and over), close-up cropping, comic speech-bubble structure
- **Light and color**: no light and shade — flat color blocks plus thick black contour lines; high-saturation flat fills (fluorescent pink / bright yellow / cyan-blue / true red) juxtaposed with exaggeration
- **Texture**: zero brushwork (the mechanical evenness of screen printing) or deliberately commercial flat illustration; collage
- **Emotion**: bright, satirical, cool, the dizziness of consumerism
- **Failure point**: given hand-made brushwork (mechanical reproduction is the identity itself; visible brushstrokes are the failure); colors tuned "tasteful" (the bluntness of pop color is the stance)

### Precisionism (1920–1940, United States)

Painting factories and barns as geometry: clean, sharp, without people, like an architectural rendering.
- **Composition**: low viewpoint looking up at buildings, strong geometric cutting, large areas of emptiness
- **Light and color**: clear sharp light and shadow while forms are simplified; clean cool flat fills — steel gray-blue, cement white, brick red, deep green
- **Texture**: smooth, no brushwork, hard edges, industrial surfaces, detail eliminated
- **Emotion**: cool, isolated, the chilly poetry of the industrial age
- **Color anchors**: `#8B9BB0` `#D9CFC0` `#A8432A` `#3A4A3A` `#2B2B33` `#C9A227`
- **Failure point**: confused with Cubism (Precisionism remains recognizable realism, only geometrized); figures entering the frame (this style's "stillness" presupposes their absence)

## The opposition principle of failure points

The failure points of the movements are **mutually distinct and often the exact opposite of one another**: Impressionism's signature (visible fragmented brushwork) is a prohibition in the classical academy; Renaissance-style smooth glazing cannot hold impasto; ukiyo-e's flatness without cast shadows is the opposite of Baroque deep shadow. Inferences:
1. **The check items for re-creating a style must be customized to the target style** — there is no universal failure checklist;
2. When mixing two DNA layers, one movement's "signature" may be exactly the other's "failure point" — check both failure lists before deciding a mix (arbitration in rule 4 of the mixing rules);
3. Failure points are the most efficient teaching of style recognition: being able to state a movement's failure points proves understanding better than listing its merits.

## The seven-layer deconstruction method (a framework for deconstructing styles)

Any style reference can be split into seven independently replaceable layers: **subject → style → lighting → color → composition → medium → emotion** (a separate lens layer governs shot size and focal length and is not part of the style itself).

- **Division of duties between layers**: the composition layer governs layout and momentum (viewpoint, symmetry, subject position, depth — D1 in this library); the lens layer governs "what shot size" (D4 in this library) — the two-layer division is isomorphic with this library's domain split.
- **Locking order, layer by layer**: subject (posture right) → style → lighting → color → medium; among these, **the lighting layer matters more to the final texture than the style word itself** (empirical finding) — when the style does not land, check the light first.
- **Deconstruction use**: given a "style reference", ask layer by layer "what choice did this layer make", and the feeling can be translated into parameters (connecting to the structured semantics of D8/translation-playbook).

## Mixing rules

1. **Primary-secondary mixing**: one movement supplies the primary DNA (≥2 layers), another lends only one layer ("ink-wash light and color with minimal composition" holds); borrowing one layer from each of three movements = neither-here-nor-there.
2. **Era proximity first**: adjacent movements mix harmoniously (Constructivism × Bauhaus); distant mixing is a gamble (Baroque light and color × flat composition).
3. **Declare the mix**: mixing is a design decision; only when you can say in one sentence "borrowing A's light and color, B's composition" is it mixing — otherwise it is loss of control.
4. **Conflict arbitration — guardrails yield to intent**: in cross-movement combinations, one movement's "taboo" often collides with another's "necessity" (ukiyo-e forbids cast shadows vs Baroque requires deep shadows). Arbitration rule: **what is positively expressed is intent, what is negative is a guardrail; on conflict the guardrail yields to intent** — but the trade-off must be declared explicitly ("to keep Baroque light, give up ukiyo-e's shadowless flatness"), never silently mixed. Empirical finding: roughly two thirds of random style-plus-lighting combinations hit such a conflict; arbitration is the norm, not the exception.

## Disambiguation of style concepts (reducing confusion to one)

| Word | What it is | What it is not | How to use it |
|---|---|---|---|
| Avant-garde | An attitude: a stance that challenges convention | Not a visual style | Useless alone — must be stacked with a specific movement word to hold |
| Contemporary | A period: the collective term for current work | Not a style itself | Must be followed by "which contemporary language" |
| Postmodern | A method: appropriation, pastiche, collage | Not retro | Manifests as deliberate quotation and mixing |
| Surreal | A content logic: dreamlike grafting | Not "finely painted" | Realistic framework plus irrational insertion (see the Surrealism DNA) |

## Style-consistency check (single frame and sequence)

- Single frame: are the three DNA layers from the same source? Are there foreign-source elements in the frame (a photo-real face suddenly inside a flat image)?
- Sequence: the three DNA layers stay constant across the whole sequence; variation happens only in the content layer (see modes/function/sequence.md).
- Re-creation verification: check item by item against the target movement's **failure points** (not against a universal list).

## Boundaries

- A DNA card states "typical features", not "everything possible": each movement contains a spectrum; the cards serve quick positioning and layer-splitting for mixing, not as exclusionary criteria.
- Contemporary digital styles (flat, skeuomorphic, neumorphic, Y2K) iterate fast: deconstruct a new style yourself with the "composition / light and color / texture" three-piece framework; there is no need to wait for a card.
- Style and subject are orthogonal: any subject can pair with any style — the pairing result is decided by the chemistry between the three DNA layers and the subject (realistic DNA × extraordinary subject = surreal; flat DNA × realistic subject = illustration).
- The extended cards (six-dimension version) cover only a limited set of movements: for movements without a card, deconstruct them yourself using the extended-card framework (three layers plus emotion plus failure points plus color anchors).

## Connections to other files

- Operational knowledge for each DNA layer: composition (D1), light and color (D2 / D3), texture (texture)
- The full movement library (421 cards): references/D6-style/movement-library/ (navigate via _index)
- Failure points turned into diagnosis: see D7/fault-library (style and texture family)
- Color anchors and palette discipline: see D3/palette-strategy
- The criteria system of the aesthetic school: see aesthetic-criteria
- The school development of the aesthetic school: see modes/schools/aesthetics.md
- Sequence consistency: see modes/function/sequence.md
