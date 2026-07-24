# 🌍 AtmoSync: Micro-Climate Arbitrage Analytics

## 📌 Project Overview

**AtmoSync: Micro-Climate Arbitrage Analytics** is an end-to-end **Data Analytics and Visualization** project developed as part of the **Infotact Solutions Data Analytics Internship**. The project leverages simulated IoT sensor data to monitor environmental conditions inside agricultural shipping containers. By analyzing **temperature, humidity, vibration, spoilage risk, and market conditions**, the solution provides interactive dashboards that help identify high-risk shipments, monitor container health, and support data-driven logistics decisions.

The project demonstrates a complete analytics workflow—from **data preparation and cloud storage using Snowflake** to **interactive dashboard development in Power BI**.

---

## 👨‍💻 Project Developer

**Himanshu Raj** *(Individual Project)*

---

# 🎯 Problem Statement

Traditional supply chain systems primarily depend on estimated transit times and macro-level weather forecasts. However, they cannot continuously monitor the micro-climate inside shipping containers. Variations in **temperature, humidity, and vibration** during transportation can accelerate spoilage of agricultural commodities, resulting in:

- 📉 Product quality degradation
- 💰 Financial losses
- 🥬 Reduced shelf life
- 🚚 Inefficient transportation decisions
- ⚠️ Increased operational risk

**AtmoSync** addresses this challenge by providing an interactive analytics solution for monitoring environmental conditions and identifying shipments that require immediate attention.

---

# 🚀 Project Objectives

The project aims to:

- Simulate IoT sensor data for agricultural shipments.
- Store and manage data using **Snowflake Cloud Data Warehouse**.
- Monitor temperature, humidity, and vibration conditions.
- Analyze spoilage risk across commodities and destinations.
- Identify high-risk shipments.
- Evaluate market price variations across destinations.
- Generate actionable operational recommendations.
- Develop interactive Power BI dashboards for executive reporting and risk monitoring.

---

# 🛠️ Technology Stack

| Category | Technology |
|-----------|------------|
| ☁️ Data Warehouse | Snowflake |
| 📊 Data Visualization | Power BI |
| 🔄 Data Transformation | Power Query |
| 📈 Data Modeling | DAX |
| 🐍 Data Preparation | Python |
| 📂 Data Storage | CSV |
| 💻 Database Querying | SQL |

---

# 📊 Dataset Information

A **simulated IoT dataset** containing **1,000 shipment records** was created for analytical purposes.

## 📋 Dataset Attributes

- Date
- Time
- Container ID
- Commodity
- Temperature (°C)
- Humidity (%)
- Vibration (g)
- Destination
- Market Price (USD per Ton)
- Spoilage Risk
- Recommended Action

---

## 🥑 Commodities

- Avocado
- Banana
- Mango
- Onion
- Tomato

---

## 📍 Destinations

- Delhi
- Mumbai
- Bengaluru
- Chennai
- Hyderabad

---

# 🔍 Data Preparation

The dataset was cleaned and transformed using **Power Query**.

## Data Processing

- ✔️ Data type validation
- ✔️ Date & Time formatting
- ✔️ DateTime creation
- ✔️ Hour extraction
- ✔️ Day Name extraction
- ✔️ Month Name extraction

---

# 📈 Analytics Performed

## 📌 Executive Analytics

- Total Containers
- Average Temperature
- Average Humidity
- Average Spoilage Risk
- Average Market Price

---

## 🌡️ Environmental Monitoring

- Temperature Monitoring
- Route Monitoring
- Commodity-wise Temperature Analysis
- Destination-wise Temperature Analysis

---

## ⚠️ Risk Analytics

- High-Risk Shipment Identification
- Commodity Environmental Profile
- Vibration Analysis
- Market Price Analysis
- Recommended Action Analysis
- Risk Category Analysis

---
# 📊 Dashboard Development

---

# 📄 Page 1 — Executive Overview

## 🎯 Dashboard Objective

The **Executive Overview Dashboard** provides a centralized view of shipment performance and environmental conditions. It enables stakeholders to monitor key business metrics, evaluate spoilage risk, and gain quick insights into overall logistics operations.

### 📌 KPI Cards

