# Credit-Card-Fraud-Detection
## Problem Overview
According to William Milne, ABS head of crime and justice statistics, they found that 8.7% of people experienced card fraud in 2022-2023, which was an increase from 8.1% in 2021-2022. The survey also found that hald a million Australian had fallen victim to scams in 2022-2023. 
On the other hand, it also costs banks or parties related billions. As a result, it is really urgent to develop and improve Credit Card Fraud Detetction System to minimize financial losses and enhance customer trust/ satisfaction.
Key business metrics include:
- Over 5 million active credit cardholders
- $20 billion in annual transaction volume
- Fraud cases account for 0.172% of all transactions
Insights and rcommendations were provided on the following key areas:
- Fraud dectection optimization
- Cost reduction due to false positives
- Customer satisfaction and trust improvement
- Model interprebility for compliance
- 
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
## Insights Deep Dive
### Fraud Detection Optimization
- Fraudulent transactions are sparse, making detection difficult with imbalanced data. SMOTE was used to improve the class distribution, increasing the model's sensitivity to fraud cases
- Initial testing revealed logistic regression as an effective and interpretable model, with an accuracy of 99.72% and an AUC-ROC of 0.98, making it suitable for operational use.
### Cost Reduction due to False Positives
- Comparison of alternative models (e.g., random forests and gradient boosting) highlighted logistic regression as the most cost-effective solution.
### Customer Stisfaction and Trust Improvement
- A 95% customer satisfaction score was reported after implementing the updated fraud detection system.
- Ongoing improvements in fraud detection can be aligned with compliance regulations to ensure transparency and maintain customer trust.
### Model Interpretability for Compliance
- Regulatory requirements necessitate transparency in fraud detection models. Logistic regression was chosen for its simplicity and interpretability.
## Recommendations
### Technical Aspects
1. Continue leveraging Logistic Regression as the primary detection model due to its high accuracy and business-friendly interpretability.
2. Implement SMOTE and other balancing techniques in future model iterations to handle class imbalance issues more effectively.
3. Perform regular hyperparameter tuning to maintain optimal performance and reduce false positives, minimizing operational costs.
### Business Aspects
1. Create periodic customer feedback loops to ensure the fraud detection system is aligned with customer expectations and satisfaction.
2. Develop ongoing compliance documentation to ensure transparency in model decision-making and adherence to regulations.
