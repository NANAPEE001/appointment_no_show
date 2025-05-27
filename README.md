# Patient No-Show Prediction

This project predicts whether a patient will show up for a medical appointment using machine learning.
It uses features like Gender, Age,Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handicap, SMS_received, and Showed_up.

Three classification models: Logistic Regression, Random Forest, and XGBoost were implemented.
The goal is to help hospitals reduce missed appointments by identifying high-risk patients in advance.
Data preprocessing included encoding categorical variables and handling class imbalance.
Each model was evaluated using accuracy, precision, recall, and F1 scores.
XGBoost and Random Forest generally outperformed Logistic Regression in predictive accuracy.
Feature importance analysis was done to show strong predictors.

After classification, we applied K-Means clustering to identify patterns in patient behavior.
The elbow method was used to choose the optimal number of clusters.
Cluster analysis revealed segments of patients with high no-show rates.

This information can be used for targeted reminder strategies or patient outreach.
The project is implemented in Python using pandas, scikit-learn, and xgboost libraries.

This work provides a useful foundation for improving healthcare appointment management through data science.


