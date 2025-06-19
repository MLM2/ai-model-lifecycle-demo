# Model Card for AI Income Prediction Model

## Model Details
- **Model type**: Logistic Regression / Random Forest
- **Task**: Binary classification
- **Target variable**: Income > $50K

## Intended Use
- Educational demonstration of AI lifecycle with responsible governance focus.

## Factors
- Sensitive attributes include gender and race.
- Potential bias analyzed with Fairlearn.

## Metrics
- Accuracy, Precision, Recall, Equalized Odds

## Ethical Considerations
- Fairness mitigation required due to historical data biases.
- Transparent communication of limitations essential.

## Caveats
- Trained on UCI Adult dataset only.
- Not suitable for production without further tuning and evaluation.
