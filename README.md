# Azure Databricks Repository

This repository contains sample notebooks, raw source files, and documentation for Azure Databricks workflows, including data ingestion, transformation, aggregation, join operations, and date/time processing.

## Repository Structure

- `Documentation/`
  - Contains HTML schema and documentation files.
- `Notebooks/`
  - Databricks notebooks demonstrating common data engineering patterns in PySpark.
- `Raw_Source/`
  - Sample input files organized by category for filtering, joining, transformation, and aggregation.

## Notebooks Included

- `Aggegations.ipynb` - Aggregation examples.
- `DataFilter.ipynb` - Data filtering examples.
- `DataRead_Malformed.ipynb` - Reading malformed data.
- `DataRead.ipynb` - Basic data ingestion.
- `DateAndTime.ipynb` - Date and time handling.
- `Joins.ipynb` - Join operations.
- `Transformation.ipynb` - Data transformation examples.

## Raw Source Samples

- `Aggregations/employee_salary_data.csv`
- `Customer_Data/` - Various customer datasets in JSON, CSV, and XML.
- `Filter_Data/Products_Purchase_Data_20210111.csv`
- `Joins/customers.csv`, `Joins/orders.csv`
- `Transformations/` - Product and purchase datasets for transformation examples.

## How to Use

1. Open the workspace in Azure Databricks.
2. Upload the notebooks and raw source files to a Databricks workspace or a connected storage account.
3. Run the notebooks in order to explore data ingestion, cleansing, transformation, and analytics patterns.

## Notes

- This repository is intended for learning and prototyping Azure Databricks data engineering workflows.
- Adjust file paths and cluster configuration as needed for your environment.
