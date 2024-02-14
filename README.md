# sql-challenge

For this challenge, I am tasked with a research project about the people whom Pewlett Hackard (a fictional company) employed during the 1980s and 1990s. 

All that was left from the employee database from this period are 6 CSV files. These are saved in a folder named <EmployeeSQL>.

The task is divided into data modelling, engineering, and analysis. 

I wrote a python code to convert the date type for 'birth_date' and 'hire_date' in <employees.csv> to the date type recognized by SQL (YYYY-MM-DD). The new csv file is saved as <employees_new.csv> back in the original folder. The code is saved as <convert_date.ipynb>. 

I developed an Entity Relationship Diagram (ERD) with the help of QuickDBD (https://www.quickdatabasediagrams.com/). This image is saved as <ERD.png>. The code for this is saved as <table_schemata.sql> with all the required conditions, definitations, and references. 

The CSVs are imported in the sequence that the tables are created - titles, departments, employees, salaries, dept_emp and dept_manager. 

Data Analysis is performed (8 queries). They are saved in <queries.sql> with simple description of the requirements prior to each query. 


