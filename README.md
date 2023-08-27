# Data-Scientist-ID-X-Partners-x-Rakamin-Academy

This project is a credit risk prediction model aimed at predicting customers who are at potential risk of defaulting on their loans based on historical loan data. The process begins with data cleaning and preprocessing, including converting non-numeric columns to numeric and removing columns with more than 50% missing values. The data used for this project is sourced from Kaggle and can be accessed through the following link: https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014. Subsequently, the data is split into training and testing sets, with special attention to the imbalanced class distribution. Feature engineering involves creating new columns that measure the duration since certain important dates. The model used in this project is Logistic Regression, with the determination of the optimal probability threshold based on the ROC curve. The final model provides insights into factors contributing to credit default risk, such as loan duration, employment length, and prior payment history.
