# Azure-Data-Factory-Project-on-Covid19


## Introduction
Welcome! This repository documents my learning journey and project implementation based on a comprehensive course on Azure Data Factory (ADF) and related Azure data engineering technologies. The course involved building a real-world data engineering solution for reporting COVID-19 trends and predicting virus spread. The skills acquired through this course have equipped me to design, implement, and manage data pipelines using Azure Data Factory.

## Key Learnings

### Azure Data Factory (ADF)
- **Solution Architecture**: Built data engineering solutions integrating ADF, Azure Data Lake Gen2, Azure Blob Storage, Azure SQL Database, Azure Databricks, and Azure HDInsight.
- **Data Integration**: Implemented pipelines to ingest data from HTTP clients, Azure Blob Storage, and Azure Data Lake Gen2.
- **Control Flow Activities**: Applied branching and chaining using `Get Metadata`, `If Condition`, `ForEach`, `Delete`, and `Validation` activities.
- **Metadata-Driven Pipelines**: Utilized parameters and variables to create reusable and dynamic pipelines.
- **Debugging and Issue Resolution**: Gained expertise in debugging and resolving pipeline issues.
- **Scheduling**: Used triggers such as Event Trigger, Schedule Trigger, and Tumbling Window Trigger for pipeline scheduling.
- **Data Transformation**: Created Mapping Data Flows using transformation steps like `Source`, `Filter`, `Select`, `Pivot`, `Lookup`, `Conditional Split`, `Derived Column`, `Aggregate`, `Join`, and `Sink`.
- **Activity Execution**: Orchestrated data transformations using HDInsight and Databricks Notebook activities.
- **Pipeline Dependencies**: Established dependencies between pipelines and triggers for orchestrated data flow.
- **Monitoring and Alerts**: Monitored pipelines and created alerts using Azure Monitor and Log Analytics.

### Azure Storage Solutions
- **Storage Account Management**: Created and managed Azure Storage Accounts, containers, and data uploads.
- **Azure Data Lake Gen2**: Implemented access control and interaction via Azure Storage Explorer.
- **Azure SQL Database**: Configured databases, loaded data, and queried data for analysis.

### Azure HDInsight & Databricks
- **HDInsight**: Created clusters, managed Hive tables, and executed activities from ADF.
- **Databricks**: Set up workspaces and clusters, mounted storage accounts, and built Databricks notebooks for data transformation.

### Azure DevOps (CI/CD)
- **Environment Setup**: Configured Azure DevOps Git repositories.
- **CI/CD Pipelines**: Implemented build and release pipelines to promote ADF artifacts to test and production environments.
- **Parameterized Releases**: Customized CI/CD pipelines for flexible deployment across environments.

## Real-World Project Implementation
The course involved building a project that reports COVID-19 trends and predicts virus spread, encompassing:
- Data ingestion from external sources into Azure Data Lake Gen2 using ADF.
- Data transformation using Mapping Data Flows and Databricks notebooks.
- Loading processed data into Azure SQL Database.
- Generating reports with Power BI on the processed data.

## Skills Gained
- Proficiency in building scalable and production-ready data pipelines in ADF.
- Ability to monitor, debug, and maintain pipelines efficiently.
- Knowledge of best practices, naming conventions, and CI/CD integration for pipeline deployment.
- Foundational skills aligned with the **Azure Data Engineer Associate Certification Exam DP203**.

