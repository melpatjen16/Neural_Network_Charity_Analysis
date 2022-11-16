# Neural_Network_Charity_Analysis

## Overview of the analysis: 

The goal of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Utilizing a given dataset of donor activity, the goal is to preprocess the dataset in order to compile, train, and evaluate the neural network model.; design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset; and optimize your model in order to achieve a target predictive accuracy higher than 75%.


## Results: 

### Data Preprocessing

* What variable(s) are considered the target(s) for your model?

Whether funding proves to influence success for those funded. [IS_SUCCESSFUL]


* What variable(s) are considered to be the features for your model?

Variables of focus included whether the application is successful, classification, application_type,   and  both amount variables. 

* What variable(s) are neither targets nor features, and should be removed from the input data?

All variables are considered with the exclusion of EIN, NSME, SPECIAL_CONSIDERATIONS, and STATUS. 


### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

For the model, the accuracy would not go beyond 54%. There were 5 layers in the final model - using the activation modes of rawly, rely, sigmoid, linear, sigmoid, and linear, respectively. 
Below is the code for the units and activations for each layer. 

![Code_Layer](Code_Layer.png)

![Summary_DNN_Model](Summary_DNN_Model.png)

* Were you able to achieve the target model performance?

I increased units and increased the number of layers but ultimately, the model performed similarly. 

![DNN_Model_Accuracy](DNN_Model_Accuracy.png)

Unfortunately, I was unable to achieve the desired accuracy but I believe Tahn may be the missing link. 

* What steps did you take to try and increase model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.