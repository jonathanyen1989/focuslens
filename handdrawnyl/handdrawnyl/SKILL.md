---
name: handdrawnyl
description: Generate YL-style hand-drawn insight illustrations. Use this skill when the user asks to turn articles, transcripts, meeting insights, leadership principles, system logic, AI workflows, project management content, data workflows, or presentation ideas into hand-drawn visual planning, shot lists, or generated illustrations.
---

# handdrawnyl

## Core Positioning

handdrawnyl is a hand-drawn insight illustration skill.

Its goal is not to create generic illustrations, cute cartoons, Xiaohei-style pictures, commercial posters, or traditional PPT infographics.

Its core goal is to first identify the cognitive anchor in the user's content, then turn one key judgment, structure, process, management insight, system relationship, or AI workflow into a clear, structured, hand-drawn note-style explanation visual.

Default visual mix:

- 50% hand-drawn notebook feeling
- 30% enterprise-level structure
- 20% AI / data / technology elements

## When To Use This Skill

Use this skill when the user asks for:

- hand-drawn insight illustrations
- visual planning or shot lists for articles, transcripts, meeting notes, or concepts
- cognitive insight diagrams
- management principle visuals
- leadership thinking visuals
- system explanation visuals
- AI Agent / Skill / automation workflow visuals
- Power BI / data platform / dashboard explanation visuals
- project management visuals
- presentation visuals in handdrawnyl style
- revising an existing visual toward handdrawnyl style

## Default Workflow

Always use a two-stage workflow.

### Stage 1: Visual Planning

First analyze the user's content and output a Shot List.

Do not generate images in Stage 1, even if the user asks to generate images directly.

### Stage 2: Image Generation

Only generate images after the user selects, confirms, modifies, or explicitly approves the Shot List.

Generate each image separately.

Do not merge multiple illustrations into one canvas unless the user explicitly asks.

## Stage 1: Visual Planning

When planning visuals:

1. Read the user's article, transcript, concept, document, screenshot, or topic.
2. Identify cognitive anchors.
3. Prefer strong visual anchors over evenly distributed illustrations.
4. Do not create a visual for every paragraph.
5. Select only points that benefit from visualization.
6. For each candidate visual, define:
   - title
   - illustration type
   - cognitive anchor
   - core message
   - composition approach
   - figure action
   - key elements
   - suggested text labels
   - recommended color mode
   - recommended canvas ratio
   - generation priority

## Shot List Quantity Rule

Decide the number of shots based on content length and insight density.

- Single concept / one-sentence insight: 1-2 shots
- Short paragraph / short meeting excerpt: 2-4 shots
- Medium article / method note / structured explanation: 4-6 shots
- Long article / full transcript / complex system document: 6-8 shots
- Default maximum: 8 shots

Do not create more shots just to fill a number.

Prefer fewer stronger cognitive anchors over many weak illustrations.

## Shot List Output Format

Use this format in Stage 1:

### 01. [Visual Title]

- Illustration Type:
- Placement / Use Case:
- Cognitive Anchor:
- Core Message:
- Composition Approach:
- Figure Action:
- Key Elements:
- Suggested Text Labels:
- Recommended Color Mode:
- Recommended Canvas Ratio:
- Generation Priority:
- Notes:

## Illustration Type Priority

Prioritize illustration types in this order:

1. Cognitive Insight Illustration
2. Structure Explanation Illustration
3. Presentation Visual
4. Project Management Visual

When in doubt, prefer cognitive insight illustrations over process diagrams.

Do not turn every input into a workflow chart.

## Style System

Use the handdrawnyl visual style:

- 50% hand-drawn notebook feeling
- 30% enterprise-level structure
- 20% AI / data / technology elements

Visual characteristics:

- clean hand-drawn lines
- black or dark gray linework
- slight hand-drawn wobble
- structured layout
- light annotation feeling
- short handwritten-style labels
- neutral recurring line figure
- restrained accent colors
- clean background

## Reference Loading Rule

Read reference files only when needed.

- references/style-dna.md: visual style, color, line, background, text label, and negative style rules.
- references/visual-figure.md: recurring hand-drawn figure.
- references/visual-elements.md: thinking, system, data, project, or execution visual elements.
- references/composition-patterns.md: illustration type, metaphor strategy, and layout pattern.
- references/prompt-template.md: before generating images.
- references/qa-checklist.md: after image generation or when revising an image.
- assets/examples/: low-frequency handdrawnyl style calibration only. Do not treat examples as composition templates. Do not keep Xiaohei-style examples in this directory.

## Stage 2: Image Generation

Only generate images after the user approves, selects, or modifies the Shot List.

Before generating each image:

1. Read the selected Shot List item.
2. Confirm the illustration type.
3. Select the color mode.
4. Select the canvas ratio.
5. Apply the correct line style and background rule.
6. Use the recurring figure only when it supports the insight.
7. Use prompt-template.md to compose the image prompt.
8. Generate each image separately.

Do not generate multiple shots as one combined image unless explicitly requested.

## Canvas Ratio Rule

Default canvas ratio is 16:9 landscape.

Use 16:9 by default for:

- presentation slides
- web presentation pages
- video covers
- dashboard explanation visuals
- method framework pages

If the user specifies another use case, adapt the ratio:

- PPT / web / video / dashboard: 16:9
- document inline illustration: 4:3 or 3:2
- social media card: 1:1
- vertical explanation / long process: portrait

User-specified ratio always takes priority.

## Negative Rules

Avoid the following styles and behaviors:

1. Do not use Xiaohei style.
2. Do not use black solid-body characters.
3. Do not use absurd / grotesque weirdness as the main visual style.
4. Do not use cute cartoon, childish illustration, emoji-like or sticker-like style.
5. Do not use strong manga, anime, comic, or storyboard style.
6. Do not create complex PPT-style infographics.
7. Do not put large amounts of explanatory text inside the image.
8. Do not create commercial poster or advertising key visual.
9. Do not use 3D rendering, glossy glassmorphism, realistic lighting, or skeuomorphic effects.
10. Do not use excessive neon tech, cyberpunk, or sci-fi visual overload.
11. Do not use realistic human figures or photorealistic images.
12. Do not use complex architecture, room, or scene backgrounds.
13. Do not stack too many icons, modules, arrows, labels, or decorative elements.
14. Do not turn the recurring figure into a mascot or main IP character.
