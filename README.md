# Predicting-loan-payback
Predict the probability that a borrower will pay back their loan.

1. Borrower’s Demographics

   a) age (int64) – Borrower's age (in years).

   b) gender (category) – Borrower's gender (Male/Female).

   c) marital_status (category) – Marital status (Single, Married, Divorced).

   d) education_level (category) – Education level (High School, Bachelor, Master, PhD).

2. Financial Information

   a) annual_income (float64) – Borrower's yearly income.

   b) monthly_income (float64) – Borrower's monthly income.

   c) employment_status (category) – Current employment type (Employed, Self-Employed, Unemployed).

   d) debt_to_income_ratio (float64) – Ratio of borrower’s debt to their income. Lower = better.

   e) credit_score (int64) – Credit bureau score (e.g., FICO). Higher = less risky.

3. Loan Information

   a) loan_amount (float64) – Amount of loan taken.

   b) loan_purpose (category) – Loan purpose (Car, Education, Home, Medical, etc.).

   c) interest_rate (float64) – Loan par annual interest rate (%).

   d) loan_term (int64) – Loan repayment duration (months, e.g., 36 or 60).

   e) installment (float64) – Monthly installment .

   f) grade_subgrade (category) – Risk category assigned to loan (A1, B2, etc.).

4. Borrower’s Credit History

   a) num_of_open_accounts (int64) – Total active credit accounts.

   b) total_credit_limit (float64) – Borrower's total available credit limit.

   c) current_balance (float64) – Borrower's outstanding balance (loan + credit card).

   d) delinquency_history (int64) – Count of late payments in borrower’s history.

   e) public_records (int64) – Negative public records (e.g., bankruptcies, legal actions).

   f) num_of_delinquencies (int64) – Total delinquencies (missed payments).

5. Target Variable

   a) loan_paid_back (int64) – Target variable:

        1 → Borrower paid loan in full.

        0 → Borrower defaulted (did not repay fully).
