# ML Pipeline with PCA and Logistic Regression

## Overview
This project demonstrates the use of a machine learning pipeline 
that combines preprocessing and classification in a structured workflow.

The pipeline includes:
- StandardScaler (Feature Scaling)
- PCA (Dimensionality Reduction)
- Logistic Regression (Classification)

## Dataset
Iris dataset from scikit-learn.

The dataset contains 150 samples with 4 numerical features 
used to classify 3 different species of iris flowers.

## Model Workflow
1. Data is split into training and testing sets.
2. Features are scaled using StandardScaler.
3. PCA reduces dimensionality to 2 principal components.
4. Logistic Regression is applied for classification.

## Results
Model accuracy is printed after evaluation.
Classification report includes precision, recall, and F1-score.

## Key Concepts Demonstrated
- Pipeline construction
- Feature scaling
- Dimensionality reduction
- Logistic regression classification
- Model evaluation
