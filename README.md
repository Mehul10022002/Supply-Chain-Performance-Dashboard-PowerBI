# Supply-Chain-Performance-Dashboard-PowerBI

Power BI dashboard analyzing supply chain performance, shipment delays, and regional trends using logistics data to identify inefficiencies and support data-driven decision making.

---

## Project Overview
This project analyzes end-to-end shipment performance and highlights operational inefficiencies using an interactive Power BI dashboard. It provides visibility into delivery timelines, delay patterns, and regional performance to support faster, data-driven decisions in supply chain operations.

---

## Business Problem
Supply chain teams often face:
- Limited visibility into delivery delays
- Difficulty comparing planned vs actual shipment timelines
- Lack of centralized reporting for regional performance
- Slow identification of operational bottlenecks

This dashboard helps track performance and quickly surface delay trends and problem areas.

---

## Objectives
- Analyze delivery performance against scheduled timelines
- Identify and categorize shipment delays (Early / On-Time / Late)
- Evaluate regional and country-level order distribution
- Enable performance monitoring through interactive visuals
- Support insight-driven improvements in shipment execution

---

## Dashboard Highlights
### Shipment Performance Tracking
- Compared scheduled vs actual shipping days to measure delays
- Calculated deviations between planned and actual timelines

### Delay Classification
- Categorized shipments into Early, On-Time, and Late
- Enabled quick identification of delayed shipments

### Regional Insights
- Visualized order distribution across regions and countries
- Helped identify high-demand and high-delay areas

### KPI Monitoring
- Total Orders
- Average Shipping Time
- Delay Frequency

---

## Key Outcomes
- Identified gaps between planned and actual delivery timelines
- Highlighted regions with higher delay frequency
- Created a structured approach to track supply chain performance
- Improved interpretability of large datasets using visualization

---

## Tools & Technologies
- Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)

---

## Technical Implementation
### Data Preparation
- Cleaned the dataset in Excel
- Removed null/irrelevant columns
- Standardized formats for analysis

### Data Modeling
- Imported dataset into Power BI
- Structured data for analysis and visualization

### DAX Calculations
#### Delay Calculation
```DAX
Delay = [Days for Shipping (Actual)] - [Days for Shipment (Scheduled)]

Delay Category =
IF([Delay] < 0, "Early",
   IF([Delay] = 0, "On-Time", "Late"))

KPI Measures 

Total Orders

Average Shipping Time

Count of Delayed Orders

Skills Demonstrated

Supply chain analytics and KPI tracking

Data cleaning and preprocessing (Excel)

Power BI dashboard development

DAX for calculated columns and measures

Trend analysis and performance monitoring

Conclusion

This project demonstrates the ability to transform raw logistics data into actionable insights through Power BI. It highlights analytical and technical skills relevant to supply chain, operations, and data analytics roles.
