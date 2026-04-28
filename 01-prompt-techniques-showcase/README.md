# Project 1 — Prompt Techniques Showcase

A comparison of 6 prompting techniques applied to the same task: customer complaint classification.

## Task Used for All Techniques

Classify this complaint:
"I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

Categories: Billing | Technical Issue | Delivery | Refund | Other

## Files in This Project

| File | What it contains |
|---|---|
| prompts/01-zero-shot.md | No examples given to model |
| prompts/02-few-shot.md | 3 examples given before task |
| prompts/03-chain-of-thought.md | Model reasons step by step |
| prompts/04-tree-of-thought.md | Model explores multiple paths |
| prompts/05-structured.md | Output forced into JSON format |
| prompts/06-role-based.md | Model given a persona |
| outputs/comparison-table.md | All outputs compared side by side |
| analysis.md | What I learned from this project |

## Results Summary

| Technique | Correct? | Reasoning Shown | Format Control |
|---|---|---|---|
| Zero-Shot | Yes | No | Medium |
| Few-Shot | Yes | No | High |
| Chain-of-Thought | Yes | Yes | Medium |
| Tree-of-Thought | Yes | Yes (deep) | Medium |
| Structured | Yes | Brief | Very High |
| Role-Based | Yes | Partial | High |

## Tools Used
- Model: Claude 3 / GPT-4
- Language: Python
- Format: Markdown
