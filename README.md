# AP-Moller-DSML-Challenge

## Methodology and Approach
1. Importing libraries and loading the dataset
2. Looking up for basic info and datatypes of the dataset
3. Visualising the distribution of categrorial variables in the dataset.
4. Exploring the numerical variables; understanding the skewness and thus to identify and remove outliers.
5. Dropping uncessary columns of the dataset.
6. Visualising the mean and median of sourcing cost w.r.t the categorical variables.
7. Understanding Source Costing Range within Categorical Columns
7. Label Encoding the Categorical Variables
8. Plotting the correlation matrix
9. Pointing out key insights from preprocessing and EDA.
10. Creating train and val set for model training.
11. Training Approach 1:
Simple application of regression models on the data:
Models: Linear Regression Model, Ridge Regression Model, Lasso Regression Model, Elastic Net Model, Random Forest Regressor, Gradient Boosting Regressor
12. Training Approach 2:
Applying hyperparameter tunning to the highest perfroming models of Training Approach I.
Models: Random Forest Regressor, Gradient Boosting Regressor
13. Training Approach 3:
Appying PCA to dataset and then training model
Models: Models: Random Forest Regressor, Gradient Boosting Regressor
14. Visualising the best model on test data
15. Conclusion and Result
16. Saving the model as pkl file

## Conclusion and Result
Out of all the models and approaches applied, PCA applied dataset + fine-tunned Gradient Boosting Regressor gave teh best results, with t=least difference between validation and test results
Validation Results:
R2 Score: 0.5735
RMSE: 32.3668
Test Results:
R2 Score: 0.3955
RMSE: 40.4959
