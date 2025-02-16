This is my first project after my Masters graduation using Azure Data Factory (ADF), where I integrated Git with ADF Studio to enable version control for my data workflows. The project demonstrates how to create, manage, and automate data pipelines in Azure.

Project Overview
In this project, I built an end-to-end data pipeline to move and transform data between various sources and destinations. The key focus was on implementing Git integration, automating data flows, and ensuring data accuracy with orchestration features in ADF.

Technologies Used
Azure Data Factory (ADF): For creating data pipelines and orchestrating workflows.
GitHub/Azure DevOps: Integrated with ADF Studio to manage version control and deployment.
Azure Blob Storage: [Add this if you used it as a data source or destination.]
Azure Synapse Analytics: [Mention if you used Synapse for analytics or data warehousing.]
Databricks: [If you used Databricks for transformations.]
Key Features
End-to-End Data Pipeline: Automates data ingestion, transformation, and loading (ETL process).
Git Integration: Allows version control for ADF pipelines and enables easier collaboration and deployment.
Data Transformation: Simple transformations applied to raw data before pushing to the destination.
Error Handling: Implemented error logging and notification for failed pipeline runs.
Project Architecture
Below is a simplified view of the project’s architecture:

Source: [Mention the data source, e.g., Azure Blob Storage, REST API, SQL Database, etc.]
Data Flow: Data is extracted, transformed (if applicable), and loaded into the destination.
Destination: [Mention your data destination, e.g., Azure Data Lake, Synapse Analytics, etc.]
Orchestration: The entire pipeline is triggered using scheduled or manual runs.
Setup Instructions
To run the project, follow these steps:

Clone this repository:
git clone https://github.com/your-repo/Azure-Data-Factory-Own-Project.git
Import the cloned repository into Azure Data Factory Studio.
Set up your data connections (e.g., linked services for Azure Blob, Synapse, etc.).
Deploy and trigger the pipelines as needed.

Learning Outcomes
Learned how to build pipelines and transform data using Azure Data Factory.
Successfully integrated Git with ADF Studio for version control.
Automated the end-to-end data movement process.
Future Improvements
Parameterization: Adding parameters for dynamic pipelines and reusability.
CI/CD: Implementing Continuous Integration/Continuous Deployment for the pipelines.
Enhanced Monitoring: Adding advanced monitoring and alerting mechanisms for better error handling.
Conclusion
This project was a hands-on experience with Azure Data Factory and helped in understanding the fundamentals of cloud-based data orchestration and automation.
