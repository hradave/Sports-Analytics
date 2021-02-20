# Predicting Goals in Football: Estimating the Probability of Scoring from Shots by FC Barcelona Players

## Abstract 
The world is changing with the advance of technology and the vast amount of data available, and so does sport. Team sports such as football, are starting to introduce mathematical methods to analyse performances, recognize trends and patterns and predict results. The purpose of this study is to develop a new metric called Scoring Probability using machine learning models that is capable of predicting when a shot is going to end up being a goal. Scoring Probability is inspired by the Expected Goals metric.

To do so, many different mathematical approaches are trained on a dataset that tries to represent the exact moment of the shot in as much detail as possible. Also, the dataset includes information about the players, their skills and the moment of the game. By doing so, a Logistic Regression algorithm is the one that yields the best performance when predicting goals, with an F1 score of 35.24%, improving the previous works on the field.

This study intends to provide new information and hidden insights to professionals - players, coaches or managers - in order to improve the game, looking for a better decision process when it comes to scoring a goal.


## Dataset
The project is mainly based on a dataset from [StatsBomb](https://statsbomb.com/) which includes features such as: location of the players on the pitch in any shot - including he position and actions of the Goalkeeper-, detailed information on defensive players applying pressure on the player in possession, or which foot the player on possession uses.

Player skills are also considered, ratings of the shooters -which is the preferred foot of the player- and the opponent goalkeepers from FIFA sourced from [FIFAindex](https://www.fifaindex.com/).

# Models Trained
* Logistic Regression
* Random Forest
* Ada Boost
* K-NN

# Results
The best result was yielded by the Logistic Regression being an accuracy of 85.89%.

# Prediction Examples
Messi GOAL with a probability of scoring of 12%.

![Alt text](https://github.com/oriolgarrobe/Sports-Analytics/blob/master/img/messi_goal.JPG?raw=true)

Giuly MISS with a probability of scoring of 88.6%.

![Alt text](https://github.com/oriolgarrobe/Sports-Analytics/blob/master/img/giuly_miss.JPG?raw=true)

