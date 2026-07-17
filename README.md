# 🌍 AtmoSync: Micro-Climate Arbitrage Analytics

## 📌 Project Overview

AtmoSync is a **Data Analytics and Visualization Project** developed as part of the **Infotact Solutions Internship**. The project focuses on monitoring environmental conditions inside agricultural shipping containers using simulated IoT sensor data.
By analyzing **temperature, humidity, and vibration patterns**, AtmoSync helps identify spoilage risks, assess container health, and support data-driven transportation decisions through interactive dashboards and analytics.

---

## 👨‍💻 Team Member

**Himanshu Raj** *(Individual Project)*

---

## 🎯 Problem Statement

Traditional supply chain systems rely on estimated transit times and general weather forecasts. They cannot monitor real-time micro-climate conditions inside shipping containers.
Sudden changes in temperature, humidity, or vibration can cause fruits and vegetables to spoil before reaching their destination, resulting in:
- Quality degradation
- Financial losses
- Reduced shelf life
- Inefficient transportation decisions

---

## 🚀 Project Objectives

The objective of this project is to:

- Simulate IoT sensor data for agricultural shipping containers.
- Monitor temperature, humidity, and vibration levels.
- Analyze spoilage risks across commodities and destinations.
- Identify high-risk shipments requiring attention.
- Generate actionable insights for shipment monitoring and decision-making.
- Develop interactive Power BI dashboards for analytics and visualization.

---

## 🛠️ Technologies Used

| Category | Tools |
|-----------|--------|
| Data Visualization | Power BI |
| Data Transformation | Power Query |
| Data Modeling | DAX |
| Data Storage | CSV |
| Data Generation | Python |
| Version Control | Git |
| Repository Hosting | GitHub |

---

## 📊 Dataset Details

A simulated dataset containing **1000 records** was created for analysis.

### Dataset Columns

| Column Name |
|-------------|
| Date |
| Time |
| Container_ID |
| Commodity |
| Temperature_C |
| Humidity_% |
| Vibration_g |
| Destination |
| Market_Price_USD_per_ton |
| Spoilage_Risk |
| Recommended_Action |

---

##  Commodities Covered

- Avocado
- Mango
- Tomato
- Banana
- Onion

---

## 📍 Destinations Covered

- Delhi
- Mumbai
- Bengaluru
- Chennai
- Hyderabad

---

# 📈 Analytics Performed

## 🔹 Data Preparation

- Data type validation
- Date and Time transformation
- DateTime column creation
- Hour extraction
- Day Name extraction
- Month Name extraction

---

## 🔹 Risk Analytics

- Spoilage Risk Analysis
- Commodity-wise Risk Assessment
- Destination-wise Risk Assessment
- Shipment Action Distribution Analysis

---

## 🔹 Business Metrics

- Total Containers
- Average Temperature
- Average Humidity
- Average Spoilage Risk
- Average Market Price

---

# 📊 Dashboard Development

## 📄 Page 1: Executive Overview Dashboard

### KPI Cards

- Total Containers
- Average Temperature
- Average Humidity
- Average Spoilage Risk
- Average Market Price

---

### Visualizations

- 🍩 Shipment Action Distribution (Donut Chart)
- 📊 Average Spoilage Risk by Commodity
- 📊 Risk by Destination
- 📈 Average Temperature Trend
- 🎛️ Interactive Slicers
  - Commodity
  - Destination
  - Recommended Action

---

### Business Insights Generated

- Identification of high-risk shipments
- Monitoring of commodity spoilage trends
- Evaluation of destination-specific risk levels
- Analysis of shipment action recommendations

---

# 🔄 Project Workflow

```text
Simulated IoT Dataset
        ↓
Data Preparation (Power Query)
        ↓
Data Modeling (DAX)
        ↓
Risk Analytics
        ↓
Power BI Dashboard
        ↓
Business Insights & Decision Support
```

---

# 📁 Repository Structure

```text
AtmoSync_Project/
│
├── data/
│   └── AtmoSync_Analytics_Dataset.csv
│
├── dashboard/
│   └── AtmoSync_PowerBI_Dashboard.pbix
│
├── docs/
│   └── Project_Report.docx
│
├── images/
│   └── Dashboard_Screenshots
│
└── README.md
```

---

# 📌 Project Status

## 🟢 Week 1 - Executive Dashboard Completed

### ✅ Completed Tasks

- Dataset creation and preparation
- Data transformation using Power Query
- DateTime, Hour, Day Name, and Month Name creation
- KPI development
- Executive Overview Dashboard creation
- Spoilage Risk Analytics
- Commodity and Destination Analysis
- Interactive Dashboard Filters

---

### 🔄 Upcoming Tasks

- Climate Monitoring Dashboard
- Container Health Analytics
- Advanced Risk Assessment
- Spoilage Arbitrage Analysis
- Business Recommendation Dashboard

---
