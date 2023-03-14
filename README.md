# Wine Quality Prediction

This project focuses on predicting wine quality from a combination of data from red and white wines of the Portuguese wine "Vinho Verde". 
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

# Output Plots

## Outlier Treatment - Capping

#### Before Outlier Treatment
![Before Outlier](https://raw.github.com/nise757/wine-quality-prediction/Outputs/before%20outlier.png)

#### After Outlier Treatment
![After Outlier](https://github.com/nise757/wine-quality-prediction/blob/main/Outputs/after%20outlier.png)

## Correlation Plot
![Correlation](https://github.com/nise757/wine-quality-prediction/blob/main/Outputs/corrplot.png)

## Principal Components Regression
![PCR]()

