# Predicting-cool-load-using-Energy-Efficency-dataset-with-Lasso-Ridge-ElasticNet


In this analysis, we worked with a dataset containing information related to building energy efficiency. We started by loading the dataset and selected relevant columns for analysis. The dataset included features like relative compactness, surface area, wall area, roof area, overall height, orientation, glazing area, glazing area distribution, and cooling load.

We checked for missing values, and fortunately, there were none. To ensure consistency, we filled any potential missing values in specific columns with zeros. Then, we prepared the data for modeling, splitting it into features (X) and the target variable (y). We further divided the data into training and testing sets.

We performed K-fold cross-validation with K=5 for three different regression models: Lasso Regression, Ridge Regression, and Elastic Net Regression. Each model was trained and evaluated using cross-validation to assess its performance.

The results of cross-validation showed promising results for all three models, with varying R-squared values. Ridge Regression consistently performed the best among the models, followed by Lasso Regression and Elastic Net Regression.

Finally, we calculated the Mean Squared Error (MSE) for each model using the test data to measure prediction accuracy. Ridge Regression achieved the lowest MSE, indicating its superior predictive performance on the test set.

In summary, we conducted a comprehensive analysis of building energy efficiency using different regression models and found that Ridge Regression provided the most accurate predictions for cooling load based on the given features.