- 📦 Total Containers
- 🌡️ Average Temperature
- 💧 Average Humidity
- ⚠️ Average Spoilage Risk
- 💰 Average Market Price

### 📈 Visualizations

- 🍩 Shipment Action Distribution
- 📊 Average Spoilage Risk by Commodity
- 📍 Risk by Destination
- 📈 Average Temperature Trend

### 🎛️ Interactive Filters

- Commodity
- Destination
- Recommended Action

---

# 📄 Week 1 — Executive Overview Dashboard

## 🔴 Business Problem

The logistics management team lacked a centralized view of shipment performance and environmental conditions. As a result, decision-makers faced challenges in answering key operational questions, such as:

- How many containers are currently being monitored?
- What are the average environmental conditions across shipments?
- What is the overall spoilage risk?
- Which shipment action is recommended most frequently?

Without an executive-level dashboard, managers had to analyze raw datasets manually, making it difficult to identify operational issues and make timely decisions.

---

## ✅ Solution Implemented

Developed an **Executive Overview Dashboard** that consolidated the most critical operational KPIs and visualizations into a single interactive dashboard.

### Key Features

**📌 KPI Cards**

- Total Containers
- Average Temperature
- Average Humidity
- Average Spoilage Risk
- Average Market Price

**📊 Visualizations**

- Shipment Action Distribution
- Commodity-wise Spoilage Risk Analysis
- Destination-wise Risk Analysis
- Temperature Trend Analysis

**🎛️ Interactive Filters**

- Commodity
- Destination
- Recommended Action

---

## 🎯 Business Outcome

The Executive Overview Dashboard enabled management to:

- Gain a centralized view of shipment performance.
- Monitor environmental conditions in real time.
- Identify high-risk shipments quickly.
- Analyze spoilage trends across commodities and destinations.
- Support faster, data-driven operational decision-making.
- Reduce manual analysis by providing interactive business insights through a single dashboard.

  ---
  ---

# 📄 Page 2 — Historical Route & Environmental Monitoring

## 🎯 Dashboard Objective

The **Historical Route & Environmental Monitoring Dashboard** provides operational visibility into shipment routes and environmental conditions. It enables logistics teams to analyze shipment distribution, monitor temperature variations, and identify routes or commodities that require closer operational attention.

### 📌 KPI Cards

- 📦 Total Shipments
- 🌡️ Average Temperature
- 🔥 Maximum Temperature
- ❄️ Minimum Temperature

### 📈 Visualizations

- 📍 Shipment Distribution by Destination
- 🌡️ Average Temperature by Destination
- 🥑 Average Temperature by Commodity
- 📦 Shipment Count by Commodity

### 🎛️ Interactive Filters

- Commodity
- Destination
- Recommended Action

---

# 📄 Week 2 — Historical Route & Environmental Monitoring

## 🔴 Business Problem

After developing the Executive Overview Dashboard, management gained a high-level summary of shipment performance. However, operational teams still lacked detailed insights into shipment movement and environmental conditions.

Key business questions remained unanswered:

- Which destinations receive the highest number of shipments?
- Which commodities are exposed to higher environmental conditions?
- How does temperature vary across different destinations?
- Are specific transportation routes more vulnerable than others?

The Executive Overview Dashboard provided strategic insights but lacked operational-level monitoring required for day-to-day logistics management.

---

## ✅ Solution Implemented

Developed the **Historical Route & Environmental Monitoring Dashboard** to provide detailed operational insights into shipment distribution and environmental conditions across commodities and destinations.

### Key Features

**📌 KPI Cards**

- Total Shipments
- Average Temperature
- Maximum Temperature
- Minimum Temperature

**📊 Visualizations**

- Shipment Distribution by Destination
- Average Temperature by Destination
- Average Temperature by Commodity
- Shipment Count by Commodity

**🎛️ Interactive Filters**

- Commodity
- Destination
- Recommended Action

---

## 🎯 Business Outcome

The Historical Route & Environmental Monitoring Dashboard enabled operations teams to:

- Monitor shipment distribution across destinations.
- Compare environmental conditions across commodities.
- Identify destinations experiencing higher temperature exposure.
- Improve route monitoring through interactive visualizations.
- Support operational planning with location-specific insights.
- Detect transportation patterns that may require proactive intervention.

