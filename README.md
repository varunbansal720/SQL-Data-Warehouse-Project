# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a complete **data warehousing and analytics** solution — from building the warehouse to generating actionable insights.  
It follows **industry best practices** in **data engineering** and **analytics**.

---

## 🏗️ Data Architecture

The architecture follows the **Medallion Architecture** with three layers:  
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer** – Raw data from source systems (CSV → SQL Server Database)  
2. **Silver Layer** – Cleaned, standardized, and normalized data  
3. **Gold Layer** – Business-ready **Star Schema** data for reporting

---

## 📖 Project Overview

**This project covers:**
- 🛠️ Data Architecture Design  
- 🔄 ETL Pipelines (Extract → Transform → Load)  
- 🗄️ Data Modeling (Fact & Dimension Tables)  
- 📊 SQL-based Analytics & Reporting  

**Skills Highlighted:**
- SQL Development  
- Data Engineering  
- Data Modeling  
- BI Reporting  

---

## 🛠️ Tools & Resources

- 📂 **[Datasets](datasets/)** – Project datasets (CSV files)  
- 🗄️ **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)** – Database server  
- 📋 **[SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)** – SQL Server Management Studio  
- 📊 **[DrawIO](https://www.drawio.com/)** – Diagrams & architecture  
- 📝 **[Notion Project Steps](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4)** – Project documentation  

---

## 🚀 Project Requirements

### **1️⃣ Building the Data Warehouse**
**Objective:**  
Create a **modern data warehouse** in SQL Server to consolidate **sales data** for analytical reporting.

**Specifications:**
- Import data from **ERP** & **CRM** CSV files  
- Cleanse and resolve **data quality** issues  
- Merge sources into a **user-friendly star schema**  
- Focus on **latest dataset only** (no historization)  
- Provide **documentation** for business and analytics teams  

---

### **2️⃣ BI: Analytics & Reporting**
**Objective:**  
Deliver insights using **SQL analytics**:
- 📈 Customer Behavior  
- 📦 Product Performance  
- 💰 Sales Trends  

Refer to **[docs/requirements.md](docs/requirements.md)** for detailed requirements.

---

## 📂 Repository Structure
data-warehouse-project/
│
├── datasets/ # Raw datasets (ERP & CRM)
├── docs/ # Documentation & diagrams
│ ├── etl.drawio
│ ├── data_architecture.drawio
│ ├── data_catalog.md
│ ├── data_flow.drawio
│ ├── data_models.drawio
│ ├── naming-conventions.md
│
├── scripts/ # SQL ETL scripts
│ ├── bronze/
│ ├── silver/
│ ├── gold/
│
├── tests/ # Quality & validation scripts
├── README.md # Project overview
├── .gitignore # Ignore unnecessary files
└── requirements.txt # Project dependencies


---

## 🌟 About Me
👋 Hi! I'm **Varun Bansal** – a passionate **Data Engineer** who loves building **scalable data solutions**, designing **modern data architectures**, and turning raw data into insights.

📧 **Email:** [varunbansal720@gmail.com](mailto:varunbansal720@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/varunbansal720](https://www.linkedin.com/in/varunbansal720)
