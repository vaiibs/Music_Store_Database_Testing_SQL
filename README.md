# 🎵 Music Store Backend & Database Testing Project

## 🚀 Project Overview
This project demonstrates backend data validation and complex SQL querying skills. Using a digital music store database, I've performed deep data analysis and implemented database testing scenarios to ensure data integrity and business logic accuracy.

## 🔍 Database Testing Scenarios Implemented
* **Data Completeness:** Verified that mandatory fields (Customer Email, Invoice Date) contain no null values.
* **Data Accuracy:** Validated that the 'Total Amount' in the Invoices table matches the sum of individual unit prices in InvoiceLines.
* **Boundary Value Testing:** Identified top-spending customers and high-performing genres using aggregate functions (`SUM`, `COUNT`, `GROUP BY`).
* **Complex Data Retrieval:** Used `JOIN` operations across 3+ tables (Tracks, Albums, Artists) to verify correct data mapping.

## 💻 Key SQL Queries
* **Top Revenue by Country:** Used to verify market-specific sales data.
* **Most Popular Genre:** Joins between `Track`, `Genre`, and `InvoiceLine` to validate sales trends.
* **Customer Lifetime Value:** Complex aggregation to identify high-value users.
