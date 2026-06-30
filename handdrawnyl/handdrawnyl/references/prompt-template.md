# Prompt Template

A good prompt translates the cognitive anchor into a visual structure, not just into a style description.

This file defines how to convert an approved Shot List item into a stable image-generation prompt for handdrawnyl.

## Prompt Construction Rule

Build each image prompt from:

1. Base handdrawnyl style block
2. Shot-specific content block
3. Illustration type block
4. Composition block
5. Figure block, if needed
6. Visual elements block
7. Color mode block
8. Line style block
9. Background block
10. Text label block
11. Canvas ratio block
12. Negative prompt block

Do not omit the negative prompt block.

## Base Image Prompt Template

Create a handdrawnyl-style hand-drawn insight illustration.

The image should look like a smart person explaining a complex idea on a whiteboard or notebook.

Visual style:

- hand-drawn notebook feeling
- clean black or dark gray sketch lines
- slight natural line wobble
- clear enterprise-level structure
- restrained accent colors
- short handwritten-style labels
- enough white space
- clean and readable layout
- 50% hand-drawn note feeling
- 30% enterprise structure
- 20% AI / data / technology elements when relevant

This is not a cute cartoon, not Xiaohei style, not a commercial poster, not a traditional PPT infographic, and not a photorealistic image.

## Shot-Specific Content Block

Include visual title, illustration type, cognitive anchor, core message, composition approach, figure action, key elements, suggested text labels, recommended color mode, and canvas ratio.

The image should make the cognitive anchor visible within 3 seconds.

## Illustration Type Blocks

### Cognitive Insight Illustration

Focus on one thinking shift, management judgment, hidden system, decision logic, or root cause insight.

Preferred compositions: surface vs system, question tree, before vs after thinking, decision fork, hidden constraint, leverage point.

Text: one main phrase + 2-4 short labels.

### Structure Explanation Illustration

Explain one system, workflow, feedback loop, data flow, or module relationship.

Preferred compositions: input-process-output, feedback loop, agent workflow, system map, data pipeline.

Text: concise module names or step labels.

### Presentation Visual

Create a slide-ready or web-ready hand-drawn visual.

Preferred compositions: big idea visual, framework page, visual summary, before / after panel, central model.

Keep the layout clean and visually stable.

### Project Management Visual

Explain one project execution logic, risk situation, milestone flow, KPI loop, owner-action relationship, or review mechanism.

Preferred compositions: risk radar, milestone roadmap, owner-action matrix, review loop, KPI flow.

Labels can be slightly more detailed but must remain short and scannable.

## Color Mode Blocks

### Tech Accent Mode

Palette:

- background: white or very light gray
- linework: black or dark gray
- accents: blue, cyan, purple

Use accent color for nodes, data flow, signals, and key highlights. Avoid neon gradients and cyberpunk feeling.

### Thinking Note Mode

Palette:

- background: white or very light warm gray
- linework: black or dark gray
- blue: structure, relationship, path
- yellow: highlight, sticky note, key point
- orange: risk, warning, blocker, tension

Make it feel like annotated thinking notes.

### Soft Color Sketch Mode

Palette:

- background: white or soft light background
- linework: black or dark gray
- fills: soft blue, soft green, soft purple, soft yellow

Keep saturation low and professional.

### Custom Mode

User-specified colors take priority.

Keep custom colors as restrained accents and preserve clear visual hierarchy.

## Chinese Label Rule

If the image includes Chinese labels, keep them very short. Prefer 2-6 Chinese characters per label when possible. Avoid long Chinese sentences inside the image. If text rendering is unstable, reduce label count and keep explanations outside the image.

## Figure Block

Use the recurring neutral sketch figure only when it helps explain the cognitive anchor.

Figure style:

- simple neutral line figure
- round or slightly oval head
- minimal body
- black or dark gray sketch lines
- no solid black body
- no cute cartoon expression
- no mascot feeling

Figure action should be meaningful: writing, circling, connecting, splitting, comparing, checking, monitoring, adjusting, mapping, reviewing, deciding.

## Negative Prompt Block

Always include:

Do not use Xiaohei style. Do not use black solid-body characters. Do not use cute cartoon, childish illustration, emoji-like, sticker-like, manga, anime, comic, or mascot style. Do not use grotesque weirdness as the main style. Do not use photorealistic people. Do not use realistic lighting. Do not use 3D rendering. Do not use glossy glassmorphism. Do not use cyberpunk or neon sci-fi overload. Do not create a commercial poster or advertising key visual. Do not create a dense PPT infographic. Do not use large text blocks. Do not overload the image with icons, modules, arrows, labels, or decorative objects. Do not use complex architecture, room, city, or office background. Do not let the recurring figure dominate the image.
