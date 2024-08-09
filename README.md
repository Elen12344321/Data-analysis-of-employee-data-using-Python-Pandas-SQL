**Project Overview**

This project involves analyzing employee data from the Employees database using SQL and Python with Pandas. The analysis includes retrieving, processing, and visualizing data to gain insights into employee hiring trends, salary information, and job positions.

**Repository Contents**

1. Data Analysis Using SQL in Python
   - Database: Employees database.
   - Repository with Database Dumps: test_db on GitHub
   - Database Structure: Sakila Database Structure
   - Tasks:
     1. Installation: Installed the mysql-connector-python library.
     2. Database Connection: Established a connection to the Employees database using con.
     3. Hire Dates Analysis: Retrieved maximum and minimum hire dates of employees.
     4. Last Salary Information: Extracted the most recent salary information for each employee.
     5. To_date Analysis: Determined how many to_date values are equal to 9999-01-01.
     6. Salary Distribution: Visualized the distribution of salaries for employees still working at the company.

2. Data Analysis Using Pandas + SQL
   - Tasks:
     1. Hiring Trends: Extracted the number of employees by hire year using pandas.read_sql.
     2. Line Graph: Created a line graph showing the number of hired employees by year of hire.
     3. Position Analysis: Analyzed the number of full years employees with the position title Engineer spent in the role.
     4. Histogram: Created a histogram showing the number of years employees with the position title Engineer spent in the role.

**Installation**

 1. Clone the repository:
```
git clone https://github.com/yourusername/repository.git
```
 2. Install the required libraries:
```
pip install mysql-connector-python pandas matplotlib
```

**Usage**

 1. Connect to the Database: Use the mysql-connector-python library to connect to the Employees database.
 2. Run SQL Queries: Execute SQL queries to retrieve data as specified in the tasks.
 3. Analyze Data: Use Pandas to process and analyze the retrieved data.
 4. Visualize Results: Create visualizations using Matplotlib or similar libraries.

**Contributing**

Feel free to submit issues or pull requests if you have suggestions for improvements.
