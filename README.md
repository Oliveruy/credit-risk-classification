# credit-risk-classification

## Overview
The purpose of this exercise is to use various techniques to train and evaluate a model based on credit risk. In this analysis, we primarily focus on comparing the performance of logistic regression and Random Forest models.

## Summary of Findings
After conducting the analysis, the following key findings were observed:

- The logistic regression model is a good fit for this dataset due to its simplicity, interpretability, and strong performance.
- It achieved 100% precision in predicting healthy loans (`0`) and demonstrated high recall for high-risk loans (`1`).
- As a bonus, Random Forest model was also tested on the data and it showed fairly good results overall but a 5% decrease in recall for high-risk loans, suggesting it may not capture the minority class as effectively.
- This supports the recommendation that logistic regression is a simple yet effective method for this type of data, providing reliable and interpretable results.

## Repository Structure
The repository contains the following structure:

- `Credit_Risk`:
  - `notebook.ipynb`: Jupyter notebook containing the analysis on the credit risk model.
  - `resources`:
    - `lending_data.csv`: Dataset used for credit risk analysis.