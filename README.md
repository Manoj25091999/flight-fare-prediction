# flight-fare-prediction
In this project my objective was to predict the flight fares based on the given data and features (Arrival hour, Destination, Duration etc.). At first I used many Machine Learning algorithms (Elastic Net Regressor, Lasso Regressor, Random Forest, SVR etc.) and checked their performance on the training dataset using "cross validation score" metric, what I find is that most of the models were not giving that much good cross validation score (around 70-80%) in comparison to "Xgboost Regressor" (around 84-85%), so in this module I have predicted the flight fares using Xgboost Regressor and then tuned it to get an r2 score around 0.88-0.89. 

This project is currently in the stage of deployment.
