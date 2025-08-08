# Breast Cancer Classification - Model Evaluation

# Today's Progress
Today, I worked on evaluating a Breast Cancer Classification Model using various performance metrics and visualization techniques.

# Steps Completed

### 1. Model Training
- Loaded the Breast Cancer dataset from kaggle.
- Scaled features using `StandardScaler`.
- Trained a Logistic Regression model on the scaled data.

### 2. Model Evaluation Metric
- Confusion Matrix: Evaluated the true positives, false positives, true negatives, and false negatives.
- Classification Report: Generated metrics such as:
  - Precision: How many predicted positives are correct.
  - Recall: How many actual positives are correctly identified.
  - F1-score: Harmonic mean of precision and recall.
- ROC-AUC Score: Measured the model's ability to distinguish between classes.

### 3. Threshold Tuning
- Used `predict_proba()` to get predicted probabilities.
- Evaluated Precision, Recall, and F1-score at multiple thresholds.
- Plotted Precision vs Threshold, Recall vs Threshold, and F1-score vs Threshold to visually choose the best threshold.
- Selected the best threshold that maximizes the F1-score.

### 4. Visualization
- Plotted the metrics vs thresholds for better understanding.
- Compared baseline threshold (0.5) vs tuned threshold performance.


