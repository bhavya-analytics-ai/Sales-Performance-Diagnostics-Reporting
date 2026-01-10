# 📊 Sales Analytics Dashboard  
**Diagnostic & Decision Intelligence**

This project is a sales analytics system designed to move from **analysis → decision-making**.  
It separates analytics into two clear layers so insights don’t get mixed with recommendations.

- **A2 – Diagnostic Dashboard** → explains *what is happening and why*  
- **A3 – Decision Dashboard** → focuses on *what should be done next*

The goal is not just visualization, but **decision support** using real, imperfect business data.

---

## 🔗 Live Dashboards

- **A2 Diagnostic Dashboard:**  
  https://xcompany-ai-sales-dashboard-bdel2x6pwedw8pcqmagvqc.streamlit.app

- **A3 Decision Dashboard:**  
  https://xcompany-ai-sales-dashboard-dsp5zzmrzjielnpwjfezp4.streamlit.app

---

## 📁 Repository Structure
```
AI-Sales-Dashboard/
│
├── README.md
├── sales_data.csv
│
├── A2_Diagnostic_Dashboard/
│ ├── app.py
│ ├── requirements.txt
│ ├── case-study.md
│ └── screenshots.png
│
├── A3_Decision_Dashboard/
│ ├── app.py
│ ├── requirements.txt
│ ├── case-study.md
│ └── screenshots.png
```

---

## 🔹 Project Overview

Many organizations have access to sales data but struggle to translate it into **clear, actionable decisions**.  
This project addresses that gap by separating analytics into two intentional layers:

- A **diagnostic layer** for exploration, trends, and root-cause analysis  
- A **decision layer** for executive-ready summaries, risk identification, and recommended actions  

This mirrors how real **business intelligence and analytics teams** structure their workflows.

---

## 🧠 Robust Data Handling (Real-World Ready)

To reflect real operational conditions, the dashboards are built with safety and robustness in mind:

- Schema validation to prevent incorrect analysis  
- Interactive column mapping for uploaded datasets  
- Safe numeric coercion and cleaning  
- Graceful handling of missing or imperfect data  

The system is designed to **fail safely**, not crash or mislead users.

---

## 🔍 A2 – Diagnostic Dashboard

### Purpose  
To explore sales performance, profitability, discount behavior, and regional trends in order to understand **what is happening and why**.

### Key Capabilities
- Sales and profit trends over time  
- Category and sub-category performance  
- Regional and state-level analysis  
- Discount vs profit risk analysis  
- Interactive filtering and visual exploration  

### Preview
![A2 Diagnostic Dashboard](A2_Diagnostic_Dashboard/screenshots.png)

---

## 🎯 A3 – Decision Dashboard

### Purpose  
To convert analytical findings into **clear, actionable business decisions** suitable for leadership and stakeholders.

### Key Capabilities
- Executive KPI snapshot (Sales, Profit, Loss Orders)  
- Profit risk by category and region  
- Discount threshold impact analysis  
- Identification of loss-making sub-categories  
- Decision summaries with recommended actions  
- Schema validation and column mapping for uploaded data  

### Preview
![A3 Decision Dashboard](A3_Decision_Dashboard/screenshots.png)

---

## 🛠️ Tech Stack

- **Python**  
- **Streamlit** – interactive dashboards  
- **Pandas** – data processing  
- **Plotly** – interactive visualizations  

---

## ✅ Key Takeaway

This project demonstrates the ability to:

- Perform structured exploratory analysis  
- Separate diagnosis from decision-making  
- Build user-safe, robust analytics tools  
- Communicate insights clearly to non-technical stakeholders  

---

## 👤 Author
**Bhavya Pandya**  
LinkedIn: https://www.linkedin.com/in/bhavya-91p/
