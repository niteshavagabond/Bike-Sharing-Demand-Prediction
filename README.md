# Bike-Sharing-Demand-Prediction
## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. 
It is important to make the rental bike available and accessible to the public at the right time as it lessens
the waiting time. Eventually, providing the city with a stable supply of
rental bikes becomes a major concern. The crucial part is the prediction
of bike count required at each hour for the stable supply of rental bikes.

## Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
Attribute Information:
* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Data preprocessing
Steps of data processing
1. Deal with null/missing values
2. Deal with duplicate data
3. Deal with outliers

## Feature engineering
1. Deal with outlier
2. Deal with wrong datatype
3. Encoding of Categorical columns

##Exploratory Data Analysis
1. Univariate Analysis
2. Bivariate Analysis
3. Multivariate Analysis

## Creating Functions
1. Function for model creation
2. Function for Evaluation Matrix
3. Function for drawing graph between actual and prediction

## Models
1. Linear regression
2. Ridge regression
3. Lasso regression
4. Elastic net regression
5. Polynomial regression
6. Decision Tree
7. Random Forest
8. Gradient Boost
9. XG Boost

## Conclusion - EDA
1.	The highest demand for the rented bike was recorded during June but the least demand was recorded during January and February.
2.	Summer is the busiest season and winter is the least busy season for the rented bike.
3.	Around 6 pm is the busiest hour of the day.
4.	On a working day, the rental bike demand is high in comparison to the holiday.
5.	the highest demand for the rented bike is seen when there is the moderate temperature that is around 25°C to 35°C.

## Conclusion - Model
1.	Based on R2 and Adjusted-R2, the Gradient Boosting model and eXtreme Gradient Boosting model are best as the accuracy of these models is above 90% and also their Adjusted-R2 values are less than R2 values.
3.	Gradient Boosting model's R2 and Adjusted-R2 values are 0.904 and 0.903 respectively.
4.	eXtreme Gradient Boosting model's R2 and Adjusted-R2 values are 0.922 and 0.921 respectively.
5.	Linear model, Lasso model, Ridge model, and Elastic net model haveR2 and Adjusted-R2 values below 60%.


