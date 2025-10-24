# 📘 Telecom Churn Prediction Project


## 🧠 Project Overview

The Telecom Market Churn Prediction System aims to predict regional subscriber churn trends to help telecom operators proactively manage network investments, optimize marketing spend, and improve customer retention.

This project uses machine learning models to analyze customer behavior and predict churn probabilities at a market level, supporting strategic decision-making and operational actions.

## 👥 Team Details

| Role                                        | Member          |
| ------------------------------------------- | --------------- |
| **Team Name**                               | N               |
| **Team Lead**                               | Tanvi Barve     |
| **Co-Team Lead**                            | Swapnali Patil  |
| **Foundation & Market Analysis**            | Sumit Bhardwaj  |
| **Feature Engineering & Target Definition** | Suhani Kumari   |
| **Baseline Model Development**              | Sumithi Pandian |
| **Advanced Model Development**              | Subhash Patel   |
| **Business Analysis & Deployment**          | Swapnali Patil  |


🚀 Key Features

Comprehensive Data Analysis covering multiple regions and years

Feature Engineering focused on temporal, competitive, and geographic dimensions

Multiple ML Models: Baseline Logistic Regression, Random Forest, XGBoost, and Stacked Ensemble

Final Model: XGBoost Classifier

Deployment: Flask-based REST API for real-time predictions

⚙️ Technical Workflow

Data Collection & Preparation

Source: Telecom market data (CSV format)

Cleaning and handling missing values

Feature extraction and scaling

Exploratory Data Analysis (EDA)

Distribution analysis of churn and non-churn customers

Temporal and market share patterns

Correlation and variance checks

Feature Engineering

Derived metrics like market_rank, share_gap_leader, and circle-based averages

Label encoding for categorical variables

Temporal lag and growth rate features

Model Development

Baseline Model: Logistic Regression (Accuracy: 85%, ROC-AUC: 0.61)

Advanced Models:

Random Forest (Accuracy: 92%, ROC-AUC: 0.97)

XGBoost (Accuracy: 95%, ROC-AUC: 0.9847)

Stacked Ensemble (Accuracy: 93%, ROC-AUC: 0.9720)


📊 Model Performance Summary
| Model               | Accuracy | ROC-AUC    |
| ------------------- | -------- | ---------- |
| Logistic Regression | 0.85     | 0.61       |
| Random Forest       | 0.92     | 0.97       |
| XGBoost (Final)     | **0.95** | **0.9847** |
| Stacked Ensemble    | 0.93     | 0.9720     |


📈 Business Impact

Customer Retention: Early identification of at-risk segments

Revenue Protection: Prevent potential losses due to churn

Marketing Optimization: Targeted retention campaigns

Strategic Planning: Data-driven insights for network investment and customer engagement


🛠️ Technologies Used

Python – pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost
Jupyter Notebook – Development and experimentation


🏁 Conclusion

The project successfully demonstrates how machine learning can accurately predict churn and help telecom companies take proactive measures. With a 95% accuracy and 0.98 ROC-AUC, the final model (XGBoost) provides strong predictive power for market-level churn forecasting.
