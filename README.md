# Customer-Churn-Analysis-through-a-Data-Pipeline-using-Airflow-AWS-Glue-S3-Redshift-and-Power-BI

In this data engineering project, I performed a customer churn analysis, built,
and automated an ETL pipeline using AWS Glue to load data from the AWS S3 bucket
into an Amazon Redshift data warehouse and then connect Power BI to the Redshift
cluster for end user view. AWS Glue served as a data crawler to infer the database
schema after the data was made available in AWS Athena to extract the data
through SQL queries. AWS Glue also served to upload the tracked and processed
data to the Redshift cluster. Apache Airflow was used to orchestrate and automate
this entire process that was previously manual.
