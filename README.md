# Credit-Scoring---Segmentation

## 📌 Overview

- Credit scoring and segmentation refer to the process of evaluating the creditworthiness of individuals or businesses and dividing them into distinct groups based on their credit profiles. It aims to assess the likelihood of borrowers repaying their debts and helps financial institutions make informed decisions regarding lending and managing credit risk.

- These credit scores are numerical representations of the borrower’s creditworthiness and indicate the likelihood of default or timely repayment. Once the credit scores are calculated, customers are segmented into different risk categories or credit tiers based on predefined thresholds.

## Dataset Decsription
- Age: This feature represents the age of the individual.
- Employment Status: This feature indicates the current employment status of the individual.
- Credit Utilization Ratio: This feature reflects the ratio of credit used by the individual compared to their total available credit limit.
- Payment History: It represents the monthly net payment behaviour of each customer, taking into account factors such as on-time payments, late payments, missed payments, and defaults.
- Number of Credit Accounts: It represents the count of active credit accounts the person holds.
- Loan Amount: It indicates the monetary value of the loan.
- Interest Rate: This feature represents the interest rate associated with the loan.
- Loan Term: This feature denotes the duration or term of the loan.
- Type of Loan: It includes categories like “Personal Loan,” “Auto Loan,” or potentially other types of loans.

## 🚀 Project Flow
### 1. 📂 Dataset Collection
Collecting the required dataset from open sources related to customer credits.

### 2. 🔍 Exploratory Data Analysis
Deriving insights from our data using:
- Histograms
- Bar graphs
- Heatmaps

 ### 3. 🗺️ Define Mapping Levels
Defining the mapping levels followed by applying maps to necessary columns.

### 4. 🛠️ Feature Engineering
Deriving a new column named credit scores, which is essential for segmenting the customers.

### 5. 📈 Applying KMeans Clustering
Using KMeans clustering to segment the credit scores.

## 📊 Credit Score Calculation
The credit score is calculated using the following formula:

Credit Score = (payment_history * 0.35) + (credit_utilization_ratio * 0.30) + (number_of_credit_accounts * 0.15) + (education_level * 0.10) + (employment_status * 0.10)

## 🏷️ Segments
The credit scores are segmented into the following categories:
- **0**: 'Low'
- **1**: 'Good'
- **2**: 'Very Low'
- **3**: 'Excellent'

## 📈 Results
### Visualizations
![Visualization 1](path_to_image1.png)
![Visualization 2](path_to_image2.png)

## 📜 Summary
This project provides a comprehensive approach to credit scoring and segmentation, enabling financial institutions to make informed lending decisions and effectively manage credit risk.
