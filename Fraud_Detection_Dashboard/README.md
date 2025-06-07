# 💳 Fraud Detection with ML Predictions – Power BI Dashboard

This Power BI dashboard visualizes fraud vs non-fraud transactions along with model-predicted outputs to aid in anomaly detection and financial analysis.

---

## 🎯 Objective

To provide analysts and decision-makers with an interactive view of:
- Transaction behavior
- Predicted fraud likelihood
- Temporal and demographic patterns

---

## 📊 Dashboard Highlights

- **KPI Cards**: Total Transactions, % Fraud, Predicted Fraud Count
- **Visuals**:
  - Fraud vs Non-Fraud (Pie Chart)
  - Claims Over Time (Line Chart)
  - State-wise Fraud Breakdown (Bar Chart)
  - Prediction Confidence Distribution
  - Heatmap: Gender, Claim Type, and Race vs Fraud

---

## 📁 Files Included

| File Name                          | Description                                  |
|-----------------------------------|----------------------------------------------|
| `Fraud data.pbix`                 | Power BI report file                         |
| `fraud_dataset_with_predictions.csv` | CSV dataset used for visuals and predictions |

---

## 🧠 Insights

- Some states show unusually high fraud detection ratios
- Gender and race show subtle but consistent fraud correlations
- Claims predicted as fraud align with patterns seen in the training model

---

## ⚙️ Dataset Info

- Features: `Transaction ID`, `Amount`, `State`, `Race`, `Gender`, `Claim Type`, `Predicted Label`
- Labels: `0` = Not Fraud, `1` = Fraud
- Prediction scores were derived from a prior ML model

---

## 📌 Status

> ✅ Clean visuals | 🔍 Actionable insights | 📈 Submission-ready
