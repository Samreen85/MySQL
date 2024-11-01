# Project Setup and MySQL Database Connection Guide
This guide provides step-by-step instructions for setting up and working with MySQL in MySQL Workbench, as well as instructions on how to connect and work with MySQL using VS Code. The folder also includes a Notes_MySQL Word document that contains additional details.

## Requirements
* MySQL Workbench
* MySQL Server
* VS Code
* VS Code MySQL Extension (recommended for easier MySQL integration)
## Getting Started with MySQL Workbench
1. Open MySQL Workbench: Launch MySQL Workbench after installation.
2. Create a New Connection:
* Go to the Database menu and select Connect to Database...
* Enter the hostname (localhost for local servers), port number (default is 3306), username, and password for the MySQL server.
* Click Test Connection to ensure the connection works.
3. Run SQL Queries:
Once connected, navigate to the SQL Editor tab.
Write your SQL queries and execute them using the Execute button (or press CTRL + Enter).
4. Explore Database Structure:
The Navigator panel on the left displays databases, tables, and other schema elements. Expand these to view table columns, indexes, and more.

Refer to Notes_MySQL for additional steps and troubleshooting tips.

## Connecting and Working with MySQL in VS Code
1. Install MySQL Extension:
* Open VS Code and go to the Extensions view (CTRL+SHIFT+X).
* Search for MySQL and install the recommended extension.
2. Create a New MySQL Connection:
* In the MySQL extension sidebar, click + New Connection.
* Enter the connection details (hostname, port, username, and password) to establish the connection.
3. Using Jupyter Notebooks in VS Code:
* Create or open a .ipynb file in VS Code.
* Install any necessary Python packages for MySQL if you plan to query the database directly from the notebook.
* Use SQL cells in the notebook to query your MySQL database, using %%sql if using SQL cells, or standard Python code with pymysql or mysql-connector-python libraries.

Refer to Notes_MySQL for specific code snippets and setup guidance.