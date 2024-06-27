# Wine-Quality-Mini-Project

## Project Description
### Wine Quality Prediction

Compared various regression models (linear, best subset, stepwise, Ridge, Lasso) to find the best for wine quality prediction.
Ridge regression achieved the lowest test error, suggesting it might be the most accurate method.

### Diabetes Classification

Analyzed different logistic regression models (baseline, best subset, stepwise, Ridge, Lasso) for diabetes classification.
Ridge and Lasso regressions resulted in the lowest error rates, potentially making them the most effective for predicting diabetes.
This aligns with findings from Project #3, where Ridge and Lasso were favorable for their ability to improve prediction accuracy.

## Used Packages
- caret
- leaps
- randomForest
- glmnet
- data.table
- bestglm

## Performed Analysis
- Linear Regression with Leave-One-Out Cross-Validation (LOOCV)
- Best Subset Selection with Adjusted R-squared (Adj. R²) and BIC criteria
- Forward Stepwise Selection
- Backward Stepwise Selection
- Ridge Regression with lambda tuning
- Lasso Regression with lambda tuning
- Baseline Logistic Regression with cross-validation
- Best Subset Selection with AIC criteria
- Forward Stepwise Selection with AIC criteria
- Backward Stepwise Selection with AIC criteria
