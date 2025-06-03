# Logistic Regression - Breast Cancer Classification

## Overview

This project applies Logistic Regression to classify tumors as malignant or benign using the Breast Cancer Wisconsin dataset. The goal is to explore how logistic regression works in binary classification and evaluate model performance using appropriate classification metrics.

---

## Dataset

- Source: Breast Cancer Wisconsin dataset from `sklearn.datasets`
- Features: 30 numeric features derived from tumor images (e.g., radius, texture, perimeter, area)
- Target: 
  - 0 = Malignant
  - 1 = Benign

There are no missing values, and all features are continuous and standardized before modeling.

---

## Objectives

- Implement Logistic Regression using scikit-learn
- Standardize features for model convergence
- Evaluate model using:
  - Confusion matrix
  - Precision, Recall, F1 Score
  - ROC-AUC and ROC curve
- Interpret the sigmoid function and decision threshold

---

## Files Included

- `Day4_LogisticRegression.ipynb`: Jupyter Notebook with all code, evaluations, and visualizations
- `README.md`: This file

---

## Results Summary

- **Accuracy**: High classification accuracy on the test set
- **Precision and Recall**: Both metrics were strong, showing low false positives and false negatives
- **F1 Score**: Balanced performance across classes
- **ROC-AUC**: Near-perfect, indicating strong model discrimination
- **Confusion Matrix**: Very few misclassifications, showing the model is reliable

---

## Conclusion

Logistic Regression proved to be a strong and interpretable model for this binary classification task. Feature scaling was essential, and model evaluation confirmed high performance. The ROC curve and AUC score validated the model’s generalization ability.

Future enhancements could include regularization (L1/L2), threshold tuning, or trying other classifiers (e.g., Random Forest, SVM) for comparison.
