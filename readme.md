# Sales Forecasting
This project is a sales forecasting solution using machine learning. It imports necessary libraries, loads the dataset, performs some exploratory data analysis (EDA), creates features, trains a model, and makes predictions.

The notebook and dataset can be found in [Kaggle](https://www.kaggle.com/code/sherpalakpa18/sales-forecasting-using-lr-rf-and-xgboost) and consists of historical sales data for 10 different stores and 50 different items. The goal is to predict the number of sales for the future days.

The code creates time series features based on the index of the data, such as the day of the week, the month, and the year. It then performs some EDA on the data, plotting sales data over time, and boxplots of sales by week, month, and quarter.

The model used are Linear Regression, Random Forest and XGBoost Regressor and compared side by side using error estimator like MAE, RMSE and R2 Score. It is trained on the training set and validated on the test set. The features used for the model are the day of the year, day of the week, quarter, month, and year. The model is then used to make predictions on the test set, and the results are plotted against the actual sales data.

## Author
This program was created by [Lakpa Sherpa](https://slakpa.com.np).
