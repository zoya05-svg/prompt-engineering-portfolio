# Prompt Version 3 — Structured Output

## Prompt Type
Structured. The prompt tells the model exactly what sections to include in the email.

## Prompt Used

Write a professional email to a client explaining a project delay.

The email must include these sections in this order:
1. Greeting using the client name: Sarah
2. One sentence acknowledging the delay
3. Two to three sentences explaining the reason for the delay
4. The new expected delivery date: December 15
5. One sentence apologizing for the inconvenience
6. One sentence assuring quality will not be affected
7. Professional sign-off with name: Zoya

Use formal business English. Keep the total email under 150 words.

## Output Received

Subject: Update on Project Timeline

Dear Sarah,

I am writing to inform you that our project has encountered an unexpected delay.
Due to a critical technical issue discovered during the final testing phase,
we require additional time to ensure all components meet our quality standards.
We have also experienced a brief resource shortage that impacted our timeline.

The revised delivery date is now December 15.

We sincerely apologize for any inconvenience this may cause.
Please be assured that the quality of the final deliverable will not be compromised.

Warm regards,
Zoya

## Scores

| Criteria | Score out of 10 |
|---|---|
| Accuracy | 9 |
| Tone | 8 |
| Format | 10 |
| Completeness | 9 |
| Total | 36 out of 40 |

## What Worked
- Every required section was included
- Format is clean and professional
- Word count was respected
- Giving the model a checklist structure dramatically improved output quality
