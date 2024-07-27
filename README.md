# Apply Filters to SQL Queries

## Objective
Investigate security issues to help keep the organization system secure. Ensuring the system is safe, investigate all potential security issues, and update employee computers as needed. Utilize SQL filters to perform security-related tasks.

## Steps
### After Hours Failed Login Attempts
A security incident occurred after business hours; identify all failed login attempts that occurred after 18:00.

Ref 1 : SQL Query demonstates how to filter for failed login attempts that occurred after business hours and the output. This query filters for failed login attempts that occured after 18:00.
![image](https://github.com/user-attachments/assets/f5fa37b7-8b0d-42e0-bd27-4113133bd548)
*Ref 1: SQL Query*

First select all data form the log_in_attempts table. Use WHERE clause with an AND operator to filter the results to output only failed login attempts that occured after 18:00. login_time > '18:00' filters for the login attempts after 18:00. success = 0 filters for the failed login attempts.
### Login Attempts on Specific Dates
![image](https://github.com/user-attachments/assets/b39f66e3-ed64-407a-930b-c30f8bf5a1c4)
### Login Attempts Outside of Mexico
![image](https://github.com/user-attachments/assets/90d9c039-ed3c-49f2-90bd-2a581e1d353e)
### Retrieve Employees in Marketing
![image](https://github.com/user-attachments/assets/4fe40760-8e30-406c-b24f-b98436d7bab3)
### Employees in Finance or Sales
![image](https://github.com/user-attachments/assets/32a1da39-2db7-4869-9ac5-2806017719a2)
### All Employees not in IT
![image](https://github.com/user-attachments/assets/bb2f35b7-6992-4f98-9950-1cddcf787afe)

## Summary
Security analysts can use SQL queries to query databases and find data to support security-related decisions. Queries used may include:<br>
-Query a database<br>
-Apply filters to SQL queries<br>
-Join tables<br>
-Perform calculations<br>
