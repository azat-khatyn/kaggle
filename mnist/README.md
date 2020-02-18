Performing image recognition task using MNIST handwritten digits dataset. 

The problem was tackled using keras Sequential model with 5 hidden layers and an output layer with the SoftMax activation function. 
Data was processed and augmented using DataGenerator class from keras framework. 

A simple grid search for hyperparameter tuning was implemented. 

The code was executed in a AWS SageMaker notebook.

The configuration of the model with the best validation accuracy score was then used to make predictions. 