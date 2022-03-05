# MPV-Predictions
Using ML techniques to predict the 2021-2022 NBA MVP

The NBA MVP is utilized as an award for the most valuable player in the league, usually exemplifying a player who is crucial for team success. It was first given in the 1955-56 season where each member of the voting panel (a group of sports journalist and broadcasters) casts a vote from 1st to 5th place in deciding on the most valuable player. Coming from a business standpoint predicting the MVP would be beneficial for forecasting supply of merchandise for NBA teams. Having an MVP candidate leads to more sales of that perspective players merchandise leading to more income for the NBA as well as the perspective NBA team. 

Data was retrieved via the official NBA API where data was pulled from 1989 to 2022. Player statistics were pulled from 3 endpoints: Player Career Stats, Team Year Stats and Player Awards. The player career stats endpoint pulls commonly recorded statistics such as Points Scored in a season, Rebounds in a Season, Games Played in a Season, Minutes Played in a season etc. etc. The Team Year Stats records the teams wins, losses and rankings for a given season. The Awards endpoint allows us to retrieve whether a player won a specific award or not and, in this case, we were able to extract out MVP given a specific player ID. After data was retrieved, we stored it into pickle so that data is stored much more efficiently and is quite easy to read with Pandas. Data was saved in a local environment as the NBA API limits the number of requests you can send.

We found that it is entirely possible to use machine learning algorithms as solutions to decide on professional league sports awards. The application of machine learning algorithms for this purpose was very interesting, as the eye test for the season has Stephen Curry as one of the players in the top ranks of the KIA MVP ladder. Steph’s high ranking is attributed to the team win percentage as his in-game statistics are not as impressive as some of the other candidates such as Giannis Antetokounmpo who reaches the no. 1 rank of the MVP ladder and Kevin Durant who is no. 2. One of the problems, with the model is Giannis and Nikola Jokic of the Denver Nuggets, are often very low on the list or sometimes not even in the top 10 of these classification models. This is most definitely attributed to some challenges in regard to the application of machine learning models for such a task, where we are at the season, and data limitations. 

Here is a look at some of the predictions our models made:

Logistic Regression Predictions:

![Logistic Regression Predictions](https://user-images.githubusercontent.com/70538240/156902834-7878528a-e1f7-47e8-9657-8656e2726147.png)

Adaboost Predictions:

![Adaboost Predictions](https://user-images.githubusercontent.com/70538240/156902839-6f5f9bc6-e9d9-463e-a70a-2d86a1637a27.png)

Random Forest Predictions:

![Random Forest Predictions](https://user-images.githubusercontent.com/70538240/156902845-86fefe68-6cdb-4ac4-ade2-421746b3011a.png)


If you are looking for a more in-depth read about this project, please check out the word document in the repo. 
