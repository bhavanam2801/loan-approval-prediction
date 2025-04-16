# Loan Approval Prediction

This project predicts whether a loan will be approved or not based on various applicant details using machine learning. The model uses Logistic Regression to classify loan approval status as either "Approved" or "Rejected."

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Requirements](#requirements)
4. [Usage](#usage)
5. [Results](#results)
6. [License](#license)

## Project Overview
This project builds a machine learning model to predict loan approval status based on applicant details such as gender, marital status, education, income, credit history, and more. The dataset is preprocessed, and categorical features are encoded to prepare the data for model training.

## Dataset
The dataset used in this project contains historical loan data, which includes various features of loan applicants. These features are used to predict whether their loan application will be approved or rejected. 

### Data Columns:
- **Loan_ID**: Unique identifier for the loan.
- **Gender**: Gender of the applicant (Male/Female).
- **Married**: Marital status of the applicant (Yes/No).
- **Education**: Applicant’s education level (Graduate/Not Graduate).
- **Self_Employed**: Whether the applicant is self-employed (Yes/No).
- **ApplicantIncome**: Income of the applicant.
- **CoapplicantIncome**: Income of the coapplicant (if any).
- **LoanAmount**: The amount of loan requested.
- **Loan_Amount_Term**: Duration for which the loan is granted (in months).
- **Credit_History**: Applicant's credit history (1 = has credit history, 0 = no credit history).
- **Property_Area**: Area where the property is located (Urban/Semiurban/Rural).
- **Dependents**: Number of dependents.
- **Loan_Status**: Target variable (Y = Approved, N = Rejected).

### Download the Dataset:
You can use a similar dataset available on [Kaggle](https://www.kaggle.com/datasets) or create your own dataset following the structure mentioned above.

### Example Dataset:
For the purpose of this project, we recommend using the following dataset:
- loan_prediction.csv

## Requirements
To run this project, you'll need to install the following Python libraries:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install the required dependencies with:

```bash
pip install -r requirements.txt
