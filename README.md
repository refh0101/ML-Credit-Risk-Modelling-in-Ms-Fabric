# ML-Credit-Risk-Modelling-in-Ms-Fabric
Building a Credit Risk Modeling system using Python and Machine Learning from scratch. Applying Scikit-learn for model training, and deploy an interactive dashboard with Streamlit.

# Introduction
In the modern financial sector, credit risk constitutes one of the most critical threats to institutional stability. Accurately predicting loan defaults is not merely a mechanism for minimizing direct financial losses, but a fundamental requirement for safeguarding asset portfolios and preventing cascading systemic failures. Machine learning provides a powerful analytical framework to mitigate these dangers by transforming historical financial behaviors into proactive risk management strategies.

To address this challenge, the renowned German Credit Data is analyzed in this study. The dataset comprises 1,000 entries, where each represents an individual bank loan application classified as either a good or a bad credit risk. The analysis is built upon a comprehensive set of personal and financial indicators, including age, sex, housing status, occupational skill level, checking and saving account balances, alongside the requested loan amount, duration, and purpose. By evaluating these critical attributes, the ultimate objective is to uncover underlying risk patterns and develop a robust predictive model for data-driven financial decision-making.


The data is gotten from kaggle link --> https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk

# Aim

- Exploratory Data Analysis (EDA): Discovering data distributions and underlying credit risk patterns.
- Data Preprocessing: Cleaning the dataset and carefully handling missing (NaN) values.
- Model Training: Building and comparing multiple classification algorithms (Logistic Regression, Naive Bayes, SVM, and KNN).
- Evaluation & Insights: Analyzing model performances and determining the most critical features for risk prediction.

## Data Description

| Variable | Description |
|---|---|
| Age | Numeric: Age of the applicant in years |
| Sex | Text: Gender of the applicant (male, female) |
| Job | Numeric: Employment status (0: unskilled & non-resident, 1: unskilled & resident, 2: skilled, 3: highly skilled) |
| Housing | Text: Living situation of the applicant (own, rent, or free) |
| Saving accounts | Text: Wealth in savings (little, moderate, quite rich, rich) |
| Checking account | Text: Status of existing checking account (little, moderate, rich), based on the balance in DM (Deutsche Mark) |
| Credit amount | Numeric: The amount of credit requested (in DM) |
| Duration | Numeric: Duration of the credit in months |
| Purpose | Text: Purpose of the loan (car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others) |
| **Risk** | Text: Final credit risk evaluation (**Target variable**: good or bad) |

# Tech Stack
 - Microsoft Fabric

# Language
 - Python


