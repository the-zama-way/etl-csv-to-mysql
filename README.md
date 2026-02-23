# ETL Pipeline: CSV to MySQL

## 📌 Project Overview
This project extracts sales data from a CSV file, transforms it using Pandas, and loads it into a MySQL database using SQLAlchemy.

## Tech Stack
- Python
- Pandas
- SQLAlchemy
- PyMySQL
- MySQL
- Git & GitHub

## ETL Flow
CSV → Pandas → Data Transformation → MySQL Table

## Features
- Column renaming & cleaning
- Sales tier classification
- Load timestamp tracking
- Automated table creation
- Error handling

## How to Run
1. Clone the repository:
      git clone https://github.com/your-username/etl-csv-to-mysql.git
2. Install dependencies:
      pip install -r requirements.txt
3. Configure MySQL credentials in the notebook/script.
4. Run the ETL notebook:
      etl_csv_to_mysql.ipynb
## 📊 Output
->The transformed data is stored in the MySQL table:
    etl_transformed_sales inside the `sales_db` database.
