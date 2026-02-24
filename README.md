
# 📊 Supply Chain Performance & Delivery Efficiency Dashboard (Power BI)

Power BI dashboard analyzing supply chain performance, shipment delays, and regional trends using logistics data to identify inefficiencies and support data-driven decision making.

---

## 📌 Project Title
Supply Chain Performance & Delivery Efficiency Analysis using Power BI

---

## 🚀 Project Overview
This project focuses on analyzing end-to-end shipment performance and identifying operational inefficiencies within a supply chain dataset. The dashboard provides visibility into delivery timelines, delay patterns, and regional performance.

---

## ⚠️ Business Problem
- Limited visibility into delivery delays
- Difficulty comparing planned vs actual shipment timelines
- Lack of centralized reporting for regional performance
- Inefficient identification of operational bottlenecks

---

## 🎯 Objectives
- Analyze delivery performance
- Identify shipment delays
- Evaluate regional trends
- Build interactive dashboard
- Improve operational visibility

---

## 📊 Dashboard Highlights
- Shipment delay analysis
- Regional performance tracking
- KPI monitoring

---

## 🛠️ Tools & Technologies
- Power BI
- Excel
- DAX

---

## ⚙️ Technical Implementation

### Data Preparation
- Cleaned dataset in Excel
- Removed null and irrelevant columns
- Standardized data formats

### Data Modeling
- Imported dataset into Power BI
- Structured data for analysis and visualization

### DAX Calculations

Delay Calculation:
Delay = [Days for Shipping (Actual)] - [Days for Shipment (Scheduled)]

Delay Category:
Delay Category =
IF([Delay] < 0, "Early",
   IF([Delay] = 0, "On-Time", "Late"))

KPI Measures:
- Total Orders
- Average Shipping Time
- Count of Delayed Orders

Dashboard Design:
- Used KPI cards for summary metrics
- Applied column charts for regional comparisons
- Integrated filters and slicers for interactivity
- Designed layout for clarity and ease of use

---

## 🧠 Skills Demonstrated
- Power BI dashboard development
- DAX calculations
- Data analysis
- Supply chain understanding

---

## 🏁 Conclusion
This project demonstrates the ability to analyze supply chain data and build dashboards that provide actionable insights for improving operational efficiency.


