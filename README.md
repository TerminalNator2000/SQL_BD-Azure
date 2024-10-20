# SQL_BD-Azure
Explanation
SQL Connection and Data Extraction:

The script connects to the SQL database using pyodbc.
It reads data using a SQL query and saves the result as a CSV file locally.
Azure Data Lake Upload:

The script connects to Azure Blob Storage using BlobServiceClient.
It uploads the local CSV file to the specified Azure container.
Notes:
Replace placeholders like your_sql_server, your_sql_database, and your_storage_account_name with your actual details.
Ensure you have access permissions set correctly in Azure Data Lake for the storage account and container.
This script should provide a good starting point for migrating data. Let me know if you need any adjustments or further details!
