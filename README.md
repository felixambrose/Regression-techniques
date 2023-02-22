# Regression-techniques
Kaggle dataset predicting house prices. It's a simple model, experimenting with linear and polynomial regression and a Random Forest Regressor.

The Method is as follows:

# Import Data
- Split data into training and test data 

# Explore Data
- Descriptive statistics and parameters of the target variable (house price).

# Clean Data
- Replacing missing data with the mean of the columns. COlumns with large amount of missing data were removed.

# Feature Engineering + Selection

- Understood variables that were correlated with target variables and shortlisted them
- Removed any feature variables that were correlated with eachother (to avoid overfitting)

- Train

Trained models with various hyperparameters (Polynomial order, estimators for RFR)

- Validate

Selected the highest performing hyperparameters 

Tested
