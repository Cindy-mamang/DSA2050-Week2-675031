
DSA2050-Week2-675031

Student Information

Name: Cindy Mamang-Kanga

Student ID: 675031

Objective

This project implements an end-to-end exploratory data analysis and database management workflow using Python, Pandas, and SQLite. The primary objective is to clean, integrate, and analyze multi-source retail datasets—consisting of customer profiles, transaction records, and JSON-based regional lookup data—to uncover actionable insights into sales performance, customer segmentation, and regional revenue drivers.

Three Key Findings

Duplicate-Key Resolution: The initial dataset contained duplicate customer records that risked inflating metrics during joins; cleaning and deduplicating by CustomerID successfully preserved data integrity, keeping total sales reconciled at KSh 113,500.

Segment Performance: Customer segment aggregation revealed varying purchasing behaviors across Retail, Corporate, and SME groups, providing leadership with clear metrics on order counts, total sales, and average order values to target marketing strategies.

Regional Distribution: Merging the JSON region lookup data with SQLite queries identified Nairobi as the leading region by total sales (KSh 32,100), though comprehensive profitability analysis remains necessary to account for regional operational costs.