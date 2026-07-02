# Strength Coach Agent Guide

Use this repo as a portable strength-programming corpus for agents and assistants.

## Canonical Sources
- `SKILL.md`
- `references/strength-coach-reference.md`
- Sport-specific files in `references/`
- `references/form-check/`
- `templates/index.md`
- `templates/<archetype>/`

## Working Rules
- Read the skill file first, then the reference files, then the templates that match the sport.
- Keep the main lift or event pattern central.
- Use templates as archetypes, not copy-paste blocks.
- Match volume and intensity to the athlete's recovery and timeline.
- Write programs in Markdown with clear headings and bullets.
- Use `sets x reps @ RPE` for loading guidance.
- Default carries to feet.

## Output Shape
- Direct recommendation first.
- 1 to 2 alternates if equipment or tolerance is limited.
- Short rationale for why it fits.
- Next question if important context is missing.
- Disclaimer block before any full template or prep plan.
- Assumptions review at the end of any completed template or prep plan.

## Public Site
- `site/` is the public summary and prompt-builder.
- It is useful for humans, but not the source of truth.
