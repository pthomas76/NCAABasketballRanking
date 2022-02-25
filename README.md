## NCAA Division 1 College Basketball Team Ranker

### Introduction/Background

We have an interest in sports and want to work with the basketball statistics from the 2013-2021 Division 1 college basketball seasons. The first NCAA Division 1 men’s basketball tournament was played in 1939 and the average men’s D1 team plays 35-40 games in a normal season. A college basketball season is broken down into a few segments: non-conference play, conference play, conference tournaments, and postseason tournaments. The vast amount of game time per season generates several important statistics and performance metrics that we can leverage to determine the quality of each team relative to their opposition. By using data modeling techniques and optimizations, the technical team and subject matters can notice valuable insights and recommendations. [1]

### Problem Definition

In the NCAA Division 1 basketball tournament, the winner is the team that scores the most points over the season. Using a dataset, factors such as the number of games played, the number of wins, offensive/defensive efficiency, rebound rate, turnover rate, and free throw rate, will be used to create a team ranking system for each season. The goal of this project is to predict the top 10 teams over multiple seasons by evaluating the efficiency of the system.

### Methods

The method we plan to use to solve this problem falls under supervised learning, specifically using a multi-layer perceptron (MLP) and gradient descent to train the model. We will parameterize the neural network using 3 layers and ReLU activations after each layer. The loss will be defined as an L2 loss over the estimated power ranking score and the labeled power ranking score. Each of the numerical features will be inputted directly into the model while the categorical features will receive a numerical encoding. These features will be merged together to form one input vector to the model of fixed dimension. If we have additional time, we plan to study using Linear Regression and compare the performance of our MLP model with a less complex technique.

### Potential Results 

Significant effort is spent in forecasting the sporting event outcome. Two important strands of sports forecasting are: to obtain the factors that affect the game result and to learn how these factors can be changed so that profitable results can be obtained. [3]

Having access to data like a win to lose ratio and different statistics of the performance of teams from the 2013 - 2021 seasons, we plan to give weights to these statistics based on current basketball trends and calculate the power rating of each team for the next few seasons. We shall first attempt to calculate the weights for each statistic by following the data trendlines that we already have. For instance, if the game has become more offensive, the adjusted offensive efficiency will have more weightage.

### Discussion

We hope to predict the next top 10 NCAA Division I basketball teams in the country over multiple seasons. The data we generate can not only help predict league and playoff results between college basketball teams but also select teams likely to produce future NBA players.

### References

[1] Sarlis, V., & Tjortjis, C. (2020). Sports analytics — Evaluation of basketball players and team performance. In Information Systems (Vol. 93, p. 101562). Elsevier BV. https://doi.org/10.1016/j.is.2020.101562

[2] Terner, Z., & Franks, A. (2021). Modeling Player and Team Performance in Basketball. In Annual Review of Statistics and Its Application (Vol. 8, Issue 1, pp. 1–23). Annual Reviews. https://doi.org/10.1146/annurev-statistics-040720-015536

[3] Jain, S., & Kaur, H. (2017). Machine learning approaches to predict basketball game outcome. In 2017 3rd International Conference on Advances in Computing,Communication & Automation (ICACCA) (Fall). 2017 3rd International Conference on Advances in Computing,Communication & Automation (ICACCA) (Fall). IEEE. https://doi.org/10.1109/icaccaf.2017.8344688

### Timeline

https://gtvault-my.sharepoint.com/:x:/g/personal/snandakumar7_gatech_edu/EZyTNxWZEbFItVvn9XkAQGwBpygKGzXsT3IK7zwTB84_Zg?e=EDf4v6


### Dataset

https://www.kaggle.com/andrewsundberg/college-basketball-dataset?fbclid=IwAR2ZbQ1hw745m661lKiKWHQPnGHdWZJ7rKAHScQUrlVt4zUSVn3-Er9mL5Y