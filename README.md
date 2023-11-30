# Azure Data Engineering Project

## Project Overview
This project establishes a comprehensive end-to-end data pipeline, spanning from an on-premise SQL Server to Azure Data Lake Gen2. It is designed to showcase a variety of Azure services and their integration for a seamless data processing and analytics workflow.

## Key Components
- **Azure Data Factory**: Utilized for efficient data ingestion from the on-premise SQL Server to Azure Data Lake Gen2.
- **Databricks**: Employed for robust and layered data processing.
- **Azure Synapse Analytics**: Used for advanced analytics on the processed data.
- **Power BI**: Integrated for dynamic reporting and visualization of insights.
- **Security**: Reinforced through the implementation of Azure Active Directory and Key Vault.

## Documentation
- The project includes detailed documentation in the form of Notes (Word files). These documents provide a step-by-step guide on the project's execution, ensuring a comprehensive understanding of each phase.

## Workflow
1. **Data Ingestion**: Data from the on-premise SQL Database was ingested into Azure Data Lake Gen 2 using Azure Data Factory (ADF).
2. **Data Processing**: The ingested data underwent transformation through Databricks, ensuring it was formatted and optimized for analysis.
3. **Data Analysis and Reporting**: The transformed data was loaded into a cloud database created within Azure Synapse Analytics. This database was then connected to Power BI for the creation of insightful visualizations and reports.
