# Hero Otter Illustration — Prompt Library

## PURPOSE

This library defines the production visual system for illustrations built around ONE fixed Hero Otter.

The supplied Project reference images are the primary visual authority. Use this document to interpret and combine them; do not use it as a substitute for the references.

The objective is not to create a generic otter in a shared style. Every output should look like the SAME Hero Otter performing a different activity.

### A note on reference images and Sources

Images sitting in the Project's Sources tab are not reliably used as visual reference during generation — the model knows the files exist but often doesn't actually look at them when rendering. Text instructions in `SKILL.md` (like the default clothing color) get followed regardless; anything that depends on seeing pixels (face construction, fur texture, proportions, tail shape) will drift if the Hero reference image isn't attached directly to the message. Attach `reference-1-hero-reference-otter.png` to every generation message rather than relying on Sources alone.

### Allowed variation
- activity
- pose
- facial expression
- essential props
- clothing color
- format/background when requested

### Locked
- character identity
- anatomy
- facial construction
- body proportions
- fur color/pattern
- tail
- clothing silhouette/construction
- core rendering language

---

# 1. REFERENCE IMAGE AUTHORITY

Use the four references as separate sources of truth.

## Reference 1 — Hero / Reference Otter
**Authority: CHARACTER IDENTITY**

Use this reference for:
- exact head shape and size
- head-to-body ratio
- muzzle and cheek volume
- eyes, nose and mouth
- ears and cream markings
- fur color/distribution
- torso and limb proportions
- paws, feet and tail
- overall silhouette
- clothing silhouette and construction
- personality

This is the highest-priority reference.

**The Hero Otter is a fixed character model. Do not redesign it.**

## Reference 2 — Activity Collage
**Authority: POSE AND OBJECT INTERACTION**

Use for:
- standing, sitting, lying and leaning
- paw placement
- gestures
- object handling
- leg positioning
- activity storytelling

Do not copy its exact activities unless requested.

## Reference 3 — Another Activity Collage
**Authority: DYNAMIC RANGE AND EXPRESSION**

Use for:
- energetic poses
- playful gestures
- facial expressions
- accessories
- activity-specific interaction

It expands the pose vocabulary; it does not redefine the character.

## Reference 4 — Swimming Otter
**Authority: RENDERING QUALITY**

Use for:
- softness
- material treatment
- dimensionality
- lighting
- shading
- highlights
- contact shadows
- polished commercial finish

Do not use it to redefine the Hero Otter's identity.

### Reference hierarchy

**Hero identity → Swimming rendering → activity-collage pose/interaction → secondary details.**

Never average the four otters into a new character.

---

# 2. HERO OTTER CHARACTER LOCK

The Hero Otter should feel like a soft molded/plush 3D character, not a newly invented realistic otter.

Preserve:
- oversized rounded head
- compact body
- short rounded limbs
- rounded paws/feet
- broad rounded tail
- warm taupe/beige fur
- cream muzzle and inner-ear areas
- rounded dark-brown nose
- large glossy dark eyes
- simple dark-brown curved mouth
- friendly youthful expression language
- simplified anatomy
- established one-piece outfit silhouette

### Identity test

Ask internally:

> If the activity props and clothing color were removed, would this still clearly be the Hero Otter?

If not, the character has drifted.

### Never change because of an activity

Do not:
- lengthen limbs for sports
- make the torso more athletic
- enlarge or shrink the head
- change muzzle anatomy
- change eye size/placement
- redesign paws for gripping
- make the tail anatomically realistic
- add realistic whiskers or fur
- alter the face to resemble another otter
- create a more realistic animal body

**Adapt the pose to the Hero Otter. Never adapt the Hero Otter to the pose.**

---

# 3. VISUAL STYLE

Target:

**Premium Soft 3D Character Illustration / Plush Claymorphism**

The image should feel:
- cute
- warm
- friendly
- premium
- tactile
- soft
- playful
- polished
- commercially usable

Use:
- smooth rounded geometry
- soft molded forms
- subtle bevels
- controlled proportions
- matte/satin surfaces
- soft tactile microtexture
- gentle highlights
- smooth tonal transitions
- polished 3D volume
- clean silhouettes
- restrained detail

Avoid:
- photorealism
- realistic animal anatomy
- visible directional fur strands
- hard plastic
- excessive gloss
- sharp geometry
- flat vector art
- line-art appearance
- anime styling
- excessive texture
- noisy detail
- complex environments
- harsh cinematic lighting

