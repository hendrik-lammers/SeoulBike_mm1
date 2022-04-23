# SeoulBike_mm1
A repository for the Seoul Bike Data Scientist Coding Challenge

# Introduction
This project is about predicting the demand of customers from a korean Bike Rental Company based on two scenarios for climate change.
This is mainly done by Random Forest Regression with Grid Search Cross Validation to optimize hyperparameters.

# Dataset
The Dataset contains 8760 observations of 11 features plus target variable ("Rented Bike Count") and Date and Time information. The features are as follows:
* Temperature(°C)
* Humidity(%)	
* Wind speed (m/s)	
* Visibility (10m)	
* Dew point temperature(°C)	
* Solar Radiation (MJ/m2)	
* Rainfall(mm)	
* Snowfall (cm)	
* Seasons	
* Holiday	
* Functioning Day

# Possible Next Steps
* Try to gather more observations to get more training data and make the model more generalizable.
* Try to enrich the dataset with more features to enhance explanation of variance
* Try other Regressors like Neural Networks

# Code
The code is written in a simple Jupyter Notebook file, to make it easily readable, understandable and executable.
