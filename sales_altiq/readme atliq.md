---

# 🚀 AtliQ Hardware Sales Insights Using Power BI & SQL

Unlock actionable sales intelligence through automated and interactive dashboards using **SQL + Power BI**. This project empowers AtliQ Hardware to transition from Excel-heavy reports to a fully data-driven decision environment.

---

## 🧠 Problem Statement

AtliQ Hardware is a computer hardware and peripherals supplier operating across India. They face challenges due to:

* ❌ Lack of centralized sales visibility
* ❌ Manual and time-consuming Excel reports
* ❌ Difficulty identifying sales and performance trends

> 📉 Sales teams struggle with outdated tools, and leadership lacks visual insights to make timely decisions.

🎯 **Objective**: Build an automated, insight-rich dashboard using **MySQL** and **Power BI** to help stakeholders identify performance gaps, enhance reporting, and drive profitability.

---

## 📊 AIMS Grid – Project Planning

| 💼 Purpose                                        | 👥 Stakeholders                                        | 🎯 End Result                                     | 📈 Success Criteria                           |
| ------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------- | --------------------------------------------- |
| Reveal hidden sales insights & reduce manual work | Sales Director, Marketing, Analytics, Customer Support | Auto-updated dashboards for business intelligence | ✅ Save 20% reporting time 🔁 10% cost savings |

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

📊 **DAX Measures** Used:

* `Total Revenue`
* `Profit Margin %`
* `Sales Quantity`
* `Top 10 Customers`
* `Profit by Region/Product`
---

## 💡 Key Insights

![Key Insights](https://github.com/gouthamjammi/sales_insight/blob/main/sales_altiq/Dashboard-IMG/key%20insights.png)

* 📌 Technology category leads in profit share (45%)
* 📌 Q2 has highest seasonal revenue each year
* 📌 Top 10 customers contribute over 60% of revenue
* 📌 Discounts above 20% drastically reduce profit

---

## 📈 Performance Insights

![Performance Insights](https://github.com/gouthamjammi/sales_insight/blob/main/sales_altiq/Dashboard-IMG/performance%20insights.png)

* ⏱️ 25% reduction in reporting time
* 📉 Identified \$250K lost to high-discounted sales
* 📍 South region outperformed in order volume but underperformed in profitability

---

## 💰 Profit Analysis

![Profit Analysis](https://github.com/gouthamjammi/sales_insight/blob/main/sales_altiq/Dashboard-IMG/profit%20analysis.png)

* 💹 Gross profit margins improved 8% YoY (with optimizations)
* 🧾 Top products identified for bundling strategy
* 💡 Suggested discontinuation of underperforming segments

---

## ✅ Features

* 📌 Interactive filters by region, category, and segment
* 📅 Date drill-down by Year, Quarter, Month
* 📊 KPI Cards with real-time metrics
* 🌍 Region-wise heatmaps & performance charts
* 🔁 Auto-refresh via SQL connector

---

## ⚙️ Tech Stack

| Tool                 | Purpose                            |
| -------------------- | ---------------------------------- |
| **MySQL Workbench**  | SQL queries and data extraction    |
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query**      | Data transformation pipeline       |
| **DAX**              | Custom metrics & KPIs              |

---

## ❤️ Made with Love by Goutham

> 💻 [GitHub Profile](https://github.com/gouthamjammi)
> ⭐ Star the repo if you found it helpful
> 📨 Open to feedback and collaboration!

