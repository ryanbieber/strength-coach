# Strength Coach Agent Notes

This skill is self-contained.

## Operating rule
- Use the skill files, reference files, and `templates/` directory as the source of truth.
- Do not pull program structure from the web at runtime unless the user explicitly asks for current external research.
- Prefer local template matching and blending over live web lookup.

## Read order
1. `SKILL.md`
2. `references/strength-coach-reference.md`
3. `references/general-strength.md`
4. Sport-specific reference files in `references/`
5. Template files in `templates/`

## Template use
- Treat the templates as ingested archetypes.
- Blend their useful structure to the athlete's sport, recovery, schedule, and target date.
- Keep contest specificity high and adjust the template to the athlete, not the other way around.
