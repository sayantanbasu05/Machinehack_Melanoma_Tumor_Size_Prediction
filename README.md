# Machinehack_Melanoma_Tumor_Size_Prediction

In this competition, we were asked to predict the tumor size based on certain features present in the dataset. The feature engineering took me to a rank of 15 alone and finally with an ensemble of two CatBoost models a leaderboard rank of 8 was achieved.

With extensive EDA I found repeated entries in train and test which were directly replaced in post processing to improve scores. Furthermore, dropping rows from train dataset with 0 as target values improved score.

[Link to the leaderboard](https://www.machinehack.com/hackathons/melanoma_tumor_size_prediction_weekend_hackathon_15)
