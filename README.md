# 📊 Customer Churn Analysis – Teco Telecom

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge)
![EDA](https://img.shields.io/badge/EDA-Data%20Exploration-orange?style=for-the-badge)

---

## 📌 Table of Contents
- [👋 Introduction](#-introduction)
- [🎯 Objective](#-objective)
- [🛠 Skills & Tools](#-skills--tools)
- [📂 Dataset Overview](#-dataset-overview)
- [🔍 Key Insights](#-key-insights)
- [📊 Visual Highlights](#-visual-highlights)
- [🚀 Recommendations](#-recommendations)
- [📂 Project Structure](#-project-structure)
- [💭 What I Learned](#-what-i-learned)
- [⭐ Final Note](#-final-note)

---

## 👋 Introduction  
Customer churn is one of the biggest challenges for telecom companies.  
For this project, I analyzed **Teco Telecom’s customer data** to uncover why customers leave and how the company can proactively retain them.  

This analysis blends **data science** with **business insight** — turning raw numbers into actionable strategies.

---

## 🎯 Objective  
- Identify the **main factors** influencing customer churn  
- Quantify churn patterns with clear, **percentage-based insights**  
- Recommend **practical retention strategies** backed by data  

---

## 🛠 Skills & Tools  
| **Skill**                | **Tools/Libraries** |
|--------------------------|--------------------|
| Data Analysis            | Python, Pandas, NumPy |
| Visualization            | Matplotlib, Seaborn |
| Business Insight         | Retention Strategy, Churn Reduction |
| Data Cleaning            | Handling Missing Values, Feature Formatting |

---

## 📂 Dataset Overview  
**File:** `Customer Churn.csv`  
Contains:  
- **Demographics**: Gender, Senior Citizen, Partner, Dependents  
- **Account Info**: Tenure, Contract Type, Payment Method, Monthly Charges  
- **Services**: Internet Type, Streaming Services, Security Options  
- **Target Variable**: `Churn` (Yes/No)  

---

## 🔍 Key Insights  

### 📅 Contract Type  
- Month-to-month: **42% churn**  
- One-year: **11% churn**  
- Two-year: **3% churn**  
💡 *Longer commitments = stronger retention.*  

### 💳 Payment Method  
- Electronic check: **45% churn**  
- Other methods: **15–18% churn**  
💡 *Switching payment methods could reduce churn.*  

### ⏳ Tenure  
- First-year customers: **50% churn**  
- 1–3 years: **35% churn**  
- 3+ years: **15% churn**  
💡 *Year one is the critical retention period.*  

### 🌐 Internet Service Type  
- Fiber optic: **30% churn**  
- DSL: **20% churn**  
💡 *Potential dissatisfaction with fiber optic quality.*  

### 👴 Senior Citizens  
- 65+ years: **41% churn**  
- Under 65: **26% churn**  
💡 *Tailored offers could help retain older customers.*  

---

## 📊 Visual Highlights  

![Churn by Contract Type](https://github.com/kasifahmed2704/Customer-churn-analysis/blob/bbe3488c2ce8da6d844265d5aee4068527108779/contract_type_chart.png)  
![Churn by Payment Method](https://github.com/kasifahmed2704/Customer-churn-analysis/blob/bbe3488c2ce8da6d844265d5aee4068527108779/payment_method_chart.png)  
![Tenure vs Churn Rate](https://github.com/kasifahmed2704/Customer-churn-analysis/blob/bbe3488c2ce8da6d844265d5aee4068527108779/tenure_chart.png)  

---

## 🚀 Recommendations  
1. **Encourage Long-Term Contracts** – Discounts or perks for annual plans  
2. **Incentivize Safer Payment Methods** – Promote credit card or bank transfer  
3. **Boost First-Year Engagement** – Loyalty bonuses, personalized onboarding  
4. **Support Senior Customers** – Dedicated helpline, simple billing  
5. **Improve Fiber Optic Experience** – Check speed/reliability  

---

## 📂 Project Structure  
```
├── Customer Churn.csv                # Dataset
├── TCA.ipynb                          # Jupyter Notebook analysis
├── Teco Customer Churn Analysys.pdf   # Summary report
├── assets/                            # Folder for charts
│   ├── contract_type_chart.png
│   ├── payment_method_chart.png
│   └── tenure_chart.png
└── README.md                          # Documentation
```

---

## 💭 What I Learned  
- Data without context doesn’t drive action — **insights do**  
- Even a few percentage points in churn can mean **millions in lost revenue**  
- **Visualization is key** to convincing stakeholders  

---

## ⭐ Final Note  
If you found this project insightful, ⭐ the repository and connect with me on [LinkedIn](https://www.linkedin.com/in/kasif-ahmed2704/).  
I’m open to discussions, feedback, and collaboration opportunities.  
