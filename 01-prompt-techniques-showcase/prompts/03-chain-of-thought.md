# Chain-of-Thought Prompt

## What is Chain-of-Thought?
You tell the model to think step by step before answering. This improves accuracy on complex tasks.

## Prompt Used

You are a customer support classifier. Classify the complaint below into:
Billing | Technical Issue | Delivery | Refund | Other

Think through your reasoning step by step before giving your final answer.

Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

## Output Received

Step 1: The customer mentions an order that has not arrived. This is about a physical shipment.
Step 2: They mention a tracking page with no update. This confirms a delivery issue.
Step 3: There is no mention of billing, a refund request, or a software problem.
Conclusion: This is a Delivery issue.

Category: Delivery

## Analysis

- Correct answer: Yes
- Reasoning shown: Yes, fully visible
- Best used when: Task is complex or needs explainability
- Weakness: Output is longer, not ideal if you only want one word
