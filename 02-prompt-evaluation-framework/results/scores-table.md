# All Scores Compared

Task: Write a professional email to a client explaining a project delay.
Model used: Claude 3 / GPT-4
Scoring method: LLM-as-Judge using eval_rubric.md

## Score Table

| Prompt Version | Accuracy | Tone | Format | Completeness | Total out of 40 |
|---|---|---|---|---|---|
| V1 Basic | 6 | 5 | 5 | 6 | 22 |
| V2 Roleplay | 8 | 9 | 7 | 8 | 32 |
| V3 Structured | 9 | 8 | 10 | 9 | 36 |
| V4 Detailed | 8 | 8 | 8 | 9 | 33 |
| V5 Chain-of-Thought | 9 | 9 | 8 | 10 | 36 |

## Score Improvement from V1 to Best Version

- Accuracy improved from 6 to 9 — 50 percent improvement
- Tone improved from 5 to 9 — 80 percent improvement
- Format improved from 5 to 10 — 100 percent improvement
- Completeness improved from 6 to 10 — 67 percent improvement
- Total improved from 22 to 36 — 64 percent overall improvement

## Key Observation

The biggest improvement came simply by adding structure to the prompt.
V1 gave the model no guidance. V3 gave it a numbered checklist.
That single change improved the total score by 14 points.

This proves that prompt structure is more important than prompt length.
