# SQLcybersecurityPractice
SQL first project getting familiar with SQL queries that are useful for a cybersecurity analyst.
 
Task 1. Retrieve employee device data
![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/4bff19e1-152e-46f9-b013-9b9dcb24ecb8)

The output returns all the contents of the machines table:
 
2. Run the following query to select only the device_id and email_client columns from the machines table. Replace X with device_id and Y with email_client:
![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/5559d970-cdbc-4c62-afca-898fd5b1a968)

3.	Complete the query to return only the device_id, operating_system, and OS_patch_date columns from the machines table. Replace X, Y, and Z with the columns that you need to return:
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/b3973336-4054-48ab-af4c-dfba51fb955e)

Task 2. Investigate login activity
1.	Write a SQL query to select the event_id and country columns from the log_in_attempts table.
![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/78e20ee0-88d8-41a1-8ee9-2e3bb75b13d7)

2.	Write a SQL query that selects the username, login_date, and login_time columns from the log_in_attempts table.
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/0c588d76-f9f6-4b8a-ab6a-09c2b093da6e)

3.	Write a SQL query that selects all columns from the log_in_attempts table, using a single symbol after the SELECT keyword.
![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/8898a449-32cf-47d7-ae0a-c1a1094392b2)
 
Task 3. Order login attempts data
1.	Run the following query, which orders log_in_attempts data by login_date:
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/a984afa4-2397-4514-9c1e-d25fe7de6b93)

2.	Modify the query from the previous step by adding the login time to the ORDER BY clause. You must replace X with the appropriate column name:
SELECT *
FROM log_in_attempts
ORDER BY login_date, login_time;
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/bebab5d8-9ae2-4a3a-88cf-c4976f5b34ff)

This is my introductory lab practice to SQL

