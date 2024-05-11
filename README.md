# Lending-Risk-Predictor

# Overview

Welcome to our credit risk analysis project! 🚀 This project aims to explore the fascinating world of machine learning in the realm of finance, specifically credit risk analysis. Whether you're a seasoned data scientist or a curious student eager to learn, there's something here for everyone.

## Prerequisites

Before diving into the project, make sure you have the following installed:

- Python (version 3.0 or higher)
- Jupyter Notebook (for running the analysis)
- Libraries: pandas, numpy, scikit-learn (for machine learning)
  
## Usage

1. **Navigate to the Project Directory**: Open your terminal or command prompt and use the `cd` command to navigate to the directory where the repository was cloned:

    ```bash
    cd Lending-Risk-Predictor
    ```

2. **Open the Jupyter Notebook**: Launch Jupyter Notebook by running the following command:

    ```bash
    jupyter notebook
    ```

    This will open a new tab in your web browser with the Jupyter Notebook interface.

3. **Run the Notebook**: In the Jupyter Notebook interface, navigate to the `credit-risk-analysis.ipynb` notebook and click on it to open it.

4. **Execute the Cells**: Follow the instructions in the notebook to execute each cell and run the analysis.

That's it! You're now ready to explore credit risk analysis using machine learning on your local machine.

## Overview of the Analysis

Welcome to our credit risk analysis adventure! 🎉 In this analysis, we set out to create some cool machine learning models using data from a peer-to-peer lending company. Our goal? To predict whether borrowers are likely to be good credit risks or not, based on a bunch of financial info.

Our dataset was packed with all sorts of interesting stuff – loan sizes, interest rates, borrower incomes, you name it! We even had a special code for loan status: 0 for low-risk loans and 1 for high-risk loans. 

Before diving in, we took a quick peek at the distribution of loan statuses using `value_counts` to see how many of each type we had. Turns out, there were more low-risk loans than high-risk ones, which was good to know!

Then came the fun part – machine learning! We went through some basic steps like cleaning up the data, training our models, and checking how well they worked. And guess what? We decided to go with logistic regression because it's simple and works great for binary classification tasks.

So, get ready to join us on this epic journey as we uncover the mysteries of credit risk analysis! 🚀

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

## Acknowledegments

Special thanks to [ChatGPT](https://www.openai.com/gpt) for providing assistance and guidance during the development of this project.

Special thanks to Berkely Data Analytics for providing code snippets and resources used in this project. [UC Berkeley Extension](https://extension.berkeley.edu/)

### Source Code

Special thanks to the contributors of the UCB-VIRT-DATA-PT-11-2023-U-LOLC GitHub repository for providing valuable code and resources used in this project.


