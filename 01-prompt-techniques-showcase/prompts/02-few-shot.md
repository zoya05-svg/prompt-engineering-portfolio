# Few-Shot Prompt

## What is Few-Shot?
You give the model 2 to 4 examples before the real task. This teaches the model the pattern you want.

## Prompt Used

Classify customer complaints into: Billing | Technical Issue | Delivery | Refund | Other

Examples:
Complaint: "My invoice shows a charge I never made."
Category: Billing

Complaint: "The app keeps crashing every time I open it."
Category: Technical Issue

Complaint: "I want to return this product and get my money back."
Category: Refund

Now classify this:
Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."
Category:

## Output Received

Delivery

## Analysis

- Correct answer: Yes
- Reasoning shown: No
- Best used when: You want consistent output format and have good examples ready
- Advantage over zero-shot: More reliable on edge cases
