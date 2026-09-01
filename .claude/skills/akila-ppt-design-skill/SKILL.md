---
name: akila-ppt-design-skill
description: Create, redesign, adapt, or review Akila PowerPoint decks and slides. Use whenever the user needs to make an Akila PPT, Akila deck, pitch deck, investor deck, client deck, slide master, or template-based slide output.
---

# Akila PPT Design Skill

Use this skill whenever the user needs to make, redesign, adapt, or review an Akila PPT/deck/slide. The output should follow the approved Akila visual system and reuse the bundled PPT template as a visual reference asset.

## Required References

- For choosing slide structures, read `references/slide-layout-index.md`.
- For typography, color, layout behavior, and Akila visual language, read `references/akila-visual-rules.md`.
- Before delivery, read and apply `references/akila-ppt-qa.md`.

## Template Asset

Use `assets/akila-slide-master-template.pptx` as the approved visual reference. It is a skill-first MVP asset, not yet a fully consolidated corporate `.potx` release.

Do not treat the template as an example-ranking set. All slides are approved references. Classify them only by reuse mode:

- `Reusable`: use directly when the new content matches the same purpose and density.
- `Adaptable`: use as a starting structure, then adjust module count, emphasis, or grouping based on content.
- `Reference only`: use for visual language only; rebuild the structure for the actual content.
- `Usage guide`: instruction material for humans or AI; do not use as an output slide layout.

## Operating Rules

1. Identify the communication job before selecting a layout: cover, statement, content explanation, comparison, metrics, feature cards, image proof, table, process, diagram, case study, team, or closing.
2. Choose the closest approved layout from the layout index. If no layout fits, adapt a related layout conservatively instead of inventing a parallel visual system.
3. Preserve Akila's visual language: dark-blue structural anchors, clean white or light surfaces, controlled bright-blue accents, real evidence, and organized information density.
4. For chart-like, diagram-like, or key existing slide structures, follow the `Reference only` rule. Do not force new content into an old diagram form.
5. Use AI for visual support when needed, but typeset exact copy, metrics, labels, and brand elements with editable PowerPoint text and shapes whenever possible.
6. Preserve source content unless the user explicitly asks for rewriting, shortening, restructuring, or translation.

## Current Scope

This skill-first MVP is intended to prove whether AI can reliably select and adapt Akila layouts. Full PowerPoint master consolidation, organization-wide `.potx` publishing, and layout-switching test decks are later hardening steps, not prerequisites for this MVP.
