# flight-fare-prediction
My first attempt in making an end-to-end Machine Learning project where I have tried to predict the flight fares from the given dataset, while building this project my objective was to predict the flight fares based on the given data and features (Arrival hour, Destination, Duration etc.), I followed all the steps from data gathering to model deployment, at first I used many Machine Learning algorithms to check their performance on the training dataset based on "cross validation score" metric, what I find is that most of the models were not giving that much good cross validation score (around 70-80%) in comparison to "Xgboost Regressor" (around 84-85%), so in this module I have predicted the flight fares using Xgboost Regressor and then tuned it to get an accuracy around 85-86%.
