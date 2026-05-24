
# 📊 UPI Transaction Data Analysis Dashboard

## 🔗 Live Dashboard  : (https://app.powerbi.com/groups/me/reports/d71cf7df-6650-4d67-aa7f-297b59822e51/8ec4a511973c28daa2a2?experience=power-bi)
---

# 📌 Project Overview

The UPI Transaction Data Analysis project focuses on analyzing large-scale digital payment transactions to uncover valuable business insights related to transaction performance, customer behavior, payment trends, banking activity, device usage, merchant analysis, and transaction success rates Using Visual Filters.

This project was developed using **Power BI** a interactive business intelligence solution. The dashboard enables stakeholders to monitor KPIs, identify transaction patterns, evaluate banking performance, compare payment methods, and make data-driven decisions for digital payment optimization.

---

# 🎯 Business Problem & Project Objective

Digital payment systems generate massive amounts of transaction data daily, making it difficult for businesses and financial institutions to:

### The main objective of this project is to:

* Analyze digital payment transaction performance
* Evaluate banking and merchant performance
* Study customer transaction behavior
* Compare payment methods and transaction types
* Identify transaction trends over time
* Build an interactive Power BI dashboard
* Generate actionable business insights for digital payment optimization
* Improve reporting efficiency using advanced Power BI techniques


---

# 🛠 Tools & Technologies

* 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
* 📂 **Power Query** – Used for data cleaning, transformation, and preprocessing.
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPIs, dynamic visuals, and conditional logic.
* 🔗 **Data Modeling** – Built relationships between transaction-related tables for cross-filtering and aggregation.
* 🎛 **Syncing Slicers** – Implemented to maintain consistent filtering across report pages.
* 📑 **Bookmarks** – Used for page navigation and dynamic user interaction.
* 📈 **Interactive Visualizations** – Used for advanced business intelligence reporting.

---

# 📂 Dataset Information

## 📌 Dataset Source

* Excel / CSV – Dataset source

## 📌 Dataset Overview

The dataset contains detailed UPI transaction records including:

1. Transaction Details
2. Customer Information
3. Banking Information
4. Merchant Details
5. Payment Information
6. Device Usage Data
7. Transaction Status Data

## 📌 Dataset Columns

The dataset includes the following important fields:

* TransactionID
* TransactionDate
* Amount
* BankNameSent
* BankNameReceived
* RemainingBalance
* City
* Gender
* TransactionType
* Status
* TransactionTime
* DeviceType
* PaymentMethod
* MerchantName
* Purpose
* CustomerAge
* PaymentMode
* Currency
* CustomerAccountNumber
* MerchantAccountNumber

---

# 📈 Dashboard Highlights

## 1️⃣ Data Collection

* Imported transaction records into Power BI
* Verified data structure and data relationships
* Loaded large-scale transactional data for analysis

## 2️⃣ Data Cleaning & Transformation

* Cleaned null and inconsistent values
* Standardized transaction categories
* Transformed data using Power Query
* Created calculated columns and DAX measures
* Optimized dataset for dashboard performance

        Calculated Columns

        1. Age Groups = IF('UPI Transactions'[CustomerAge]<=25, "A1", 
                     IF('UPI Transactions'[CustomerAge]<=35,"A2", "A3"))

## 3️⃣ KPI Development

Developed dynamic KPIs including:

* Build Different Visual Filters For Filtering Graphs 

* Some Visual Filters are

        1. BankNameSent
        2. BankNameReceived
        3. City
        4. DeviceType
        5. Gender
        6. Age groups
        7. MerchantName
        8. PaymentMethod
        9. Purpose
        10. TransactionType

* Transaction By Month Using Line charts & Column Charts

* Balance By Month  Using Line Charts Charts & Column Charts 

* Created Table Where we have Shown Amount and RemainingBalance By City Currency and With Respect to Different Months 


## 4️⃣ Dashboard Development

Developed highly interactive dashboards with:

* Slicers and filters
* Syncing slicers across pages
* Bookmark-based navigation
* Dynamic KPI cards
* Time-series trend analysis
* Merchant-level insights
* Bank-wise analysis
* Drill-through functionality
* Interactive charts and visuals
* User-friendly dashboard design

---

# 📊 Dashboard Preview

## 🔹 Data Cleaning & Transformation

![Image](https://github.com/ROHIT19K/UPI-Transaction-Data-Analysis-Power-BI-DashBoard/blob/main/Data%20Cleaning%20And%20Transformation%20Of%20UPI%20Transaction%20Data%20Analysis%20%20.png)

## 🔹 Dashboard Overview

![Image](https://github.com/ROHIT19K/UPI-Transaction-Data-Analysis-Power-BI-DashBoard/blob/main/UPI%20Page1.png)

![Image](https://github.com/ROHIT19K/UPI-Transaction-Data-Analysis-Power-BI-DashBoard/blob/main/UPI%20Paghe2.png)

![Image](https://github.com/ROHIT19K/UPI-Transaction-Data-Analysis-Power-BI-DashBoard/blob/main/UPI%20PAGE2.2.png)

## 🔹 Power BI Service Published Report

![Image](https://github.com/ROHIT19K/UPI-Transaction-Data-Analysis-Power-BI-DashBoard/blob/main/UPI%20Transaction%20Power%20BI%20Service%20Published%20.png)

---

# 🔍 Key Insights

* Visual Filter Or Slicers Through We will be able to Filter Out Certain Information Related to Transaction By Month and Balance By Month

* Implemented syncing slicers across multiple dashboard pages to maintain consistent filtering and improve user experience.

* Used bookmarks for:

        1. Dashboard navigation
        2. Interactive storytelling
        3. Dynamic visual switching
        4. Enhanced report usability

* Implemented advanced filtering using:

        1 Date Filters
        2 City Filters
        3 Merchant Filters
        4 Bank Filters
        5 Transaction Status Filters
        6 Payment Method Filters

---

# 🚀 Future Enhancements

* Add real-time SQL data refresh
* Implement live API transaction integration
* Add fraud detection analytics
* Integrate machine learning-based transaction forecasting
* Build mobile-optimized dashboard version
* Add customer segmentation analysis
* Create automated ETL pipelines
* Deploy enterprise-level Power BI Service reporting

---

# ▶️ How to Run the Project

## Step 1: Download the Project Files

* Download the UPI Transaction Data Analysis `.pbix` Power BI dashboard file
* Download the SQL dataset or Excel backup dataset

## Step 2: Open Power BI Dashboard

* Open the  UPI Transaction Data Analysis`.pbix` file using Power BI Desktop

## Step 3: Explore Dashboard

* Use slicers and filters
* Navigate dashboard pages using bookmarks
* Analyze transaction trends and KPIs

---

# 📊 Project Workflow

1. Data Collection from SQL Database
2. Data Cleaning & Transformation
3. Data Modeling
4. KPI Development
5. Dashboard Design
6. Syncing Slicers Implementation
7. Bookmarks Integration
8. Business Insights Generation
9. Interactive Reporting

---

# ✅ Results & Outcomes

* Successfully built an interactive Power BI dashboard for UPI transaction analysis.
* Improved visibility into transaction performance and customer behavior.
* Implemented advanced Power BI functionalities including syncing slicers and bookmarks.
* Created dynamic KPI monitoring system.
* Delivered actionable business insights for decision-making.
* Enhanced reporting efficiency using SQL-based analytics.

---

# 📬 Contact

## 👤 Author

**Your Name**

* LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
* GitHub: [https://github.com/yourusername](https://github.com/yourusername)
* Email: [yourmail@gmail.com](mailto:yourmail@gmail.com)
