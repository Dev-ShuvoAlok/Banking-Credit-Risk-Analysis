# Credit-Card-Fraud-Detection
In this project we have use various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud. 

# Our Goals:
- Understand the little distribution of the "little" data that was provided to us.
- Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions. (NearMiss Algorithm)
- Determine the Classifiers we are going to use and decide which one has a higher accuracy.
- Create a Neural Network and compare the accuracy to our best classifier.
- Understand common mistaked made with imbalanced datasets.

# Challenges 
- the most important challenge here is to handle data imbalance. the number of Fraud transection is much less than comparing to Non-fraud transection. In ML, data balancing is crucial because it has a huge impact in model training. In this project, we have implemeted several data balancing method to handle this cahllenges and improve model perfromance.

# The Technique We have implemeted:

For Feature Selection:
-  t-sne + pca
-  Anova
  
For Handeling Imbalance:
- Random Undesampling
- SMOTE
- Combination of SMOTE + UnderSampling

Machine Learning Model:
- KNN
- Logistic Regreesion
- Decision Tree
- Random Forest
- Nweural Network
