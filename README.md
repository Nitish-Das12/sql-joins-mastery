# SQL Joins Mastery

Author: **Nitish Kumar Das** — Data Analyst Practice

## Overview
This repository contains comprehensive SQL practice scripts and documentation focused on mastering SQL `JOIN` clauses[cite: 1, 2]. It covers table setup with deliberate unmatched data patterns to explore join behaviors and edge cases across different join types[cite: 1].

## Covered Topics & Join Types
- **Table Setup & Data Insertion**: Creating schema and inserting sample datasets across 7 practice tables (`CUSTOMERS_J`, `ORDERS_J`, `MOVIES`, `MEMBERS`, `MEALS`, `DRINKS_J`, `STAFF_SELF`)[cite: 1, 2].
- **LEFT JOIN**: Preserving all records from the left table while matching right table data[cite: 1, 2].
- **RIGHT JOIN**: Preserving all records from the right table while matching left table data[cite: 1, 2].
- **INNER JOIN**: Returning matching records present across both tables[cite: 1, 2].
- **FULL OUTER JOIN**: Combining `LEFT JOIN` and `RIGHT JOIN` using `UNION` for MySQL compatibility[cite: 1, 2].
- **CROSS JOIN**: Generating Cartesian products to calculate all combinations and bills[cite: 1, 2].
- **SELF JOIN**: Querying employee-manager hierarchical structures within a single table[cite: 1, 2].

## Repository Structure

sql-joins-mastery/
├── 5.SQL_JOINS.sql          # SQL script with table schema, inserts, and join queries
├── SQL_Practice_Joins.docx  # Document containing problem statements (Q1–Q33)
├── LICENSE                  # MIT License
└── README.md                # Project documentation