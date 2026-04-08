# Breast Cancer MCQ Validation

## Overview

This repository contains **200 expert-level multiple-choice questions (MCQs)** on breast cancer, developed for a benchmarking study comparing **human experts vs. LLMs**. Before distributing the questions to 25 expert reviewers, we need a clinical deep-dive validation to ensure every question is accurate and up to date.

**Your task:** Review each MCQ as a clinician and validate whether the classification, treatment, and overall question quality are correct.

---

## Files

| File | Description |
|------|-------------|
| `MCQ_Validation_Interface.html` | Interactive validation tool — open in your browser |
| `08042026_expert_questions_final1.json` | Raw question data (200 MCQs) |
| `README.md` | This file |

---

## How to Use the Validation Tool

### 1. Open the Interface

- Download `MCQ_Validation_Interface.html`
- Double-click to open it in your browser (Chrome, Firefox, or Edge)
- No installation needed — everything runs locally in your browser

### 2. Enter Your Name

- In the left sidebar, enter your name in the **Reviewer** field
- Your name will be saved automatically and included in the export

### 3. Review Each Question

For each MCQ, the interface shows you:

- **Question stem** — the full clinical scenario
- **Answer options (A–E)** — correct answer highlighted in green, wrong options in light orange
- **Rationale & References** — click to expand and see why the correct answer is right, why the others are wrong, and the supporting references

### 4. Validate with 3 Quick Clicks

After reviewing each question, answer these three things:

| # | Question | Options | What to check |
|---|----------|---------|---------------|
| 1 | **Correct answer is right?** | Yes / No | Is the marked correct answer actually correct? Check subtype classification (TNBC, HR+, HER2+, HER2-low), biomarker cutoffs (HR%, HER2 IHC/ISH), and staging |
| 2 | **Wrong options suitable?** | Yes / Partially / No | Are the distractors (wrong answers) clearly wrong? Or could any of them be arguably correct given current guidelines? |
| 3 | **MCQ usable?** | OK / Revise / Reject | Overall verdict — can this question go to the expert panel as is? |

If something is wrong, please leave a **comment** explaining what needs to change.

### 5. Navigate Efficiently

- Use the **sidebar** to jump to any question
- Use **arrow keys** (← →) to move between questions
- Use **keyboard shortcuts**: press `1` = correct answer yes, `2` = distractors yes, `3` = MCQ OK
- Use **filters** (All / Open / OK / Revise / Reject) to focus on unreviewed questions
- Switch to the **Overview** tab to see your progress across all sections

### 6. Take Breaks

Your progress is **saved automatically** in your browser. You can close the tab, shut down your laptop, and come back later — everything will still be there. Just make sure to always use the **same browser**.

### 7. Export Your Results

When you are done (or at any point for a backup):

- Click **Export CSV** in the top right
- A CSV file with all your ratings and comments will download automatically
- Send this CSV file back to us

---

## What to Watch For

Please pay special attention to these clinical nuances:

- **HR-low (1–10%):** These tumors may behave more like TNBC. Check if the question and treatment reflect this
- **HER2-low (IHC 1+ or IHC 2+/ISH−):** Now a targetable category (e.g., T-DXd). Verify classification and treatment options
- **HER2-ultralow (IHC >0 but <1+):** Emerging category — check if questions account for this
- **gBRCA-mutated tumors:** Affects treatment (PARPi eligibility). Ensure this is reflected where relevant
- **Guideline alignment:** Does the correct answer match current guidelines (NCCN, ESMO, AGO, S3)?
- **Outdated treatments:** Has the standard of care changed since the question was written?

---

## Verdict Definitions

| Verdict | Meaning |
|---------|---------|
| **OK** | Clinically accurate and ready for the expert panel |
| **Revise** | Has fixable issues — please describe what needs to change in the comment field |
| **Reject** | Fundamentally flawed or misleading — please explain why in the comment field |

---

## Questions?

If you are unsure about a question or need clarification about the validation process, feel free to reach out.

Thank you for your time — your clinical expertise is essential to making this benchmark reliable!
