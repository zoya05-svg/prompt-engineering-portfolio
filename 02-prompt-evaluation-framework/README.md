# Project 2 — Prompt A/B Testing and Evaluation Framework

A mini evaluation system where I test multiple versions of a prompt on the same task.
Each version is scored using a rubric based on accuracy, tone, format, and completeness.
Results are presented in a structured report.

## What is LLM-as-Judge?
Instead of manually scoring outputs, I use another LLM call to score each output.
I give the judge model a rubric and ask it to rate the output out of 10.
This is the same method used by real AI companies to evaluate prompts at scale.

## Task Used for This Project
Task: Write a professional email to a client explaining a project delay.

Five different prompt versions were tested on this same task.
Each version was scored on four criteria.

## Files in This Project

| File | What it contains |
|---|---|
| eval_rubric.md | The scoring rubric used to judge outputs |
| prompts/v1-basic.md | Version 1 of the prompt |
| prompts/v2-roleplay.md | Version 2 of the prompt |
| prompts/v3-structured.md | Version 3 of the prompt |
| prompts/v4-detailed.md | Version 4 of the prompt |
| prompts/v5-cot.md | Version 5 of the prompt |
| results/scores-table.md | All scores compared in one table |
| results/winner-analysis.md | Which prompt won and why |

## Final Result Summary

| Prompt Version | Accuracy | Tone | Format | Completeness | Total/40 |
|---|---|---|---|---|---|
| V1 Basic | 6 | 5 | 5 | 6 | 22 |
| V2 Roleplay | 8 | 9 | 7 | 8 | 32 |
| V3 Structured | 9 | 8 | 10 | 9 | 36 |
| V4 Detailed | 8 | 8 | 8 | 9 | 33 |
| V5 CoT | 9 | 9 | 8 | 10 | 36 |

Winner: V3 Structured and V5 CoT tied at 36/40

## Tools Used
- Model: Claude 3 / GPT-4
- Language: Python
- Libraries: Pandas
- Format: Markdown and Jupyter Notebook
