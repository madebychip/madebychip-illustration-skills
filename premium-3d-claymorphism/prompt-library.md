# Premium 3D Claymorphism Icon — Prompt Library

## Purpose

This document defines the visual language for a premium 3D icon system.

The reference images attached in the Project's Sources tab are the primary visual authority for:
- illustration style
- geometry
- proportions
- materials
- lighting
- rendering quality
- composition
- level of detail
- color relationships

When generating a new icon, visually match the reference images rather than interpreting this document in isolation.

The goal is to create a coherent family of icons that look as though they were designed and rendered as part of the same commercial icon system.

---

# 1. CORE VISUAL STYLE

## Style Name

Premium 3D Claymorphism / Soft 3D Commercial Iconography.

The icon should feel:
- polished
- friendly
- premium
- tactile
- modern
- approachable
- highly recognizable
- commercially usable

The aesthetic is closer to a high-end 3D product/interface icon than to a photorealistic object.

Use:
- smooth rounded geometry
- soft bevels
- simplified forms
- subtle depth
- soft material transitions
- gentle highlights
- clean silhouettes
- restrained detailing

Avoid:
- photorealism
- realistic photography
- excessive mechanical detail
- sharp industrial geometry
- overly complex textures
- noisy surfaces
- cartoon line art
- flat vector appearance
- excessive reflections
- metallic realism unless specifically requested

---

# 2. REFERENCE IMAGE PRIORITY

When generating an icon, use the supplied reference images as a visual style reference.

Match the references in this approximate priority order:

1. Overall 3D visual language
2. Shape language and rounded geometry
3. Material and surface softness
4. Lighting and shadow behavior
5. Composition and object scale
6. Color treatment
7. Level of detail
8. Secondary decorative elements

The subject itself may change completely, but the visual language should remain consistent.

For example:

"Generate a Calendar icon"

should produce a Calendar that feels like it belongs to exactly the same icon family as the supplied Car, Umbrella, Location Pin, Calendar, Phone, or other reference-style illustrations.

Do not simply make a generic 3D calendar.

---

# 3. GEOMETRY

Use soft, rounded, molded geometry.

Characteristics:
- rounded corners
- generous bevels
- soft edges
- smooth transitions
- slightly inflated forms
- simplified geometry
- toy-like but premium proportions
- visually substantial forms

Objects should generally have enough volume to feel like physical 3D objects.

Avoid:
- razor-sharp corners
- thin fragile components
- overly intricate geometry
- unnecessary micro-details
- excessive segmentation

The silhouette should remain immediately recognizable at small sizes.

---

# 4. MATERIAL

Default material:

Soft matte / satin molded plastic.

Surface characteristics:
- smooth
- slightly tactile
- low-to-medium gloss
- subtle specular highlights
- soft diffuse response
- no obvious plastic scratches
- no realistic wear
- no noisy texture

The object should feel like a carefully manufactured premium 3D icon.

Use subtle ambient occlusion where appropriate to reinforce depth.

---

# 5. LIGHTING

Use soft commercial studio lighting.

Preferred characteristics:
- large diffuse key light
- soft fill light
- subtle rim/highlight
- gentle ambient occlusion
- soft contact shadow
- smooth gradients
- no harsh directional shadows

Lighting should reveal the rounded geometry without becoming dramatic.

Avoid:
- hard shadows
- cinematic lighting
- dramatic spotlights
- excessive bloom
- strong lens effects
- moody environments

---

# 6. COMPOSITION

Default composition:

- 1:1 square canvas
- single primary icon
- centered composition
- generous breathing room
- object occupies approximately 70–90% of the canvas
- slight 3/4 perspective where appropriate
- front-facing or slightly elevated perspective
- visually balanced
- no unnecessary background objects

The icon should read immediately when viewed at thumbnail size.

Unless explicitly requested otherwise, use a clean white or transparent background.

---

# 7. COLOR SYSTEM

The icon system supports customizable brand colors.

## Default palette

Primary:
#0D88AA

Accent:
#FFA100

Supporting:
#FFFFFF

The default visual relationship is:

- Primary color = dominant structural/object color
- Accent color = secondary highlight / functional emphasis
- White = supporting details, highlights, negative space, secondary components

The exact distribution may vary according to the subject.

Do not force every icon to contain all three colors if doing so makes the object less natural.

---

# 8. COLOR CUSTOMIZATION

Users may provide custom colors.

If the user provides:

Primary: [COLOR]
Accent: [COLOR]

replace the default colors throughout the icon while preserving the same visual hierarchy.

Example:

Primary: #7B3FF2
Accent: #FFB000

The generated icon should use:
- #7B3FF2 as the dominant color
- #FFB000 as the accent color
- white / neutral supporting elements where appropriate

