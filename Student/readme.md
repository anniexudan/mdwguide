# Welcome to the Modern Data Warehouse WTH!

This is a challenge-based hack. It's NOT step-by-step. Don't worry, you will do great whatever your level of experience! Modern Data Warehouse is a key upgrade motion for organizations to scale out their on-premise analytical workloads to the cloud.  This hack will help data engineers and administrators upgrade their skills to migrate to Azure Synapse Analytics. The hack will be the sequential migration steps required to migrate from on-premise to Synapse Analytics and re-platform attached workloads like ETL and reporting.  The total duration time will be 3 days.


## **Introduction**

The solution will require us to migrate the on-premise data warehouse to Azure Synapse Analytics.  In the first challenge, you will want to source data from the WWI OLTP sample database to **Azure Synapse Analytics**.  Data will be loaded from source to target thru the DailyETL packages (SSIS) found in the WWI importers sample database.  Secondly, a data lake  (**Azure Data Lake Store**) will be built out to be your staging area for future challenges to stage data prior to loading it into Azure Synapse. Third, the SSIS packages in Challenge 1 will be refactored into **Azure Data Factory** jobs to optimize the data loads and leverage the Data Lake as a staging area.  Next, clickstream data will be streamed into the Data Lake using **Azure HDInsight Kafka Cluster**.  This data will be stored in the lake and interactively queried via **Azure Databricks**.  Lastly, Power BI data model will be built out with a set of reports to streamline the performance.  You will work on how to optimize them via report design, data model tuning and Azure Synapse optimizaitons.


## **Solution architecture**

Below is a diagram of the solution architecture you will build in this hack. Please study this carefully, so you understand the whole of the solution as you are working on the various components.

![The Solution diagram is described in the text following this diagram.](images/solution_arch.png 'Solution diagram')


## Technologies

Azure services and related products
* Azure Synapse Analytics
* Azure Data Factory
* Azure HDInsight Kafka Cluster
* Azure Databricks
* Power BI

## Azure solution
Modern Data Warehouse


## Challenges
0.	[Setup](./challenges/Setup.md)
1.  [Data Warehouse Migration](./challenges/CreateResources.md)
2.  [Data Lake Integration](./challenges/Configuration.md)
3.  [Data Pipeline Migration](./challenges/Deployment.md)
4.  [Real-time Data pipeline](./challenges/PortalFunctions.md)
5.  [Analytics migration](./challenges/Monitoring.md)



## Optional Challenges
TBD