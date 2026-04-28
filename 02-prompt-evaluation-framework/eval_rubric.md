# Evaluation Rubric

This rubric is used to score every prompt output in this project.
Each output is scored out of 10 on four criteria.
Maximum total score is 40.

## Scoring Criteria

### 1. Accuracy (out of 10)
Does the output correctly complete the task?
- 9 to 10: Perfectly completes the task with no errors
- 7 to 8: Mostly correct with minor issues
- 5 to 6: Partially correct but missing key elements
- Below 5: Incorrect or off-topic

### 2. Tone (out of 10)
Is the tone appropriate for the context?
- 9 to 10: Perfectly professional, empathetic, and appropriate
- 7 to 8: Good tone with minor issues
- 5 to 6: Tone is acceptable but not ideal
- Below 5: Tone is wrong for the context

### 3. Format (out of 10)
Is the output well structured and easy to read?
- 9 to 10: Perfect structure, clear paragraphs, proper greeting and sign-off
- 7 to 8: Good structure with minor formatting issues
- 5 to 6: Some structure but inconsistent
- Below 5: No clear structure

### 4. Completeness (out of 10)
Does the output include all required information?
- 9 to 10: All required elements present and well explained
- 7 to 8: Most elements present
- 5 to 6: Some elements missing
- Below 5: Major elements missing

## How LLM-as-Judge Works

I send this rubric to the model along with each output and ask it to score the output.
The prompt used for judging is:

You are an expert evaluator. Score the following email output based on this rubric:
- Accuracy out of 10
- Tone out of 10
- Format out of 10
- Completeness out of 10

Reply only in this format:
Accuracy: X
Tone: X
Format: X
Completeness: X
Total: X