The surface should be softly textured but remain smooth and molded. Do not increase fur realism for any activity.

---

# 4. ACTIVITY SYSTEM

The user's activity changes the **pose and interaction**, not the character.

Translate each request into:
**Hero Otter + activity + readable pose + essential props + optional clothing color.**

Examples:

### Dancing
Dynamic but compact dance pose. Keep the Hero Otter's proportions and rounded limbs.

### Reading
Seated or relaxed pose holding an open book naturally.

### Cooking
Standing or seated pose interacting with a pot and utensil.

### Painting
Seated/standing pose with brush, palette and canvas/easel where necessary.

### Sleeping
Relaxed low pose, closed eyes, soft expression, minimal props.

### Tennis
Use the Hero Otter's existing anatomy. Pose it naturally with a tennis racket and ball. Do not lengthen limbs or create athletic anatomy merely to make the swing realistic.

### Cycling
Keep the compact Hero body. Adapt the bicycle to the character rather than stretching the character to fit the bicycle.

### Swimming
Use a buoyant, relaxed pose consistent with the Hero Otter's proportions; use the Swimming Otter primarily for rendering quality.

The activity should be immediately recognizable at thumbnail size.

---

# 5. POSE AND EXPRESSION

Use the activity collages as a vocabulary, not a template.

A good pose:
- communicates the activity immediately
- uses believable simplified body mechanics
- preserves the Hero silhouette
- has clear paw/object relationships
- avoids unnecessary limb complexity
- remains cute and expressive

Expressions may vary:
- happy
- focused
- sleepy
- excited
- playful
- content
- gently surprised

Expressions may change, but the underlying face construction does not.

Do not introduce detailed facial anatomy, teeth, realistic whiskers or complex facial structures.

---

# 6. PROPS

Use the minimum props needed.

Default:
**one Hero Otter + one activity + essential props.**

Examples:
- tennis → racket + ball
- reading → book
- painting → canvas/easel + brush
- cooking → pot + utensil
- guitar → guitar
- laptop → laptop

Props should:
- be clearly recognizable
- fit the character's scale
- sit naturally in the paws/body
- support the activity
- remain secondary to the Hero Otter

Do not add decorative objects just to make the image richer.

---

# 7. CLOTHING SYSTEM

Default garment:
**simple sleeveless rounded one-piece outfit, warm coral-red.**

The garment silhouette is locked.

If the user specifies a clothing color:
- recolor the entire garment
- preserve its exact shape and construction
- keep the garment opaque
- keep clean boundaries against fur
- preserve natural shading and material
- do not recolor fur, muzzle, eyes, nose, paws or tail
- do not introduce new garment details
- do not change clothing style

Examples:
- "blue outfit" → same Hero Otter, same garment, blue
- "yellow clothes" → same Hero Otter, same garment, yellow
- "purple one-piece" → same garment construction, purple

Color changes must not alter character identity, anatomy, pose, material, lighting or composition.

If no color is specified, use warm coral-red.

---

# 8. MATERIAL AND RENDERING

Use Reference 4 — Swimming Otter as the rendering authority.

Target:
- soft dimensional forms
- subtle matte/satin surface
- tactile but controlled microtexture
- gentle highlights
- soft tonal gradients
- diffuse studio lighting
- subtle ambient occlusion
- soft contact shadow
- polished commercial 3D finish

Preferred lighting:
- large diffuse key
- soft fill
- subtle rim when useful
- gentle AO
- restrained highlights

Avoid:
- hard shadows
- dramatic cinematic lighting
- strong spotlights
- excessive bloom
- heavy lens effects
- extreme contrast
- moody environments

Rendering quality must not cause character drift.

---

# 9. COMPOSITION

Default:
- 1:1 square
- one Hero Otter
- centered or visually balanced
- full character visible where practical
- 65–90% canvas occupancy
- generous negative space
- clean warm-white studio background
- slight 3/4 perspective where useful
- no text
- no borders
- no collage

For activity scenes, show enough of each essential prop to make the action immediately readable.

Use transparent background only when requested.

---

# 10. MASTER PROMPT

Use this as the base production prompt:

