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


Metrics Explained
R-squared (R2):

This metric indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

A R-squared value of 1 indicates a perfect fit, meaning the model explains all the variability in the target variable.
A R-Squared value of 0 indicates that the model does not explain any variability in the target variable.


Mean Absolute Error (MAE):

MAE measures the average magnitude of the errors in a set of predictions, without considering their direction (i.e., it's a measure of prediction accuracy).
It is calculated as the average of the absolute differences between predicted values and observed values.
Lower MAE values indicate better model performance.


Time Taken:

This metric measures the computational time required to train and evaluate the model.
Shorter times are better, especially for large datasets or when computational resources are limited.
Results


Model Performance
Linear Regression:

R-Squared: 0.8849866646482115
MAE: 2816.6087291319423
Time Taken: 0.0026941299438476562 seconds
Interpretation: Good R-Squared indicating a decent fit, but relatively high MAE.

DecisionTree:
R-Squared: 0.9423155803979703
MAE: 822.3256961999989
Time Taken: 0.006546974182128906 seconds
Interpretation: Excellent R-Squared indicating a very good fit, and low MAE, suggesting high accuracy.

RandomForest:
R-Squared: 0.9911922648688082
MAE: 377.234870041499
Time Taken: 0.31728672981262207 seconds
Interpretation: Outstanding R-Squared indicating almost perfect fit, and very low MAE, indicating high accuracy. However, it takes longer to compute.

MLP (Multi-Layer Perceptron):

R_Squared: 0.9462261037256653
MAE: 1394.7935544029287
Time Taken: 3.6834280490875244 seconds
Interpretation: Very good R-Squared and reasonably low MAE, but much higher computational time compared to other models.


Support Vector Regression (SVR):
R-Squared: 0.007294690769123702
MAE: 34838.30757195061
Time Taken: 0.06341719627380371 seconds
Interpretation: Extremely poor performance with very low R-Squared and very high MAE, indicating it is not suitable for this dataset.
XGBoost:

R-Squared: 0.9431746126142454
MAE: 963.8603035500003
Time Taken: 0.17070913314819336 seconds
Interpretation: Excellent R-Squared and low MAE, indicating high accuracy, with moderate computational time.

Top Two Models
RandomForest:

R^2: 0.9911922648688082
MAE: 377.234870041499
Time Taken: 0.31728672981262207 seconds
Reason: This model has the highest R-Squared indicating the best fit, and the lowest MAE, indicating the highest accuracy. Although it takes longer to compute compared to some other models, the accuracy benefits outweigh the computational cost.

DecisionTree:

R^2: 0.9423155803979703
MAE: 822.3256961999989
Time Taken: 0.006546974182128906 seconds
Reason: This model also performs very well with a high R-Squared and low MAE, and it has a very short computation time, making it efficient and effective.


Summary
The RandomForest regressor stands out as the best overall performer with the highest  R-Squared and lowest MAE, making it highly accurate for predicting profits in this case. The DecisionTree regressor also performs excellently, balancing high accuracy with extremely efficient computation time.
