
## Learning Analytics Dashboard for Writing Improvement
This project analyses how different types of AI feedback influence student writing improvement.
It builds directly on the Multi-Persona AI Writing Assistant by examining the outcomes of feedback rather than the generation process itself.

The focus is on learning analytics, feedback quality, and behavioural change in writing.

## Related Project

This project is part of a two-stage research pipeline.

• Project 1: Multi-Persona AI Writing Assistant (Feedback Generation)
👉[ https://github.com/YOUR_GITHUB_USERNAME/Multi-Persona-AI-Writing-Assistant](https://github.com/ijaycyndy/Multi-Persona-AI-Writing-Assistant.git)

Project 1 generates structured AI feedback using multiple personas.
This repository focuses on analysing how that feedback affects writing quality.

## Open in Google Colab

Use the button below to run the full analysis notebook in Google Colab.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/PROJECT2_REPO_NAME/blob/main/writing-feedback-learning-analytics.ipynb)


## Project Motivation

Most AI writing tools provide feedback, but few evaluate whether that feedback actually helps learners improve.

This project asks:

• How does student writing change after receiving AI feedback?
• Which feedback personas lead to clearer structure or stronger arguments?
• What trade-offs exist between clarity, structure, and readability?

The aim is to move from feedback generation to evidence-based evaluation.

## Data Source

The dataset is derived from Project 1 (multi_persona_writing_assistant).

Each record includes:

• Original student paragraph
• AI persona providing feedback (critic, explainer, supporter, planner, combined)
• Feedback text
• Before-and-after writing metrics

This creates a small but traceable learning dataset suitable for exploratory analysis.

## What This Project Contains

• A cleaned feedback outcomes dataset
• Derived metrics for writing change, including:

clarity score difference

structure score difference

argument strength difference

readability change (Flesch score)

word count change

• Exploratory analysis comparing personas
• Visualisations showing average improvement by feedback type

## Key Analyses

The notebook explores:

• Which personas lead to the greatest clarity improvement
• Structural improvement patterns across personas
• Trade-offs between readability and argument strength
• Whether combined feedback outperforms single-persona feedback

All analysis is intentionally transparent and reproducible.

## Educational Relevance

This project aligns with AI for Education research by:

• Treating feedback as an educational intervention
• Measuring learner response rather than model output quality alone
• Demonstrating how learning analytics can evaluate AI-supported writing tools

The work reflects real challenges in designing feedback that is both helpful and cognitively appropriate for learners.

## Files in This Repository

• learning_analytics_dashboard.ipynb – Full analysis notebook
• persona_feedback_outputs.csv – Input dataset from Project 1
• README.md – Project documentation

## Notes on Scope

This is an exploratory study using a small dataset.
Results are not intended to be generalised, but to demonstrate method, reasoning, and evaluation design.
