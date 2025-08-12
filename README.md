# Predicting-CS-GO-game-outcome

Goal: Predict whether the Counter-Terrorists (CT) or Terrorists (T) win a round in Counter-Strike: Global Offensive using round-level match data.

# Dataset used: https://www.kaggle.com/datasets/christianlillelund/csgo-round-winner-classification

# Workflow
Data Preprocessing

Stratified train-test split (80/20)

Encode target (CT=0, T=1)

Convert booleans to numeric (bomb_planted)

One-hot encode map

Robust scaling to handle outliers

# Model Used

Logistic Regression

Evaluation Metrics

Accuracy: 75.0%

Precision, Recall, F1-score

ROC-AUC Score: ~0.75

Confusion Matrix for class-wise performance
