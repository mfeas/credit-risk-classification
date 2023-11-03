# credit-risk-classification

Module Twenty

## Overview of the Analysis

I used machine learning to analyze lending data for a financial institution. The data included loan details like size, interest rate, borrower's income, ect. The goal was to predict if loans were healthy or high-risk. I divided the data, trained a model using LogisticRegression on the training set, and tested its predictions. I also tried a second model with oversampled data to see if it improved predictions.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- Machine Learning Model 1:

  - Model 1 Accuracy: 99%
  - Precision for Healthy Loans: 1.00 (100% accurate)
  - Precision for High-Risk Loans: 0.85 (15% misclassified as healthy)
  - Recall for Healthy Loans: 0.99 (99% correctly identified)
  - Recall for High-Risk Loans: 0.91 (9% misclassified as healthy)

- Machine Learning Model 2:
  - Model Accuracy: 99%
  - Precision for Healthy Loans: 1.00 (100% accurate)
  - Precision for High-Risk Loans: 0.84 (16% misclassified as healthy)
  - Recall for Healthy Loans: 0.99 (99% correctly identified)
  - Recall for High-Risk Loans: 0.99 (1% misclassified as healthy)

## Summary

If your priority is avoiding high-risk loans, I would recommend using Model 2. While it has a slightly lower precision for high-risk loans (84% compared to 85% in Model 1), it significantly outperforms in high-risk recall (99% versus 91% in Model 1). This means that although both models have a similar rate of misclassifying loans as high-risk, Model 2 misses fewer actual high-risk loans (1% compared to 9% in Model 1). Both models excel in precision and recall for healthy loans.
