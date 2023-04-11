# Neural_Network_Charity_Analysis

## Purpose of the analysis.
Based on our dataset and maschine learning and neural network teqnique we need to figire it out if any new applicants who will be sponcored(funded) by a certain organization will be successful. Our dataset contains information about 34,000 organiations who previosly recieved fundings from same company, so we can use this data to train our neural network and make predictions.

## Results.

What variable(s) are considered the target(s) for your model?
If application will be successfull, that is my target variable,thats what we are trying to predict.

What variable(s) are considered to be the features for your model?
The features for my model will be application type, income, special consideration, anything that is involved in training maschine model.

What variable(s) are neither targets nor features, and should be removed from the input data?
Identification variables such as EIN or Name can be removed.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I have selected 2 hidden layers for this model, 110 neurons (80 in the first layer and 30 in the second), and ReLu activation function. all those parameters were chosen to try to acchive higher accuracy.

Were you able to achieve the target model performance?
No, closest i got was 72%

What steps did you take to try and increase model performance?
I tried 3 different options:
1. Increase the number of epochs from 100 to 500, got same accuracy rate.
2. Updated the number of hidden nodes in the first hidden layer to 100, and got same results.
3. Changed activation function from ReLu to Leaky Relu, and got even lower accuracy rate of 51%.

## Summary.
To be very honset with you i wont be able to give any recomendations on how to improve accuracy score of which method to use. from my observation increasing epochs amount makes maschine run longer, other then that from my research ReLu is considered to be very good option for such model and 70% is not a bad score at all.
