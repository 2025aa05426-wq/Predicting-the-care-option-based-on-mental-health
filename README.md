# Predicting-the-care-option-based-on-mental-health
# Problem Statement - 
The given dataset is a mental-health-related survey containing multiple categorical attributes such as work environment, stress factors, mood indicators, and personal habits. The target variable chosen for this task is CareOptions, a multi-class label describing what type of mental-health care options an individual prefers.
# Dataset Description -
Dataset Name: Mental Health dataset

Source: https://www.kaggle.com/datasets/alamshihab075/mental-health-dataset?select=Mental+Health+dataset1.csv

Target Variable: CareOptions (Multi-class) 

Features: The dataset contains 16 categorical attributes like Gender, Country, Occupation, Treatment, Family history and many more. Number of samples: 261328 

Number of features: 16

Problem type: Multi-class classification

# Models Used -
| ML Model            | Accuracy | AUC | Precision | Recall | F1 | MCC |
| ------------------- | -------- | --- | --------- | ------ | -- | --- |
| Logistic Regression | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |
| Decision Tree       | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |
| KNN                 | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |
| Naive Bayes         | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |
| Random Forest       | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |
| XGBoost             | ✓        | ✓   | ✓         | ✓      | ✓  | ✓   |

Model	Observation -
Logistic Regression: Simple baseline, fast but limited by linearity
Decision Tree:	Overfits, sensitive to data splits
KNN:	Sensitive to high dimensionality
Naive Bayes:	Fast but independence assumption limits accuracy
Random Forest:	Strong performance, robust to overfitting
XGBoost:	Best overall performance with highest macro-F1

Best Model: XGBoost achieved the best overall performance with the highest macro-F1 score and ROC-AUC.
