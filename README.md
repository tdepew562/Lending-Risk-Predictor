# Lending-Risk-Predictor
## Overview of the Analysis

In this analysis, we aimed to develop machine learning models for credit risk analysis using historical lending data from a peer-to-peer lending services company. The purpose of the analysis was to predict the creditworthiness of borrowers based on various financial attributes.

The dataset contained information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (0 for low-risk loans and 1 for high-risk loans). We explored the distribution of loan statuses using `value_counts` to understand the imbalance between the two classes.

The machine learning process involved several stages, including data preprocessing, model training, and evaluation. We used logistic regression as our primary algorithm to build predictive models due to its simplicity and effectiveness in binary classification tasks.

## Overview of the Analysis

Welcome to our credit risk analysis adventure! 🎉 In this analysis, we set out to create some cool machine learning models using data from a peer-to-peer lending company. Our goal? To predict whether borrowers are likely to be good credit risks or not, based on a bunch of financial info.

Our dataset was packed with all sorts of interesting stuff – loan sizes, interest rates, borrower incomes, you name it! We even had a special code for loan status: 0 for low-risk loans and 1 for high-risk loans. 

Before diving in, we took a quick peek at the distribution of loan statuses using `value_counts` to see how many of each type we had. Turns out, there were more low-risk loans than high-risk ones, which was good to know!

Then came the fun part – machine learning! We went through some basic steps like cleaning up the data, training our models, and checking how well they worked. And guess what? We decided to go with logistic regression because it's simple and works great for binary classification tasks.

So, get ready to join us on this epic journey as we uncover the mysteries of credit risk analysis – one loan at a time! 🚀

## Results

* Logistic Regression Model:
    * **Accuracy:** The model achieved an accuracy of 99%, meaning it correctly classified 99% of the loans in the dataset.
    * **Precision (Safe loans):** The precision for predicting safe loans (label `0`) was 1.00, indicating that almost all loans predicted as safe were indeed safe.
    * **Recall (Safe loans):** The recall for safe loans was also 1.00, meaning the model correctly identified almost all instances of safe loans.
    * **Precision (Risky loans):** For predicting risky loans (label `1`), the precision was 0.86, indicating that about 86% of loans predicted as risky were indeed risky.
    * **Recall (Risky loans):** The recall for risky loans was 0.91, indicating that the model correctly identified about 91% of actual risky loans.

## Summary

So, after diving deep into the data and crunching some numbers, it's pretty clear that the logistic regression model was best in terms of performance. With an awesome 99% accuracy and solid precision and recall scores for both safe and risky loans, the logistic regression model proved itself as a reliable credit risk predictor.

When it comes to picking the best model, the logistic regression model really shines. It does a great job at figuring out which loans are safe and which ones are risky, which is super important for lenders making lending decisions.

Now, the choice of model might vary depending on what exactly the lender is trying to do. Sometimes, it's more important to get those risky loans right to avoid big losses, while other times, nailing down the safe loans might be the top priority.

In my opinion, I'd go with the logistic regression model for credit risk analysis in this case. It's simple, effective, and easy to understand – perfect for lenders who want to make smart lending decisions without getting lost in the complexity of other models.


