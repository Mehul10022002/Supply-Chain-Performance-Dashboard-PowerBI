
# Supply Chain Performance and Delivery Efficiency Dashboard (Power BI)

This project focuses on analyzing supply chain performance using a Power BI dashboard. It looks at shipment timelines, delivery delays, and regional trends to better understand how operations are performing and where inefficiencies exist.

---

## Project Title
Supply Chain Performance and Delivery Efficiency Analysis using Power BI

---

## Project Overview
The objective of this project was to analyze shipment data and build a dashboard that provides visibility into delivery performance. The dashboard helps in comparing planned vs actual shipment timelines and identifying delay patterns across different regions.

---

## Business Problem
In many supply chain operations, it is difficult to track delivery performance consistently. There is often limited visibility into delays, and comparing scheduled timelines with actual delivery can be time-consuming. This makes it harder to identify where the process is breaking down.

---

## Objectives
- Compare scheduled and actual shipment timelines  
- Identify and categorize delivery delays  
- Analyze order distribution across regions and countries  
- Build a dashboard for tracking performance metrics  
- Highlight areas where operational efficiency can be improved  

---

## Dashboard Highlights
- Analysis of shipment delays based on actual vs scheduled days  
- Classification of orders into early, on-time, and late deliveries  
- Regional breakdown of order volume and performance  
- Basic KPI tracking for monitoring operations  

---

## Tools and Technologies
- Power BI  
- Microsoft Excel  
- DAX  

---

## Technical Implementation

### Data Preparation
- Cleaned the dataset in Excel  
- Removed columns that were empty or not useful  
- Standardized formats for easier analysis  

### Data Modeling
- Imported the cleaned dataset into Power BI  
- Structured the data to support reporting and visualization  

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

### Dashboard Design
- Used KPI cards to summarize key metrics  
- Used charts to compare regional performance  
- Added filters to make the dashboard interactive  
- Kept the layout simple and easy to understand  

---

## Skills Demonstrated
- Data cleaning and preparation  
- Power BI dashboard development  
- Use of DAX for calculations  
- Basic supply chain performance analysis  

---

## 🏁 Conclusion
This project demonstrates the ability to analyze supply chain data and build dashboards that provide actionable insights for improving operational efficiency.



