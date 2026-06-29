# Strength Coach Agent Notes

This skill is self-contained.

## Operating rule
- Use the skill files, `references/` directory, and `templates/` directory as the source of truth.
- Keep `references/` for coaching guidance, definitions, substitutions, and planning rules.
- Keep `templates/` for program archetypes and phase structures only.
- Do not pull program structure from the web at runtime unless the user explicitly asks for current external research.
- Prefer local template matching and blending over live web lookup.
- Keep `README.md` in sync with user-facing coaching rules, especially distance units, RPE guidance, and example outputs.
- Keep `references/program-catalog.md` in sync with the external programs that are worth studying or citing in user-facing answers.

## Read order
1. `SKILL.md`
2. `references/strength-coach-reference.md`
3. `references/general-strength.md`
4. Sport-specific reference files in `references/`
5. `references/program-catalog.md`
6. `references/form-check/index.md`
7. `templates/index.md`
8. Archetype folder indexes in `templates/<archetype>/index.md`
9. Template files in `templates/<archetype>/`

## Template use
- Treat the templates as ingested archetypes.
- Blend their useful structure to the athlete's sport, recovery, schedule, and target date.
- Keep contest specificity high and adjust the template to the athlete, not the other way around.
- Prefer sport-specific templates when the athlete's goal is clear, and use the general-strength template when the goal is broader or still being defined.
- Before a full template or prep plan, include a disclaimer block that says the content is for educational purposes only, is not medical advice, and should be cleared by a doctor or qualified clinician first.
- When outputting a full template or prep plan, include a short assumptions review so the user can correct bad assumptions before the plan is treated as final.
- When the user submits an existing program, review it against the stated goal and call out obvious mistakes such as too many deadlift days, poor fatigue distribution, or missing peaking specificity.
- When the user uploads a video or asks for technique review, assume they want a form check and route through the form-check references without asking for the lift or angle first unless the clip is too ambiguous to identify.
- Call out confidence limits if camera angle or quality is poor, but do not block the review on follow-up questions when the clip is already usable.