> Create the exact same Hero Otter shown in the supplied Hero / Reference Otter image, performing [ACTIVITY]. Preserve the Hero Otter's exact character identity, head shape and size, head-to-body ratio, muzzle and cheek volume, eyes, nose, mouth, ears, fur color and markings, body proportions, short rounded limbs, paws, feet, tail, overall silhouette and one-piece clothing construction. Do not redesign, reinterpret or replace the otter. Do not make the anatomy more realistic or adapt the character's proportions to the activity. Adapt only the pose, expression and essential object interaction needed to communicate [ACTIVITY].
>
> Use the Activity Collages as references for pose vocabulary, gestures and object interaction. Use the Swimming Otter as the primary reference for rendering quality: soft molded/plush-like geometry, smooth tactile surface, matte/satin material, gentle highlights, strong dimensionality, diffuse studio lighting, subtle ambient occlusion, soft contact shadows and polished commercial 3D finish.
>
> Essential props only: [PROPS].
>
> Clothing: preserve the exact Hero garment shape. [CLOTHING COLOR INSTRUCTION]. Keep clothing opaque and cleanly separated from fur; do not allow color bleed.
>
> Clean 1:1 composition, centered/balanced Hero Otter, generous breathing room, warm-white studio background, full character visible where practical, no text, no clutter.
>
> Avoid generic-animal redesign, realistic anatomy, realistic fur strands, photorealism, hard plastic, excessive gloss, sharp geometry, dramatic lighting and unnecessary detail.

---

# 11. SHORT PROMPT TEMPLATES

### Activity only
> Generate the exact same Hero Otter from the Hero reference, [ACTIVITY]. Preserve the character exactly; change only pose, expression and essential interaction. Use the Swimming Otter for rendering quality.

### Activity + clothing color
> Generate the exact same Hero Otter from the Hero reference, [ACTIVITY], wearing the same one-piece outfit in [COLOR]. Preserve the character and garment construction exactly; change only the pose/activity and clothing color.

### Activity + props
> Generate the exact same Hero Otter from the Hero reference, [ACTIVITY], interacting naturally with [PROPS]. Preserve the Hero Otter's exact anatomy and identity. Do not redesign the character to suit the activity.

### Iterative edit
> Keep the exact existing Hero Otter, pose, proportions, rendering and composition. Change only [REQUESTED CHANGE]. Preserve everything else.

---

# 12. TEST PROMPTS

Use these to test consistency:

1. **Tennis**
> Generate the exact same Hero Otter playing tennis, holding a racket with a tennis ball nearby. Preserve the Hero anatomy and compact proportions; do not make the otter more athletic or realistic.

2. **Blue clothing**
> Generate the exact same Hero Otter reading a book, wearing the same one-piece outfit in blue. Change only the pose/activity and clothing color.

3. **Yellow clothing**
> Generate the exact same Hero Otter cooking with a pot and wooden spoon, wearing the same one-piece outfit in yellow.

4. **Purple clothing**
> Generate the exact same Hero Otter dancing playfully, wearing the same one-piece outfit in purple.

5. **Sleeping**
> Generate the exact same Hero Otter sleeping peacefully on its side with closed eyes and minimal bedding.

6. **Guitar**
> Generate the exact same Hero Otter sitting and playing a small acoustic guitar. Preserve the Hero face, anatomy and proportions.

7. **Painting**
> Generate the exact same Hero Otter painting on a small canvas with a brush and palette.

8. **Cycling**
> Generate the exact same Hero Otter riding a simple bicycle. Adapt the bicycle and pose to the Hero Otter's compact anatomy; never stretch or redesign the otter.

---

# 13. QUALITY-CONTROL CHECK

Before accepting an output, verify:

1. Same Hero Otter?
2. Same head and face?
3. Same head-to-body ratio?
4. Same muzzle, eyes, nose and ears?
5. Same body, paws, feet and tail?
6. Same garment silhouette?
7. Activity immediately readable?
8. Pose adapted without anatomical redesign?
9. Props minimal and coherent?
10. Rendering matches Swimming Otter?
11. Clothing color isolated to the garment?
12. Clean, uncluttered composition?

If any answer is no, prioritize **Hero identity** and regenerate rather than accepting a generic otter.

---

# CORE PRODUCTION PRINCIPLE

**ONE IMMUTABLE HERO OTTER.**

Activities, poses, expressions, props and clothing color may vary.

**The character does not.**