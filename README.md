# 04b-Pair-DatabaseGranularAccess
# Database Access using SQL Server Authentication

This guide provides instructions on how to access a SQL Server database using SQL Server Authentication. SQL Server Authentication requires a username and password for authentication.

## Prerequisites

- **SQL Server Management Studio:**  
- **Database Credentials:** Username: Charlie Password: Password123

## Connecting to the Database

1. **Install SQL Server Management Studio (SSMS):**
   If you don't have SSMS installed, download and install it from the official [SQL Server Management Studio download page](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms).

2. **Open SQL Server Management Studio:**
   - Launch SQL Server Management Studio.

3. **Connect to the Database:**
   - In the "Connect to Server" window, provide the following information:
     - **Server Type:** Select "Database Engine."
     - **Server Name:** granulardatademo.database.windows.net
     - **Authentication:** Choose "SQL Server Authentication."
     - **Login:** Charlie
     - **Password:** Password123
     - **Options** Click the Options button to expand Options
     - **Additional Connection Parameters** Click on the Additional Connection Parameters Tab
     - **Update Connection String** enter the following (without quaotation marks) in the provided text window "Initial Catalog=granulardata-demo;"

4. **Connect:**
   - Click the "Connect" button to establish a connection to the SQL Server instance.

## Database Operations

Once connected, you can perform various database operations using SQL Server Management Studio, SQL scripts, or your preferred database management tool.

### Running Queries:

1. Open a new query window.
2. Write your SQL query.
3. Execute the query to interact with the database.

### Managing Tables, Views, and Stored Procedures:

1. Navigate to the "Object Explorer" window.
2. Expand the database node to view tables, views, and stored procedures.
3. Right-click on objects to perform management tasks.


## Troubleshooting

- If you encounter connection issues, verify the correctness of the server name, credentials, and network configuration.

## Resources

- [SQL Server Management Studio Documentation](https://docs.microsoft.com/en-us/sql/ssms/sql-server-management-studio-ssms)

Feel free to reach out for any assistance or clarification.

