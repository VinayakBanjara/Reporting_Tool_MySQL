# Reporting_Tool_MySQL
## Install MySQL Database:

step1: https://dev.mysql.com/downloads/installer/ download installer

step2: Install MySQL using MySQL installer by following the instructions

 

Note: You need a MySQL database server (5.0+) and run the commands below through a user that has the following privileges:

**SELECT, INSERT, UPDATE, DELETE,
CREATE, DROP, RELOAD, REFERENCES,
INDEX, ALTER, SHOW DATABASES,
CREATE TEMPORARY TABLES,
LOCK TABLES, EXECUTE, CREATE VIEW**

## Create dummy data for  :

1. Download the repository:  https://github.com/datacharmer/test_db
2. open terminal and Change directory to the downloaded repository in your terminal
3. Log in to MySQL using command:  mysql -u username -p it will ask for the password, enter your password and proceed for login.
4. use following command after login into mysql on terminal to create dummy data. 
    
    USE your_database_name;
    
    source script.sql;
