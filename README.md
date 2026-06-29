# Strength Coach Skill

This repo powers the `strength-coach` skill. It helps turn a lifting goal, event timeline, and equipment setup into a concrete program or coaching recommendation.

## Core behavior

- Use the skill files, references, and templates as the source of truth.
- Default to feet for carries and other distance work unless the user explicitly asks for meters.
- Use `sets x reps @ RPE` when giving loading guidance.
- Treat `RPE 7-9` as the normal working range for most productive sets.
- Use near-`RPE 10` sparingly for powerlifting, strongman, and weightlifting when specificity, readiness, or competition practice call for it.
- Use the closest event-specific implement or a close simulation when the exact equipment is missing.

## How it works

1. Identify the sport, goal, timeline, constraints, and available equipment.
2. Choose the main movement pattern first, then select the specific lift or event variation.
3. Use the templates as archetypes and blend them to the athlete's recovery and schedule.
4. Use RPE to adjust load when exact percentages are not available.
5. Keep specificity high as the target date approaches and cut unnecessary fatigue first.

## Programs To Study

The repo keeps sport-specific external-program catalogs in:

- [`templates/general-strength/programs.md`](./templates/general-strength/programs.md)
- [`templates/bodybuilding/programs.md`](./templates/bodybuilding/programs.md)
- [`templates/strongman/programs.md`](./templates/strongman/programs.md)
- [`templates/powerlifting/programs.md`](./templates/powerlifting/programs.md)
- [`templates/weightlifting/programs.md`](./templates/weightlifting/programs.md)

These are reference points for how good programs are structured. They are not copied wholesale into the skill.

## Example request

> For powerlifting, strongman, and weightlifting, getting close to RPE 10 is an important training tool. Use it sparingly.

## Example output

```markdown
Use near-`RPE 10` work sparingly, but do not remove it entirely.

- Powerlifting: occasional top singles or heavy doubles can sharpen meet-specific readiness.
- Strongman: rare near-max event exposures can help rehearse contest demand and confidence.
- Weightlifting: small doses of very heavy singles can reinforce technical exposure if the bar speed and positions stay clean.

Keep most working sets in the `RPE 7-9` range, and reserve `RPE 10` for planned tests, peaking exposures, or contest-specific practice.
```

## Why this matters

The skill is designed to answer like an experienced coach, not a generic template generator. That means:

- precise units by default
- realistic intensity targets
- sport-specific use of heavy work
- clear examples that show how the guidance should look in practice

## Maintenance

If `SKILL.md`, `references/`, or `templates/` change in a way that affects user-facing behavior, update this README in the same change so the summary stays accurate.
