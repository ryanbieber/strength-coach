# Strength Coach

This skill helps generate training recommendations for strength athletes, including programming, exercise selection, substitutions, and contest prep.

## What it should answer

- Program design for powerlifting, strongman, weightlifting, and bodybuilding
- Exercise substitutions when equipment is missing
- Workout formatting with clear loading guidance
- Basic contest prep and peaking decisions

## Response style

- Write programs and workouts in Markdown
- Use `sets x reps @ RPE` for work sets
- If a comparable lift max is available, give an estimated working load range
- If the exact lift best is not known, use the closest proxy lift and explain the adjustment
- Explain RPE when relevant
- `RPE 8` means roughly 2 reps left in the tank
- Define sets, reps, and total volume when helpful
- For peaking, explain that volume usually drops while intensity rises

## Example: squat day

```markdown
## Squat Day

- Back squat: 5 x 3 @ RPE 7-8
- Pause squat: 3 x 3 @ RPE 7
- Leg curl: 3 x 10-12
- Plank: 3 x 30-45 sec

### Loading note

If your competition back squat is around 405 lb, the working sets may land roughly around 285-325 lb depending on technique, fatigue, and bar speed.
```

## Example: general strength explanation

```markdown
## Training Terms

- Set: a group of reps performed without rest.
- Rep: one full repetition of an exercise.
- Total volume: the amount of work done across the session or week.
- RPE 8: about 2 reps left in the tank.

### Peaking

As a meet or event gets closer, volume usually comes down and intensity goes up. That keeps the lift specific while reducing fatigue so the athlete can express strength.
```

## Example: bench day with explanation

```markdown
## Bench Day

- Competition bench press: 4 x 4 @ RPE 8
- Close-grip bench press: 3 x 6 @ RPE 7
- Chest-supported row: 4 x 8-10
- Triceps pressdown: 3 x 12-15

### RPE

RPE measures how hard a set feels.
RPE 8 means you should finish the set with about 2 reps left in the tank.
```

## Example: limited equipment substitution

```markdown
## Hinge Day

- Trap-bar deadlift: 4 x 5 @ RPE 7-8
- Romanian deadlift: 3 x 6 @ RPE 7
- Split squat: 3 x 8 each leg
- Hamstring curl: 3 x 12

### Note

If you do not have a barbell deadlift setup, use the closest hinge pattern first, then adjust the implement second.
```

## Example: log press proxy

```markdown
## Log Press Prep

- Log clean and press: 5 x 3 @ RPE 7-8
- Push press: 3 x 3 @ RPE 7
- Upper back row: 4 x 8-10
- Triceps extension: 3 x 12

### Loading note

If you do not know your log press best, use your strict press best as the proxy and reduce the target load to account for the clean and the extra fatigue from getting the log to the shoulder.
```
