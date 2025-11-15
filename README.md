# Predicting-loan-payback
Predict the probability that a borrower will pay back their loan.

1. Borrower’s Demographics

age (int64) – Borrower's age (in years).

gender (category) – Borrower's gender (Male/Female).

marital_status (category) – Marital status (Single, Married, Divorced).

education_level (category) – Education level (High School, Bachelor, Master, PhD).

2. Financial Information

annual_income (float64) – Borrower's yearly income.

monthly_income (float64) – Borrower's monthly income.

employment_status (category) – Current employment type (Employed, Self-Employed, Unemployed).

debt_to_income_ratio (float64) – Ratio of borrower’s debt to their income. Lower = better.

credit_score (int64) – Credit bureau score (e.g., FICO). Higher = less risky.

3. Loan Information

loan_amount (float64) – Amount of loan taken.

loan_purpose (category) – Loan purpose (Car, Education, Home, Medical, etc.).

interest_rate (float64) – Loan par annual interest rate (%).

loan_term (int64) – Loan repayment duration (months, e.g., 36 or 60).

installment (float64) – Monthly installment .

grade_subgrade (category) – Risk category assigned to loan (A1, B2, etc.).

4. Borrower’s Credit History

num_of_open_accounts (int64) – Total active credit accounts.

total_credit_limit (float64) – Borrower's total available credit limit.

current_balance (float64) – Borrower's outstanding balance (loan + credit card).

delinquency_history (int64) – Count of late payments in borrower’s history.

public_records (int64) – Negative public records (e.g., bankruptcies, legal actions).

num_of_delinquencies (int64) – Total delinquencies (missed payments).

5. Target Variable

loan_paid_back (int64) – Target variable:

1 → Borrower paid loan in full.

0 → Borrower defaulted (did not repay fully).
