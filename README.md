# Pewlett-Hackard-Analysis

![git-hub](https://github.com/MonaElahi/Pewlett-Hackard-Analysis/blob/721dd5368843482fbc03358d2c10e2ac006327e5/Office.jpg)

# Overview 
Pewlett Hackard has a large number of employees who have been hired for 
decades and most of them are in retiring age parameter.  
In this project it is required to determine the number of retiring 
employees and identify the number of employees who are eligible to qualify 
in a mentorship program. There are six CSV's given and PostreSQL will be used to creat Pewlett Hackard's employment 
database and PGAdmin to access data and create tailored lists to extract desired results.

# Resources
- Data Source: department.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv.
- Software: PostgreSQL 11, VS Code 

# Results

There are two new CSV's have been created in order to count retiring employees by titles
and employees who are eligible to participate in mentorship program.  

* retiring_titles.csv 
* mentorship_eligibility.csv 

## Findings

- There were 90,398 number of employees in Pewlett Hackard who meet retirement criteria.
- The breakdown of retiring employees is as follows 


![git-hub](https://github.com/MonaElahi/Pewlett-Hackard-Analysis/blob/3f7fc9b65974fa55cfbe3363d3d846c2a6f9d903/Retiring%20Titles%20and%20Number.PNG)


As shows in the table above, Senior Engineer and Staff had the highest number among
total retiring number. Then comes Engineer and staff, which is approx. half of the number 
of senior titles. Further reduction had been observed in Technical Leader and Assistant
Engineer titles and lowest number is in Manager title. 
- There would be thousands of jobs openings in senior titles and Technical Leader position.
- The employees who were retiring also eligible for Mentorship Program are 1,549.
- There are only 2 managers in retirement age group.

# Summary 

According to this analysis, there are 90,398 number for position which are supposed to be filled
as "Silver Tsunami" begins. 

## Number of roles to be filled as "Silver Tsunami" begins:

There are 7 different roles which needs to be filled when positions are vacant after the retirement.

 * Senior Engineer
 * Senior Staff
 * Engineer
 * Staff
 * Technique Leader
 * Assistant Engineer
 * Manager

##  Are there enough qualified, retirement-ready employees in the departments to mentor the next generation PH

There are 1,549 employees who are eligible to particiapte in Mentorship program. 
Yes! The number of retirement ready employees are in excess to mentor
the next generation of Pewlett Hackard.

![git-hub](https://github.com/MonaElahi/Pewlett-Hackard-Analysis/blob/a17267c6b7d0c0dc8b659447e8925986859d5540/Queries/Mentorship%20code.PNG)
![git-hub](https://github.com/MonaElahi/Pewlett-Hackard-Analysis/blob/06c995a5fcb663bd8c72150416efb0229aa91e73/Mentorship%20Stats.PNG)

