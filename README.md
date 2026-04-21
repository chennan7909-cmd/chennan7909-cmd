# Nan Chen

**Master of Business Analytics & AI · Ontario Tech University, Toronto**  
Former Corporate Banker (10 years) · Now building ML systems for finance

Credit Risk · Supply Chain Finance · Machine Learning · Big Data Engineering

---

## About Me

I spent 10 years structuring billion-dollar financing deals at China CITIC Bank and China Construction Bank. Now I combine that domain expertise with machine learning and data engineering to build smarter financial systems.

Currently based in **Toronto, Canada**, actively seeking **data and fintech internship or full-time opportunities**.

📫 chennan7909@gmail.com

---

## Projects

### [Real-Time Canadian SME Credit Risk Analytics Pipeline](https://github.com/chennan7909-cmd/sme-credit-risk-pipeline)

> Lambda Architecture pipeline — batch ML training + real-time Kafka streaming + MongoDB serving layer

A production-grade credit risk system processing 2.26 million Lending Club loan records. Trains an XGBoost default prediction model with Bayesian hyperparameter optimization (Optuna), then scores live loan applications via a simulated Kafka → Spark Structured Streaming pipeline with real-time KS-test model drift detection.

**Tech:** PySpark · Apache Kafka · Spark Structured Streaming · XGBoost · Optuna · SHAP · MongoDB · WoE Encoding · Parquet  
**Results:** AUC-ROC 0.70 · KS 0.29 · $845M portfolio Expected Loss estimated · 500 real-time applications scored · drift detected across 6/10 micro-batches  
**Business context:** Mirrors architecture used by Canadian fintech lenders under the Open Banking framework; includes Basel II EL formula, geographic risk ranking, and fair lending compliance checks

---

### [AI-Driven Risk Detection and Price Forecasting in Cryptocurrency Markets](https://github.com/chennan7909-cmd/crypto-risk-forecasting)

> Dual-task ML pipeline — LSTM price regression + XGBoost tail-risk classification across BTC and SOL

A dual-task prediction system targeting Solana (SOL) using Bitcoin as a cross-asset leading signal. Simultaneously forecasts next-day closing price (LSTM regression) and detects days with drawdowns exceeding 5% (XGBoost binary classification). BTC signals are lagged 1, 3, and 7 days and validated via Pearson cross-correlation, confirming BTC leads SOL by 1–3 days.

**Tech:** TensorFlow/Keras · XGBoost · Scikit-Learn · yfinance · NumPy · Pandas · TimeSeriesSplit  
**Results:** SOL LSTM MAPE 2.5% · BTC XGBoost ROC-AUC 0.77 · F1 0.41 on 5% crash detection  
**Business context:** Covers two full crypto market cycles (2021–2026); walk-forward validation prevents data leakage; decision threshold tuned for risk-management use-case (recall-prioritised)

---

## Tech Stack

```
Languages:    Python · SQL
ML / DL:      XGBoost · LSTM (TensorFlow) · Scikit-Learn · SHAP · Optuna
Big Data:     Apache Spark (PySpark) · Kafka · Spark Structured Streaming · Parquet
Data:         Pandas · NumPy · Matplotlib
Databases:    MongoDB · MySQL · PostgreSQL
Tools:        Git · Jupyter · Google Colab
```

---

## Domain Expertise

| Area | Background |
|------|-----------|
| Credit Risk Assessment | 10 years, CAD 1.8B+ portfolio |
| Supply Chain Finance | Designed platforms for 30+ enterprise suppliers |
| Structured Finance | ABS, ABN, Syndicated Loans, Cross-border |
| Green Finance / ESG | CAD 46M green agricultural loan |
| Private Equity | Co-structured CAD 295M SME fund, 5 IPOs |

---

## Currently Learning

- MLOps and model deployment (FastAPI · Docker)
- Open Banking APIs and Canada's regulatory framework
- LLM applications in financial services

---

*Open to data engineering, ML engineering, and fintech internship or full-time opportunities in Toronto.*
