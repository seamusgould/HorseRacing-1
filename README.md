# HorseRacing-1
I created this model to try to come up with an algorithm that could make earnings at the racetrack by using the most basic statistical methods.  In summary, I tried to win money by adding new information to a model that was based on a model that just chooses a horse based on the odds of a horse.  Here is a summary of my methods:

1) Predicted the finish times of each horse by using a simple linear regression
2) Used the results of the finish time to fit a logistic regression to determine whether or not my model with predicted finish time and count adds significance to the original model that just fits the betting odds to a logistic regression.
3) I compared my betting strategy, an odds betting strategy, and a random betting strategy by simulating around 1000 races 1000 times.  I compared the three different strategies using a Welches T-test.

In the end, all models lost money, though my model that included the predicted finish times lost less money.  This model could be improved by using conditional logistic regression because my original one violated the independence assumption.  
