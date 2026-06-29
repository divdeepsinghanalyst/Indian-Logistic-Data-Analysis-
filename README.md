# 🚀 Indian Logistics Operations Data Analytics

### Project Overview
This project presents an integrated, end-to-end data analytics pipeline developed for the Indian logistics sector—one of the world's most complex supply chain ecosystems. The objective was to transform raw, multi-dimensional, and dispersed logistics data into actionable business intelligence. By employing a "triple-validation" strategy, this project demonstrates high-level competency in data cleaning, relational database management, and interactive business intelligence visualization.

---

### The Problem
Raw logistics data is often messy, multi-dimensional, and spread across disparate systems. Logistics companies frequently face challenges in:
* **Data Inconsistency**: Handling incomplete delivery timelines, mismatched shipment IDs, and fragmented records.
* **Operational Bottlenecks**: Difficulty in identifying causes for shipment delays, warehouse overstocking, and poor carrier performance.
* **Decision Lag**: Lack of centralized, real-time visual dashboards to monitor KPIs like revenue trends, delivery success rates, and route risk.

---

### What I Did
I implemented a robust analytical workflow to solve these issues, performing redundant validation across multiple platforms:

1. **Data Ingestion & Cleaning**
    * **Excel**: Performed initial data cleansing, including handling missing values and date-time standardization.
    * **Python**: Automated complex cleaning tasks (handling nulls, duplicate detection, and schema validation) using `pandas` and `numpy`.
2. **Database Engineering**
    * **SQL Server**: Engineered a relational database architecture (Star Schema) using SSMS.
    * **T-SQL**: Developed reusable views for KPI calculations, implemented foreign key constraints, and optimized query performance using indexes.
3. **Exploratory Data Analysis (EDA)**
    * Utilized **Jupyter Notebook** for iterative statistical analysis and generated insightful visualizations with `matplotlib`[cite: 1].
4. **Business Intelligence**
    * **Power BI & Excel**: Built multi-page interactive executive dashboards[cite: 1].
    * **DAX Proficiency**: Implemented complex measures (`DATEDIFF`, `AVERAGEX`, `DIVIDE`) to track SLA compliance and financial performance[cite: 1].

---

### Tools & Technologies
| Category | Tools Used |
| :--- | :--- |
| **Languages** | Python (pandas, numpy, matplotlib), T-SQL |
| **Database** | MS SQL Server (SSMS) |
| **BI & Analytics** | Power BI (DAX), MS Excel |
| **Environment** | Jupyter Notebook |

---

### Key Insights
* **Total Revenue**: ₹1.89 Cr across 6,800+ shipments.
* **SLA Compliance**: Identified an 893-shipment delay count (13.1% of volume) requiring carrier-level intervention.
* **Performance Metrics**: Established a 6-day average delivery cycle with specific bottlenecks linked to low-rated carriers and high-risk routes.

---

### Contact
* **Author**: Divdeep Singh
* **Role**: Aspiring Data Analyst
