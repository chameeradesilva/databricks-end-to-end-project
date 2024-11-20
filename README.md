# databricks-end-to-end-project
DataBricks to create multiple ETL pipelines using the Python API of Apache Spark

Getting Started:

Clone this repo
Set up Databricks CE
Upload data files (CSV, Parquet, Delta)
Clone notebooks (instructions in HTML source files)
Run notebooks:
customer_delta_table_creation (first time only)
Optional: Delete Delta logs (%fs rm -r dbfs:/user/hive/warehouse)

Code:
Factory Pattern for data source readers
PySpark/Spark SQL for data transformations
Data loading to Data Lake & Lakehouse
Note: Detailed explanations in notebooks.
