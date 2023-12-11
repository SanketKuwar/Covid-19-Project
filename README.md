# 🚀 PROJECT ARCHITECTURE - COVID 19 PROJECT

![Project Image](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/Image.png)

## PROJECT OVERVIEW

### Tech Stacks:
- 🌐 Azure Data Factory
- 🌐 Azure Databricks
- ☁️ Azure Blob Storage
- ☁️ Azure Data Lake Storage Gen 2
- 🌐 Azure SQL Database
- 📊 Power BI

Welcome to my project where the synergy of Azure technologies orchestrates seamless data integration, transformation, and dazzling reporting. Below is a journey through each pivotal component:

#### ✅ Data Integration and Orchestration:
- 🎭 **Azure Data Factory (ADF):** The maestro orchestrating data integration and tasks. ADF elegantly connects diverse data sources, providing a spectrum of connectors for future expansion. Think of it as a choreographer for workflow execution, including transformations in HDInsight and Azure Databricks.

#### ✅ Storage Solutions:
- 📦 **Azure Blob Storage:** The heartbeat, storing population data and distributing it to different teams.
- 📁 **Azure Data Lake Storage Gen 2:** A robust Data Lake managing extensive data volumes securely and efficiently.
- 💾 **Azure SQL Database:** The data warehouse powerhouse, chosen for its scalability and parallel processing prowess.

#### ✅ Transformation Technologies:
- 🌀 **Data Flow within Data Factory:** A code-free wizard for simple to moderately complex data transformations.
- 🌌 **HDInsight and Azure Databricks:** Unleashing coding magic in Python or Spark SQL for intricate transformations.

#### ✅ Reporting:
- 📈 **Power BI:** Where data visualization becomes an art form.

## INGESTION

![Project Image](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/Injection_activity_1.png)

Embark on the data collection odyssey from Azure Blob Storage to our data lake, courtesy of Azure Data Factory:

### 1. Data Ingestion from Azure Blob

Behold the dance of data with these steps:
- ✅ **Copy Activity:** The fundamental mover of data.
- ✅ **Creating Link Services and Datasets:** Meticulous setup for seamless data flow.
- ✅ **Pipeline Construction:** Components woven into a flawless execution.
- ✅ **Triggers for Automation:** Scheduling ballet for data pipelines.

### 2. Data Ingestion from HTTP (Git)

The exploration of ECDC data, the creation of dynamic pipelines, and the passage of parameters unfold in these steps:
- ✅ **Exploration of ECDC Data:** A journey into the ECDC website's data intricacies.
- ✅ **Pipeline Creation:** The initiation of the pipeline creation ritual.
- ✅ **Dynamic Pipelines:** The infusion of dynamism with variables and parameters.
- ✅ **Parameter Passing:** An exploration of passing parameters for added flexibility.
- ✅ **Metadata-Driven Pipeline:** A symphony of components creating a metadata-driven pipeline.

## TRANSFORMATION

Witness the metamorphosis of cases, deaths, and hospital admission data with enchanting transformations:

### 1. Transformation using Data Flows

![Project Image](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/Cases_Tranform.png)

#### Data Flows - Cases & Deaths Data Transformation:

A tale told in transformational steps:
- ✅ **Source Transformation:** Defining the data source for structured accessibility.
- ✅ **Filter Transformation:** Selective extraction of relevant data points.
- ✅ **Select Transformation:** Choosing data attributes for streamlined analysis.
- ✅ **Pivot Transformation:** Reshaping data for analytical elegance.
- ✅ **Lookup Transformation:** Enriching data with external wisdom.
- ✅ **Sync Transformations:** Ensuring synchronized and updated transformed data.

#### Data Flows - Hospital Admissions Data Transformation:

![Project Image](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/Hospital_Transformation.png)

A saga of transformational arts:
- ✅ **Source Transformation:** Extracting data from various sources for manipulation.
- ✅ **Select Transformation:** Filtering and structuring data with finesse.
- ✅ **Lookup Country:** Enriching data with additional layers of insight.
- ✅ **Conditional Split Transformation:** Skillful routing of data based on predefined conditions.
- ✅ **Derived Column Transformation:** Crafting new data columns for expanded utility.
- ✅ **Aggregate Transformation:** Summarizing and aggregating data for profound analysis.
- ✅ **Join Transformation:** Merging data from diverse sources for comprehensive insights.
- ✅ **Pivot Transformation:** Reshaping data for captivating visualization.
- ✅ **Sort Transformation:** Mastering effective data sorting techniques.
- ✅ **Sink Transformation:** Guiding transformed data to its destination efficiently.
- ✅ **Create ADF Pipeline:** The birth of an Azure Data Factory pipeline for streamlined transformation.
  
<img align="right" height="235" width="400" alt="" src="https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/HD_insight.png" />

### 2. Transformation using HDInsight

- ✅ **Create HDInsight Cluster:** Initiating the creation of an HDInsight cluster, a crucial step for unleashing HDInsight activity within Data Factory.
- ✅ **Create ADF Pipeline with Hive Activity:** Structuring components into an Azure Data Factory pipeline, incorporating the Hive activity for data transformation.
- ✅ **Delete HDInsight Cluster:** The importance of tidying up – deleting the HDInsight cluster when not in use.
  
<img align="right" height="235" width="400" alt="" src="https://github.com/SanketKuwar/Covid-19-Project/blob/main/Covid%2019%20Images/project1.png" />

### 3. Transformation using DataBricks

The magic of Azure Databricks unfolds:
- ✅ **Create Azure Databricks Service:** Initiating the project with the creation of an Azure Databricks service.
- ✅ **Create Azure Databricks Cluster:** Creating a Databricks cluster, the gateway to mounting storage accounts into the Databricks workspace.
- ✅ **Mounting Azure Data Lake Storage:** Ensuring seamless data access by mounting storage accounts for Azure Block Storage and Data Lake into our Databricks workspace.
- ✅ **Create ADF Pipeline Databricks Notebook Activity:** Organizing components into an Azure Data Factory pipeline, incorporating the Databricks Notebook activity for streamlined data processing.

  🔗  [Databricks Mount Code](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Code_mount.py)

  🔗  [DataBricks Transformation Code](https://github.com/SanketKuwar/Covid-19-Project/blob/main/Code_transform_population_data.py)

## DATA VISUALIZATION ( POWER BI )

![Project Image](https://github.com/SanketKuwar/Covid-19-Project/blob/main/PowerBI_Reports_Covid19/PowerBI_Reports_Covid19.png)
