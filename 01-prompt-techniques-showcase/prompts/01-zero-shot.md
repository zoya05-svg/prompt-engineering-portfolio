# Zero-Shot Prompt

## What is Zero-Shot?
No examples are given. The model uses only its training to answer.

## Prompt Used

Classify the following customer complaint into exactly one of these categories:
Billing | Technical Issue | Delivery | Refund | Other

Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

Reply with only the category name.

## Output Received

Delivery

## Analysis

- Correct answer: Yes
- Reasoning shown: No
- Best used when: The task is simple and clear
- Weakness: If complaint is unclear, it fails silently with no explanation
