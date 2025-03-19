# IMDb Data Profiling - Data Engineering Project
---
## 📖 Project Overview
This project involves **end-to-end data processing** of IMDb datasets, leveraging **Azure, Snowflake, Python, and Alteryx** for data ingestion, cleaning, modeling, and visualization.
---

## 🛠 Technology Stack
- **Cloud Storage:** 🌩 **Azure Blob Storage**
- **Data Processing:** 🐍 **Python, Alteryx**
- **Data Modeling:** 🏗 **ER Studio**
- **Data Warehouse:** ❄ **Snowflake**
- **ETL Pipelines:** 🔀 **Azure Data Factory (ADF)**
- **Visualization:** 📊 **Power BI**

---

## 🏗 End-to-End Data Processing Pipeline
### 🔹 **1. Data Ingestion (Medallion Architecture)**
- **Raw Data (Bronze Layer):** Stored in Azure Data Lake Storage.
- **Processed Data (Silver Layer):** Converted to **Parquet format** for optimized storage.
- **Final Data (Gold Layer):** Loaded into **Snowflake** for transformations & reporting.

### 🔹 **2. Data Cleaning & Preprocessing**
- Handled missing values:
  - `NULL` values replaced with placeholders (`Unknown`, `NA`, `9999`, `00`).
- Trimmed **extra spaces** from text columns.
- Processed **comma-separated values (CSV)** into structured format.

### 🔹 **3. Data Modeling (ER Studio)**
- Designed a **dimensional model**:
  - **2 Fact tables**
  - **8 Dimension tables**
  - **3 Bridge tables**
- Maintained **referential integrity** and optimized query performance.

### 🔹 **4. Data Transformation (Azure Data Factory - ADF)**
- **Join Operations**: Used **INNER JOINS** to maintain integrity.
- **Surrogate Key Generation**: Created unique **identifiers** for records.
- **Derived Columns**: Added computed attributes for analysis.

### 🔹 **5. Data Loading & Reporting**
- **Incremental data loading** to **optimize performance**.
- **Power BI Dashboard** created for visualization of insights.

---

## 📊 Visual Representations
### 📍 **Logical ER Model**
![1](https://github.com/shrutisen/DAMG7370_Midterm/blob/main/Screenshot%202025-03-11%20at%2020.24.17.jpeg)

### 📍 **Analytics**
![1](https://github.com/shrutisen/DAMG7370_Midterm/blob/main/Screenshot%202025-03-15%20at%2020.37.47.jpeg)
![2](https://github.com/shrutisen/DAMG7370_Midterm/blob/main/Screenshot%202025-03-15%20at%2020.37.00.jpeg)
![3](https://github.com/shrutisen/DAMG7370_Midterm/blob/main/Screenshot%202025-03-15%20at%2020.38.15.jpeg)



---

