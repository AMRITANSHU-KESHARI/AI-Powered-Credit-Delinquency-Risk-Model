# AI-Powered-Credit-Delinquency-Risk-Model

## 📌 Project Overview
Financial institutions often struggle to identify customers who are likely to miss payments **before delinquency occurs**. Traditional collections approaches are reactive, manual, and treat all customers the same, leading to higher costs and poor customer experience.

This project demonstrates an **AI-powered, human-centered collections system** that:
- Predicts delinquency risk using customer financial behavior
- Segments customers into risk categories
- Recommends ethical, AI-assisted collection actions
- Visualizes insights through an interactive dashboard built entirely in Google Colab
---
## 🎯 Problem Statement
The key challenge addressed in this project is:
> **How can financial institutions proactively identify at-risk customers and take the right collection action early, without increasing cost or harming customer trust?**

This project solves the problem by combining:
- Data-driven risk analysis
- Explainable decision logic
- Responsible AI principles
- Clear visual storytelling for stakeholders
---

## 📁 Dataset Description
- **Dataset Size:** 1,200 customer records  
- **Data Type:** Synthetic but realistically generated financial data  
- **Target Variable:** `Delinquent_Account` (1 = Delinquent, 0 = Not Delinquent)

### Key Features
- Age  
- Income  
- Credit Score  
- Credit Utilization  
- Missed Payments  
- Loan Balance  
- Debt-to-Income Ratio  

### Data Quality Notes
- Feature distributions follow real-world financial patterns
- Delinquency labels are rule-based, not random
- No personally identifiable information (PII)
- Suitable for public sharing and demonstrations
---

## 🧠 Solution Approach

### 1️⃣ Risk Identification
Customers are analyzed using financial and behavioral indicators to identify early signs of delinquency.

### 2️⃣ Risk Segmentation
Customers are grouped into:
- **Low Risk**
- **Medium Risk**
- **High Risk**

This allows prioritization of collection efforts.

### 3️⃣ AI-Assisted Recommendations
Instead of automated enforcement, the system suggests:
- Friendly reminders for low-risk customers
- Flexible payment nudges for medium-risk customers
- Human agent escalation for high-risk customers

AI acts as a **decision-support system**, not a replacement for human judgment.

---

## 📊 Dashboard Features (Built in Google Colab)

The interactive dashboard includes:
- Executive KPI summary
- Risk distribution and funnel visualization
- Portfolio stress gauge
- Correlation heatmap of delinquency drivers
- Risk vs behavior analysis (box plots, bar charts)
- AI-recommended action breakdown
- High-risk customer worklist for collections teams

---

## 📈 Model Evaluation (Conceptual)

While the focus is on visualization and decision support, the risk logic is aligned with standard ML evaluation practices:

- **Accuracy:** Overall correctness
- **Precision:** Ensures flagged high-risk customers are truly risky
- **Recall:** Prioritized to avoid missing delinquent customers
- **AUC-ROC:** Measures separation between delinquent and non-delinquent groups

In collections use cases, **recall is prioritized**, with human review ensuring fairness.

---

## ⚖️ Ethical & Responsible AI Considerations
- No automated punitive decisions
- Human-in-the-loop for high-risk cases
- Explainable decision logic
- Fair treatment across customer segments
- Focus on supportive, early interventions

---
## 🧾 Business Impact
### For the Business
- Early delinquency detection
- Reduced operational costs
- Improved agent productivity
- Scalable and consistent decision-making

### For Customers
- Fair and transparent treatment
- Reduced harassment
- Supportive repayment options
- Improved trust and experience

---
## 🛠 Tools & Technologies
- Python
- Pandas
- Plotly
- Matplotlib / Seaborn
- Google Colab

---

## 🚀 How to Run the Project
1. Upload `credit_data_large_1200.csv` to Google Colab
2. Run the notebook cells in sequence
3. Interact with the visual dashboard outputs

---

## 📌 Key Takeaway
This project demonstrates how **AI, analytics, and responsible design** can transform collections from a reactive process into a proactive, ethical, and data-driven system.

---

## 👤 Author
**Amritanshu Keshari**  
GenAI-Powered Data Analytics Project  
