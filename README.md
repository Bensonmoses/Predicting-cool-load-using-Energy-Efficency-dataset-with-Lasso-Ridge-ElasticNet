# Predicting-cool-load-using-Energy-Efficency-dataset-with-Lasso-Ridge-ElasticNet


In this project, we loaded a housing dataset using Pandas, containing information about various housing attributes like price, area, bedrooms, bathrooms, stories, and categorical features. We conducted data exploration, finding no missing values, and retained all 545 rows.

Next, we explored correlations between numerical features and "price." Notably, "area" and "bathrooms" had strong positive correlations. We preprocessed the data, applied one-hot encoding to categorical features, and standardized numerical features.

Data was split into training and testing sets (70:30 ratio) and scaled. A Logistic Regression classifier was used for predictions, though it's primarily for classification, which may not be ideal for regression.

Principal Component Analysis (PCA) was applied for dimensionality reduction to two components, capturing a significant portion of variance.

Model evaluation metrics include Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and R-squared (R2). MAPE and RMSE were relatively high, indicating significant prediction errors. A negative R2 score is unexpected, suggesting potential issues with model performance or evaluation.

A scatter plot visualized predicted vs. actual median house values.

In summary, our initial model using Logistic Regression yielded suboptimal results. Further exploration, feature engineering, or different regression algorithms may improve predictive accuracy for house prices.
