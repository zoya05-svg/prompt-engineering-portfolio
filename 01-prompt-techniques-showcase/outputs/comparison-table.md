# Output Comparison Table

All 6 techniques tested on the same complaint:
"I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

| Technique | Output | Correct? | Reasoning? | Token Cost |
|---|---|---|---|---|
| Zero-Shot | Delivery | Yes | No | Low |
| Few-Shot | Delivery | Yes | No | Low |
| Chain-of-Thought | Delivery with steps | Yes | Yes full | Medium |
| Tree-of-Thought | Delivery with 3 paths | Yes | Yes deep | High |
| Structured | JSON with confidence | Yes | Brief | Medium |
| Role-Based | Category plus next action | Yes | Partial | Medium |

## Key Takeaway

All techniques got the correct answer on this clear complaint.
The real differences show when the complaint is ambiguous.

- Ambiguous complaint: Use Chain-of-Thought or Tree-of-Thought
- Need output in code: Use Structured
- Need next steps: Use Role-Based
- Need speed and low cost: Use Zero-Shot or Few-Shot
