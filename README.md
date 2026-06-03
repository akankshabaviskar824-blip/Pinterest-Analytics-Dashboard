# Pinterest-Analytics-Dashboard
Pinterest-inspired analytics dashboard built in Power BI using DAX, Power Query, interactive visualizations, KPI cards, slicers, and geographic insights.

<img width="1713" height="781" alt="Screenshot 2026-06-03 133957" src="https://github.com/user-attachments/assets/4496c95c-4717-446e-ab07-c328b9952649" />


📖 Project Overview

This project is a Pinterest-inspired Analytics Dashboard developed using Microsoft Power BI. The dashboard provides insights into Pinterest performance metrics such as impressions, saves, clicks, follower growth, device usage, category performance, and geographic audience distribution.

---

🎯 Objectives

- Analyze Pinterest engagement metrics.
- Track impressions and audience growth.
- Identify top-performing content categories.
- Understand device-wise user behavior.
- Visualize audience distribution across countries.
- Create an interactive and aesthetically pleasing dashboard.

---

🛠️ Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX (Data Analysis Expressions)

---

📊 Dashboard Features

KPI Cards

- Total Impressions
- Total Saves
- Click Through Rate (CTR)
- Followers

Visualizations

- Impression Trend Analysis (Line Chart)
- Device-wise Click Distribution (Donut Chart)
- Category-wise Saves Analysis (Bar Chart)
- Country-wise Audience Distribution (Map Visual)

Interactive Filters

- Date Filter
- Category Filter
- Device Filter

---

📂 Dataset Information

The dataset contains sample Pinterest analytics data with the following fields:

Column Name| Description
Pin_ID| Unique Pin Identifier
Pin_Title| Title of the Pin
Category| Content Category
Date| Posting Date
Impressions| Total Views
Saves| Number of Saves
Clicks| Number of Clicks
Shares| Number of Shares
Followers| Total Followers
Country| Audience Country
Device| Device Type
Image_URL| Image Reference

---

📈 DAX Measures Used

Total Impressions

Total Impressions =
SUM(Pinterest_Analysis[Impressions])

Total Saves

Total Saves =
SUM(Pinterest_Analysis[Saves])

CTR

CTR =
DIVIDE(
SUM(Pinterest_Analysis[Clicks]),
SUM(Pinterest_Analysis[Impressions])
)

Followers Growth

Followers Growth =
MAX(Pinterest_Analysis[Followers])

---

📷 Dashboard Preview

Add your dashboard screenshot here:

"Dashboard Preview" (dashboard.png)

---

🚀 Key Insights

- Track overall Pinterest account performance.
- Monitor engagement trends over time.
- Identify the most successful content categories.
- Analyze user behavior across devices.
- Understand audience reach by country.

---

👩‍💻 Author

Akanksha Baviskar

B.Tech – Artificial Intelligence & Data Science

Power BI | Data Analytics | Dashboard Development
