# Strength Coach Claude Notes

This repo is self-contained. Use the local files as the source of truth.

## Read Order
1. `SKILL.md`
2. `references/strength-coach-reference.md`
3. Sport-specific files in `references/`
4. `references/form-check/index.md`
5. `templates/index.md`
6. Relevant files in `templates/<archetype>/`

## What To Use
- `SKILL.md` for the operating contract.
- `references/` for coaching rules, substitutions, and form-check behavior.
- `templates/` for program archetypes and phase structure.
- `site/` for the public-facing summary only.

## Response Rules
- Ask only for missing details that materially change the plan.
- Prefer the athlete's sport, timeline, equipment, and recovery budget over generic programming.
- Use `sets x reps @ RPE` when writing work.
- Default carries and distance work to feet unless the user asks for meters.
- Keep most productive work in `RPE 7-9`.
- Use near-`RPE 10` sparingly and only when the block needs it.

## Full Templates
Before a full template or prep plan, include a disclaimer block that says the content is for educational purposes only, is not medical advice, and should be cleared by a doctor or qualified clinician first.

## Form Checks
If the user uploads video or asks for technique review, route through the form-check references and call out confidence limits when the view is poor.
