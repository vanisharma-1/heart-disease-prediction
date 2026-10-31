# Heart Disease Prediction

Logistic Regression model to predict heart disease from patient data.

## Dataset

Heart Failure Prediction Dataset by fedesoriano (Kaggle):
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

918 patients, 11 features, target is `HeartDisease` (0/1).


## What I did

Checked the data and fixed the zero values in `RestingBP` and `Cholesterol`
Converted text columns to numbers
Train/test split (80/20)
Scaled the features and trained Logistic Regression

## Result

Accuracy on the test set: 88%

No disease: precision 0.88, recall 0.85

Disease: precision 0.88, recall 0.90

Confusion matrix:

Actual no disease: 70 predicted correctly, 12 predicted wrongly as disease
 Actual disease: 92 predicted correctly, 10 missed

## Note

This is a learning project, not for real medical use. Results are from one split only.
