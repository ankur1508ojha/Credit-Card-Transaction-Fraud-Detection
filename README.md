# Credit-Card-Transaction-Fraud-Detection

**Data Description **
The dataset consists of 96,753 records and 10 distinct fields, documenting real card payments made between January 1, 2010, and December 31, 2010. Each record in this dataset captures essential transaction details such as card numbers, transaction dates, merchant numbers, descriptions, states, zip codes, payment amounts in US dollars, and fraud scores. (The Dataset is highly imbalanced)


This project aims to develop a supervised machine-learning model that can detect and predict credit card transaction fraud. Credit card transaction fraud is a type of fraud where someone illegally uses another person's credit card information to make unauthorized purchases or cash advances. This can result in significant financial losses for both the cardholder and the card issuer and damage to the victim's credit score. The prevalence of credit card transaction fraud has increased with the growing use of online shopping and the widespread use of credit cards for payment transactions.

To achieve our goal, we followed a process consisting of data cleaning, variable creation, feature selection, and modelling. We examined the dataset and removed any inaccuracies, generated new and insightful features from the existing data, selected the most relevant features from the dataset, and built and tested multiple machine learning models, including Logistic Regression, Random Forest, Light GBM, and Neural Network.
This report aims to document the process of creating and completing a supervised machine-learning algorithm that can detect and prevent fraud in real-time.
 
 • Data Cleaning: Examine the dataset and remove any inaccuracies 
 • Variable Creation: Generate new and insightful features from the existing data
 • Feature Selection: Select the most relevant features from the dataset. 
 • Modeling: Build and test multiple machine learning models, to determine the most efficient
   and effective model for detecting and predicting fraud in real-time.
    
**Conclusion:** After testing different algorithms, including Logistic Regression, Random Forest, Light GBM, and Neural Network, we experimented with various hyperparameter combinations for each model and compared their performance based on FDR at 3%. 

**Our machine learning model has demonstrated that we are not overfitting and achieving good performance. By rejecting the top 3% of credit card transaction applications, we are able to catch 55.63% of all fraud cases. Furthermore, the dollar savings calculated at this cut-off point for the model are estimated to be around 21 million dollars annually, indicating that our model has the potential to prevent significant financial losses due to credit card transaction fraud.
**
