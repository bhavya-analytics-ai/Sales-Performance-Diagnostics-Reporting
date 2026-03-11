





# Sales Performance Diagnostics
### Turning messy sales data into executive-ready decisions — built in two layers.

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)](https://plotly.com)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org)

---

## 🔗 Live Demos

| Dashboard | Purpose | Link |
|-----------|---------|------|
| **A2 — Diagnostic** | What's happening and why | [Launch →](https://xcompany-ai-sales-dashboard-bdel2x6pwedw8pcqmagvqc.streamlit.app) |
| **A3 — Decision** | What to do about it | [Launch →](https://xcompany-ai-sales-dashboard-dsp5zzmrzjielnpwjfezp4.streamlit.app) |

---

## The Problem

Most BI tools mix diagnosis with recommendations — and the result is dashboards that show everything but tell you nothing.

This system separates those concerns into two deliberate layers, mirroring how real analytics teams actually operate:

- **Diagnostic layer (A2)** — explore, investigate, root-cause
- **Decision layer (A3)** — summarize, prioritize, act

The data is messy by design. Real sales data always is.

---

## A2 — Diagnostic Dashboard

> *What is happening, and why?*

Built for analysts who need to dig. Not a summary — a full exploratory environment.

**Capabilities:**
- Sales and profit trend analysis over time
- Category and sub-category performance breakdown
- Regional and state-level heatmaps
- Discount vs. profit risk scatter analysis
- Fully interactive filters across all dimensions

![A2 Diagnostic Dashboard](A2_Diagnostic_Dashboard/screenshots.png)

---

## A3 — Decision Dashboard

> *What should we do next?*

Built for stakeholders who need answers, not charts.

**Capabilities:**
- Executive KPI snapshot — Sales, Profit, Loss Order rate
- Profit risk flagged by category and region
- Discount threshold impact modeling
- Loss-making sub-category identification
- Decision summaries with recommended actions

![A3 Decision Dashboard](A3_Decision_Dashboard/screenshots.png)

---

## Built for Real Data

Both dashboards are hardened for production-grade messiness:

- Schema validation before any analysis runs
- Interactive column mapping for custom datasets
- Safe numeric coercion and null handling
- Graceful error states — won't crash, won't mislead

Upload your own CSV. It'll adapt.

---

## Tech Stack

| Layer | Tool |
|-------|------|
| Dashboards | Streamlit |
| Data Processing | Pandas |
| Visualizations | Plotly |
| Language | Python |

---

## Repo Structure

```
AI-Sales-Dashboard/
├── sales_data.csv
├── A2_Diagnostic_Dashboard/
│   ├── app.py
│   ├── requirements.txt
│   ├── case-study.md
│   └── screenshots.png
└── A3_Decision_Dashboard/
    ├── app.py
    ├── requirements.txt
    ├── case-study.md
    └── screenshots.png
```

---

## What This Demonstrates

- Separating **diagnosis from decision** as an architectural choice, not an afterthought
- Building analytics tools that are **safe for non-technical users**
- Communicating findings at both the analyst level and executive level
- Handling real, imperfect data without brittle assumptions

---

**Bhavya Pandya** · [LinkedIn](https://www.linkedin.com/in/bhavya-91p/) · M.S. Data Analytics, LIU Brooklyn
