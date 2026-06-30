# QA Checklist

A beautiful image fails if it does not express the cognitive anchor.

A handdrawnyl image passes QA only if it clearly turns one cognitive anchor into one readable hand-drawn visual structure.

The viewer should understand the main idea within 3 seconds.

## Cognitive Anchor Check

Pass if the main idea is visually obvious, the image shows a judgment/contrast/structure/decision/hidden system/action logic, the image matches the approved Shot List item, and the viewer can explain the core message after a quick glance.

Fail if the image looks nice but does not express the insight, the visual is too generic, the cognitive anchor is lost, or the image only shows objects without meaning.

## Composition Check

Pass if one image expresses one main cognitive anchor, the selected composition matches the illustration type, the structure is readable, hierarchy is clear, and arrows/grouping/panels/layers clarify the logic.

Fail if the image tries to express too many ideas, the layout is busy but conceptually weak, the image becomes a generic workflow chart, or the image becomes a dense architecture diagram.

## Style DNA Check

Pass if it has hand-drawn notebook feeling, clean black or dark gray sketch lines, slight natural line wobble, enterprise-readable structure, restrained accent colors, and enough white space.

Fail if it looks like Xiaohei style, cute cartoon, commercial poster, formal PPT infographic, photorealistic image, 3D rendering, or excessive neon/cyberpunk effects.

## Figure Check

Pass if the figure is simple, neutral, line-based, supports the cognitive action, interacts with the structure, acts as a thinking operator, and does not dominate the canvas.

Fail if the figure looks like Xiaohei, has a black solid body, looks cute/childish/emoji/mascot-like, is decorative, has exaggerated cartoon expression, or dominates the image.

## Visual Elements Check

Pass if all elements directly support the cognitive anchor, the image uses a controlled number of elements, elements clarify the logic, and elements do not compete with the main idea.

Fail if icons are stacked without meaning, technology symbols are added randomly, arrows are overused, there are too many modules, or decorative objects distract from the main idea.

## Color Mode Check

Fail if colors are too saturated, too many colors are used, color usage is decorative rather than meaningful, or the selected Color Mode is not recognizable.

## Text Label Check

Pass if labels are short, support structure, easy to scan, and look handwritten-style.

Fail if long paragraphs appear inside the image, labels look like dense PPT text, Chinese labels are too long, text errors make the image unusable, or labels explain what the image should have shown visually.

For Chinese labels:

- prefer 2-6 Chinese characters per label when possible
- avoid long Chinese sentences
- reduce label count if text rendering is unstable

## Negative Style Check

The image fails QA if it contains Xiaohei style, black solid-body character, grotesque weirdness, cute cartoon / childish illustration / emoji / sticker feeling, strong manga/anime/comic style, complex PPT infographic feeling, large explanatory text blocks, commercial poster/KV feeling, 3D rendering, glossy glassmorphism, photorealistic people, neon/cyberpunk overload, complex room/city/architecture background, or recurring figure becoming mascot/main IP.

## Regenerate Criteria

Regenerate if the cognitive anchor is missing, the image does not match the approved Shot List, the style is clearly not handdrawnyl, the image looks like Xiaohei style, the figure has a black solid body, the image is cute cartoon or mascot-like, the image becomes a dense PPT infographic, the image is too crowded to read, the metaphor is wrong or misleading, text errors are severe, the selected color mode is completely ignored, or the image is photorealistic/3D-rendered.

## Minor Revision Criteria

Revise instead of fully regenerating if the main concept is correct but labels are too long, the layout is mostly good but slightly crowded, the color accents are too strong, the figure is useful but too large, one or two visual elements are unnecessary, the background texture is too visible, or the image needs more white space.

## Delivery Review

After generating images, report generated image count, file names/paths, corresponding Shot List item, selected illustration type, selected Color Mode, whether each image passed QA, strongest image, image that may need iteration, and recommended revision if needed.
