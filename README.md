# 🚀 Healthcare Data Management Project

## 📚 Project Overview
Transforming a real-world healthcare dataset from a raw CSV file into a fully normalized, structured, and queryable SQL Server database.

---

## 🛠️ Workflow Summary

| Step | Description |
|:---|:---|
| 1. Data Preparation | Cleaned and standardized the dataset using Power Query. |
| 2. Database Design | Built ERD, performed Normalization up to 3NF, and mapped entities to relational tables. |
| 3. SQL Server Integration | Imported data, created `RawData` table, and distributed into normalized tables. |
| 4. SQL Query Execution | Ran advanced SQL queries for analysis and insights extraction. |

---

## 📋 Detailed Steps

### 1. Data Preparation (Power Query)
- Removed duplicate rows.
- Extracted **Title** and **Suffix** from patient and doctor names.
- Standardized date formats (`Day/Month/Year`).

### 2. Database Design (ERD, Normalization & Mapping)
- Designed **Entity-Relationship Diagram (ERD)**.
- Normalized data into multiple tables:
  - **Patients**, **Doctors**, **Hospitals**, **Insurance Providers**, **Admissions**, **Medications**.
- Mapped relationships between entities and ensured referential integrity using Primary and Foreign Keys.

### 📸 ERD Diagram:
![ERD Diagram](.[/images/ERD_Diagram.png](https://github.com/HagerSalahRamadan/SQL_Healthcare-Data-Management-Project/blob/main/SQL_Project_ERD.drawio.png))

### 📸 Normalization & Relational Mapping:
![Normalization Mapping](./images/Normalization_Mapping.png)

---

### 3. SQL Server Integration
- Imported the cleaned dataset into SQL Server.
- Created a **RawData** table to initially store the complete data.
- Structured the final normalized database using SQL DDL scripts.

### 📸 SQL Server Database Diagram:
![Database Diagram](./images/Database_Diagram.png)

---

### 4. SQL Querying
- Executed advanced SQL queries using:
  - `JOIN` operations across tables.
  - `CTE` (Common Table Expressions).
  - `Subqueries`.
  - `CASE` statements.
  - `GROUP BY`, `HAVING`, and aggregate functions.

#### 🛠️ Examples of Insights:
- Classifying patients as **Senior** or **Adult** based on age using `CASE`.
- Listing patients treated in a specific hospital.
- Calculating total billing amounts per hospital.
- Identifying patients admitted multiple times.

### 📸 SQL Query Snapshots

#### 🔹 Basic SELECT & WHERE Filtering
Retrieve the names and genders of all patients.
Display all patients with blood type O+.

![SELECT Query](./images/select_query.png)


#### 🔹 Aggregation + GROUP BY & ORDER BY Sorting
Count the number of patients in each blood type.
Order patients by age from oldest to youngest.
![GROUP BY](./images/groupby_query.png)


#### 🔹 JOIN with Condition
Display all patients treated in 'Carter Ltd' using JOIN.
Display patients admitted through 'Emergency'	
![JOIN Query](./images/join_query.png)


#### 🔹 DATEDIFF Function & CASE Statement + JOIN + Filtering
Patients discharged 10+ days after admission.
Classify patients as Senior or Adult based on age.
![DATEDIFF Query](./images/datediff_query.png)


#### 🔹 Aggregation Function + HAVING & Subquery Filtering
List patients who were admitted more than once.
Show patients with billing amounts above the average.
![HAVING Query](./images/having_query.png)


#### 🔹 CTE Usage
Using a CTE, show patients over age 40 admitted as 'Urgent'.
![CTE Query](./images/cte_query.png)
---

---

## ⚙️ Tools Used
- **Microsoft Excel** (Power Query)
- **SQL Server Management Studio**
- **draw.io** (for diagrams)

---

## 📢 Key Topics
`#SQL` `#DataCleaning` `#DatabaseDesign` `#HealthcareData` `#PowerQuery` `#DataNormalization` `#ERD` `#SQLServer`

---

## Contact

For any questions Contact via email **hagersalah.r39@gmail.com**.
