## Aerial Cactus Identification

This notebook contains a solution for the Aerial Cactus Identification Challenge.
https://www.kaggle.com/c/aerial-cactus-identification

### About the challenge:

Create an classifier that can identify a specific type of cactus in aerial imagery.


### About this notebook:

This notebook will use Keras Sequential Model with five hidden layers with ReLU and an output layer with a sigmoid activation function. Images will be preprocessed using three separate DataGenerator classes in keras, each for training, validation and test data. 
 
The code will be executed in a AWS SageMaker notebook. 