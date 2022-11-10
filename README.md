# Neural_Network_Charity_Analysis
## Overview 
The non profit company, Alphabet Soup is looking for a way to vet potential charities that the company plans on donating too that are not going to be a scam. To do this, we created a deep learning neural network to interpret the data and give a prediction about the charities.

## Results
- I selected 120 neurons with a sigmoid function for my first layer, 50 nuerons with a ReLU function for the second, and 18 neurons with for the third, and a sigmoid function for the outer layer. I chose to change the activation function for the first layer because it increased the model's performance.
- I only achieved an accuracy of 67% after the optimizations and was not able to achieve the target model performance.
- I tried to increase the model performance by dropping more columns, creating more bins for rare occurances in columns, decreasing the number of values in some bins,    adding more neurons to the hidden layers, using a differnet activation function, and increasing the number of epochs.

## Summary
the accuracy of my optimized model for predicting whether a donation is successful ended up being 0.6679 and its loss metric was 1.5166.

## Recommendation
Using a random forest model could yield a more accurate result and model.
