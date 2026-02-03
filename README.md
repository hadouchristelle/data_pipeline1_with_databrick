# data_pipeline1_with_databrick

# Scenario
This project involves the design and implementation of end-to-end data pipeline folowing Lakehouse Architecture (Bronze,Silver,Gold) using Databrick and apache spark.The data sources consist of six filesnoriginating from crm and epr systems.
The solution covers the complete data lifecycle,including:
  . Data ingestion from source system,
  .Data cleansing and transformation,
  .Data aggregation and analytical modeling,
  .Pipeline orchestration and scheduling
The main objective is to deliver reliable,well_strutured, and anlytics-ready datasets that support business intelligence, data analysis, and insight generation.
# Requirements
The data pipeline is built on a lakehouse architecture.Data is first ingested into databricks through volumes(ingestion layer), then loaded into delta tables inthe bronze layer. the data is subsequently cleaned and normalized in the silver layer before being aggregated and exposed in the gold layer for analytical purposes.
# Technologies used
.Databricks
.Apache Spark
.PySpark
.untity Catalog
# Project architecture
<img width="2104" height="1192" alt="image" src="https://github.com/user-attachments/assets/cba041be-7e73-4006-b9c5-b330da3b6edf" />
# process for completing the project
1- built Lake house

