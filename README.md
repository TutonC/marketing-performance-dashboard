# marketing-performance-dashboard
Power BI dashboard analyzing global marketing performance, ROI, expenditure and profitability.

1. 📊 Project Title / Headline

Marketing Pulse: Global Campaign Performance & ROI Dashboard
An interactive Power BI dashboard designed to analyze global marketing spend, revenue, profit, and campaign ROI across regions and campaign types for data-driven decision-making.

2. 📝 Short Description / Purpose

The Marketing Pulse Dashboard is a comprehensive business intelligence solution built in Power BI to evaluate the effectiveness of marketing campaigns across different regions and channels. It enables stakeholders to monitor financial performance, compare campaign efficiency, and identify high-performing and underperforming marketing strategies to improve overall profitability.

3. 🛠 Tech Stack

The dashboard was built using the following tools and technologies:

  📊 Power BI Desktop – Main platform for building interactive reports and dashboards
  📂 Power Query – Used for data cleaning, transformation, and preparation
  🧠 DAX (Data Analysis Expressions) – Used to create calculated measures such as Total Revenue, Total Spend, Total Profit, and Average ROI
  🧩 Data Modeling – Relationships built between campaign and region tables for dynamic filtering
  📁 File Format – .pbix for development and .png for dashboard preview

4. 🗂 Data Source

The dashboard is powered by three interconnected CSV files:

📁 1. marketing campaign details.csv - This dataset contains campaign dimension data, including:

    Campaign Name / Campaign ID
    Campaign Type (Digital / Traditional)
    Marketing Channel (Influencer, Social Media, TV, Email, Radio, etc.)
    Used to categorize campaigns and enable campaign-based filtering.

📁 2. marketing campaign performance.csv - This is the main fact table used for analysis and includes:

    Campaign Name / Campaign ID
    Total Spend
    Total Revenue
    ROI
    Calculated Profit (Revenue − Spend)
      
      This dataset feeds:
      KPI cards
      Campaign spend vs. ROI analysis
      Total ROI by campaign rankings

📁 3. region performance.csv - This dataset contains regional marketing performance, including:

    Region Name
    Regional Total Spend
    Regional Total Revenue
    Regional Profit
      
      This data is used to analyze and compare:
      Marketing performance by geographical region
      Regional profitability and revenue contribution

🔗 Data Modeling Approach

The Marketing Campaign Performance table acts as the central fact table.
The Marketing Campaign Details table is linked using Campaign Name/ID.
The Region Performance table is linked using Region.
The relationships enable interactive cross-filtering across all visuals.

5. ⭐ Features / Highlights
🔍 Business Problem

Organizations invest large amounts of money across multiple marketing channels and regions, but often lack a unified view to:

Identify which campaigns generate the highest ROI

Understand regional profitability

Track overall marketing efficiency

Optimize digital vs. traditional marketing spending

Without centralized analytics, marketing decisions become fragmented and inefficient.

🎯 Goal of the Dashboard

To provide a centralized, interactive, and executive-ready dashboard that:

Monitors global marketing performance in real time

Compares spend, revenue, and profit across regions

Measures campaign effectiveness using ROI

Helps optimize marketing budgets and resource allocation

Supports strategic and operational marketing decisions

📈 Walkthrough of Key Visuals
✅ Top KPI Cards

Total Revenue: 42.5M

Total Spend: 25.7M

Average ROI: 0.68

Total Profit: 16.8M

Best Performing Campaign: Influencer Marketing

These KPIs provide an instant financial performance overview.

🌍 Total Spend & Revenue by Region (Stacked Column Chart)

Regions analyzed:

Africa

Asia

North America

Europe

Oceania

South America

This visual enables direct comparison of spending efficiency and profitability across regions.

📣 Total Spend vs. Average ROI by Campaign (Combo Chart)

Campaigns included:

Search Engine Ads

Social Media Ads

Content Marketing

Influencer Marketing

Radio Ads

Email Marketing

TV Commercials

Billboards

This chart highlights how Influencer Marketing achieves the highest ROI despite moderate spending.

🏆 Total ROI by Campaign (Horizontal Bar Chart)

Campaign ranking by total ROI:

Influencer Marketing – 137 (Highest)

Social Media Ads – 88

Search Engine Ads – 88

Content Marketing – 82

Radio Ads – 82

Billboards – 78

Email Marketing – 70

TV Commercials – 51 (Lowest)

📊 Campaign Type Distribution (Pie Chart)

Digital Campaigns: 62.5%

Traditional Campaigns: 37.5%

Shows the organization’s strategic emphasis on digital marketing.

🎯 Sum & Average ROI Gauge

Displays a combined ROI performance value of 676.26, representing overall campaign effectiveness.

💼 Business Impact & Insights

Budget Reallocation: High returns from Influencer and Social Media campaigns justify increased digital ad spend.

Regional Growth Opportunities: Africa and North America show strong profitability potential.

Digital Strategy Validation: Over 60% of campaigns are digital, supporting modern marketing trends.

Profit Optimization: Clear visibility into 16.8M total profit supports executive decision-making.

Cost Control: Low ROI from TV Commercials and Billboards signals areas for optimization.
