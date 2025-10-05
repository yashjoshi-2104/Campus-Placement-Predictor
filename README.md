# Campus-Placement-Predictor
This project predicts whether a student gets placed after college using a Logistic Regression model. It explores academic, technical, and soft-skill factors affecting placement.

1. Preprocessing

Dropped College_ID as irrelevant.

Converted categorical columns (Internship_Experience, Placement) to numeric (1/0).

Split dataset (70/30) into training/testing.

Scaled numeric columns 

2. Model

Algorithm: Logistic Regression 

Parameters: max_iter=1000

Goal: Predict Placement

3. Results

Accuracy	0.90

Precision (Placed)	0.76

Recall (Placed)	0.61

The model shows 90% overall accuracy but needs recall improvement for placed students.

4. Visualizations

Confusion matrix.

ROC curve & AUC score.

Feature importance (coefficients heatmap).
