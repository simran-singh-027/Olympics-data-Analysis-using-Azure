**Azure end to end project on Olympics dataset**

**Short Description of the Architectural Daigram Used in this project:**

ETL:It means Extract, Tranform, Load. It is used to extract data from multiple sources, perform transformation logics on the our data like cleaning datasets, removing null/ duplicates values, renaming columns etc. Then we load this tranformed data into the target data sources.

Data sources: Our raw dataset used in the project. I have used Olympics dataser from Kaggle.

Azure Data Factory:  It is data intregration tool use to connect to variosu tool, do some basic tranformations on our data. We create data pipelines here in ADF.

Azure data lake storage Gen2:It is object storage account where we can store our blob files, create containers, create tables.

Azure Databricks:We will use the data from data lake Gen2 and write code in Apache Spark in databricks and do some transformations and again load our tranform data onto data lake storage Gen2.

Azure Synapse Analytics: Here we will be using SQL Functions,notebooks to do some analytics like who won highest gold medal by country or which country scored most medals using SQL queries.

Power BI: Here we will build the dashboard using Power BI.
