# BikeSharingDemandPrediction
This repository is for my machine learning project "Bike Sharing Demand prediction".

Data Link:
UC Irvine Machine Learning Repository
https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand

The dataset contains count of public bicycles rented per hour in the Seoul Bike Sharing System, with corresponding weather data and holiday information.

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. 
The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. 
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information. 

Variable Information
Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius 
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


The dataset is also available on Kaggle:
https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction


In this project, I:
●	Applied feature engineering, dropped correlated variables, and encoded categorical features.
●	Utilized linear regression models (Linear, Ridge, Lasso, Elastic Net) and non-linear ML regression models (Decision Tree, Random Forest, Gradient Boosting, k-NN, SVM).
●	Used GridSearchCV for hyperparameter tuning and k-fold cross-validation to assess the performance using Mean Square Error and R-Square metrics on the test data.
