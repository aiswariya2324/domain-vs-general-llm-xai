# Domain-Specific LLM vs General LLM in Explainable AI (XAI)

## Overview

This repository contains the implementation developed for my MSc dissertation, which investigates the effectiveness of domain-specific and general-purpose Large Language Models (LLMs) for generating human-understandable explanations in Explainable Artificial Intelligence (XAI).

The project uses the Framingham Heart Study dataset to build an XGBoost model for cardiovascular disease risk prediction. SHAP (SHapley Additive exPlanations) is used to generate feature-level explanations, which are then provided as structured prompts to different LLMs. The generated explanations are evaluated using both automated metrics and human assessment.

---

## Research Objectives

- Develop an interpretable cardiovascular disease prediction model.
- Generate local feature explanations using SHAP.
- Compare domain-specific and general-purpose LLMs for explanation generation.
- Evaluate explanation quality using automated metrics and statistical analysis.
- Investigate whether domain-specific LLMs produce more faithful and clinically meaningful explanations.

---

## Methodology

The project follows the workflow below:

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. XGBoost model development
4. Hyperparameter optimisation using Optuna
5. SHAP explanation generation
6. Prompt engineering
7. LLM explanation generation
8. Automated evaluation
9. Human evaluation
10. Statistical significance testing

---

## Technologies Used

- Python
- XGBoost
- SHAP
- Optuna
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Hugging Face Transformers
- Mistral
- Jupyter Notebook

---

## Repository Structure

```
.
├── notebooks/
├── data/
├── outputs/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Dataset

This project uses the Framingham Heart Study dataset.

The dataset is used solely for academic research purposes.

---

## Current Status

This repository is under active development as part of an MSc dissertation.

Future updates will include:

- Code refactoring into Python modules
- Additional evaluation experiments
- Improved documentation
- Final dissertation results

---

## Author

MSc Dissertation Project

University of Stirling

2026
