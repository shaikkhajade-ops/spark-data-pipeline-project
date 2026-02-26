# End-to-End Data Pipeline using PySpark and Spark SQL

This project demonstrates building an end-to-end ETL pipeline using PySpark.

The pipeline:
- Reads raw CSV data
- Performs data cleaning and transformations
- Applies joins and aggregations
- Writes output in ORC format

## Project Overview

This project simulates a real-world data engineering pipeline.  
It demonstrates how raw data is processed, transformed, and stored in optimized format using PySpark and Spark SQL.

## Technologies Used
- Python
- PySpark
- Spark SQL

## Topics Covered
- DataFrame creation
- Reading CSV files
- Select & Filter
- Aggregations
- Joins
- Group By
- Writing ORC output files

## Project Structure

├── data/              # Input CSV and JSON files

├── scripts/           # Spark SQL Python scripts

├── README.md          # Project documentation


## Author
Shek Khaja Moinuddin

## How to Run

Run the Spark script using:

spark-submit scripts/etl_pipeline.py
