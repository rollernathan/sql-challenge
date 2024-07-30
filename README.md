# Pewlett Hackard Employee Analysis
sql-challenge
Week 9 Challenge

## Entity Relationship Diagram
The first step to understand employment at Pewlett Hackard in the 1980s and 1990s is to look at the structure of the data received. We received data on employees, including ID number, first name, last name, sex, title, birth date, hire date, salary, and department in which each employee worked. If the employee was a manager of a department, that was also provided in the data. Each employee was the manager for at most one department and had at most one salary and title. However, employees may have been an employee at multiple departments. You can explore more in the Entity Relationship Diagram provided below.

![ERD](https://github.com/rollernathan/sql-challenge/blob/main/EmployeeSQL/Data_Modeling_ERD/employee_db_ERD.png)

## Employee Analysis
Data was provided on 300,024 employees across 9 departments. Of those 300,024 employees, 36,150 were hired in 1986. Of the 300,024 employees, 137,952 are in Sales and Development, including 52,245 in Sales and 85,707 in Development.

Across all employees, there are 1,638 unique last names. With one exception, each last name is shared by 145 to 226 employees. The last name Baba occurs the most and is shared by 226 employees. There is also a lone employee with the last name of Foolsday, a Technique Leader in the Development department.

### Department Managers
Twenty-four (24) of the employees are managers at the 9 departments as shown in the following table.

![department_managers]()

### Hercules, Hercules B
There are 20 employees named Hercules with a last name starting with B. Those employees are shown in the table below along with their sex.


![Hercules_B]()


