# Employee Database
This SQL script creates four tables (employees, departments, dept_emp, titles, and salaries) and inserts dummy data into them.

Here's a brief description of each table:

employees: This table stores information about employees, including their unique employee number (emp_no), birth date (birth_date), first name (first_name), last name (last_name), gender (gender), and hire date (hire_date). The emp_no column serves as the primary key, ensuring each employee record is uniquely identifiable.

departments: This table contains data about departments within the organization. It includes the department number (dept_no) and the department name (dept_name). The dept_no column is the primary key, and the dept_name column has a unique constraint to ensure each department name is unique.

dept_emp: This table establishes the relationship between employees and departments, indicating which employees are assigned to which departments during specific periods. It includes the employee number (emp_no), department number (dept_no), start date (from_date), and end date (to_date) of each assignment. The combination of emp_no and dept_no forms the primary key, allowing for multiple assignments for the same employee across different departments.

titles: This table stores employees' job titles and the corresponding periods during which they held those titles. It contains the employee number (emp_no), title (title), start date (from_date), and end date (to_date) for each title. The combination of emp_no, title, and from_date serves as the primary key, ensuring each title assignment is uniquely identified.

salaries: This table records employees' salary information over time. It includes the employee number (emp_no), salary amount (salary), start date (from_date), and end date (to_date) for each salary entry. The combination of emp_no and from_date forms the primary key, allowing for multiple salary entries for the same employee at different times.

The script inserts dummy data into these tables to simulate a small-scale employee database, including employees' personal details, department assignments, job titles, and salary information. Each table's structure and relationships between them facilitate the storage and retrieval of employee-related data for organizational management and analysis purposes.
