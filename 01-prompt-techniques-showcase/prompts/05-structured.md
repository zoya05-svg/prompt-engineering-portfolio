# Structured Output Prompt

## What is Structured Prompting?
You force the model to reply in a fixed format like JSON. Output can be used directly in code.

## Prompt Used

Classify the customer complaint below.
Reply ONLY in this exact JSON format with no extra text:

{
  "category": "one of: Billing, Technical Issue, Delivery, Refund, Other",
  "confidence": "High, Medium, or Low",
  "reason": "one sentence explanation"
}

Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

## Output Received

{
  "category": "Delivery",
  "confidence": "High",
  "reason": "The package has not arrived after 2 weeks and tracking shows no progress, indicating a delivery failure."
}

## Analysis

- Correct answer: Yes
- Reasoning shown: Brief
- Best used when: Building apps where output feeds into a system or database
- Advantage: Output is machine-readable, no parsing needed
