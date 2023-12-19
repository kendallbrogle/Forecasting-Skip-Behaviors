# Forecasting-Skip-Behaviors

Project Description: 
Music is something that struggles to fit the bounds of traditional data that predictions are usually made on whether it is stock market data or sentiment analysis. It can be deeply personal or superficial simply depending on the seemingly arbitrary and random mood of its listener. We attempt to break these walls of unpredictability and predict whether or not a listener will skip the song they are currently listening to. We do this with the following:
Extracting the Spotify data to show us information about a particular song such as its energy, danceability, and acousticness
Using specific user data such as time listened to and historical performance
The visualization of any correlation present between any feature using heatmaps
Classic regressions and classification with gradient boosting, random forest, and decision trees 
Basic and complex LSTMs for a more robust prediction
Feature importance on everything to see what is most influential 


The repository contains several files:
Milestone 1.pdf
	Contains information regarding the EDA that we performed including basic regressions 
	and correlations present.
Milestone 2.pdf
	Contains information regarding the ML concepts leveraged such as gradient boosting, 
	decision tree, random forest, feature importance and a basic LSTM.
Milestone 3.pdf
	Contains information finalizing our findings and making our analysis more robust by 
	making the LSTM more complex. 
Exploratory Data Analysis.ipynb
ML (Gradient Boosting, Decision Tree, Random Forest, and Feature Importance).ipynb

To run the EDA:
Load the tf_mini.csv and log_mini.csv datasets
Run the Exploratory Data Analysis.ipynb file in your environment

To run the Gradient Boosting/Decision Tree/Random Forest/Feature Importance:
Make sure the previous datasets are still loaded in your environment
Run the ML (Gradient Boosting, Decision Tree, Random Forest, and Feature Importance).ipynb file

To run the LSTM:
LSTM_Loss_Accuracy.ibynb: ensure to load the tf_mini.csv and log_mini.csv datasets. The file contains the necessary preprocessing code, including one hot encoding the required variables. This file contains the simple LSTM models, along with their model loss and accuracy scores and their visualizations. The file contains a total of 4 different LSTM models: skip_1, skip_2, skip_3 , and not_skipped.
HyperparameterTuning_skip1.ibynb and HyperparameterTuning_skip3.ibynb: Both of these files contain the refined LSTM models for skip_1 and skip_3, respectively. The files include the LSTM models with the addition of hyperparameter tuning, along with the necessary model loss, accuracy, AUC/ROC scores and curves. The files were initially created for further analysis to ensure that our models are not overfitting. 


References:
Link to data:
https://www.aicrowd.com/challenges/spotify-sequential-skip-prediction-challenge/dataset_files
Click on training_set_track_features_mini.tar
