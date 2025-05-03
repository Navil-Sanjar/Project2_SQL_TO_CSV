# 📊 Project: Employee Data Analysis using SQL + Python

This project simulates a real-world data engineering workflow where employee records stored in a relational database are queried using SQL and analyzed using Python. The results are exported into clean CSV reports.

---

## 🧠 Objective

To create a data pipeline that connects to a PostgreSQL database, runs analytical SQL queries, and exports the output to CSV files using Python.

---

## 📂 Project Structure

employee_analysis_project/ │ ├── sql/ │ ├── create_table.sql # SQL script to create the table │ └── insert_data.sql # Script to insert dummy employee data │ ├── scripts/ │ └── analyze_employees.py # Python script to run analysis │ ├── reports/ │ ├── top_5_salaries.csv │ ├── avg_salary_per_department.csv │ └── most_populated_department.csv │ ├── requirements.txt # Python packages └── README.md # This file


---

## ⚙️ Technologies Used

- **PostgreSQL** – for storing employee data  
- **Python 3** – for querying and exporting data  
- **pandas** – for data analysis and CSV generation  
- **psycopg2** – PostgreSQL database connector  

---

## 🚀 Setup Instructions

### 🧱 1. Database Setup

1. Install PostgreSQL and pgAdmin
2. Create a new database (e.g., `employee_db`)
3. Run the following SQL scripts:

```bash
-- Create table
psql -d employee_db -f sql/create_table.sql

-- Insert sample data
psql -d employee_db -f sql/insert_data.sql

| Report Name | Description |
|-------------|-------------|
| `top_5_salaries.csv` | Top 5 highest-paid employees |
| `avg_salary_per_department.csv` | Average salary by department |
| `most_populated_department.csv` | Department with the most employees |



Connect with me on LinkedIn- https://www.linkedin.com/in/navil-sanjar-08299293/
