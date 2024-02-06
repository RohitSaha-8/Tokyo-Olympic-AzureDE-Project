# Tokyo Olympic Data Engineering Project

## Overview
This project is about building an end-to-end data engineering project on Azure Cloud. It uses Azure Data Factory to extract Olympic data from an API and load it onto Azure Data Lake. Spark code is used for transformation in Databricks and Synapse Analytics for analysis.

## Services Used
1. Azure Data Factory
2. Azure Data Lake Gen 2
3. Azure Databricks
4. Azure Synapse Analytics
5. Microsoft PowerBi

## Steps
1. The data set contains information about 11,000 athletes, 46 disciplines, and 743 teams participating in the Tokyo Olympics 2021.
2. Create an Azure account and subscription.
3. Create a storage account and data factory in Azure.
4. Extract and load data from GitHub to Azure Data Lake storage using Azure Data Factory.
5. Data from GitHub is stored using Azure Data Factory.
6. Create a connection between Azure Databricks and Azure Data Lake Storage.
7. Create connection to Azure data Factory and mounted data Lake.
8. Data transformation using Apache Spark and writing data onto target location.
9. Setting up Synapse Analytics workspace for Tokyo Olympic data storage.
10. Loading and transforming data in Synapse for Olympic analytics.
11. Validating column names and deploying changes and Using SQL for data analysis and calculations.
12. Create connection between Azure Synapse and Microsoft PowerBi for final visualization.

## Dataset used
https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

## Architecture
![Olympic Data - Architecture](https://github.com/RohitSaha-8/Tokyo-Olympic-AzureDE-Project/assets/63776719/c782866f-c4c7-4e1f-b9a4-ba38600f2d25)



