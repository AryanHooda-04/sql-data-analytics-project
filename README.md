# SQL Data Analytics Project

![SQL](https://img.shields.io/badge/Language-SQL-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

## 📌 Project Overview
This repository contains a comprehensive set of SQL scripts designed for data exploration, cleaning, and advanced business analytics. The goal of this project is to transform raw data into actionable insights using structured query language. This project demonstrates real-world data analytics workflows used in business intelligence, reporting, and decision-support systems.

![Project Roadmap](docs/Project_Roadmap.png)

## 🚀 Key Features
* **Data Cleaning:** Scripts for handling NULL values, formatting date strings, and data normalization.
* **Exploratory Data Analysis (EDA):** Initial queries to determine data distribution and summary statistics.
* **Business Logic & KPIs:** * Revenue and Profitability trends.
    * Customer segmentation (RFM Analysis).
    * Year-over-Year (YoY) growth calculations.
* **Advanced SQL:** Implementation of CTEs (Common Table Expressions), Window Functions, and Subqueries.

## 📂 Repository Structure
```text
├── datasets/                      # Datasets used for analysis
├── scripts/                       # SQL source code
│   ├── 00_init_database.sql       # Database & Table definitions
│   ├── 02_cleaning.sql            # Data transformation scripts
│   └── 03_analysis.sql            # Analytical queries
├── docs/                          # Project Overview
└── README.md                      # Project documentation
```
## 🛠️ Getting Started

### Prerequisites
You will need a SQL database management system (e.g., MySQL, PostgreSQL, or SQL Server) and a client like MySQL Workbench, pgAdmin, or DBeaver.

### Supported Databases
- MySQL
- PostgreSQL
- SQL Server

### Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AryanHooda-04/sql-data-analytics-project.git
   ```
2. **Initialize Database:**
* Open your SQL client and connect to your server.
* Execute the contents of `scripts/00_init_database.sql` to build the environment.

3. **Load Data**
* Import the datasets found in the `datasets/` directory into their respective tables.

## 📊 Usage
To view the results of the analysis, run the queries located in: `scripts/03_analysis.sql`

These scripts are organized by business question, allowing you to run specific blocks to see insights regarding sales, customer growth, or inventory.

### Example Business Questions Answered
- Which customers generate the highest lifetime value?
- What products drive maximum revenue?
- Which regions show highest YoY growth?

## 📈 KPIs Covered
- Revenue Growth
- Customer Retention Rate
- Average Order Value (AOV)
- Profit Margins
- Customer Lifetime Value (CLV)

## 🎯 What This Project Demonstrates
- Analytical thinking
- Business problem solving
- Data modeling
- SQL optimization
- KPI-driven analytics
- Data storytelling

## ☕ Stay Connected

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryan04)

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Aryan Hooda**, an aspiring **Data Analyst**. Stay tuned for more upcoming data analytics projects. Excited to drop those soon!
