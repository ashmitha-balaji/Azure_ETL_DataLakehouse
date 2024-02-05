**Azure_Data_Lakehouse_ETL_Pipeline-Project
**

Project Showcase: Demonstrates the end-to-end migration of data from On-Premise to the cloud.


Tools Used: Azure Data Factory,
            Databricks,
            Synapse Analytics,
            Data Lake Storage Gen2,
            Power BI,
            Azure Key Vault,
            Azure Active Directory.



Architecture: Adopts a Lakehouse architecture with bronze, silver, and gold data layers for various stages of transformation and storage.


Steps:

Environment Setup: Creates a resource group with Azure services.

Data Ingestion: Transfers on-prem SQL data to Azure Data Lake Storage Gen2 using Azure Data Factory.

Data Transformation: Utilizes Azure Databricks for curated data transformation with bronze, silver, and gold layers.

Data Loading: Moves processed data from Azure Data Lake Storage Gen2 Gold layer to Azure Synapse Analytics.

Data Reporting: Develops Power BI dashboards for interactive analysis.

Security and Governance: Implements Azure Active Directory and Azure Key Vault for security.

End-to-End Pipeline Testing: Ensures seamless data flow through comprehensive testing.

Overall: A comprehensive Azure-based ETL pipeline project emphasizing elegance and efficiency in data management and analytics.



