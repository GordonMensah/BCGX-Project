# BCGX-Project

## Overview 
The BCGX Project analysis the Data of PowerCo , a major gas and electricity utility that supplies to corporate, SME (Small & amp; Medium Enterprise), and residential customers, The aim of this project was todiagnose the source of churning SME customers. Price sensitivity was a hypothesis for the churn. 
In this analysis I found the correlation between the different parameters given in the data and Churn to be high , compared to the hypothesis

Performed data cleaning
Data Preparartion and Transformation 
Feature Engineering 
Hyperparameter Tuning
Machine Learning Modeling Using RandomForest



#BUSINESS OBJECTIVE

Total number of Churned Customers
Factors leading to churn
General Trends on the Data set
Recommendation


#DATA CLEANING

Added features:number of Monthly subscribers,Month and year the subscription began, tottal number of years the subscription was active.
Corrected Skewness In the data
Analysed features that were of importance and if they had an increasing or decreasing regression

#DATA MODELLING
Random Forest was used for the classification and prediction of the model
Correlation was checked usng a heat map and some features were dropped(Num_of_sub_years', 'has_gas','margin_net_pow_ele', 'price_mid_peak_fix','price_off_peak_var','price_peak_fix','price_peak_var','year_sub_began')
Model was recheked after dropping features
Confusion Matrix Was used to confirm changes made and Random DData Sampling was done to balance the data
Hyperparameter Tunning was finaly done to ensure increased Accuracy and Precision


# INSIGHTS
Forecast meter, net margin, consumption and the net power posed posed as the main indicators for churn.
The price wasnt a concern but quality of services given by the company, Suggestions were made to look into complaints and sentiments of customer, Fact checking if customers that churned made calls or reports on certain issues
