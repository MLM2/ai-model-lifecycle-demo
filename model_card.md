# 🧾 Model Card – AI Model Lifecycle Demo

## Overview
This model predicts whether an individual's income exceeds $50K based on UCI Adult Census demographic data. It is intended to demonstrate the full lifecycle of responsible AI development including preprocessing, training, fairness evaluation, and explainability analysis.

## Intended Use
- Demonstrate responsible AI development aligned with governance principles
- Educational demo for explainability (SHAP) and bias evaluation (Fairlearn)
- Support policy discussions around model accountability and risk

## Model Details
- **Model Type**: Random Forest Classifier
- **Framework**: scikit-learn
- **Training Data**: UCI Adult Income Dataset
- **Target Variable**: Binary classification (`>50K` income)

## Evaluation Metrics
- Accuracy, F1-score
- Group fairness metrics using Fairlearn (e.g., demographic parity difference)

## Explainability
- SHAP is used to explain feature contributions at the individual and global level
- Visual summary plots included in Notebook 04

## Risks & Limitations
- Dataset may encode historical biases (e.g., gender income disparities)
- Model performance may not generalize outside the dataset population
- Predictions should not be used for real-world financial decisions

## Risk Mitigation
- Applied fairness metrics and SHAP explainability
- Transparent documentation and Jupyter notebooks
- Demonstrated alignment with the **NIST AI RMF** and **ODNI Responsible AI** goals

## Governance Relevance
This model card supports AI assurance and transparency for policy applications. It aligns with national security and intelligence sector goals for **responsible AI adoption** and **model lifecycle accountability**.

