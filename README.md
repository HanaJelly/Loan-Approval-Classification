# Loan-Approval-Classification

This project predicts whether a loan application will be approved or not using machine learning techniques. It implements and compares models such as Logistic Regression and Random Forest, evaluating their performance with metrics like accuracy, classification reports, and ROC-AUC scores.

## Dataset

The project utilizes the Loan Approval Classification Dataset from Kaggle, which is structured and contains features related to loan applicants, such as income, credit history, and other financial indicators. This dataset is publicly available and commonly used in machine learning and data analysis to develop models and algorithms that predict the likelihood of loan approval.

You can access and download the dataset here:
https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data

## Methodology

- **Data Preprocessing**
  The dataset was cleaned and prepared for modeling. Missing values were handled appropriately, categorical variables were encoded into          numerical form, and numerical features were scaled to maintain consistency across variables. These steps ensured the models received
  well-structured and unbiased input data.

- **Model Training**
  Two models were implemented: Logistic Regression and Random Forest. Logistic Regression was chosen for its simplicity and interpretability,    while Random Forest was used for its ability to capture non-linear relationships and improve accuracy through ensemble learning.

- **Evaluation**
  The trained models were assessed using performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. These metrics           provided a comprehensive view of how well each model predicted loan approvals.

- **Visualization**
  ROC curves were plotted to compare the models visually and analyze their ability to distinguish between approved and non-approved loans.       Additional charts helped interpret the model outputs and feature importance, offering insights into which applicant characteristics most       affected approval decisions.

## Results

The Random Forest model delivered the best performance, achieving higher accuracy and ROC-AUC compared to Logistic Regression. It demonstrated strong predictive capability in identifying approved and non-approved loan applications.

Key findings showed that factors such as applicant income, credit history, and loan amount had the most significant impact on loan approval outcomes. These insights highlight the potential of data-driven approaches to improve decision-making in financial risk assessment.

## How to Use 

1) **Download the Project**
  -Go to the GitHub page: https://github.com/HanaJelly/Loan-Approval-Classification
  -Click the green **Code** button → Choose **Download ZIP**
  -Unzip the file on your computer.

2) **Open the Project**
   -Open the unzipped folder.
   -Double-click or open the file named loan_classification.ipynb in Jupyter Notebook or Google Colab.

3) **Run the Notebook**
  -Run each cell in order to see the data preprocessing, model training, and results.
  

