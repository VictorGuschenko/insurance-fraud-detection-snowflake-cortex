# 🚨 Predicting Insurance Claim Fraud with Snowflake & Cortex AI

## 📊 Problem Statement
Insurance fraud costs billions annually. This project aims to detect potentially fraudulent claims using historical insurance data and AI-powered analysis in Snowflake.

## 🧠 Solution
We use Snowflake’s Cortex AI for sentiment and fraud prediction based on structured claim data, combined with Python and Snowsight dashboards.

## 🛠️ Stack
- Snowflake (Snowpark, Cortex AI, UDFs)
- Python
- Snowsight / Streamlit (for visualization)
- dbt (optional)

## 📁 Project Structure
├── data/ # Raw and clean data
├── sql/ # SQL transformation scripts
├── python/ # Python UDFs or data loading scripts
├── dashboard/ # Snowsight dashboards / Streamlit app
└── README.md # This file

## 💡 Key Features
- Cortex AI model for fraud scoring
- Snowflake Zero-Copy Cloning (optional)
- Time-based anomaly detection
- Dashboard with KPIs and fraud alerts
