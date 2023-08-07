Restaurant Rating Prediction Project 

1. Problem statement :
The main goal of this project is to perform extensive Exploratory Data Analysis(EDA) on 
the Zomato Dataset and build an appropriate Machine Learning Model that will help 
various Zomato Restaurants to predict their respective Ratings based on certain 
features.

Basic Workflow of the project :

1. DATA COLLECTION :
The dataset used for analysis is restaurant rating prediction which is provided by the zomato in bangalore. It has attributes like order method, book table , votes ,location , restaurant type ,cuisines ,amount , menu name 

2. DATA PREPROCESSING :
The data preprocessing is done since the dataset containing  missing values, outliers and other duplicate data. Once we clean the data we can visualize the data with much more insights.

3. EDA:
Exploratory Data Analysis is carried out on the dataset to get      deep insights about the data. EDA ensures that the correct attributed in patterns and trends are made available for training the model to achieve the correct outcome, like a successful model. Therefore, carrying out the right EDA with the correct will help achieve the expected goal. 

4. FEATURE ENGINEERING :
Feature engineering helps to represent an underlying problem to predictive models in a better way, which as a result, improve the accuracy of the model for unseen data. The predictive model contains predictor variables and an outcome variable, and while the feature engineering process selects the most useful predictor variables for the model.


5. MODEL BUILDING :
ExtraTressRegressor is an ensemble machine learning algorithm that is based on decision tree regressors. It combines multiple decision trees to make predictions. When compared to other machine learning techniques , extraTress regressor gives high accuracy so we have built the model using this technique.

6. DEPLOYMENT : 
Deploying a machine learning model built using the ExtraTrees Regressor on the Flask framework involves creating a web application that takes input from users, sends the input to the model for prediction, and then displays the prediction to the user. Here's a high-level overview of the steps includes , Create a Flask Application, Model Loading, Create Web Form, Route Creation, Model Prediction, Render Prediction, Styling (Optional), Run the Flask App.





