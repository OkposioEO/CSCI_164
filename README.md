Summary

This project focuses on building and evaluating multiple machine learning models using the scikit-learn library on the Iris dataset. The goal is to demonstrate a complete machine learning workflow, from data preprocessing to model comparison and interpretation.

The analysis begins with data exploration and visualization, including pairplots to understand feature relationships and class separation. The dataset is then split into training, validation, and test sets, followed by feature scaling to ensure consistent model performance.

Three supervised learning models were implemented:

Logistic Regression (using stochastic gradient descent)
K-Nearest Neighbors (KNN)
Multilayer Perceptron (MLP)

Each model was optimized using grid search with cross-validation to identify the best hyperparameters. Model performance was evaluated using multiple metrics, including accuracy, precision, recall, F1-score, and AUC.

To ensure robustness, 5-fold stratified cross-validation was used, and results were visualized using boxplots, confusion matrices, and ROC curves. A final comparison between training and test performance was conducted to assess generalization and detect overfitting.

Overall, this project highlights the importance of model selection, hyperparameter tuning, and proper evaluation techniques in building reliable machine learning models.
