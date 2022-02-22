## NCAA Division 1 College Basketball Team Ranker

### Introduction/Background 

As a group, we have a strong interest in sports and wanted to utilize this opportunity to work with the basketball statistics from the 2013-2021 Division 1 college basketball seasons. The first NCAA Division 1 men’s basketball tournament was played in 1939. The average men’s D1 team plays 35-40 games in a normal season, and then a select few more in the postseason. In 2018 and 2019, there were more than 5,800 games played. A college basketball season is broken down into a few segments: non-conference play, conference play, conference tournaments, and postseason tournaments. The number of games in conference play varies by conference with the ACC, Big Sky, Big Ten, MAAC, Southland, and Sun Belt conferences playing 20-game schedules in 2019-2020 and the Ivy League playing a national-low 14 conference games. The vast amount of game time per season generates several important statistics and performance metrics that we can leverage to determine the quality of each team relative to their opposition and other teams in the nation.

### Problem Definition

In the NCAA, the winner of the basketball tournament is the college team (from Division 1) that scores the most points. Using a dataset, factors such as the number of games played, the number of wins, offensive/defensive efficiency, rebound rate, turnover rate, and free throw rate, will be used to create a team ranking system for each season. The goal of this project is to predict the top 10 teams over multiple seasons by evaluating the efficiency of the system.

### Methods 

The method we plan to use to solve this problem falls under supervised learning, specifically using a multi-layer perceptron (MLP) and gradient descent to train the model. We will parameterize the neural network using 3 layers and ReLU activations after each layer. The loss will be defined as an L2 loss over the estimated power ranking score and the labeled power ranking score. Each of the numerical features will be inputted directly into the model while the categorical features will receive a numerical encoding. All these features will be merged together to form one input vector to the model of fixed dimension. If we have additional time, we plan to study using Linear Regression and compare the performance of our MLP model with a less complex technique.

### Potential Results 

Having access to data like a win to lose ratio and different statistics of the performance of teams from the 2013 - 2021 seasons, we plan to give weights to these statistics based on current basketball trends and calculate the power rating of each team for the next few seasons. We shall first attempt to calculate the weights for each statistic by following the data trendlines that we already have. For instance, knowing that the game has become more offensive, the adjusted offensive efficiency can be given more weightage.

### Discussion

We hope to predict the next top 10 NCAA Division I basketball teams in the country over multiple seasons. This might also shed light on which college is more likely to produce future stars of basketball to play in the NBA. The data we produce might also be able to help predict league and playoff results between different college basketball teams.

### References

[1] Sarlis, V., & Tjortjis, C. (2020). Sports analytics — Evaluation of basketball players and team performance. In Information Systems (Vol. 93, p. 101562). Elsevier BV. https://doi.org/10.1016/j.is.2020.101562

[2] Terner, Z., & Franks, A. (2021). Modeling Player and Team Performance in Basketball. In Annual Review of Statistics and Its Application (Vol. 8, Issue 1, pp. 1–23). Annual Reviews. https://doi.org/10.1146/annurev-statistics-040720-015536

[3] Jain, S., & Kaur, H. (2017). Machine learning approaches to predict basketball game outcome. In 2017 3rd International Conference on Advances in Computing,Communication & Automation (ICACCA) (Fall). 2017 3rd International Conference on Advances in Computing,Communication & Automation (ICACCA) (Fall). IEEE. https://doi.org/10.1109/icaccaf.2017.8344688

### Timeline
