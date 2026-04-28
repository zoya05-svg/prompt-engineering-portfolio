# 🧠 Project 1 — Prompt Techniques Showcase

A structured comparison of 6 prompting techniques applied to the **same real-world task**: customer complaint classification.

Each technique is tested on identical inputs. Outputs are compared and scored on accuracy, clarity, and format.

---

## 🎯 Task Used for All Techniques

**Task:** Classify a customer complaint into one of these categories:
`Billing` | `Technical Issue` | `Delivery` | `Refund` | `Other`

**Input used:**
> "I ordered a laptop 2 weeks ago and it still hasn't arrived. The tracking page shows no update since Day 1."

---

## 📂 Files

| File | Description |
|---|---|
| `prompts/01-zero-shot.md` | No examples given to the model |
| `prompts/02-few-shot.md` | 3 examples given before the task |
| `prompts/03-chain-of-thought.md` | Model asked to reason step by step |
| `prompts/04-tree-of-thought.md` | Model explores multiple reasoning paths |
| `prompts/05-structured.md` | Output format strictly enforced |
| `prompts/06-role-based.md` | Model given a persona/role |
| `outputs/comparison-table.md` | Side-by-side output comparison + scores |
| `analysis.md` | Full written analysis of findings |

---

## 📊 Quick Results Summary

| Technique | Correct Category? | Format Quality | Reasoning Shown |
|---|---|---|---|
| Zero-Shot | ✅ Yes | ⭐⭐⭐ | ❌ No |
| Few-Shot | ✅ Yes | ⭐⭐⭐⭐ | ❌ No |
| Chain-of-Thought | ✅ Yes | ⭐⭐⭐⭐ | ✅ Yes |
| Tree-of-Thought | ✅ Yes | ⭐⭐⭐⭐⭐ | ✅ Yes |
| Structured | ✅ Yes | ⭐⭐⭐⭐⭐ | ❌ No |
| Role-Based | ✅ Yes | ⭐⭐⭐⭐ | ✅ Partial |

---

## 🛠️ Tools Used

- **Model:** Claude 3 / GPT-4
- **Language:** Python (optional scripts in `/scripts` if added later)
- **Format:** Markdown documentation
