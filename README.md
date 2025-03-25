# Bank Marketing Classifier Comparison (Practical Application III)

This repository contains a Jupyter Notebook project that applies multiple machine learning classification models to a real-world dataset of bank marketing telemarketing contacts. The notebook follows the CRISP-DM process and addresses a practical classification problem.

## Business Objective

Predict whether a client will subscribe to a term deposit based on features collected during past marketing campaigns. This enables more efficient and targeted marketing.

## Files

- `prompt_III.ipynb`: Final Jupyter Notebook with all problem solutions, model evaluations, hyperparameter tuning, and recommendations.
- `data/bank-additional-full.csv`: Raw dataset used for training and evaluation.

## CRISP-DM Process Covered

1. **Business Understanding**: Define objective of predicting subscription.
2. **Data Understanding**: Load and inspect dataset features.
3. **Data Preparation**: One-hot encoding, missing value checks, feature scaling.
4. **Modeling**: Train Logistic Regression, KNN, Decision Tree, and SVM classifiers.
5. **Evaluation**: Use Accuracy, Precision, Recall, F1 Score, and ROC AUC for evaluation.
6. **Deployment & Recommendation**: Final summary of findings and best practices.

## Features

- One-hot encoding of categorical variables
- Scikit-learn-based model training and evaluation
- GridSearchCV for hyperparameter tuning
- Performance metrics visualization
- Runtime and accuracy comparison table