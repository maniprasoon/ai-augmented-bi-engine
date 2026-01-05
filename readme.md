# AI-Augmented Business Intelligence & Decision Analytics Engine

An end-to-end analytics system that transforms raw transactional data into **executive-ready insights** by combining **Python analytics, Gemini LLMs, and Power BI**.  
The project focuses on explaining **what changed, why it changed, and what actions to take**, not just reporting metrics.

---

## 🚀 Project Overview

Traditional dashboards show *what* happened.  
This system goes further by automatically identifying **root causes of change** and generating **plain-English business explanations** for decision-makers.

**Key outcomes:**
- Automated KPI generation
- Root-cause analysis for revenue changes
- AI-generated executive summaries
- Decision-focused Power BI dashboards

---

## 🧠 Architecture

Olist Transactional Data (CSV)
↓
Python (Data Cleaning, KPIs, Change Detection)
↓
Gemini LLM (Executive Insights)
↓
Power BI (Decision-Focused Dashboards)

yaml
Copy code

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy)
- **Google Gemini API** (LLM-based business insights)
- **Power BI Desktop**
- **CSV-based transactional datasets (Olist)**

---

## 📊 Data Sources

This project uses a real-world Brazilian e-commerce dataset (Olist), including:
- Orders
- Order items (revenue & freight)
- Payments
- Customers (geographic attribution)

These datasets simulate a **production-grade business environment** with multi-table joins.

---

## 🔍 Key Features

- **Unified Master Table**  
  Joined orders, items, payments, and customers into a single business-ready fact table.

- **KPI Engine**  
  Automatically computes revenue, growth, order value, and operational efficiency metrics.

- **Change Detection & Root Cause Analysis**  
  Identifies which regions contributed most to revenue changes using optimized order-level aggregation.

- **AI-Generated Executive Insights**  
  Uses Gemini LLM to explain:
  - What changed  
  - Why it changed  
  - Business risks  
  - Recommended actions  

- **Power BI Decision Dashboard**  
  Visualizes KPIs, trends, and root causes with an executive-first design.

---

## 📈 Power BI Dashboard Pages

1. **Executive Summary**
   - KPI cards
   - AI-generated business insights

2. **Revenue & Operations**
   - Revenue trends over time
   - Average delivery performance

3. **Why It Changed**
   - Regional revenue change attribution
   - Contribution analysis

---

## 📂 Project Structure

ai-augmented-bi-engine/
│
├── data/
│ ├── olist_orders_dataset.csv
│ ├── olist_order_items_dataset.csv
│ ├── olist_order_payments_dataset.csv
│ └── olist_customers_dataset.csv
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_kpi_engine.ipynb
│ ├── 03_change_detection.ipynb
│ └── 04_gemini_insights.ipynb
│
├── outputs/
│ ├── master_table.csv
│ ├── kpis.csv
│ ├── change_analysis.csv
│ └── insights.txt
│
├── README.md
└── .gitignore

yaml
Copy code

---

## 💡 Why This Project Matters

- Demonstrates **decision intelligence**, not just reporting
- Shows ability to work with **real-world, multi-table data**
- Integrates **AI with BI workflows**
- Mirrors how analytics is used in real business environments

---

## 📌 Resume Summary (One-Liner)

> Built an AI-augmented BI system using Python, Power BI, and Gemini LLMs to detect revenue changes, identify root causes, and generate executive-ready decision insights.

---

## 📬 Notes

- API keys are excluded for security.
- This project is designed for **Data Analyst / Business Analyst roles**.
