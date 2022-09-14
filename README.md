

#  Bike Sharing Demand Prediction
## Introduction
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## Problem Statement
We are tasked with predicting the number of bikes rented each hour so as to make an approximate estimation of the number of bikes to be made available to the public given a particular hour of the day.
##  Overview Of The Data
We are given the following columns in our data:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
## Steps involved
1) Installing libraies and getting the dataset.
2) Performing EDA (exploratory data analysis).
3) Drawing conclusions from the data.
4) Preprocessing the data.
5) Training different models.
6) Evaluating metrics of all the models.
## Algorithms used
1) Linear,Lasso,Ridge and Elastic Regression
2) Decision tree Regressor
3) Random Forest
4) Gradient Boosting Regression(Gradient Boosting Machine)

## Conclusion
We used R2-score to understand which model fit our data better, and the scores are as follows:

Linear Regression - 0.6183

Decision Tree Regressor - 0.8381

Random Forest Regressor(GridSearch CV) - 0.8782

Gradient Boosting Regression(GridSearch CV)- 0.9130

Its evident from above that the Random forest Regressor and Gradient boosting regression model performed well in fitting the data with R2-score of 0.8782 and 0.9130. The model which performed poorly was elastic net regularization with R2-score of 0.6140
