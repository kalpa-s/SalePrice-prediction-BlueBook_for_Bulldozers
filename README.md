# SalePrice-prediction-BlueBook_for_Bulldozers
 This repo contains code for [Blue Book for Bulldozers competition](https://www.kaggle.com/competitions/bluebook-for-bulldozers), hosted by Kaggle.<br>
## Main Goal of this project
Predicting the future sale price of a particular piece of equipment at auction, based on it's usage, equipment type, configuration and historical data of similar equipments sold.

## Business Context
Predicting Sale Price provides a valuable insight for a business when buying, selling or analyzing market dynamics.

When analyzing a business's own inventory, a reliable price prediction model can have a say in creating annual budgets and projecting revenue. Additionally, the information gained, sheds light on important features that tend to have the biggest impact on sale price at auction time. <br><br>
Knowing these features can inform a business on how to build and maintain inventory that holds value over time. This insight can additionally help with budgeting and negotiating during purchase.

## Problem Definition
 * We are attempting to predict a number so the problem we are exploring is a <b>Regression problem</b>.<br>
 * There is a time attribute associated to the dataset, so this is a <b>Time Series problem</b>, as we have to analyze a sequence of data points collected over an interval of time.
 
## Dataset
* The data is downloaded from the Kaggle Bluebook for Bulldozers competition: [https://www.kaggle.com/c/bluebook-for-bulldozers/data](https://www.kaggle.com/c/bluebook-for-bulldozers/data)
* This dataset consists of data from auction postings and sales prices. It includes information on the usage and specifications of the machinery.
* It has 412,698 rows and 52 features, with <b>"SalePrice"</b> being the target column.
* Kaggle provides a [data dictionary](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data) which contains information about what each attribute of the dataset means.

## Steps involved in this project:
1. Installing the necessary Tools.
2. Loading the data
3. Data Analysis
4. Feature Engineering
5. Model Building
6. Evaluation
7. Hyperparameter Tuning
8. Make predictions on Test Data
9. Save predicted vales to csv file

## Tools and Methods Used
Python 
* Data Processing - Pandas, Numpy
* Machine Learning - Scikit-learn, `Random Forest Regression model`
* Data Visualization - Matplotlib, seaborn
* Evaluation metrics - RMSLE, MAE, R^2
