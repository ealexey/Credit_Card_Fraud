# Credit card fraud prediction

The code for the project is located in Credit_card_fraud.ipynb

## Data 
In the current project, a data set from the US Irvine Machine Learning Repository was analyzed. The data set includes transactions made by credit cards during two days in September 2013 in Europe. There are totally 284,807 transactions. Among these transactions 492 are fraudulent. The dataset is highly imbalanced because fraudulent transactions account for 0.172% of all transactions. The data set contains totally 31 variables. 28 variables are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features are not provided. Two feature variables 'Time' and 'Amount' are not transformed by PCA. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The ‘Time’ variable is irrelevant to the current study and was deleted from the data frame. The feature 'Amount' is the transaction amount. The variable 'Class' is the target variable and it takes value 1 in case of fraud and 0 otherwise. 

## Goal of the project
The goal of this project is to build a few ML models, select the best one and select several the most important features in predicting fraud.

## Algorithms.
Decision Tree, Random Forest, and Logistic regression were used to build models.


## Conclusion
The best performance to detect credit card fraud showed the logistic regression model with threshold 0.001644
The six top important features to detect fraud are V4, V10, V14, V20, V9, V17

