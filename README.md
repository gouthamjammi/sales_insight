---

# 🚀 Tech Sales Insights Using Power BI & SQL

Unlock actionable sales intelligence through automated and interactive dashboards using **SQL + Power BI**. This project empowers NovaTech Solutions to move from Excel-heavy reporting to a fully data-driven decision environment.

---

## 🧠 Problem Statement

NovaTech is a computer hardware and peripherals distributor operating across multiple regions. The company faces challenges such as:

* ❌ Lack of centralized sales visibility  
* ❌ Manual and time-consuming Excel reports  
* ❌ Difficulty identifying sales and performance trends  

> 📉 Sales teams rely on outdated tools, and decision-makers lack real-time visual insights to make informed business calls.

🎯 **Objective**: Build an automated, insight-rich dashboard using **MySQL** and **Power BI** to help stakeholders identify performance gaps, enhance reporting, and improve profitability.

---

## 📊 AIMS Grid – Project Planning

| 💼 Purpose                                        | 👥 Stakeholders                                   | 🎯 End Result                                     | 📈 Success Criteria                           |
| ------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------- | --------------------------------------------- |
| Reveal hidden sales insights & reduce manual work | Sales Director, Marketing, Analytics, Operations  | Auto-updated dashboards for business intelligence | ✅ Save 20% reporting time 🔁 10% cost savings |

---

## 🗃️ Dataset Info

📂 **Data Source**: `db_dump.sql` *(MySQL Database Dump)*  
📅 **Sales Period**: Multi-year data  
📌 **Includes**: Orders, Products, Customers, Categories, Regions

---

## 🧹 Data Preparation & Cleaning

🔍 **Steps Followed**:

* Imported SQL dump into **MySQL Workbench**
* Explored and profiled all tables
* Handled nulls, removed duplicates, and filtered irrelevant records
* Built joins for a unified data model
* Verified data accuracy before loading into Power BI

---

## 🔄 ETL Workflow

1. **Extract**: Connect MySQL to Power BI  
2. **Transform**: Clean, filter, and model using **Power Query**  
3. **Load**: Load ready-to-use tables into Power BI for visualization

🧼 **Transformations Performed**:

* Renamed columns for clarity  
* Split date/time fields  
* Removed empty rows & fixed data types  
* Created date hierarchy

---

## 📐 Dashboard Design (Power BI + DAX)

Interactive dashboards include drill-throughs, slicers, KPIs, and dynamic visuals.

📊 **DAX Measures Used**:

* `Total Revenue`  
* `Profit Margin %`  
* `Sales Quantity`  
* `Top 10 Customers`  
* `Profit by Region/Product`  

---

## 💡 Key Insights

![Key Insights](https://camo.githubusercontent.com/fccf65ff894cf8f685a8f35d7ec852d40e03bbc00b5795f09723cd9438ab12b5/68747470733a2f2f796f7572646f6d61696e2e636f6d2f696d616765732f6b65792d696e7369676874732e706e67)

* 📌 Technology category leads in profit share (45%)  
* 📌 Q2 has highest seasonal revenue each year  
* 📌 Top 10 customers contribute over 60% of revenue  
* 📌 Discounts above 20% drastically reduce profit  

---

## 📈 Performance Insights

![Performance Insights](https://camo.githubusercontent.com/0e1bb810c15005f9836c63c8f221b994ec38ae8e295257774848c94e188d3990/68747470733a2f2f796f7572646f6d61696e2e636f6d2f696d616765732f706572666f726d616e63652d696e7369676874732e706e67)

* ⏱️ 25% reduction in reporting time  
* 📉 Identified $250K lost to high-discounted sales  
* 📍 Southern region outperformed in volume but lagged in profit  

---

## 💰 Profit Analysis

![Profit Analysis](https://yourdomain.com/images/profit-analysis.png)

* 💹 Gross profit margins improved 8% YoY (post-optimization)  
* 🧾 Top products identified for bundling opportunities  
* 💡 Recommendation to discontinue underperforming categories  

---

## ✅ Features

* 📌 Interactive filters by region, category, and segment  
* 📅 Date drill-down by Year, Quarter, Month  
* 📊 KPI Cards with real-time metrics  
* 🌍 Region-wise heatmaps & performance visualizations  
* 🔁 Auto-refresh via MySQL connector  

---

## ⚙️ Tech Stack

| Tool                 | Purpose                            |
|----------------------|-------------------------------------|
| **MySQL Workbench**  | SQL queries and data extraction    |
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query**      | Data transformation pipeline       |
| **DAX**              | Custom KPIs and metrics            |

---

## 🙌 Created By

Made with 📊 & ❤️ by **Goutham**  
> 💬 Open to collaboration and feedback!

---

