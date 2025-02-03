# Anomaly Detection in Financial Transactions

This repository implements anomaly detection in financial transaction data using **Isolation Forest**. The project aims to identify unusual transactions that might indicate fraud, ensuring trust and security in financial systems.

## Project Overview
- **Goal:** Detect anomalies in banking data to enhance financial fraud prevention.
- **Techniques Used:** 
  - Isolation Forest (via PyOD library).
  - Data preprocessing with Pandas.
  - Visualization with Matplotlib and Seaborn.

## Dataset
- **Data Source:** Simulated financial transactions dataset (`transactions.csv`).
- **Key Columns:** 
  - `TransactionAmount`: Amount of the transaction (USD).
  - `TransactionDuration`: Duration of the transaction (seconds).
  - `AccountBalance`: Account balance after the transaction.

## Results
- Transactions flagged as anomalies are highlighted in visualizations and summarized in the `/results` folder.
