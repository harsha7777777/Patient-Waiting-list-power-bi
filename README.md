# 🏥 Patient Waiting List Dashboard – Power BI Project

## 📌 Overview

This Power BI dashboard project is designed to **track and analyze patient waiting list data** across multiple dimensions. It enables stakeholders in the healthcare domain to better understand the current and historical status of waiting lists, with drill-down capabilities by specialty and age profile.

## 🎯 Problem Statement

The healthcare sector often faces challenges in managing patient backlogs. The primary goal of this project is to:

- Monitor the **current status** of patient waiting lists  
- Analyze **monthly historical trends** in both **Inpatient** and **Outpatient** categories  
- Provide **granular insights** by **specialty** and **age group** to aid operational and strategic decision-making

## 📅 Data Scope

- **Timeframe:** 2018 to 2021  
- **Categories:** Inpatient and Outpatient

## 📊 Metrics Tracked

- **Average Waiting List**  
- **Median Waiting List**  
- **Current Total Waiting List**

## 🖥️ Dashboard Views

- **Summary Page** – High-level KPIs and trend lines  
- **Detailed Page** – Deep-dive filters by specialty, age profile, and category

## 📂 Data Collection

The project uses Power BI's **Folder Connection** method to access data files:

- All required CSV/Excel files are stored in a **central local folder**
- This folder acts as the **data repository** and supports **automatic refresh** of the dashboard when new files are added

### Common Power BI Data Connectors (for reference):

- Excel / CSV  
- Folder Connection  
- SQL Server / Databases  
- Power BI Services  
- Cloud Platforms: Azure, AWS, GCP  
- ERP Systems: Salesforce, SAP  
- SharePoint  
- Web / JSON  

## 🔧 Setup Instructions

1. **Download the ZIP file** from the repository  
2. **Extract files** to a new folder on your desktop (this will serve as your data source)  
3. Open the Power BI `.pbix` file  
4. Ensure the folder path in Power BI matches your local folder for data refresh to work properly  
5. Refresh the dashboard and explore the visualizations

## 📁 Repository Contents

- `/data` – Sample data files (2018–2021)  
- `Patient_Waitlist_Dashboard.pbix` – Power BI file  
- `README.md` – Project documentation (this file)

## 🚀 Future Enhancements

- Integrate real-time data via SQL or API connection  
- Add patient prioritization metrics (e.g., urgency scores)  
- Deploy to Power BI Service for online access and scheduled refresh

## 📬 Feedback

Feel free to open an issue or submit a pull request with suggestions or improvements!

