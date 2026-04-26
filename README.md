# 🚀 SSIS ETL Sales Project

## 📌 Overview
This project demonstrates a complete **ETL (Extract, Transform, Load)** pipeline using **SQL Server Integration Services (SSIS)** to process sales data.

The pipeline extracts raw data, transforms it into a clean and structured format, and loads it into a Data Warehouse for analytics and reporting.

---

## 🧱 Architecture

```
Source Data  →  Staging Layer  →  Data Warehouse  →  Reporting
```

---

## 🔄 ETL Process

### 1. Extract
- Extract data from source  Database

### 2. Transform
- Handle NULL values
- Remove duplicates
- Data type conversion
- Apply business rules
- Lookup transformations

### 3. Load
- Load data into:
  - Dimension Tables
  - Fact Table (Sales)

---

## 🛠️ Technologies Used

- SQL Server
- SSIS (SQL Server Integration Services)
- SSMS (SQL Server Management Studio)
- Visual Studio

---

## 📂 Project Structure

```
SSIS_ETL_SALES_PROJECT/
│
├── SSIS Packages
├── SQL Scripts
├── Data Sources
├── Staging Tables
└── Data Warehouse Tables
```

---

## 🔁 Loading Strategy

### Initial Load
- Load full data into staging
- Transform and load into Data Warehouse

### Incremental Load
- Load only new and updated data
- Apply Slowly Changing Dimensions (SCD)

---

## ⭐ Features

- End-to-End ETL Pipeline
- Data Cleaning & Transformation
- Star Schema Design
- Incremental Load
- Error Handling

---

## ▶️ How to Run

```bash
git clone https://github.com/ahmedtarikalrefaay/SSIS_ETL_SALES_PROJECT
```

1. Open the project in Visual Studio  
2. Configure database connection  
3. Run SSIS packages  

---

## 📊 Use Cases

- Sales Analysis  
- Business Intelligence  
- Data Engineering Practice  

---

## 📈 Future Improvements

- Add Power BI Dashboard  
- Automate using SQL Server Agent  
- Add logging & monitoring  

---

## 👨‍💻 Author

**Ahmed Alrefaay**  
Data Engineer | ETL Developer
