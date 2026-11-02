# Data Cleaning Using SQL – Layoffs Dataset

## 📌 Project Overview
This project focuses on cleaning and preparing a raw layoffs dataset using MySQL. The objective is to improve data quality, maintain consistency, and make the dataset more reliable for further analysis.

## 🛠️ Tools & Technologies
- MySQL

## 🔍 Data Cleaning Process

### 1. Removing Duplicates
- Identified duplicate records using `ROW_NUMBER()`.
- Used Common Table Expressions (CTEs) to identify duplicate rows.
- Removed duplicate records to maintain data accuracy.

### 2. Standardizing Data
- Removed unnecessary spaces using `TRIM()`.
- Standardized inconsistent industry and country values.
- Ensured consistent formatting across the dataset.

### 3. Handling NULL and Blank Values
- Identified missing and blank values.
- Converted blank industry values into NULL.
- Used self-joins to populate missing industry information where matching data was available.
- Removed records with no layoff information.

### 4. Date Formatting
- Converted text-based date values into a proper DATE format using `STR_TO_DATE()`.
- Modified the column data type to DATE.

### 5. Removing Unnecessary Columns
- Removed the helper column created during duplicate identification.

## 📚 Key Learnings
- Practical application of SQL for data cleaning.
- Working with CTEs and Window Functions.
- Using JOINs to handle missing values.
- Understanding data inconsistencies and standardization.
- Importance of data quality in the data analysis process.

## 📂 Project Files
- `Data Cleaning – Layoffs Dataset.sql` – SQL queries used to clean and prepare the layoffs dataset.

## 🎯 Project Outcome
The project demonstrates how SQL can be used to transform raw, inconsistent data into a cleaner and more structured dataset, making it more suitable for further data analysis.

---

**Project Type:** Personal Project  
**Domain:** Data Analytics  
**Tools:** MySQL | SQL
