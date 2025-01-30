# House_Price_Prediction

# Overview
The goal of this project is to develop a regression model that can predict the median value 
of homes in Boston based on several features such as crime rate, property age, and number of rooms.
XGBoost, a powerful gradient boosting algorithm, is employed due to its high performance in predictive tasks. 
The performance of the model is evaluated using Mean Squared Error (MSE).

# Dataset
The dataset used in this project is the Boston Housing Dataset, which contains 506 rows and 13 feature columns. Each row represents a housing unit in Boston, and the columns represent features such as:

CRIM: Crime rate
ZN: Proportion of residential land zoned for large plots
INDUS: Proportion of non-retail business acres per town
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX: Nitrogen oxide concentration (parts per 10 million)
RM: Average number of rooms per dwelling
AGE: Proportion of owner-occupied units built before 1940
DIS: Weighted distance to employment centers
RAD: Index of accessibility to radial highways
TAX: Property tax rate
PTRATIO: Pupil-teacher ratio
B: Proportion of residents of African American descent
LSTAT: Percentage of lower status population
MEDV: Median value of owner-occupied homes (target variable)
