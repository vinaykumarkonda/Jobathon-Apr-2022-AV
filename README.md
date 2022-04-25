# Jobathon-Apr-2022-AV
## Problem Statement

ABC is a car rental company based out of Bangalore. It rents cars for both in and out stations at affordable prices. The users can rent different types of cars like Sedans, Hatchbacks, SUVs and MUVs, Minivans and so on.

In recent times, the demand for cars is on the rise. As a result, the company would like to tackle the problem of supply and demand. The ultimate goal of the company is to strike the balance between the supply and demand inorder to meet the user expectations. The company has collected the details of each rental. Based on the past data, the company would like to forecast the demand of car rentals on an hourly basis.

## Objective

The main objective of the problem is to develop the machine learning approach to forecast the demand of car rentals on an hourly basis.

## Approach
1. Perform Basic EDA and analyse what and how to featurize</br>
  <b>Observation: Found to be their is some trend in Month, Weekday. So, based on the observation created below features</b>
2. Features using date <b>['month','weekday','day','IsWeekend']</b> & using basic statistics <b>['month_mean', 'weekday_mean', 'hourly_mean', 'month_min', 'weekday_min', 'hourly_min', 'month_max', 'weekday_max', 'hourly_max']</b>
3. Try out all models with default parameters and pick the best model out of them</br>
  a. Linear Regression</br>
  b. SupportVector Regression</br>
  c. DecisionTree Regression</br>
  d. RandomForest Regression</br>
  e. XGBoost Regression</br>
  f. Stacking - Pick the outputs of each model and build another XGBoost model</br>
 <b>Observation : Found to be XGBoost stands out best amongst all models</b>
4.  Tune the best model XGBoost and submit the result

## Final Result

<b>Private Leaderboard Rank - 32 </br></b>
Public Leaderboard Rank - 71
