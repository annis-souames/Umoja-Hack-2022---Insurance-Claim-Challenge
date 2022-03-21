# Umoja Hack 2022 : Insurance Claim Challenge
 My solution for the 7th place / 245 in the Umoja Hack 2022 challenge

 Umoja Hack Africa is a yearly hackathon organized by Zindi, a data science platform for African data scientist, the hackathon contain 3 challenges : Beginner, Intermediate & Andvanced, this is my solution for the Intermediate challenge which allowed me to avoid overfitting and rank 7th in the final leaderboard while I was 25th in the public leaderboard. 

 The solution is based on a slightly tuned LGBM regressor model with basic feature engineering, but the model was trained on log(1+y) instead of the target directly in order to reduce the optimisation space and give good results, this improved the score a lot.

 Besides, I've set up a good cross validation strategy with 10 folds, the CV did follow the private Leaderboard, this is my best solution according to the local CV. 

 **If you enjoyed this solution don't forget to star the repo :)**
