# Company Profitability Prediction Project

Purpose

The purpose of this project is to analyze and predict a company's profitability based on various factors such as R&D Spend, Administration, and Marketing Spend. By understanding the relationship between these factors and profit, we aim to develop a predictive model that can assist in decision-making processes within the company.

Dataset

The dataset used in this project contains the following columns/features:

R&D Spend,
Administration,
Marketing Spend,
Profit


Methodology

Exploratory Data Analysis (EDA):
Utilized various techniques including dist-plots, scatterplots, and histograms to understand the distribution and relationships within the dataset.


Regression Models:
Implemented several regression algorithms to predict profitability:
Linear Regression (lr)
Decision Tree Regression (dt)
K-Nearest Neighbors Regression (kn)
Random Forest Regression (rf)
Support Vector Regression (svr)


Data Preprocessing:
Applied log transform using numpy to handle outliers and improve model performance.


Results

Performance of Regression Models:
Linear Regression (lr):
R-squared: 0.9828,
Mean Absolute Error: 1271.04,
Time taken: 0.0027 seconds,
Description: Achieved the highest predictive accuracy among the models tested.


Decision Tree Regression (dt):
R-squared: 0.9422,
Mean Absolute Error: 879.02,
Time taken: 0.0058 seconds,
Description: Showed competitive performance, but with potential for overfitting.


Random Forest Regression (rf):
R-squared: 0.9983,
Mean Absolute Error: 279.06,
Time taken: 0.3560 seconds,
Description: Demonstrated robust performance, balancing bias and variance effectively.


MLP Regression (mlp):
R-squared: 0.9424,
Mean Absolute Error: 1861.60,
Time taken: 3.6188 seconds.


Support Vector Regression (svr):
R-squared: 0.0092,
Mean Absolute Error: 34789.77,
Time taken: 0.0588 seconds.
Description: Performed relatively less accurately compared to other models, possibly due to the complexity of the dataset.