Do not redesign the illustration style when colors change.

Changing colors should NOT change:
- geometry
- proportions
- perspective
- lighting
- material
- composition
- rendering style

Only the palette should change.

---

# 9. COLOR APPLICATION RULES

Use the Primary color for:
- main body
- major structural surfaces
- dominant object components

Use the Accent color for:
- handles
- buttons
- highlights
- secondary objects
- badges
- small emphasis areas
- functional indicators

Use White for:
- highlights
- secondary structural components
- paper/card surfaces
- neutral details
- contrast areas

Maintain strong visual hierarchy.

The primary color should normally dominate the icon.

The accent color should normally occupy a smaller visual area.

Avoid making the icon look like a 50/50 split between primary and accent colors unless the subject naturally requires it.


## COLOR AUTHORITY

Brand colors are explicit design variables, not colors to be inferred from the reference images.

Default palette:

Primary: #0D88AA
Accent: #FFA100
Support: #FFFFFF

When a hex color is provided by the user, treat that hex value as the intended BASE / ALBEDO COLOR of the corresponding material.

Do NOT sample, estimate, or reinterpret the brand color from the reference images.

Reference images define:
- illustration style
- geometry
- proportions
- material softness
- bevels
- lighting
- shadows
- composition
- rendering quality

Reference images do NOT override explicit hex color values.

The final rendered pixels may naturally become lighter or darker because of lighting, shading, curvature, ambient occlusion and highlights. Preserve the underlying hue and color identity of the specified brand color.

Avoid unnecessary hue shifting, especially:
- Primary drifting toward bright cyan
- Primary drifting toward navy
- Accent drifting toward yellow
- Accent drifting toward red

The goal is visual color consistency, not literal flat-color rendering.

---
# 10. SUBJECT INTERPRETATION

The requested subject should remain immediately recognizable.

Examples:

"Calendar"
→ recognizable calendar silhouette with rounded 3D construction.

"Location pin"
→ recognizable map pin with a clear location-marker silhouette.

"Phone call"
→ recognizable telephone/mobile phone combined with a call/communication cue where appropriate.

"Car repair"
→ recognizable vehicle plus a repair/service cue.

"Gift rewards"
→ recognizable gift box with a reward/star cue.

The icon should communicate the concept without requiring text.

---

# 11. ICON SIMPLIFICATION

Prefer one strong visual metaphor over many small objects.

When a concept can be represented with one main object and one supporting element, use that approach.

For example:

Car repair:
- main object = car
- supporting object = repair/service element

Avoid:
- multiple tools
- multiple badges
- excessive symbols
- unnecessary coins
- decorative background elements

unless specifically requested.

---

# 12. DETAIL LEVEL

Target:

"premium simple 3D icon"

rather than:

"highly detailed 3D scene."

Use enough detail to:
- clarify the subject
- create depth
- make the object feel premium

but not enough to:
- clutter the composition
- weaken the silhouette
- make the icon visually inconsistent with the reference family

---

# 13. OUTPUT QUALITY

Generate:
- high resolution
- crisp edges
- clean geometry
- polished commercial rendering
- consistent proportions
- consistent lighting
- consistent visual language

Default aspect ratio:
1:1

If transparency is requested:
- use a transparent background
- preserve clean edges
- avoid halos around the object

---

# 14. CONSISTENCY RULE

Every generated icon should look like it belongs to the same product/design system.

If there is a conflict between:
- the subject
- generic visual conventions
- the reference images

prioritize consistency with the reference images while maintaining recognizability of the requested subject.

---

# 15. MASTER VISUAL PROMPT

Use the following conceptual prompt when generating any icon:

"Create a premium 3D claymorphism commercial icon based on the supplied reference images. Match the reference family's soft rounded geometry, molded toy-like proportions, smooth satin/matte material, subtle bevels, soft studio lighting, gentle ambient occlusion, subtle contact shadow, clean silhouette, polished commercial rendering, minimal but highly recognizable forms, and restrained level of detail.

Create a single centered icon on a clean 1:1 composition. Use Primary as the exact intended base color for the main material.
Treat the supplied hex value as the color source of truth. Preserve its teal hue and avoid shifting it toward cyan, navy, or green. Allow natural 3D shading and highlights to create tonal variation while maintaining the same underlying color identity.
Use Accent as the exact intended base color for secondary/accent materials.
Preserve its orange hue and avoid shifting it toward yellow or red.
Allow natural 3D shading and highlights.

The result must look like a member of the same professionally designed icon family as the supplied references, while clearly representing the requested subject.

Avoid photorealism, flat vector graphics, line-art illustration, excessive detail, hard shadows, dramatic lighting, clutter, unnecessary decorative elements, and unrelated objects."