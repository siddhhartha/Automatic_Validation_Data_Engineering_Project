# Automatic_Validation_Data_Engineering_Project

This project implements an automated data ingestion and validation pipeline using Azure Data Factory (ADF) and Azure Databricks, designed to process files in Azure Data Lake Storage Gen2 (ADLS Gen2). The solution continuously monitors incoming files and ensures data quality by validating each file before moving it to the appropriate location:

✅ Staging Folder – for valid files that pass all validation rules

❌ Discarded Folder – for invalid or corrupt files

 Key Components:
Azure Data Lake Storage Gen2 (ADLS Gen2): Stores incoming raw data.

Azure Data Factory (ADF): Triggers and orchestrates the pipeline automatically when a new file arrives.

Azure Databricks: Executes custom validation logic using PySpark or Scala.

Validation Rules: Configurable checks such as schema matching, null checks, data type enforcement, and value constraints.

Objectives:
Automate data ingestion and validation

Ensure data quality before loading into downstream systems

Minimize manual intervention in data preprocessing

