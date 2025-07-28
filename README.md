# 🎧 Sound & Audio Equipment Analytics Dashboard

An end-to-end data analysis project analyzing sound and audio equipment sales, built using **Excel**, **SQL Server**, and **Power BI**. This project replicates a real-world business request — from setting up the data infrastructure to delivering an executive-level dashboard.

> 🔗 [View the Power BI Report Online](https://app.powerbi.com/groups/me/reports/2edd31af-50c2-4800-b146-8099ad0c4d1b/ecee9a2d0b83e6ebe63c?experience=power-bi)

---

## 📌 Project Overview

In this project, I followed a structured data workflow to deliver a complete analytical dashboard that tracks **revenue**, **profit**, and **year-over-year trends** for a company dealing in sound and audio equipment.

The steps covered include:

1. **Understanding a Business Request**
2. **Building and Populating a SQL Database**
3. **Writing SQL Queries to Extract Business Insights**
4. **Connecting SQL Data to Power BI**
5. **Designing an Executive-Level Dashboard**

---

## 📊 Dashboard Features

- Revenue trends over time and by country
- Year-over-year profit calculations
- Image slicer and tooltip interactions
- Animated visuals and layout design best practices
- Clean and interactive visuals (bar charts, pie charts, cards)

> 📁 You can download and explore the full `.pbix` file in this repository.

---

## 🛠️ Tools & Technologies Used

- **SQL Server Management Studio (SSMS)**
- **Microsoft Excel**
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**

---

## 🧠 Key Learning Outcomes

- How to interpret and break down a management analytics request  
- Setting up relational databases and creating relationships  
- Querying datasets efficiently with SQL  
- Data modeling and dashboard creation in Power BI  
- Using DAX for time intelligence and KPI calculations  

---

## 📅 DAX Calendar Table Tip

To create a custom Date table in Power BI:

1. Go to the **Modeling** tab  
2. Click **New Table**  
3. Paste this DAX formula:
   ```DAX
   Calendar = CALENDAR("1/1/2022", "12/31/2023")
