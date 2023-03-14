# Wine Quality Prediction

This project focuses on predicting wine quality from a combination of data from red and white wines (Count = 6,397) of the Portuguese wine "Vinho Verde". 
Combining the two data sets and cleaning it for outliers - [Capping](https://www.educative.io/answers/how-to-cap-outliers-from-a-series-dataframe-column-in-pandas). Various subset selection methods were experimented with to come up with the final model. 

Additionally, cross-validation methods were used to evaluate the models on different sets of training and test data. The final model that most accurately predicts wine quality is a *9-parameter linear regression model* with parameters determined via best subset selection.

# Parameters

1. Fixed Acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol content

# Outputs

## Quality Distribution
![quality distrib](https://user-images.githubusercontent.com/124890367/225135798-e7907039-44ba-4d91-be47-a4bbf0e3a81e.png)

## Alcohol vs Density
![alcohol vs density](https://user-images.githubusercontent.com/124890367/225135962-cdcf21ad-35ad-4b25-9cd7-ba3221eb6d0f.png)

## Alcohol vs Quality
![alcohol vs quality](https://user-images.githubusercontent.com/124890367/225135987-ad2c3ee2-efbe-46cf-a5e9-2946a048b8db.png)

## Outlier Treatment - Capping

#### Before Outlier Treatment
![before outlier](https://user-images.githubusercontent.com/124890367/225134790-2034e285-71f9-4e48-988f-c28cbfd1c0b0.png)

#### After Outlier Treatment
![After Outlier](https://github.com/nise757/wine-quality-prediction/blob/main/Outputs/after%20outlier.png)

## Correlation Plot
![Correlation](https://github.com/nise757/wine-quality-prediction/blob/main/Outputs/corrplot.png)

## Adjusted R-squared, Mallows Cp & BIC (For Parameter Selection)
![r2CpBIC](https://user-images.githubusercontent.com/124890367/225135657-38d22887-d86f-4d77-989c-207d79efe808.png)

## Principal Components Regression
![PCR](https://user-images.githubusercontent.com/124890367/225134951-48963fd6-fcb1-45a7-bae7-50324bf3aaac.png)

## Partial Least Squares Regression
![PartialLS](https://user-images.githubusercontent.com/124890367/225135216-ff49409d-88d0-43cb-b74d-26e0335e94bb.png)

## LASSO Regression

#### Coefficients
![lasso1](https://user-images.githubusercontent.com/124890367/225135472-30e3579f-9cff-44f8-800f-3896ec8c4c94.png)

#### MSE
![lasso2](https://user-images.githubusercontent.com/124890367/225135505-c159b5d9-fec1-4a7f-8ac6-9dd02d315535.png)

## Ridge Regression

#### Coefficients
![ridge1](https://user-images.githubusercontent.com/124890367/225135534-1e633770-35b9-4d0f-8f37-f42c387bf53a.png)

#### MSE
![ridge2](https://user-images.githubusercontent.com/124890367/225135551-7149d332-7509-4403-a015-a02c70810072.png)





