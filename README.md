# Flight-Price-Prediction-Project
Flight Price Prediction Project 

Project Overview
This project focuses on predicting flight booking prices using a Linear Regression model, Decision Tree Regressor and Randon Forest Regressor. The dataset contains various features related to flight bookings, and the goal is to build a model that can accurately predict the price of a booking based on these features.

Dataset-
The dataset used in this project is a hypothetical Flight Booking dataset containing the following columns:

airline: Name of the airline
source_city: City from which the flight is departing
departure_time: Time of the day when the flight departs
stops: Number of stops between source and destination
arrival_time: Time of the day when the flight arrives
destination_city: City to which the flight is arriving
class: Class of the flight (Economy/Business)
duration: Duration of the flight
days_left: Number of days left before the flight
price: Price of the flight (Target variable)

Data Preprocessing-
Label Encoding: Categorical variables were encoded using Label Encoding to convert them into numerical form.
Removing Duplicates: Duplicate rows were removed to ensure the data quality.
Feature Scaling: StandardScaler was used to standardize the independent variables.

Model Training-
A Linear Regression model, Decision Tree Regressor and Random Forest Regressor were used to predict flight prices based on the features. The data was split into training and testing sets to evaluate the model's performance.

Model Evaluation-
R-squared Score: The R-squared value was calculated to measure the goodness of fit of the model.
Root Mean Squared Error (RMSE): RMSE was computed to measure the standard deviation of the residuals.

Conclusion- Random Forest Regressor had the best r2_score and rmse .
