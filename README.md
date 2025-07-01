# 3MTT-SQL-Project
FE/24/8023274694
A  comprehensive summary of your SQL Capstone Project, including where JOINs were made, summary of what was done, KPIs derived, and recommendations for business decisions based on your analysis.

## 1. JOINs Explained

JOINs were used to combine information from related tables to produce comprehensive and meaningful reports.

| **Query No.** | **JOIN Used**                     | **Purpose**                                               |
| ------------- | --------------------------------- | --------------------------------------------------------- |
| Q5            | `Supplier` + `Product`            | To list each supplier with the products they supply       |
| Q6            | `Order` + `Customer`              | To get complete order info with customer details          |
| Q7            | `OrderItem` + `Product` + `Order` | To break down orders by product, quantity, and unit price |
| Q12           | `Supplier` + `Product`            | To count number of products each supplier offers          |
| Q15           | `Order` + `Customer`              | To calculate total revenue per customer                   |
| Q19           | `Order` + `Customer`              | To calculate average order value per customer             |


## 2. Summary of Project Execution

This SQL project explored a business database with 5 key tables:

* `Customer`
* `Order`
* `OrderItem`
* `Product`
* `Supplier`

Main Tasks Completed:

* Extracted specific data (e.g., customers from a country)
* Concatenated names for clean presentation
* Used `CASE` for conditional formatting
* Aggregated data using `COUNT()`, `SUM()`, `AVG()`
* Filtered and sorted data using `WHERE`, `ORDER BY`, and `HAVING`
* Analyzed time-based data (orders in January 2013)

## 3. KPIs (Key Performance Indicators) Derived

|   KPI                                   |   Query   |   Insight                                                |
| --------------------------------------- | --------- | -------------------------------------------------------- |
|    Total products per supplier          | Q12       | Helps evaluate supplier contribution to inventory        |
|    Customers per country                | Q13, Q14  | Shows regional market penetration                        |
|    Total revenue per customer           | Q15       | Identifies high-value customers                          |
|    Average order size                   | Q19       | Aids in customer segmentation and loyalty programs       |
|    Monthly sales (Jan 2013)             | Q20       | Tracks seasonal demand and revenue trends                |
|    Supplier availability by region      | Q16       | Indicates supplier diversity and dependency risks        |
|    Product packaging (jars, 'Ca%' etc.) | Q10, Q11  | Useful for logistics, warehousing, marketing focus       |
|    Supplier language (CASE)             | Q9        | Important for localization and global expansion planning |


## 4. Business Recommendations

### Customer Strategy

* Focus on high-revenue customers identified in Q15 with loyalty or VIP programs.
* Target countries with >10 customers (Q17) with localized offers and marketing.
* Explore underserved markets by comparing Q13 and Q14 with global population trends.

### Supplier Optimization

* Diversify suppliers in countries with only 1–2 suppliers to reduce risk (Q16).
* Suppliers with many products (Q12) should be nurtured as strategic partners.

### Product Strategy

* Products starting with "Ca" or packaged in jars (Q10, Q11) could indicate trending categories.
* Discontinued products (Q8) may need reevaluation for reactivation or marketing tweaks.

### Sales and Order Insights

* Use Q19 to segment customers based on spending patterns for personalized campaigns.
* Use Q20 to track monthly performance trends and adjust inventory/marketing accordingly.

### International Strategy

* From Q9, understanding the primary language per supplier helps in:

  * Effective communication
  * Cultural alignment
  * Improved compliance

#### Abimbola Odunola Ige
Fellow ID: FE/24/8023274694
Cohort 3

