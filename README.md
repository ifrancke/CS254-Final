# CS254-Final
Final project for CS254 Machine Learning by Gabriela Salazar Lopez, Chongqing Gao, Lichao Yang, and Isabelle Francke

Summary: Code for creating and evaluating a machine learning model that predicts the severity of depression based on patient data. 
We used the [2019 NHIS adult interview dataset](https://www.cdc.gov/nchs/nhis/2019nhis.htm) to train our model. 

## Scripts contained in this repo:

InitialDataExploration.pynb: exploring dataset, looking at size, missing data, datatypes, etc

inital_model_data_preprocessing.pynb: preprocessing/cleaning of data for training initial model 

Data_Cleaning_Final.pynb: final data cleaning, removes irrelevant columns, removes missing data codes for numerical and categorical ordinal data without N/A's, replaces appropriate NaNs with an N/A code for categorical data, splits into training and testing data, normalizes numerical data, one-hot encodes nomical categorical data

RandomForest.pynb: training for initial random forest model 

RandomForestFinalModelParameterOptimization.ipynb: optimization and training for final random forest models including parameter search with cross-validation

RandomForestFeatureSelection.pynb: analyzes feature importance using permutation and iteratively selects features using cross validation

Logistic_Regression.ipynb: training for initial logistic regression

SVM.ipynb: training for initial SVM model with binary encoding

