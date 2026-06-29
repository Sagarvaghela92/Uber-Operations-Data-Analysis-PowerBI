# 🚖 Uber Operations Dashboard (Power BI)

## 📌 Project Overview
Developed an executive-level Power BI dashboard to track demand, revenue, and fleet performance across a network of 20,000+ rideshare records. The dashboard helps operations managers identify high-demand hotspots, revenue leakage, and cancellation trends.

## 📊 Key Insights & Metrics
- **Total Revenue:** $720.17K tracked across multiple cities.
- **Total Bookings:** 20,000 rides analyzed with an 84.14% completion rate.
- **Cancellation Rate:** 14.8% total cancellation rate (2,966 rider vs 897 driver cancellations).
- **Average Trip Fare:** $36.01 with an average surge multiplier of 1.26.

## 🛠️ Tech Stack & Skills Used
- **Tool:** Power BI Desktop, Excel
- **Data Modeling:** Star Schema (Fact & Dimension tables linked via Date and City keys)
- **DAX Functions:** Built 12+ measures including conditional MoM (Month-over-Month) growth indicators, `DIVIDE`, `CALCULATE`, `REMOVEFILTERS`, and `KEEPFILTERS`.
- **Data Cleaning:** Power Query (Data validation, handling blanks, formatting text columns).

## 🖼️ Dashboard Preview
![Dashboard Home](Screenshots/Screenshot 2026-06-29 201321.jpg)

## 💡 Business Recommendations Based on Analysis
1. **Optimize Driver Allocation:** Allocate more drivers to high-demand areas like IAH Airport and Sugar Land during peak hourly demand waves.
2. **Reduce Revenue Leakage:** Investigate the specific cancellation reasons (e.g., 'personal emergency' and 'too long wait') to improve driver matching algorithms and retention.
