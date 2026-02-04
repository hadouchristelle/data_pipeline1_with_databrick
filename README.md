# data_pipeline1_with_databrick

# Scenario
This project involves the design and implementation of end-to-end data pipeline folowing Lakehouse Architecture (Bronze,Silver,Gold) using Databrick and apache spark.The data sources consist of six filesnorig from source_01 and source_02 systems.
The solution covers the complete data lifecycle,including:
  Data ingestion from source system,
  Data cleansing and transformation,
  Data aggregation and analytical modeling,
  Pipeline orchestration and scheduling.
The main objective is to deliver reliable,well_strutured, and anlytics-ready datasets that support business intelligence, data analysis, and insight generation.
# Requirements
The data pipeline is built on a lakehouse architecture.Data is first ingested into databricks through volumes(ingestion layer), then loaded into delta tables inthe bronze layer. the data is subsequently cleaned and normalized in the silver layer before being aggregated and exposed in the gold layer for analytical purposes.
# Technologies used
Databricks,
Apache Spark,
PySpark,
untity Catalog
# Project architecture
This Lakehouse architecture on Databricks follows the bronze/silver/gold pattern,enabling reliable ingestion of raw data, progressive data cleasing and reporting. The use of delta lake ensures data quality, traceability, and high performance across the entire data pipeline
<img width="2104" height="1192" alt="image" src="https://github.com/user-attachments/assets/cba041be-7e73-4006-b9c5-b330da3b6edf" />
# process for completing the project
1- built Lake house
### Catalog creation: In this project I used the Databrick unity catalog(workspaces)
### Creation of bronze,silver, gold schemas
<img width="2656" height="1336" alt="image" src="https://github.com/user-attachments/assets/df2d124a-014f-409b-b235-f1a16948f590" />
### creation of volumes and ingestion into volumes
<img width="2098" height="872" alt="image" src="https://github.com/user-attachments/assets/e46cdc94-ab3f-4087-8948-8f34753444e9" />



