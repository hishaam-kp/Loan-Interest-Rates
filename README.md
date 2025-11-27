<h1>
📊 Loan Interest Rate Prediction – Capstone Project <br>
Overview 
</h1>

This project explores how borrower characteristics influence loan interest rates using a real-world peer-to-peer lending dataset from Bondora. As a fintech analyst, I built a predictive model to estimate interest rates and uncover actionable insights for personalizing loan offers.
<br/>
<br/>
<h1>🔍 Dataset</h1>

The dataset includes over 380,000 loan records with rich borrower and loan attributes:

Demographics: Age, Gender, Country, Education, Employment Duration

Financials: Applied Amount, Received Amount, Income, Existing Liabilities

Loan Details: Loan Duration, Rating, Verification Type, Previous Loan History

Target Variable: Interest Rate

Due to size constraints, the full dataset is not hosted here. You can access the original source on Bondora P2P Loans via Kaggle. The link for it is: 
https://www.kaggle.com/datasets/marcobeyer/bondora-p2p-loans?select=LoanData.csv

<br/>
<br/>
<h1>🧪 Project Steps</h1>
<h4>1. Data Cleaning & Preprocessing </h4>

Set LoanId as index

Created new features like DebtToIncome and IsRisky to flag high-risk borrowers

Encoded categorical variables using get_dummies

<h4>2. Exploratory Data Analysis</h4>
Descriptive statistics of interest rates and loan amounts

Box plots to segment interest rates by education level

Scatter plots and correlation analysis for numeric predictors

Confidence interval estimation for loan amount discrepancies

<h4>3. Modeling</h4>
🔹 Simple Linear Regression
Predictor: AmountOfPreviousLoansBeforeLoan

R²: 0.031 — weak predictive power

🔹 Multiple Linear Regression
Predictors: Loan duration, liabilities, previous loans, and encoded categorical features

R²: 0.613 — strong model performance

All variables statistically significant (p < 0.05)

<br>
<h1>📈 Key Insights</h1>
Borrowers with lower job stability and high debt-to-income ratios tend to receive higher interest rates

Loan ratings (A to HR) are strong predictors of interest rate levels

Education and employment duration also influence loan terms

<h1>🛠️ Tech Stack</h1>
Python (Pandas, Seaborn, Matplotlib, Statsmodels, Scipy)

Jupyter Notebook

Statistical modeling and visualization

<h1>🚀 How to Run</h1>
Download the dataset from the link provided above

Clone this repository to your local machine

Open the notebook (Loan_Interest_Rate_Prediction.ipynb) in Jupyter

Run all cells sequentially to reproduce the analysis and model

<h1>📬 Contact</h1>
Created by Hishaam Khan Pathan 📧 hishaamp88@gmail.com 🔗 https://www.linkedin.com/in/hishaam-pathan-614175187/
