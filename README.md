# ChillarPay AI Support: Zero-Shot vs. Few-Shot Prompting

A fictional FinTech case study evaluating when **zero-shot prompting** is sufficient and how **few-shot prompting** improves AI customer-support ticket triage for **ChillarPay**, a UPI payments app.

---

## Overview

Customer support teams handling UPI payments deal with high-volume, time-sensitive queries—ranging from routine status checks to ambiguous payment failures, mandate issues, and potential fraud or chargeback escalations.

This repository documents an experiment comparing zero-shot and few-shot prompting strategies for triaging incoming support tickets, including:
- **Synthetic support data** representing realistic UPI user scenarios
- **Prompt templates** for zero-shot and few-shot runs
- **AI model outputs** across test cases
- **An evaluation scorecard** measuring classification accuracy, routing precision, format consistency, and edge-case handling

---

## Repository Structure

```text
chillarpay-ai-support-zero-to-few-shot/
├── README.md        # Project overview and evaluation guide
├── data/            # Synthetic UPI customer support tickets
├── prompts/         # Zero-shot and few-shot prompt definitions
├── outputs/         # Model responses for each prompting approach
└── scorecard/       # Evaluation criteria, rubric, and results
