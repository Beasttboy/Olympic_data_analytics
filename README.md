# Olympic Data Analytics Project – Azure End-to-End Data Engineering
This README provides an overview and setup guide for the Olympic Data Analytics project, as demonstrated in this YouTube video by Darshil Parmar. The project showcases how to build a complete data engineering pipeline using Microsoft Azure services to analyze Tokyo 2021 Olympic data.

**Project Overview**

This project demonstrates an end-to-end data engineering workflow on Azure, including:

Data Extraction: Ingesting raw Olympic data from a public dataset.
Data Storage: Storing raw and transformed data in Azure Data Lake Storage Gen2.
Data Transformation: Cleaning and transforming data using Azure Databricks (Apache Spark).
Analytics & Visualization: Querying transformed data with Azure Synapse Analytics and creating visualizations (optionally with Power BI).


**Project Architecture**

![image](https://github.com/user-attachments/assets/4f3894c1-9fc6-4c43-ba34-524beeb94b91)




**Dataset**

Source: Tokyo Olympics 2021 Dataset on Kaggle


**Files Included :**

•	athletes.csv

•	coaches.csv

•	entries_gender.csv

•	medals.csv

•	teams.csv


**Azure Services Used**

•	Azure Data Factory: Orchestrates data ingestion from the source to Azure Data Lake.

•	Azure Data Lake Storage Gen2: Stores both raw and processed data.

•	Azure Databricks: Performs data cleaning and transformation using Spark.

•	Azure Synapse Analytics: Enables SQL-based analytics and reporting.

•	(Optional) Power BI: For dashboarding and visualization.
