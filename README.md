# SCRABBLE RATINGS PREDICTION
Predicting the ratings of players based on Scrabble gameplay 

In the second edition of this Kaggle Competition featuring data from Woogles.io, participants are challenged to predict the ratings of players based on Scrabble gameplay. The evaluation algorithm is RMSE.
 
 # DATASET DESCRIPTION 
 
 The dataset includes information about ~73,000 Scrabble games played by three bots on Woogles.io: BetterBot (beginner), STEEBot (intermediate), and HastyBot (advanced). The games are between the bots and their opponents who are regular registered users. You are using metadata about the games as well as turns in each game (i.e., players' racks and where and what they played, AKA gameplay) to predict the rating of the human opponents in the test set (test.csv). You will train your model on gameplay data from one set of human opponents to make predictions about a different set of human opponents in the test set.

There is metadata for each game (games.csv), gameplay data about turns played by each player in each game (turns.csv), and final scores and ratings from BEFORE a given game was played for each player in each game (train.csv and test.csv).

Here is an example of a game played on woogles.io: https://woogles.io/game/icNJtmxy. Use the "Examine" button to replay the game turn-by-turn.

# Files

1. games.csv - metadata about games (e.g., who went first, time controls)
2. turns.csv - all turns from start to finish of each game
3. train.csv - final scores and ratings for each player in each game; ratings for each player are as of BEFORE the game was played
4. test.csv - final scores and ratings for each player in each game; ratings for each player are as of BEFORE the game was played
5. sample_submission.csv - a sample submission file in the correct format
 
