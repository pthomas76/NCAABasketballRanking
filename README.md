## NCAA Division 1 College Basketball Team Ranker

### Introduction/Background 

### Problem Definition

In the NCAA, the winner of the basketball tournament is the college team (from Division 1) that scores the most points. Using a dataset, factors such as number of games played, wins, offensive/defensive efficiency, rebound rate, turnover rate and free throw rate, will be used to create a team ranking system for each season. The goal of this project is to predict the top 10 teams over multiple seasons by evaluating the efficiency of the system. 

### Methods 

The method we plan to use to solve this problem falls under supervised learning, specifically using a multi-layer perceptron (MLP) and gradient descent to train the model. We will parameterize the neural network using 3 layers and ReLU activations after each layer. The loss will be defined as an L2 loss over the estimated power ranking score and the labeled power ranking score. Each of the numerical features will be inputted directly to the model while the categorical features will receive a numerical encoding. All these features will be merged together to form one input vector to the model of fixed dimension. If we have additional time, we plan to study using Linear Regression and comparing the performance of our MLP model with a less complex technique.

### Potential results & discussion 

### References

### Timeline