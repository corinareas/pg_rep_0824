# Overview
This project includes a set of SQL scripts and database objects related to surveys and responses. The following components are included:

* Tables for surveys, questions, users, and responses.
* A view to display survey details and calculated scores.
* Stored procedures for calculating survey scores.

Prerequisites
* PostgreSQL version 13 or later.
* A PostgreSQL client (e.g., pgAdmin, psql).

Setup Instructions
1. Create Tables: Execute the  SQL scripts to create the necessary tables in your PostgreSQL database.
2. Insert Sample Data: To populate the tables with sample data, execute the SQL scripts for insert.
3. Create Stored Procedure: Run the query to  create the stored procedure for calculating survey scores.
4. Create the View: Run the query to Create the view to display survey details and calculated scores.

Testing and Validation
* Verify that the tables are created correctly and contain sample data.
* Test the CalculateSurveyScore procedure to ensure it returns the correct scores.
* Check the view SurveyResponseDetails for an accurate display of survey details and scores.

Troubleshooting
* Error: Table does not exist: Ensure all tables are created before running the scripts.
* Error: View or function already exists: Use CREATE OR REPLACE to update existing objects.

Contact
* For questions or issues, please contact corinareas@gmail.com.
