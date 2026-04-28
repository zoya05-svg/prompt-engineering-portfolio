# Analysis — What I Learned

## Overview
This project tested 6 prompting techniques on one customer complaint classification task.
Goal: understand the tradeoffs of each technique, not just get the right answer.

## Finding 1 — All techniques worked on a clear complaint
When a complaint is obvious, even zero-shot works fine.
Technique choice matters most on ambiguous or complex inputs.

## Finding 2 — Structured prompting is best for real applications
Any system where output feeds into code needs structured prompting.
JSON output with a confidence score is far more useful than plain text.

## Finding 3 — CoT and ToT are best for explainability
In regulated industries you need to explain why a decision was made.
Chain-of-Thought and Tree-of-Thought make reasoning auditable.

## Finding 4 — Role-Based prompting adds unexpected value
Giving the model a senior analyst persona caused it to include a next action recommendation without being asked. Very useful in customer service automation.

## Finding 5 — Token cost is a real tradeoff

| Technique | Approx Output Tokens |
|---|---|
| Zero-Shot | 5 |
| Few-Shot | 5 |
| Chain-of-Thought | 80 |
| Tree-of-Thought | 150 |
| Structured | 50 |
| Role-Based | 60 |

At scale, technique choice has a direct cost impact.

## Conclusion
There is no single best technique. The right choice depends on:
- Task complexity: simple vs ambiguous
- Output destination: human vs machine
- Explainability needs: does someone need to audit the reasoning?
- Cost constraints: how many tokens can you afford?

This judgment is the core skill of a prompt engineer.
