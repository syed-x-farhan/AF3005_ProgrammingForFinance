# Smart Financial Management System

SecureBank's Smart Financial Management System is an automated solution designed to assist with financial decision making with python. The system performs various financial operations, including loan eligibility assessment, investment risk classification, loan repayment tracking, stock market monitoring, and currency exchange tracking.

## Features

✅ Assess customer eligibility for loans.  
✅ Classify investment portfolios based on risk.  
✅ Automate loan repayment tracking.  
✅ Monitor stock market trends and trigger alerts.  
✅ Track currency exchange rates and suggest conversions.  

This project utilizes ipywidgets for interactive user input, ensuring an intuitive and user-friendly experience.

## Installation & Requirements

### Prerequisites

Ensure you have Python installed on your system. You also need Jupyter Notebook to run the interactive widgets.

### Install Dependencies

To install the required libraries, run:

```sh
pip install ipywidgets
```

## Overview

### 🟢 Part 1: Loan Eligibility & Interest Rate Calculation [4 Marks]

#### 📌 Requirement
Approves loans based on employment status, income, and credit score.

Interest rate:

- 750+ → 5%
- 650 - 749 → 8%
- Below 650 → Loan rejected
- Unemployed applicants are automatically rejected.

#### 🛠 Implementation Steps

- Structure if-elif-else logic for loan decision.
- Use ipywidgets for interactive user input.

#### 🖥 Usage
Run `loan_eligibility.py` in Jupyter Notebook.

---

### 🟢 Part 2: Investment Risk Assessment [4 Marks]

#### 📌 Requirement
Evaluates stock portfolio risk:

- Negative return → High Risk
- At least one stock return <5% → Medium Risk
- All stock returns ≥5% → Low Risk

#### 🛠 Implementation Steps

- Iterate through stock returns using loops.
- Apply if-elif conditions for risk classification.
- Use ipywidgets for interactive input.

#### 🖥 Usage
Run `investment_risk.py` in Jupyter Notebook.

---

### 🟢 Part 3: Loan Repayment Tracking [4 Marks]

#### 📌 Requirement
Customers who receive a loan should be able to track their loan balance as they make monthly payments. The system should:

✔ Start with an initial loan balance (e.g., PKR 500,000).  
✔ Deduct a fixed monthly payment (e.g., PKR 25,000).  
✔ Continue tracking until the loan balance reaches zero.  
✔ Display the remaining balance after each payment.  

#### 🛠 Implementation Steps

- Used while loop .
- Ensured the loop stops once the loan is fully paid.
- Implements a Python program using ipywidgets to simulate loan repayment interactively.

#### 🖥 Usage
Run `loan_repayment.py` in Jupyter Notebook.

---

### 🟢 Part 4: Stock Price Monitoring & Trading Strategy [4 Marks]

#### 📌 Requirement

- Tracks stock prices daily.
- Skips missing data (`None` values).
- Stops tracking when price reaches PKR 200.

#### 🛠 Implementation Steps

- Handle missing stock data (`continue`).
- Stop tracking once the target price is hit (`break`).
- Used ipywidgets for interactive monitoring.

#### 🖥 Usage
Run `stock_monitoring.py` in Jupyter Notebook.

---

### 🟢 Part 5: Currency Exchange Rate Tracker [4 Marks]

#### 📌 Requirement

- Starts at PKR 290/USD.
- Increases by 1 PKR per day.
- Stops at PKR 300/USD.

#### 🛠 Implementation Steps

- Use a loop to increment the exchange rate daily.
- Stop when PKR 300/USD is reached.
- Use ipywidgets for interactive input.

#### 🖥 Usage
Run `currency_tracker.py` in Jupyter Notebook.

## Contributing

Contributions are welcome! If you’d like to improve the system, feel free to fork the repository and submit a pull request.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added feature XYZ"`).
4. Push the changes (`git push origin feature-branch`).
5. Create a pull request.

