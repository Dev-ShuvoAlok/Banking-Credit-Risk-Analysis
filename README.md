# 1. Credit-Card-Fraud-Detection
In this project we have use various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud. 

## Our Goals:
- Understand the little distribution of the "little" data that was provided to us.
- Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions. (NearMiss Algorithm)
- Determine the Classifiers we are going to use and decide which one has a higher accuracy.
- Create a Neural Network and compare the accuracy to our best classifier.
- Understand common mistaked made with imbalanced datasets.

## Challenges 
- the most important challenge here is to handle data imbalance. the number of Fraud transection is much less than comparing to Non-fraud transection. In ML, data balancing is crucial because it has a huge impact in model training. In this project, we have implemeted several data balancing method to handle this cahllenges and improve model perfromance.

## Things we have done here:
- Done Exploratory Data Abalysis
  - find relation between data
  - find their distribution and other related statistics
  - etc.
- Done Feature Selection:
  -  t-sne + pca
  -  Anova
- Handele Data Imbalance:
  - Random Undesampling
  - SMOTE
  - Combination of SMOTE + UnderSampling
- Apply  Machine Learning Model:
  - KNN
  - Logistic Regreesion
  - Decision Tree
  - Random Forest
  - Nweural Network
- Evalue Model using
  - matirces such as accuracy,precision etc.
  - Confusion matrices
    
# 2. Personal-Bank-Loan-Classification
To use different classification models to predict the likelihood that a customer will buy a personal loan.

## Problem
- To predict whether a liability customer will buy a personal loan or not.
- Which variables are most significant.
- Which segment of customers should be targeted more.
- Does Age have any impact of customer buying loan?
- Do people with less income borrow loans .?
  
## Objective
- To use different classification models to predict the likelihood that a customer will buy a personal loan.

# 3. Loan-Eligibility-Prediction-Using-ML-Models
It is expected that the development of ML models that can help the company predict loan approval in accelerating decision-making process for determining whether an applicant is eligible for a loan or not.

## Objectives of Notebook
This notebook aims to:
- Analyze customer data provided in data set (EDA)
- Build various ML models that can predict loan approval

## The machine learning models used in this project are:

- Logistic Regression
- K-Nearest Neighbour (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest
- Gradient Boost

# 4. Bank Marketing Campaign for Opening a Term Deposit 

## Objectives

In general, datasets which contain marketing data can be used for 2 different business goals:

- Prediction of the results of the marketing campaign for each customer and clarification of factors which affect the campaign results. This helps to find out the ways how to make marketing campaigns more efficient.
- Finding out customer segments, using data for customers, who subscribed to term deposit. This helps to identify the profile of a customer, who is more likely to acquire the product and develop more targeted marketing campaigns.


## Approach

In order to optimize marketing campaigns with the help of the dataset, we will have to take the following steps:

- Import data from dataset and perform initial high-level analysis: look at the number of rows, look at the missing values, look at dataset columns and their values respective to the campaign outcome.
- Clean the data: remove irrelevant columns, deal with missing and incorrect values, turn categorical columns into dummy variables.
- Use machine learning techniques to predict the marketing campaign outcome and to find out factors, which affect the success of the campaign.

## Conclusion
Key outcomes of the analysis are the recommendations for future marketing campaigns:

1. The customer's account balance has a huge influence on the campaign's outcome.
2. People with account balance above 1490$ are more likely to subscribe for term deposit, so future address those customers.
3. The customer's age affects campaign outcome as well. Future campains should concentrate on customers from age categories below 30 years old and above 50 years old.
4. Number of contacts with the customer during the campaign is also very important. The number of contacts with the customer shouldn't exceed 4.


