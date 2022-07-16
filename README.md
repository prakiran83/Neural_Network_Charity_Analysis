# Neural_Network_Charity_Analysis

## Overview
The purpose of this project is to use deeplearning neural networks with TensorFlow platform to analyze success rate of charitable donations.

We will be using following methods for this project:
1. preprocessing the data for the neural network model,
2. compiling, training, and evaluating the model,
3. optimizing the model.

## Results

![1](https://user-images.githubusercontent.com/100887673/179371162-6ba72589-8bec-4805-9071-4998c5289c80.png)

1. The columns EIN and NAME are identification information and have been removed from the input data.
2. The column IS_SUCCESSFUL, which will be considered as the main component of our deeplearning neural network, shows if the charity donation was properly used or not. 
3. The rest of the columns are the featues of the model.

![2](https://user-images.githubusercontent.com/100887673/179371877-0b9bf4c1-986b-4cfa-b759-5db4f7f580f3.png)

4. This model is made of 2 hidden layers with 80 & 30 neurons.

![3](https://user-images.githubusercontent.com/100887673/179371914-f5d7aa30-3098-4b80-b11e-c7902e210859.png)
5. The model accuracy is less than 75%.

## Summary
This model did not reach the target of 75% accuracy so we can say that the model is not performing optimally.
