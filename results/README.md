# Results

This folder contains selected evaluation results from the stroke risk prediction project.

## 1. Baseline Model Performance

Five individual machine learning models were first evaluated using their baseline configurations:

- K-Nearest Neighbors
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost

Detailed baseline results are available in [`baseline_model_performance.csv`](baseline_model_performance.csv).

## 2. Optimized Models and Final Stacking

The five individual models were optimized using Optuna.

Based on the optimized performance, the three best-performing models were selected as base learners for the stacking ensemble:

- K-Nearest Neighbors
- Random Forest
- XGBoost

Random Forest was used as the meta learner.

Detailed optimized model and final stacking results are available in [`optimized_and_stacking_performance.csv`](optimized_and_stacking_performance.csv).

## Evaluation Metrics

All models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Specificity
- Matthews Correlation Coefficient (MCC)
- ROC AUC
