# Assm2 Cloud Platform Code Documentation

This README provides an overview of two key files in the `Assm2` code, which are designed for sensor data processing using Databricks and Azure. These files are integral to managing and analyzing IoT sensor data, focusing on tasks such as data ingestion, transformation, and visualization.

## File 1: `sensor_ingestion.py`
This file handles:
- **Data Ingestion:** Imports sensor data from Azure Blob Storage into Databricks.
- **Preprocessing:** Cleans and formats the data for further analysis.
- **Storage:** Saves the processed data into Azure Cosmos DB.

## File 2: `data_analysis.py`
This file is responsible for:
- **Data Transformation:** Performs operations to prepare data for analysis, such as filtering and aggregating sensor readings.
- **Visualization:** Generates insights using Power BI, providing visualizations on air quality, traffic, and energy usage.

These files leverage Azure services to ensure efficient and scalable data management for IoT-based smart city applications.
