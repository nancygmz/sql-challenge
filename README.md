# SQL-Challenge
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.
For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data.

## Reviewing & Organizing the Data
In reviewing the CVS files provided, I've put together an Entity Relationship Diagram to illustrate the different files and to assist with my queries. 

![ERD image](https://github.com)


## Data Analysis
After tables were created and CSV files imported into Postgres SQL, I was able to run queries to meet the following requests: 

 List the employee number, last name, first name, sex, and salary of each employee.

 List the first name, last name, and hire date for the employees who were hired in 1986.

 List the manager of each department along with their department number, department name, employee number, last name, and first name.

 List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

 List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

 List each employee in the Sales department, including their employee number, last name, and first name.

 List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
