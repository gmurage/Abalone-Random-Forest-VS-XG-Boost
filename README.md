# Abalone-Random-Forest-VS-XG-Boost
A predictive analysis project using machine learning to predict the number of rings using RSMLE with Random Forest and XG Boost amd then comparing the RSMLE obtained from the Linear Regression model.
Data is provided by Kaggle.com " Regression with Abalone Dataset". The test, train and sample_submission data is obtained from Kaggle.com as csv.
Pythom Jupyter notebooks using Anaconda are used to run the machine pipelines for random forest first, and then for XG Boost. The RMSLE obtained is improved compared to the logistic regression obtained RMSLE as you go from Logistic regression, to random trees to XG Boost.
Random Forest (RMSLE: 0.1557)
The Random Forest model performs better than Linear Regression, with a lower RMSLE of 0.1557.

Random Forest is more flexible and can capture non-linear relationships in the data, which explains the improvement.

XGBoost (Default Hyperparameters, RMSLE: 0.1531)
The XGBoost model with default hyperparameters has a lower RMSLE (0.1531) than Random Forest, making it the best-performing model so far.

XGBoost is a powerful ensemble method that often outperforms Random Forest due to its gradient-boosting framework and regularization techniques.

XGBoost (Best Model from Grid Search, RMSLE: 0.1521)
After hyperparameter tuning using Grid Search, the best XGBoost model achieves a slightly lower RMSLE of 0.1521.

This improvement shows that hyperparameter tuning can help optimize the model's performance.

XGBoost (Log-Transformed Target, RMSLE: 0.1514)
Applying a log transformation to the target variable further reduces the RMSLE to 0.1514.

Log transformation helps handle skewness in the target variable, making the model more robust to extreme values.
