# Ames-Housing-Project

## Purpose of Project: 

This project uses a dataset of housing sales in Ames Iowa (go Cyclones!) from 2006 to 2010. TThe purpose of the project was to predict house sales using a variety of features related to the quality and physical attributes of the house. 

The project involved a train and test dataset. The train dataset includes the target variable of SalePrice, while the test dataset does not. As part of the project, a Kaggle challenge was set up, not available to the public, just for class, and I predicted sale prices on the test dataset. 

## Process: 

1. Cleaning and EDA: In this notebook, I examine the dataset, deal with null values, dummy code the categorial variables, and do some basic plots and correlations. 

2. Regression Models. In this notebook, I use three models to predict Sale Price: Basic linear regression, Lasso regularization, and a stacked model of several regression models. The Lasso model won with an R-squared of .96. 
