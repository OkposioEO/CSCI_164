Project Summary

This project demonstrates a complete machine learning workflow using the scikit-learn library on two datasets: the Iris dataset and the Breast Cancer dataset.

The analysis is organized into the following Jupyter Notebooks:

iris(2).ipynb → Machine learning analysis on the Iris dataset
breast-cancer-wisconsin-diagnosis(4).ipynb → Machine learning analysis on the Breast Cancer dataset

The datasets used include:

iris.csv
bcancer.csv


⚙️ What This Project Does

Each notebook follows a structured machine learning pipeline:

Data loading and exploration
Data preprocessing (encoding, scaling, splitting)
Model training and evaluation
Hyperparameter tuning using grid search
Cross-validation for performance estimation
Visualization (pairplots, confusion matrices, ROC curves, and comparison plots)



🤖 Models Implemented

The following supervised learning models were applied:

Logistic Regression (using stochastic gradient descent)
K-Nearest Neighbors (KNN)
Multilayer Perceptron (MLP)

Each model was optimized using cross-validation and evaluated using:

Accuracy
Precision
Recall
F1-score
AUC (Area Under the ROC Curve)



📊 Key Features
5-fold stratified cross-validation for reliable performance estimates
Train vs test comparison to detect overfitting
Visualizations for model comparison and interpretation
Clean, reusable helper functions for evaluation



🎯 Goal

The goal of this project is to compare different machine learning models and understand their performance, stability, and ability to generalize to unseen data. It highlights the importance of preprocessing, hyperparameter tuning, and proper evaluation in building effective predictive models.
