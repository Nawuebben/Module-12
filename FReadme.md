# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Purpose of Analysis: The intentions of the following analysis is to create and asses a machine learning model that attempts to forecast the credit-worthy customers who are attempting to borrow.

Financials: The data model is tasked with predicting the appropriate loan status for the client. The prediction is classified as either, healthy, or high-risk. The financial data that was used in the model prediction were the following: Loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and loan status.

Variables and Data information:

* Borrower Income: Refers to the amount of income the borrower makes; important variable when considering the feasibility of repayment.
* 
* Debt to Income: The debt-to-income ratio is measured by taking the amount of debt divided by the income.
* 
* Loan Size: The amount of the loan (dollars).
* 
* Interest Rate: The rate at which the interest is charged on the loan.
* 
* Total Debt: The total amount of debt accrued upon the borrower over all held accounts.
* 
* Derogatory Marks: Refers to the borrowers credit report, marks may include such things as: late payments, defaults, and other negative financial markers.
* 
* Number of Accounts: The number of accounts help by the borrower that is in consideration.
* 
* Loan Status: The final product of the analysis; determines whether the applied for loan is a high-risk loan or whether the loan has a healthy amount of risk.
* 
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
 
  * Accuracy: 95.2%
  * Class 0 - Healthy - Precision: 1.00, Recall: 0.99
  * Class 1 - High Risk - Precision: 0.85, Recall: 0.91



* Machine Learning Model 2:(OverSampled)
  * Description of Model 2 Accuracy, Precision, and Recall scores.
 
  * Accuracy: 99.36%
  * Class 0 - Healthy - Precision: 1.00, Recall: 0.99
  * Class 1 - High Risk - Precision: 0.84, Recall: 0.99

## Summary

   * The second machine learning model provided the best Accuracy. This is in part because in designed to do so; Oversampling makes minority classes more expressive and therefore helps boost accuracy. The flaw to this method is that it could possibly lead to bias in the model, but in this case I believe that the oversampling method that was deployed created a better tool for forecasting future loan status'.


