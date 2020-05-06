### Titanic Kaggle Challenge

This notebook contains a solution for the Titanic Kaggle Challenge. 
https://www.kaggle.com/c/titanic/overview

#### About the challenge:

The task is to use machine learning to create a model that predicts which passengers would survive the Titanic shipwreck.

Two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. are provided. 
The 'train.csv' file contains the details of a subset of the passengers on board and reveals whether they survived or not.
The 'test.csv' file contains similar information but does not disclose the outcome for each passenger. The task is to predict these outcomes.


#### About this notebook:

This notebook will start with feature exploration, followed by feature engineering for both train and test datasets. 
Three models - Linear Regression, Random Forest and Linear SVM - will be used to perform GridSearch for best hyperparameters and CrossValidation. A model with the best f1 score will be trained on the full data set and used to make final predictions. 

#### About the result:

A model obtained with the procedure descrived above, scored 0.80861, which corresponds to the top 6% of all submissions.