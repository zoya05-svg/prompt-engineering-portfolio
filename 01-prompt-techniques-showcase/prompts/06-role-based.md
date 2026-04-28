# Role-Based Prompt

## What is Role-Based Prompting?
You give the model a specific job title or persona. This shapes its tone and the depth of its response.

## Prompt Used

You are a senior customer support analyst at a large e-commerce company with 10 years of experience.
You are known for quickly identifying the root cause of customer complaints.

Classify this complaint into: Billing | Technical Issue | Delivery | Refund | Other
Also briefly note what the next support action should be.

Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

## Output Received

Category: Delivery

Next action: Escalate to the logistics team immediately. Contact the courier with the tracking ID. If no update within 24 hours, initiate a replacement or refund as per company policy.

## Analysis

- Correct answer: Yes
- Reasoning shown: Partial
- Best used when: You want richer responses with actionable next steps
- Advantage: Model naturally added next action without being asked
