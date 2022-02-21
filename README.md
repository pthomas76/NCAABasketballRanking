## NCAA Division 1 College Basketball Team Ranker

### Introduction/Background 

As a group, we have a strong interest in sports, and wanted to utilize this opportunity to work with the basketball statistics from the 2013-2021 Division 1 college basketball seasons. A college basketball season is broken down into a few segments: non-conference play, conference play, conference tournaments and postseason tournaments. The number of games in conference play varies by conference with the ACC, Big Sky, Big Ten, MAAC, Southland and Sun Belt conferences playing 20-game schedules in 2019-2020 and the Ivy League playing a national-low 14 conference games. The vast amount of game time per season generates several important statistics and performance metrics that we can leverage to determine the quality of each team relative to their opposition and other teams in the nation. 

### Problem Definition

In the NCAA, the winner of the basketball tournament is the college team (from Division 1) that scores the most points. Using a dataset, factors such as number of games played, wins, offensive/defensive efficiency, rebound rate, turnover rate and free throw rate, will be used to create a team ranking system for each season. The goal of this project is to predict the top 10 teams over multiple seasons by evaluating the efficiency of the system. 

### Methods 

The method we plan to use to solve this problem falls under supervised learning, specifically using a multi-layer perceptron (MLP) and gradient descent to train the model. We will parameterize the neural network using 3 layers and ReLU activations after each layer. The loss will be defined as an L2 loss over the estimated power ranking score and the labeled power ranking score. Each of the numerical features will be inputted directly to the model while the categorical features will receive a numerical encoding. All these features will be merged together to form one input vector to the model of fixed dimension. If we have additional time, we plan to study using Linear Regression and comparing the performance of our MLP model with a less complex technique.

### Potential results & discussion 

### References

### Timeline