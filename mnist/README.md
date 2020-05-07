### Digit Recognizer Challenge

This notebook contains a solution for the Digit Recognizer Kaggle Challenge.https://www.kaggle.com/c/digit-recognizer

#### About the challenge:

The goal of the challenge is to correctly identify digits from a dataset of tens of thousands of handwritten images.


#### About this notebook:


The problem was tackled using keras Sequential model with 5 hidden layers and an output layer with the SoftMax activation function. Data was preprocessed and augmented using DataGenerator class from keras framework. 

A simple grid search for hyperparameter tuning was implemented. 

The configuration of the model with the best validation accuracy score was then used to make predictions. 

This solution prepared in a AWS SageMaker notebook.


#### About the result:

 The solution presented in this notebook showed a result corresponding to top 12 % of submissions on the leaderboard.