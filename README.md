# Mental Fitness Tracker

Predicting Disability-Adjusted Life Years (DALYs) for Mental Health Disorders

Purpose:
The purpose of this project is to develop a machine learning model that predicts the Disability-Adjusted Life Years (DALYs) associated with mental health disorders for different countries. DALYs provide a comprehensive measure of the burden of disease by considering both mortality and disability. By accurately predicting DALYs, this project aims to provide valuable insights into the impact of mental health disorders on population health and guide policy decisions, resource allocation, and intervention strategies.

Scope:
The project focuses on mental health disorders, including anxiety disorders, schizophrenia, bipolar disorder, eating disorders, depressive disorders, and other relevant conditions. It considers data from the years 1990 to 2019, covering a 30-year period. The analysis is conducted at a country level, aiming to provide predictions and insights for each individual country.

Results: The models used are SVR regressor, Decision Tree Regressor and Linear Regression. The model which gave the highest accuracy and lowest mean-squared error is Decision Tree Regressor with criterion as "Poisson" with an accuracy of 0.9847 and MSE of 0.28006. Used hyper parameter testing for SVR regressor which gave values for "C", "gamma", and "kernel" of 1000, 1 and "rbf" respectively which ended up giving an accuracy of 0.98214 and MSE of 0.30311. Linear Regression gave the least accuracy of 0.72923 and MSE of 1.1804. 
