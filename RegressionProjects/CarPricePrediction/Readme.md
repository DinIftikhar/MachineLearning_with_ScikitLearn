# Project1: Car Price Prediction

This is my first project in Machine Learning with Scikit Learn. It is a supervised regression based problem. My goal is to predict the car price given different features. The dataset is downloaded from [Kaggle](https://www.kaggle.com/manoranjankrthakur/cardekho). I have used XGBoost Regressor with RandomizedSearchCV for prediction. I have achieved MAE = 0.22, MSE = 0.078 and RMSE = 0.2797 on the predicted dataset. The model is saved using pickle and deployed using Flask. Thanks to Krish Naik video on youtube.

### Summary of the steps:

- Importing the important libraries
- Reading and Understanding the Dataset
- Preprocessing the Dataset
- Exploratory Data Analysis
- Preparing the data for model building
- Defining the model
- Hyperparameter tuning using RandomizedSearchCV
- Predicting the test dataset
- Evaluating the model
- Saving the model using Pickle
