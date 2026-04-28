# Tree-of-Thought Prompt

## What is Tree-of-Thought?
The model explores multiple possible answers, gives a reason for and against each, then picks the best one.

## Prompt Used

You are a customer support classifier. Classify the complaint into:
Billing | Technical Issue | Delivery | Refund | Other

Explore at least 3 possible categories this complaint could belong to.
For each give a reason FOR and a reason AGAINST.
Then pick the best one.

Complaint: "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

## Output Received

Path 1 - Delivery:
FOR: The complaint is about an item not arriving. Clearly a logistics issue.
AGAINST: Could overlap with Technical Issue if the tracking page itself is broken.

Path 2 - Technical Issue:
FOR: Tracking page shows no update could mean a website bug.
AGAINST: The real complaint is about a missing package, not a broken website.

Path 3 - Refund:
FOR: Customer may want a refund for an undelivered item.
AGAINST: They have not asked for a refund. They want the item delivered.

Best path: Delivery

Category: Delivery

## Analysis

- Correct answer: Yes
- Reasoning shown: Yes, very deep
- Best used when: Task is genuinely ambiguous and you need a well-reasoned decision
- Weakness: Slowest and most expensive technique
