# Regression

## Regression Statistics
### Multiple R
  * This is the correlation coefficient between the observed and predicted values. (linear relationship)
### R Square
  * This is the coefficient of determination, showing how much variance in the dependent variable is explained by the model.
  * It measures the proportion of variance in the dependent variable (Y) that is explained by the independent variables (X) in your model.
  * The percentage of variability in the outcome (e.g., price or demand) that can be explained by the predictors in your regression model.
  * The remaining is unexplained—due to factors not included in the model or random noise.

<img width="855" height="252" alt="Screenshot 2025-11-08 at 1 37 35 PM" src="https://github.com/user-attachments/assets/b88c8dda-dccf-4e5a-96ea-c9d5e00baf64" />

### Adjusted R Square
  * Adjusted for the number of predictors and sample size.
  * R² always increases when you add more predictors—even if they’re irrelevant. This can make a model look better than it really is.
  * Adjusted R² penalizes unnecessary complexity, so it only increases if the new predictor improves the model more than expected by chance.

<img width="855" height="315" alt="Screenshot 2025-11-08 at 1 41 37 PM" src="https://github.com/user-attachments/assets/73e7549b-d7ac-4bfd-a0df-8e449e71cdfa" />

### Standard Error
* This is the standard deviation of the residuals (errors).
### Observations
* Number of data points

## ANOVA
* Part of the regression output and helps you understand the overall significance of the model

### Degress of Freedom

#### Regression df
* Number of predictors in the model
#### Residual df
* Number of obersvations minus (predictors + intercept) (The constant term that represents the expected value of the dependent variable when all predictors are zero in a regression model)
#### Total df
* obersvations - 1

### Sum of Sqaures (SS)
#### Regression SS
* Variation explained by the model.
#### Residual SS
* Varation not explained (error)
#### Total SS
* Overall variation of the dependent variab;e 
