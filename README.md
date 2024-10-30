# Predictive Model for Sex Determination Using Sella Turcica related parameters

## Overview

This repository contains the implementation and evaluation of a supervised machine learning model aimed at predicting sex based on sella turcica (ST) related parameters derived from lateral cephalometric radiographs. The study explores the application of various machine learning algorithms to enhance accuracy in sex determination within forensic and anthropological contexts.

## Methodology

### Data Collection

- **Dataset**: Lateral cephalometric radiographs from 470 patients were used.
- **Features**: The study focused on morphometric assessment of the ST related parameters.
- **Target Variable**: Sex (male or female).

### Machine Learning Algorithms

The following supervised machine learning algorithms were implemented and evaluated:

- Logistic Regression
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Multilayer Perceptron Classifier (MLP)
- Decision Tree
- AdaBoost Classifier
- Random Forest Classifier

### Model Training and Evaluation

- **Training**: Each algorithm was trained using the dataset to predict the sex based on ST measurements.
- **Validation**: 5-fold cross-validation was employed to validate the models.
- **Evaluation Metrics**: Model performance was assessed using the following metrics:
  - Area Under the Curve (AUC)
  - Accuracy
  - Recall
  - Precision
  - F1 Score
  - ROC Curves

---
