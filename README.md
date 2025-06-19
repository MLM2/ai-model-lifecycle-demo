# AI Model Lifecycle Demonstrator: Design, Development & Governance

This repository demonstrates the complete AI model development lifecycle, including data preprocessing, model training, fairness evaluation, and explainability analysis. The project reflects best practices aligned with the NIST AI Risk Management Framework and ODNI Responsible AI guidance.

## Structure

- `data/`: UCI Adult Income dataset
- `notebooks/`: Jupyter notebooks for each phase of model development
- `model/`: Saved trained models
- `model_card.md`: Documentation describing the model's purpose, risks, and governance attributes

## Notebooks

This project includes end-to-end demonstration notebooks for designing, developing, and governing AI models responsibly:

- `01_data_preprocessing.ipynb`: Clean and prepare the UCI Adult Income dataset.
- `02_model_training.ipynb`: Train a Random Forest classifier to predict income levels.
- `03_fairness_evaluation_fairlearn.ipynb`: Use Fairlearn to assess and report disparities by gender.
- `04_explainability_shap.ipynb`: Visualize feature influence using SHAP (SHapley values) for explainable AI.

Each notebook reflects key stages of the AI lifecycle, with an emphasis on fairness, transparency, and alignment with the [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) and ODNI Responsible AI objectives.

## Tools

- scikit-learn
- pandas
- Fairlearn
- SHAP
- matplotlib

## Objective

Train a model to predict whether an individual's income exceeds $50K based on demographic features, while analyzing and mitigating bias.

## Alignment

This project is designed to demonstrate skills relevant to the SAIC ODNI AI Policy Engineer role, including responsible AI implementation, model fairness, and transparent documentation.
