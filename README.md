# marketing-performance-dashboard
Power BI dashboard analyzing global marketing performance, ROI, expenditure and profitability.

# 📊 Marketing Pulse: Global Campaign Performance & ROI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![CSV Data](https://img.shields.io/badge/Data-CSV%20Files-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

An interactive **Power BI dashboard** designed to analyze global marketing spend, revenue, profit, and campaign ROI across regions and campaign types to support data-driven marketing decisions.

---

## 📚 Table of Contents
- [📊 Project Overview](#-project-overview)
- [📝 Purpose](#-purpose)
- [🛠 Tech Stack](#-tech-stack)
- [🗂 Data Source](#-data-source)
- [⭐ Features](#-features)
- [📈 Key Visuals](#-key-visuals)
- [💼 Business Impact](#-business-impact)
- [🖼 Dashboard Preview](#-dashboard-preview)
- [📬 Contact](#-contact)

---

## 📊 Project Overview

**Marketing Pulse** is a business intelligence dashboard built using **Power BI**. It centralizes marketing performance insights, allowing users to evaluate ROI, profitability, and channel effectiveness across global regions.

---

## 📝 Purpose

The dashboard enables organizations to:

- Evaluate marketing campaign performance  
- Monitor global and regional profitability  
- Identify high-ROI vs. low-ROI campaigns  
- Optimize digital vs. traditional marketing spend  
- Support strategic marketing decisions through data visualization  

---

## 🛠 Tech Stack

- **📊 Power BI Desktop** – Dashboard development  
- **📂 Power Query** – Data cleaning, transformation, and preparation  
- **🧠 DAX Measures** – Profit, Revenue, Spend, ROI, KPIs  
- **🧩 Data Modeling** – Relationship building across datasets  
- **📁 File Formats** – `.pbix` for dashboard, `.csv` for data, `.png` for preview  

---

## 🗂 Data Source

**Source:** Internal Structured Marketing Dataset (CSV Files)

The dashboard uses **three interconnected datasets**:

---

### 📁 `marketing campaign details.csv`
Campaign metadata including:
- Campaign Name / ID  
- Campaign Type (Digital / Traditional)  
- Marketing Channel (Influencer, Social Media, TV, Email, etc.)

Used for campaign segmentation and filtering.

---

### 📁 `marketing campaign performance.csv`
Main fact table containing:
- Total Spend  
- Total Revenue  
- ROI  
- Profit (Revenue − Spend)

Feeds KPI cards, ROI rankings, and performance visuals.

---

### 📁 `region performance.csv`
Regional performance table:
- Region  
- Regional Spend  
- Regional Revenue  
- Regional Profit  

Used for geographic comparisons.

---

### 🔗 Data Modeling Structure

