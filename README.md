# NYC-Taxi-Trip-Duration-Regression-Analysis

### Performing EDA on NYC Taxi Trip Duration and using preprocessed dataset to build regression models and verify the assumptions associated with it.

#### The below steps were used

- Splitting Train dataset into with outliers and without outliers and building two modelpipelines in the next steps
- Transformations on predictors and target after analyzing and visualizing their distrbution and properties
- Encoding categorical predictors using Catboost Encoding
- Standardising numerical predictors to bring them to same scale using StandardScaler as non tree based algorithms are used.
- Checking multicollinearity between independent predictors using VIF( Variance Inflation factor) and removing it
- Creating a sklearn model pipeline for the above steps
- Using Elastic Net Polynomial Regression and using OPTUNA library for hyperparameter tuning
- Verifying the assumptions of Linear Regression for the trained models

For EDA, refer to https://github.com/prasum/NYC_Taxi_Trip_Duration_EDA
