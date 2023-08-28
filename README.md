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

Server version: 10.3.39-MariaDB-0+deb10u1 Debian 10

SECOND EXERCISE
Task 1. List all organization machines
•	Run a SQL query to retrieve only the device_id and operating_system columns from the machines table.
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/6968bbbd-5c9a-4400-a794-94559f49f83e)

Task 2. Retrieve a list of the machines with OS 2
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/f10083c8-a250-4093-a043-c971c3b8096a)


Task 3. List employees in specific departments
1.	Filter the rows returned from department column in the employees table to include only employees from the 'Finance' department. Replace X with the appropriate column name and Y with the appropriate value to complete the filter:
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/9c72e534-630a-4015-b3f2-0649c903af7c)

2.	Modify the previous query so that it returns employees who are in the 'Sales' department.
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/5f74217e-5f8a-4c3c-b15a-3d463e653748)

Task 4. Identify employee machines
A machine in 'South-109' has an issue. I need to determine which employee uses that computer so I can send them an alert.
1.	Write a query to identify which employee uses the office in 'South-109'. (The data must be returned from the office column in the employees table.)
![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/2514f09e-19f8-4059-9904-1c0f9825bde6)
 

Next, my team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, 'South-109').
2.	Modify the query you used in the previous step so that it returns information on all the employees in the 'South' building. Use the LIKE operator with % in this query.
 ![image](https://github.com/kalejcamto/SQLcybersecurityPractice/assets/101201140/dc79e621-d0f2-44d4-9a35-d8c05b12b938)

•	This has been practical experience applying the WHERE clause to filter what a SQL query returns and
•	use the LIKE operator to filter for patterns.

