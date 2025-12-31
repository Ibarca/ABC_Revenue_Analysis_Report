# 📊 ABC Report for Category Management (SQL + BigQuery + Google Sheets)

## Overview
This project showcases a **production-ready analytical dataset** built with **BigQuery SQL** and **integrated with Google Sheets** to enable automated, scalable reporting for Category Management teams.

The dataset consolidates multiple operational sources into a **single source of truth at SKU level**, designed to support prioritization, performance monitoring, and optimization decisions.

---

## BI / Data Analyst Perspective
From a Business Intelligence standpoint, this project focuses on:

- Data modeling at SKU granularity  
- Metric standardization across teams  
- SQL window functions for cumulative analytics (ABC classification)  
- Automation and self-service analytics via Google Sheets  
- Reducing dependency on ad-hoc analysis and manual reporting  

This dataset is intended as a **first analytical layer**, enabling fast exploration and decision-making before deeper analysis in specialized dashboards.

---

## Key Metrics
- Revenue & units sold (last 365 days)
- ABC classification (cumulative revenue logic)
- Revenue contribution per SKU
- Average selling price
- CM1 / CM2 / CM3 margins
- Service level (stock availability over time)
- Current stock on hand
- Supplier, country & lead time

---

## Automation & Delivery
- Query runs in **BigQuery**
- Connected directly to **Google Sheets**
- Automatic refresh
- End users work with filters, pivots, and conditional logic
- No manual data extraction required

---

## Real-World Usage
I implemented this structure (adapted to each data model) in **two different e-commerce companies**, where it became:

- The **core dataset** for Category Management
- The entry point for weekly business reviews
- A foundation that **significantly improved data accessibility and transparency**
- A bridge between analytics and business users

---

## Scalability
The model is intentionally flexible and can be extended with additional KPIs such as:
- Funnel metrics (views, add-to-cart, conversion)
- Return rates
- Delivery performance
- Forecast accuracy
- Supplier reliability

---

## Data Flow Diagram

<img width="1106" height="257" alt="Screenshot 2025-12-31 at 10 50 59" src="https://github.com/user-attachments/assets/0227ad89-e48b-4f52-a70b-8d953e52ab64" />


## 📬 Contact

If you want to discuss my work, analytics methods, or e-commerce projects:

- **LinkedIn:** [https://www.linkedin.com/in/yago-b-35582644/]
- **Email:** ibarreirocanda@gmail.com 
