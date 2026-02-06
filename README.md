# 📊 Supply Chain Analysis Power BI Project

### **Optimizing Logistics for Atliq Mart**

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/powerpoint)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

## 📖 Overview

**Efficiency is the backbone of the FMCG industry.** This project analyzes the supply chain performance of **Atliq Mart** (a fictional FMCG company). The goal was to solve a service level issue by tracking essential delivery metrics and identifying areas where the supply chain was failing to meet customer demands.

By integrating database querying with advanced visualization, this dashboard provides the supply chain team with a clear picture of their On-Time and In-Full delivery performance.

> *"Tracking the journey from warehouse to customer with precision."*

---

## 🎯 Key Metrics Tracked

To evaluate the service levels effectively, I focused on five major Key Performance Indicators (KPIs):

* **🕒 OT % (On Time Delivery):** Percentage of orders delivered by the promised date.
* **📦 IF % (In Full Delivery):** Percentage of orders delivered with the complete quantity requested.
* **✅ OTIF % (On Time & In Full):** The gold standard metric—orders that were both on time and fully complete.
* **📉 LIFR (Line Fill Rate):** Measurement of how many distinct line items were fulfilled.
* **📊 VOFR (Volume Fill Rate):** Measurement of the total volume of goods fulfilled against the demand.

---

## 🛠️ Tools Used

* **🐬 MySQL:** Used for querying the database and extracting relevant datasets.
* **📊 Power BI:** The primary tool for data modeling, DAX calculations, and visualization.
* **📝 PowerPoint:** Used to synthesize findings and present actionable insights to stakeholders.

---

## 🧠 Knowledge & Skills Applied

This project pushed my boundaries in both domain knowledge and technical implementation:

* **🚚 Supply Chain Domain:** Deepened understanding of logistics terminology and operational flows.
* **🧮 Advanced DAX:** * Mastered logic for finding date gaps.
    * Understood nuances between `COUNT`, `COUNTA`, `COUNTROWS`, and `DISTINCTCOUNT`.
* **📈 Trend Analysis:** Implemented trend charts alongside single-value metrics to show historical context immediately.
* **🎨 UX/UI Design:** Explored page navigation techniques and **Switch Buttons** for a cleaner, interactive user experience.

---

## ⚙️ The Workflow

The data journey involves extracting raw data from the SQL database and transforming it into visual insights.

```mermaid
graph TD;
    A["🗄️ MySQL Database\nAtliq Mart Data"] -->|Query & Extract| B{"⚙️ Power BI\nData Transformation"};
    B -->|DAX Measures| C["🧮 Calculation Engine\n(OT, IF, OTIF, LIFR)"];
    C -->|Visualization| D["📈 Interactive Dashboard"];
    D -->|Analysis| E["💡 Insights Presentation\nPowerPoint"];

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
