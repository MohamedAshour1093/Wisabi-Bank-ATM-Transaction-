# Wisabi Bank ATM Transaction Analytics | Power BI

## 📊 Project Overview
This project analyzes ATM transaction data for Wisabi Bank to understand customer behavior, ATM utilization, and regional performance.  
The goal is to provide actionable insights that help improve ATM service availability, customer experience, and operational efficiency.

---

## 🎯 Business Objective
Banks rely heavily on ATM networks for customer access to cash and basic banking services.  
This analysis helps stakeholders to:
- Monitor ATM usage patterns
- Identify high and low utilization locations
- Understand customer transaction behavior
- Support data-driven decisions for ATM placement and optimization

---

## 🛠️ Data Preparation (Power Query)
Data cleansing was performed to ensure accuracy and consistency before analysis:

- Imported raw ATM transaction data into Power Query
- Removed duplicate records to avoid skewed results
- Handled missing values based on business relevance
- Standardized date, time, and transaction formats
- Performed transformations such as:
  - Column splitting and merging
  - Data type corrections
  - Derived metrics creation

**Tools used:**  
- Power BI (Power Query)

---

## 🧱 Data Modeling
A structured data model was created to support scalable analysis:

### Fact Tables
- Kano Transactions
- Lagos Transactions
- FCT Transactions
- Rivers Transactions

### Dimension Tables
- Calendar Dimension
- Transaction Type Dimension
- Customer Dimension
- Location Dimension

Relationships were defined between fact and dimension tables to enable accurate filtering, aggregation, and time-based analysis.

**Tools used:**  
- SQL Server  
- Power BI Data Modeling

---

## 📊 Dashboard Development (Power BI)
An interactive dashboard was built to visualize key insights and performance indicators.

### Key Metrics Analyzed
- ATM utilization rates (highest and lowest performing locations)
- Average transaction time by location
- Transaction amount distribution
- Transaction frequency by region
- Regional performance comparison

### Dashboard Features
- Interactive filters and slicers
- Location-based performance views
- Customer demographic analysis
- Transaction behavior insights

---

## 📈 Insights & Outcomes
- Identified ATMs with consistently high and low utilization rates
- Highlighted regional differences in transaction volume and behavior
- Provided visibility into transaction patterns by customer demographics
- Enabled stakeholders to identify opportunities for ATM network optimization

---

## 🧰 Tools & Technologies
- **Power BI** — Dashboard creation and visualization
- **Power Query** — Data cleansing and transformation
- **SQL Server** — Data modeling support

---

## 📂 Project Assets
- Power BI Dashboard (PBIX)
- Dashboard Images
- Stakeholder Presentation (PPTX)

📎 [View Presentation](./Wisabi%20Bank-Report.pptx)

---

## 📌 Notes
This project reflects a real-world **banking operations and ATM analytics workflow**, focusing on operational visibility and service optimization rather than purely exploratory analysis.
