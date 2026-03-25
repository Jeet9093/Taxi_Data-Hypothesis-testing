🚖 Taxi Fare Hypothesis Testing Analysis
📌 Project Overview

This project focuses on performing statistical hypothesis testing on a taxi trip dataset to analyze whether the payment type (Card vs Cash) has a significant impact on the fare amount.

The study applies Exploratory Data Analysis (EDA), Data Cleaning, Visualization, and Statistical Testing to derive meaningful business insights.
🎯 Objective

The main objective of this project is to:

Analyze taxi fare patterns
Understand customer payment behavior
Test statistical significance between fare distributions
Apply real-world statistical decision-making techniques
📊 Dataset Description

The dataset contains taxi trip records including:

Passenger Count.
Fare Amount.
Payment Type.
Trip Distance.

The data was preprocessed to remove:

Missing values
Outliers
Incorrect fare entries
🧠 Hypothesis Testing
🔹 Problem Statement

Does payment type affect taxi fare amount?

🔹 Null Hypothesis (H₀)

There is no significant difference in mean fare between card and cash payments.

🔹 Alternative Hypothesis (H₁)

There is a significant difference in mean fare between card and cash payments.

🔹 Statistical Test Used

Independent T-Test (Welch’s t-test)

🔹 Result
T-Statistic = 69.65
P-Value < 0.05

✅ Null hypothesis rejected
➡️ Payment type significantly impacts fare amount.

📈 Exploratory Data Analysis

Performed:

Passenger count distribution analysis.
Payment type usage trends.
Fare distribution visualization.
Stacked bar chart analysis.
Normality testing (QQ Plot).

📉 Key Insights
Most taxi rides are taken by single passengers.
Card payments dominate taxi transactions.
Fare distributions vary significantly by payment method.
Larger passenger groups use taxis less frequently.

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Statsmodels
Jupyter Notebook

📂 Project Structure
Taxi-Hypothesis-Testing
│
├── hypothesis_testing.ipynb
├── dataset.csv
├── README.md
└── requirements.txt

📌 Conclusion
Statistical testing confirmed that payment method plays a significant role in determining taxi fare patterns, providing actionable insights for 
pricing strategy and customer behavior analysis.
