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

**Marketing Pulse: Global Campaign Performance & ROI Dashboard**  
A comprehensive business intelligence solution built in **Power BI** to analyze global marketing spend, revenue, profit, and campaign ROI across regions and campaign types for executive-level decision-making.

---

## 📝 Purpose

The **Marketing Pulse Dashboard** evaluates the effectiveness of marketing campaigns across different regions and channels. It enables stakeholders to:

- Monitor overall financial performance  
- Compare campaign efficiency  
- Identify high-performing and underperforming strategies  
- Improve marketing profitability through data-driven insights  

---

## 🛠 Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main platform for building interactive reports and dashboards  
- 📂 **Power Query** – Data cleaning, transformation, and preparation  
- 🧠 **DAX (Data Analysis Expressions)** – Used to create calculated measures such as:
  - Total Revenue  
  - Total Spend  
  - Total Profit  
  - Average ROI  
- 🧩 **Data Modeling** – Relationships built between campaign and region tables for dynamic filtering  
- 📁 **File Formats**
  - `.pbix` – Power BI development file  
  - `.png` – Dashboard preview images  

---

## 🗂 Data Source

**Source:** Internal Structured Marketing Dataset (CSV Files)

The dashboard is powered by three interconnected CSV files:

### 📁 1. `marketing_campaign_details.csv`

Contains campaign dimension data:

- Campaign Name / Campaign ID  
- Campaign Type (Digital / Traditional)  
- Marketing Channel (Influencer, Social Media, TV, Email, Radio, etc.)  

**Purpose:**  
Used for campaign categorization and filtering.

---

### 📁 2. `marketing_campaign_performance.csv`

Main **fact table** used for analysis:

- Campaign Name / Campaign ID  
- Total Spend  
- Total Revenue  
- ROI  
- Calculated Profit (Revenue − Spend)  

**Drives:**
- KPI cards  
- Campaign spend vs. ROI analysis  
- Total ROI by campaign rankings  

---

### 📁 3. `region_performance.csv`

Contains regional marketing performance:

- Region Name  
- Regional Total Spend  
- Regional Total Revenue  
- Regional Profit  

**Used to analyze:**
- Marketing performance by region  
- Regional profitability and revenue contribution  

---

## 🔗 Data Modeling Approach

- **Marketing Campaign Performance** is the central **fact table**.
- **Marketing Campaign Details** is linked using **Campaign Name / ID**.
- **Region Performance** is linked using **Region**.
- These relationships enable **dynamic cross-filtering** across all visuals.

---

## ⭐ Features

### 🔍 Business Problem

Organizations invest heavily across multiple marketing channels and regions but often lack a unified view to:

- Identify which campaigns generate the highest ROI  
- Understand regional profitability  
- Track overall marketing efficiency  
- Optimize digital vs. traditional marketing spending  

This dashboard solves the problem of fragmented marketing analytics.

---

### 🎯 Goal of the Dashboard

To deliver a **centralized, executive-ready dashboard** that:

- Monitors global marketing performance in real time  
- Compares spend, revenue, and profit across regions  
- Measures campaign effectiveness using ROI  
- Optimizes marketing budgets and resource allocation  
- Supports strategic and operational decisions  

---

## 📈 Key Visuals

### ✅ Top KPI Cards

- **Total Revenue:** 42.5M  
- **Total Spend:** 25.7M  
- **Average ROI:** 0.68  
- **Total Profit:** 16.8M  
- **Best Performing Campaign:** Influencer Marketing  

Provides an instant snapshot of financial performance.

---

### 🌍 Total Spend & Revenue by Region (Stacked Column Chart)

**Regions Analyzed:**
- Africa  
- Asia  
- North America  
- Europe  
- Oceania  
- South America  

Used to compare regional spending efficiency and profitability.

---

### 📣 Total Spend vs. Average ROI by Campaign (Combo Chart)

**Campaigns Included:**
- Search Engine Ads  
- Social Media Ads  
- Content Marketing  
- Influencer Marketing  
- Radio Ads  
- Email Marketing  
- TV Commercials  
- Billboards  

Shows that **Influencer Marketing** delivers the highest ROI with moderate spending.

---

### 🏆 Total ROI by Campaign (Horizontal Bar Chart)

| Rank | Campaign               | Total ROI |
|------|------------------------|-----------|
| 1    | Influencer Marketing   | 137       |
| 2    | Social Media Ads       | 88        |
| 3    | Search Engine Ads      | 88        |
| 4    | Content Marketing      | 82        |
| 5    | Radio Ads              | 82        |
| 6    | Billboards             | 78        |
| 7    | Email Marketing        | 70        |
| 8    | TV Commercials         | 51        |

---

### 📊 Campaign Type Distribution (Pie Chart)

- **Digital Campaigns:** 62.5%  
- **Traditional Campaigns:** 37.5%  

Demonstrates the organization’s strategic emphasis on digital marketing.

---

### 🎯 Sum & Average ROI Gauge

Displays a combined ROI value of **676.26**, representing total campaign effectiveness.

---

## 💼 Business Impact

- **Budget Reallocation:** High ROI from Influencer and Social Media campaigns justifies increased digital marketing spend.  
- **Regional Growth:** Africa and North America show strong growth and profitability potential.  
- **Digital Strategy Validation:** Over 60% of campaigns are digital.  
- **Profit Optimization:** Visibility into **16.8M total profit** supports executive planning.  
- **Cost Control:** Low ROI from TV Commercials and Billboards highlights optimization opportunities.  

---

## 🖼 Dashboard Preview

Full dashboard screenshot includes:

- KPI cards  
- Regional performance comparison  
- Campaign ROI and spend analysis  
- Digital vs. traditional campaign distribution  

<img width="756" height="426" alt="image" src="https://github.com/user-attachments/assets/ff0dd2a2-331b-46a7-a2ff-02b5cfea7fbc" />


---

## 📬 Contact

For questions, feedback, or collaboration:

- **Author:** Tuton Chakraborty 
- **Email:** tutonchakraborty4@gmail.com
- **LinkedIn / Portfolio:** https://www.linkedin.com/in/tutonc/

---
