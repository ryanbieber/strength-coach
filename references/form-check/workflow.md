# Form Check Workflow

## Intake
- Assume the user wants a form check when they upload a video.
- Do not ask for the lift or angle first unless the user did not upload enough information to identify the movement at all.
- If the clip is clear enough, start the review immediately.
- If the clip is ambiguous, state the uncertainty and only then ask the minimum needed follow-up.

## Evaluation Steps
1. Identify the lift and rep phase.
2. Note the setup, bar path, joint positions, and timing.
3. Compare the clip to the lift-specific rubric.
4. Call out the biggest issue first if there is one.
5. Decide whether the problem is technique, setup, load choice, fatigue, or camera angle.
6. If the clip is too noisy or the angle is bad, say so and limit the confidence of the review.

## Model Strategy
- Use a vision model to describe what is visible in the clip.
- Use movement standards and known-good examples as the reference frame.
- Homography can help normalize camera angle, but it is only preprocessing.
- The actual review should focus on motion, positions, and timing.
