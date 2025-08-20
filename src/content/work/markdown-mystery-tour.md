---
title: "E-Commerce Analytics Dashboard"
publishDate: 2025-08-19
img: "/assets/python.jpg"
img_alt: "Streamlit sales dashboard with KPIs, charts, and filters"
description: |
  A Streamlit-powered analytics app for exploring e-commerce sales:
  KPIs, monthly trends, category & city leaders, CSV export, and a 3-month sales forecast (Holt-Winters).
tags:
  - Python
  - Streamlit
  - Forecasting
---

## Overview
Interactive dashboard built with **Python + Streamlit** to analyze orders and revenue.  
Users can filter by **Month-Year**, **Category**, and **City**, view KPIs, trends, and top performers, export filtered data, and generate a short-term **sales forecast**.

### 🔍 Features
- **KPIs:** Total Sales, Total Profit, Avg. Order Value  
- **Trends:** Monthly sales line chart  
- **Leaders:** Top categories & Top 10 cities (bar charts)  
- **Filters:** Month-Year, Category, City  
- **Data export:** Download filtered CSV  
- **Forecasting:** 3-month projection via **ExponentialSmoothing (Holt-Winters)**

### 🧰 Tech Stack
- **Python**, **Pandas**, **Matplotlib**
- **Streamlit** (UI & layout)
- **statsmodels** (Holt-Winters)
- Optional: **Plotly** (for interactive visuals)

### ▶️ Run Locally


```bash
pip install -r requirements.txt
streamlit run app.py
```

### 🔗 GitHub Repo
<a href="https://github.com/Mubashir7933/-e-commerce-analytics-dashboard" target="_blank">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" 
       alt="GitHub Repo" width="60" height="60" />
</a>