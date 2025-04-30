## Credit Card Fraud Detection

This repository contains a machine learning model designed to detect fraudulent credit card transactions. 
The model is built using **Logistic Regression**, a binary classification algorithm, to predict whether a transaction is fraudulent or not based on various features.

Key Features:
Data Preprocessing: Missing values and outliers are handled before training.
Class Imbalance Handling: SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the class distribution.
Model Evaluation: The model’s performance is evaluated using a confusion matrix, classification report, and accuracy score.

Dataset:
The dataset used in this project is provided by Kaggle and contains 284,807 transactions, of which only 0.17% are fraudulent. 
You can find the dataset here https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

Requirements: 
pandas, 
numpy,  
imbalanced-learn, 
scikit-learn,  
matplotlib,  
seaborn 

Results:
After training, the model achieves:
Accuracy: 99.91%
Recall: 69.39% (on fraud class)
Precision: 82.61% (on fraud class)

Future Improvements:
1. Experiment with other classification algorithms
2. Optimize model thresholds for better recall
3. Implement feature selection or engineering to improve performance



