# Credit-Card-Fraud-Detection
## Problem Overview
According to William Milne, ABS head of crime and justice statistics, they found that 8.7% of people experienced card fraud in 2022-2023, which was an increase from 8.1% in 2021-2022. The survey also found that hald a million Australian had fallen victim to scams in 2022-2023. 
On the other hand, it also costs banks or parties related billions. As a result, it is really urgent to develop and improve Credit Card Fraud Detetction System to minimize financial losses and enhance customer trust/ satisfaction.
## Introduction
The dataset contains transactions made by credit cards in September by European cardholders, which has 492 frauds out of **284,807 transactions**. This is indicated the **highly imbalance** of the dataset, where frauds ( Class 1) accounts for 0.172% of all transactions. 
Besides, this only contains numerical variables which are the result of **PCA transformation except Time and Amount variables**, which can be assumed that the data is scaled. However, there is limitation to explain model decisions ot interpret feature importance in business terms.
## Approach
In this project, machine learning techniques are used to develop models identifying fraudulent transactions. 
- To address the imbalance, I used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the classes in the training set.
- I choose logistic regression because of its interpretability.
- I fine-tuned the logistic regression model using **Grid Search, optimizing hyperparameters** such as regularization strength to enhance detection capabilities."
**##Steps have been done**
1. Data Exploration
2. Data splitting
3. Apply SMOTE with Logistic Regression
4. Train the model
5. Evaluation Performance
6. GridSearchCV based parameter tuning
   
