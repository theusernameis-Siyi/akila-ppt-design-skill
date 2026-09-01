# Akila PPT QA

Run these checks before delivering Akila slides.

## Content Fit

- Preserve user-supplied content unless rewriting or restructuring was explicitly requested.
- Check every slide for clipped text, overflow, cramped cards, orphan final words, and labels too close to borders.
- If content does not fit, shorten copy or change to a more suitable layout. Do not shrink body text until it becomes illegible.

## Layout Selection

- Confirm each slide's communication job matches the selected layout.
- Confirm `Reference only` slides were not used as direct fill-in structures.
- For chart-like or diagram-like slides, confirm the structure follows the actual data, relationship logic, and message hierarchy.
- Do not invent a parallel visual system when an approved Akila layout can be reused or adapted.

## Color

- Confirm `#385AEA` is not the dominant large-area fill by default.
- Confirm `#B523B9` stays below 5% of the slide when used.
- Confirm `#45C5CC` is used only as a controlled accent, especially for large titles on `#1E2856`.
- Confirm body copy, small descriptions, and captions use neutral colors rather than accent colors.
- Avoid pages that rely only on `#45C5CC` and `#385AEA`.

## Typography

- English title-like text uses `Clarity City` with bold styling.
- English body text uses `Clarity City` regular.
- Chinese title-like text uses `OPPOSans B`.
- Chinese body text uses `OPPOSans R`.

## Evidence Integrity

- Use real customer, project, product, data, and screenshot evidence when the slide implies real-world proof.
- Do not create fake logos, fake dashboards, fake screenshots, or invented business outcomes.
- If a claim, metric, logo, screenshot, or project fact is not provided, mark it as a placeholder or ask for source material.

## Delivery Checks

- Render the deck to images and inspect the output visually.
- Run a PowerPoint overflow or canvas-boundary check when tools are available.
- Known current template issue: slides 10 and 24 may report existing off-canvas objects in `slides_test.py`; this was present before the skill package and should not be treated as a new generation failure unless visible content is affected.
