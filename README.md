# Machine-Learning-Algorithm-to-Predict-Loan-Repayment
## Project Overview
This project was developed during ITADATHACK2024, an Italian university-focused hackathon. The goal was to build a machine learning model capable of predicting whether a customer would be able to repay their debt.

## Dataset
The dataset was provided by an Italian company specializing in software for banks. Due to data privacy and proprietary concerns, the dataset cannot be made publicly available. The data includes the credit history of millions of customers, divided into 20 periods (each period representing 4 months). The key feature of the dataset is the column "repays_debt" (0 or 1), which indicates whether the customer repaid their debt. This column served as the target variable for the testing phase of the competition.

The aim of the project was to develop a machine learning model capable of predicting the outcome of the "repays_debt" column. One of the main challenges was dealing with highly imbalanced data, which made the prediction task more complex.

## Initial Implementation
We experimented with various algorithms, including Random Forest, Neural Networks, Linear Regression, and Logistic Regression. After evaluating their performance, we decided to use XGBoost, primarily for its efficiency. It became evident that the choice of algorithm had less impact on the results compared to how the data was handled.

## Final Solution
XGBoost was selected due to its speed, which allowed us to explore different approaches within the limited time available. We implemented several key data preprocessing steps:

* Outlier Management: Identified and handled outliers in the dataset.
* Feature Segmentation: Classified features into numerical and categorical types.
* Feature Engineering: Created new features to enhance the model's predictive power.
* Data Balancing: Addressed the issue of imbalanced data to improve model performance.
  
After these preprocessing steps, we proceeded with the training and testing phases. The final model performed well, earning us a place in the top 10 of the final leaderboard.
