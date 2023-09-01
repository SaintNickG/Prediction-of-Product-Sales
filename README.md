# Prediction-of-Product-Sales
## * Author- Nicholas Giuffrida
## Project Overview
-  Predict future sales of items based on the factors provided

-  ##  Data
-  To prepare this data, the data was cleaned, and the following processes were performed:
## Expolratory Data Analysis
![exploratory](https://github.com/SaintNickG/Prediction-of-Product-Sales/assets/137968958/3cf5ad37-1cd4-45f5-a996-49dab462ae8dthi)

>  **The comparison of Low Fat, versus Regular Items in our data set**
>
> 
> 
 ![heatmap](https://github.com/SaintNickG/Prediction-of-Product-Sales/assets/137968958/b1829aaa-99e7-4520-9b89-611b9ef36c3f)
>  **A heatmap to show correlation between our numerical features**
>
> 
> 
## Maching Learning Using the Following Models:
- Linear Regression Model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

###  Models Evaluated & Results

1 Linear Regression Model : Test Data
------------------------------------------------------------
- MAE = 804.225
- MSE = 1,194,696.265
- RMSE = 1,093.022
- R^2 = 0.567

- 
2 Random Forest Regressor Model: Test Data
------------------------------------------------------------
- MAE = 763.708
- MSE = 1,213,209.449
- RMSE = 1,101.458
- R^2 = 0.560

- 
3 Tuned Random Forest Regressor Model: Test Data
------------------------------------------------------------
- MAE = 733.810
- MSE = 1,116,342.487
- RMSE = 1,056.571
- R^2 = 0.595

The Final Model Chosen was a Random Forest Regressor Model.

For the testing set on the model, 59.5% of the variance in y was explained by x.

The Mean Absolute Error was off by about 733.81.

The Mean Squared Error was 1,116,342.48.

The Root Mean Squared Error had a calculation of 1,056.571 .




