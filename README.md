# RFID-Based Employee Access & Data Analytics System

## Project Overview
This project is an RFID-based employee access monitoring system integrated with a data warehousing and analytics solution.  
It captures employee access events using RFID technology, processes the data through a Python ETL pipeline, stores it in a SQL Server data warehouse, and visualizes insights using Power BI dashboards.
The system aims to enhance access control, track attendance, and provide meaningful analytics for decision-making.

---

## Key Features
- RFID-based access system for employees  
- Python ETL pipeline for data extraction, transformation, and loading  
- SQL Server data warehouse designed using a star schema  
- Interactive dashboards and visual reports in Power BI  
- Attendance and access behavior analysis  

---

## Technologies Used
- **Programming Language:** Python  
- **Database:** Microsoft SQL Server  
- **Data Modeling:** Star Schema (Fact & Dimension Tables)  
- **Visualization:** Power BI  
- **Hardware:** RFID Reader and RFID Tags  

---

## System Architecture
1. Employees scan their RFID cards  
2. Access data is collected and logged  
3. Python ETL processes and cleans the data  
4. Data is loaded into a SQL Server data warehouse  
5. Power BI dashboards visualize insights and trends  

---

## Database Design
The data warehouse follows a **Star Schema**:
- **Fact Table:** Employee Access Events  
- **Dimension Tables:**  
  - Employee  
  - Time  
  - Access Point / Location  
This design allows fast querying and efficient reporting.

---

## Power BI Dashboards
The Power BI reports provide insights such as:
- Employee attendance trends  
- Access frequency per employee  
- Peak access hours  
- Department-level access analysis  

---

## Author

Maram Ghribi

This project reflects a strong integration of hardware, data engineering, and business intelligence, combining RFID technology with data warehousing and analytical visualization to support secure access control and informed decision-making.
