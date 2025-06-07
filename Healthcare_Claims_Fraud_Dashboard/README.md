# 🏥 Healthcare Claims Fraud Detection – Power BI Dashboard

This Power BI dashboard analyzes healthcare insurance claims data to detect potential fraudulent patterns using patient, inpatient, and outpatient datasets.

---

## 🎯 Objective

To support fraud detection teams in identifying high-risk claims by analyzing:
- Total reimbursed amounts
- Chronic conditions
- Procedure counts
- Demographics (age, gender, race)

---

## 📁 Files Included

| File Name                             | Description                            |
|--------------------------------------|----------------------------------------|
| `Unseen_Outpatientdata-1542969243754.pbix` | Power BI report with full visuals    |
| `Train-1542865627584.csv`            | Historical claim + fraud flag dataset |
| `Unseen_Beneficiarydata-1542969243754.csv` | Patient info (gender, DOB, death) |
| `Unseen_Inpatientdata-1542969243754.csv`   | Inpatient claim breakdown            |
| `Unseen_Outpatientdata-1542969243754.csv`  | Outpatient claim breakdown           |

---

## 📊 Dashboard Highlights

- KPI Cards: Total Claims, Unique Providers, Total Reimbursed
- Visuals:
  - Claims over time (line chart)
  - Claim Type vs Fraud (stacked bar)
  - Gender & Race breakdown
  - State-wise fraud trends
  - Heatmap of Chronic Conditions vs Fraud
- Matrix with conditional formatting for provider fraud

---

## 🧠 Insights

- Chronic condition count has a strong link to fraud labels  
- Specific states and providers show consistent high-risk patterns  
- Some claim types have disproportionately high fraud flags

---

## ⚙️ Data Processing

The `.pbix` file includes data modeling from:
- Merged patient, inpatient, and outpatient datasets
- Fraud labels from `Train.csv`
- Created calculated columns for provider flags, chronic condition totals, and claim frequency

---

## 📌 Status

> ✅ Ready | 📈 Presentation-Ready Visuals | 🕵️‍♂️ Fraud-Focused
