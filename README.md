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
2. open the terminal and Change the directory to the downloaded repository in your terminal
3. Log in to MySQL using the command:  mysql -u username -p it will ask for the password, enter your password, and proceed to login.
4. use the following command after logging into mysql on terminal to create dummy data. 
    
    USE your_database_name;
    
    source script.sql;

## setup apache superset
1. Install Docker Desktop: https://docs.docker.com/desktop/install/windows-install/
2. clone repository: git clone https://github.com/apache/superset.git
3. Run following commands one by one:
   	git checkout 3.0.0
	set TAG=3.0.0
   	docker compose -f docker-compose-non-dev.yml pull
	docker compose -f docker-compose-non-dev.yml up



## TODO: pointed noted for superset:

1: Admin-user permission-based view.

2: super admin to have all permissions by default 
	https://superset.apache.org/docs/security/

3: Can we change the icon?
	https://stackoverflow.com/questions/56540328/how-can-i-change-the-favicon-on-my-superset-application

4: google sign-in
	https://stackoverflow.com/questions/66778866/how-to-use-google-login-with-apache-superset

5: can we show the DB structure on its (side)

6: safety and security notes for no data leak.
	https://superset.apache.org/docs/security/

side tasks:
1: report: group by manager
2: report: group by new join (3m /6m/9m/1y/ 3y/5y)
3: report: group by department. (HR/IT/DEV/QA/Admin)
4: filter/group/category based on salary.
