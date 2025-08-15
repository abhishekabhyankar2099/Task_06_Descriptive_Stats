# Task 06 – Descriptive Statistics & LLM Comparison(Part 2)

## 📌 Overview
This project is part of Task 6: **Descriptive Statistics and Large Language Models**.  
The goal is to:
- Analyze a sports dataset using Python to generate **ground truth** descriptive statistics.
- Ask the same questions to a **Large Language Model** (Perplexity AI).
- Compare the results to evaluate accuracy, reasoning, and consistency.

## 📂 Dataset
- **Sport:** NBA Basketball (2023–24 Season)
- **Source:** [Basketball Reference](https://www.basketball-reference.com/)
- **Format:** Excel (`.xlsx`)
- **Columns Used:** Player name, games played, points, assists, rebounds, turnovers, FG%, triple-doubles, awards.

## 🔍 Summary
- Tested **10 questions**, ranging from simple factual retrieval to complex reasoning.
- Python results served as the **ground truth**.
- Perplexity AI achieved **7/10** accurate or mostly accurate responses.
- Main differences were caused by:
  - Different metric definitions
  - Threshold assumptions
  - Handling of special cases (e.g., infinite ratios)

## 🚀 Next Steps
- Expand to advanced metrics and team-level summaries.
- Include visualizations for interpretation by LLM.
- Prepare a conversational **"AI Street Interview"** narration of findings.
