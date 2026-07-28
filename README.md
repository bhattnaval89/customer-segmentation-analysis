# CUSTOMER SEGMENTATION ANALYSIS v1

Customer segmentation project built using the Online Retail II dataset. The project applies **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering** to group customers based on purchasing behavior.

## Overview

This project follows a complete data analysis and machine learning workflow:

- Data Understanding
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- RFM Feature Engineering
- Feature Scaling
- K-Means Clustering
- Customer Segment Analysis

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Plotly |
| Machine Learning | Scikit-learn |
| Development | Jupyter Notebook, Git, GitHub |

## Repository Structure

```text
customer-segmentation-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_EDA.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   └── 05_Customer_Segmentation.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Workflow

```text
Retail Transactions
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
RFM Feature Engineering
        │
        ▼
Feature Scaling
        │
        ▼
K-Means Clustering
        │
        ▼
Customer Segments
```

## Output

The model groups customers into four business-oriented segments:

- VIP Customers
- Loyal High-Value Customers
- Regular Customers
- At-Risk Customers

## Future Improvements

- Interactive Streamlit dashboard
- Additional clustering algorithms
- Model evaluation metrics
- Automated reporting
