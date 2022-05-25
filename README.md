# Problem Statement:
#### Ad-campaign-Conversion-Prediction
A digital markeing agency ran an ad-campaign on facebook. As per their data collected, we need to predict the 
a) total conversions for future campaigns based on multiple parameters used.
b) approved conversions for future campaigns based on multiple parameters used.

The problem statement was solved using Multiple Linear Regression where feature selection for the model was done using Backward Elimination & VIF method.

Features:
impressions, clicks, spent, CTR, Avg CPC, App Install, total_conversion, approved_conversion    

Steps:
##### 1. import libraries
##### 2. import data
##### 3. EDA - 
##### a. Univariate Analysis
#####    a.i) Checking Missing Values
#####    a.ii) Remove outliers
##### b. Bivariate Analysis - Check relationship between the independent variable & dependent variable
#####    b.i) Correlation Co-efficient Between variables
#####    b.ii) Heatmap (10x10 Matrix)

##### 4. Data Partition
##### 5. Model Building
##### a. Multicolinearity - with VIF
##### b. Removing the insignificant variable
##### c. Backward Elimination Method
##### d. VIF of Model

##### 6. Assumption of Model
##### a) Homoscedasicity
##### b) Normality
##### c) Model Error IID
##### 7. Prediction on Test Data
##### 8. MSE & MAE & RMSE for evaluation of Model on test data
##### 9. MSE & MAE & RMSE for evaluation of Model on train data
