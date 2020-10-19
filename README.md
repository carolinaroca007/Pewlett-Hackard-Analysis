# Pewlett-Hackard-Analysis

## Overview

Pewlett-Hackard has a number of employees approaching retirement and management has tasked the Human Resource Analyst, Bobby, and I with determining who are the employees that will be eligible for retirement packages, and how many positions the company will need to fill as a result of the retirements. The purpose of this analysis is to provide Pewlett-Hackard's management team with the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program, a new concept the HR department is entertaining as a means to train the next generation of employees. 

## Results

* 90,398 employees are eligible for retirement
* 29,414 Senior Engineers are eligible for retirement, the highest count from the titles in the retirement list
* 1,549 employees are eligible to participate in the mentorship program
* The 2 retirement eligible managers are not eligible to participate in the mentorship program according to the conditions given

## Summary

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?

90,398 employees are eligible for retirement; 29,414 Senior Engineers, 28,255 Senior Staff, 14,222 Engineers, 12,242 Staff, 4,502 Technique leaders, 1,761 Assistant Engineers, and 2 Managers. You can also use the department table, inner join with the dept_emp table on dept_no primary key, and also join unique_titles table on emp_no primary key, and use the COUNT and GROUPBY agreggate functions to determine number of retirement eligible employees by department name.

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are not enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. There are a total of 90,398 employees eligible for retirement while there are only 1,549 employees eligible to participate in the mentorship program. 