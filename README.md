# CFPB Complaints ETL SSIS Project
This project demonstrates an ETL (Extract, Transform, Load) solution for complaint data from the Consumer Financial Protection Bureau (CFPB). It showcases data handling, cleansing, transformation, and loading into a SQL Server database using SQL Server Integration Services (SSIS).

---

## 🎯 Objective
The goal of this project is to:
- **Extract**: Load complaint data from a CSV file.
- **Transform**: Clean, validate, and standardize the data.
- **Load**: Insert cleaned data into a SQL Server table while ensuring data quality and integrity.

Key competencies demonstrated:
- File handling
- Data transformation and validation
- Error handling and logging
- Loading data into SQL Server tables
- Following best practices in SSIS design

## 🗂️ Destination Table
The final destination is a SQL Server table:
**Table Name:** `CFPB_Complaints`  
**Primary Key:** `ComplaintID`  


### 📥 Load
- **Target:** `CFPB_Complaints` table in SQL Server.
- **Deduplication:** No duplicate `Complaint ID`s are allowed.
- **Error Handling:** Invalid rows are redirected to error logs for auditing and debugging.

---

## ⚠️ Error Handling
- Invalid or problematic rows are redirected to error outputs or logged in a dedicated error table for later review and correction.

## 💡 Best Practices Followed
✅ Data type matching  
✅ Consistent naming conventions  
✅ Handling of NULLs and optional fields  
✅ Robust error handling and redirection  
✅ Modular and maintainable SSIS package design  

---

## 🚀 Outcome
The result is a clean, validated, and reliable SQL Server table containing complaint data, ready for analysis and reporting.

