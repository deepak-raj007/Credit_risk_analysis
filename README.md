# Credit risk analysis
Credit risk analyzing using Machine Learning (Supervised learning-Classification)
Credit Risk Analysis
This GitHub repository contains code for a machine learning classification project aimed at predicting loan status as either approved or rejected. The project uses data from Kaggle, which originally belonged to a lending club based in the U.S.

[Data Set](https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset)

The data set used for this project includes a variety of factors that were used to determine loan approval or rejection, such as debt-to-income ratio, income, property owned, and previous defaults. The target column had an imbalance, which was resolved by using oversampling techniques (SMOTE).

Classification Algorithms
Several classification algorithms were trained on the data set, including:

Logistic Regression
Random Forest Classifier
Decision Tree
XGBClassifier
XGBoost
The best model was selected based on its F1 score. GridsearchCV was performed to optimize the hyperparameters of each algorithm. Ultimately, the random forest classifier was determined to be the best model, with an F1 score of 0.74.

Business Interpretation
In addition to selecting the best model, the project also identified the top features that were most important for predicting loan status. This information can be used for business interpretation and decision-making.

To use this repository, simply clone the code and run the Jupyter notebook. The code includes all necessary libraries and functions, as well as detailed explanations of the steps taken in the analysis
