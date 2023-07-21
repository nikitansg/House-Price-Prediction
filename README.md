# House-Price-Prediction
This project focuses on predicting the sale prices of residential homes in Ames, Iowa, using machine learning regression algorithms. The rising house prices make accurate predictions crucial for both developers and clients. The goal is to develop a robust predictive model that can help developers determine the selling price of a house and aid clients in deciding the best time to make a purchase. The dataset used for this project is the Ames Housing dataset, obtained from Kaggle, containing 79 variables that influence house prices.

The project involves the following key steps:

1. Data Exploration and Preprocessing: The dataset will be explored to understand the features and their relationships with the target variable (sale prices). Data preprocessing techniques will be applied to handle missing values, categorical variables, and feature engineering for better model performance.
2. Model Selection: Various regression algorithms will be applied, including Linear Regression, Lasso, Ridge, Support Vector Regression with radial basis function (SVR-rbf), Support Vector Regression with polynomial kernel (SVR-poly), and Gradient Boosting Regressor. Each algorithm will be evaluated to determine its performance.
3. Hyperparameter Optimization: Grid search will be used to find the optimal hyperparameters for each regression algorithm. This process aims to fine-tune the models for better accuracy.
4. Ensemble Learning: The Gradient Boosting Regressor, an ensemble learning technique, will be used to combine the predictions of multiple models and further enhance prediction accuracy.
5. Evaluation and Validation: The models will be evaluated using various metrics such as mean squared error, mean absolute error, and R-squared. K-Fold cross-validation will be applied to validate the model's generalization performance.
6. Prediction: The final trained model will be used to make predictions on new data, providing estimates for house sale prices.
   
Data Source: ‘House Prices: Advanced Regression techniques’ https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview
