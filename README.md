
# EXPLORATORY DATA ANALYSIS OF FINANCIAL CONSUMER COMPLAINTS FOR BANK OF AMERICA(2017-2023)
# Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) of consumer complaints submitted to Bank of America between 2017 and 2023. The goal is to uncover meaningful patterns in customer issues, identify high-complaint products, evaluate seasonal trends, analyse how complaints are resolved, and assess the timeliness of company responses.

The project demonstrates data cleaning, feature engineering, descriptive analysis, visualization, and insight generation using Python.

# Project Aim

The aim of this project is to analyse Bank of America’s consumer complaint dataset (2017–2023) to:

- Identify seasonal and yearly trends in complaint volumes

- Determine which products receive the most complaints

- Explore the most common issues reported by customers

- Understand how complaints are typically resolved

- Analyse timely vs untimely responses and identify patterns

- Generate actionable insights to improve complaint management

# Dataset Information

Source: Consumer complaint data from Bank of America (2017–2023)

Format: Excel file


# Tools & Libraries Used

Python

Pandas – Data cleaning & manipulation

NumPy – Data processing

Matplotlib – Visualizations

Seaborn – Statistical plots

Jupyter Notebook – Interactive development

# 1. Data Loading & Pre-processing

The dataset was imported using Pandas and inspected using .head(), .info(), and .describe().
Pre-processing steps included:

- Handling missing or inconsistent values

- Converting date fields to datetime format

- Creating new features (year, month, year–month)

- Standardising categorical variables

- Ensuring all columns were formatted correctly for analysis

These steps ensure that the dataset is clean, reliable, and ready for EDA.

# 2. Exploratory Data Analysis (EDA) & Visualizations

A comprehensive EDA was performed, including:

- Univariate Analysis

- Most frequent products

- Most common issues

- Submission channels

- Complaint resolution types

- Timely vs untimely responses

- Bivariate & Multivariate Analysis

- Complaints per year

- Seasonal complaint patterns (month-wise)

- Product vs issue heatmaps

- Product vs response type analysis

- Timeliness across products

- Untimely responses per year

# Visualizations Created

Using Matplotlib & Seaborn:

Bar charts

Line charts

Pie charts

Heatmaps

Stacked bar charts

These visualizations help reveal dominant products, critical issue clusters, seasonal spikes, and response performance.

# 3. Key Insights

Below are some major insights discovered during the analysis:

- Core banking products receive the most complaints, especially checking/savings accounts and credit cards.

- “Managing an account” is the most common issue, showing possible challenges with digital account management or customer understanding.

- Complaint volumes peak every July, indicating a consistent mid-year surge.

- Complaints increased year-over-year until 2022, with a decline seen in 2023.

- Over 70% of complaints are submitted online, highlighting customer dependence on digital channels.

- Most complaints are closed with explanation, with monetary relief being rare.

- Timely responses are the norm, but 2021 saw a spike in untimely responses, suggesting operational challenges.

- Heatmaps show strong issue clustering, especially for account-related problems within key products.

# 4. Insight Generation & Recommendations

After analysing the complaints, several recommendations were proposed:

- Investigate root causes of “Managing an account” issues, especially the 2023 spike.

- Prioritise improvements in high-complaint products, such as checking/savings accounts and credit cards.

- Review operational challenges in 2021 that led to increased untimely responses.

- Evaluate the effectiveness of “Closed with explanation” outcomes and whether they resolve customer concerns.

- Implement ongoing monitoring dashboards for complaint volumes, resolution patterns, and timeliness.

These recommendations aim to strengthen customer satisfaction and operational reliability.

# Repository Contents

The GitHub repository contains:

📦 Bank-of-America-Complaint-EDA/
│
├── 📄 README.md                → Project documentation  
├── 📓 Consumer_Complaints.ipynb → Jupyter Notebook with full analysis  
├── 📈 Insight_Report.pdf        → Summary of findings (optional)  
├── 📁 data/
│   └── Consumer_Complaints.xlsx → Original dataset  
└── 📁 images/                   → Visualizations (optional)

# How to Run This Project

Clone the repository:

git clone https://github.com/yourusername/Bank-of-America-Complaint-EDA.git


Open the Jupyter Notebook:

jupyter notebook Consumer_Complaints.ipynb


Run all cells to reproduce analysis and visualizations.

# Conclusion

This project provides a detailed, data-driven view of Bank of America’s complaint patterns over seven years. Through structured EDA, visualization, and insight generation, it highlights areas of customer dissatisfaction, operational bottlenecks, and opportunities for improvement. The analysis can support decision-making in service optimization, digital experience enhancements, and complaint-handling processes.
