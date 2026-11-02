# Model Training and Evaluation

This project implements and evaluates three distinct machine learning classifiers on a benchmark dataset using Scikit-Learn.

## 1. Selected Models
- **Logistic Regression:** Linear baseline with feature scaling ($C=1.0$).
- **Random Forest:** Ensemble of decision trees ($n\_estimators=100, max\_depth=5$).
- **K-Nearest Neighbors (KNN):** Distance-based non-parametric classifier ($k=5$).

## 2. Evaluation Results (Test Set)
- **Logistic Regression:** Accuracy: 0.9825, F1 Score: 0.9861
- **Random Forest:** Accuracy: 0.9561, F1 Score: 0.9655
- **K-Nearest Neighbors:** Accuracy: 0.9561, F1 Score: 0.9655

## 3. Best Performing Model
Logistic Regression performed best due to standardized features and strong linear separability of the dataset classes.
