# Sales Forecasting
This project is a sales forecasting solution using machine learning. It imports necessary libraries, loads the dataset, performs some exploratory data analysis (EDA), creates features, trains a model, and makes predictions.

The dataset is loaded from a [Kaggle competition Dataset](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data?select=train.csv) and consists of historical sales data for 10 different stores and 50 different items. The goal is to predict the number of sales for the future days.

The code creates time series features based on the index of the data, such as the day of the week, the month, and the year. It then performs some EDA on the data, plotting sales data over time, and boxplots of sales by week, month, and quarter.

The model used is an XGBoost Regressor. It is trained on the training set and validated on the test set. The features used for the model are the day of the year, day of the week, quarter, month, and year. The model is then used to make predictions on the test set, and the results are plotted against the actual sales data.