# Pewlett-Hackard-Analysis

# Overview
Pewlett_Hackard believes there is a "Silver Tsnuami" about to hit its workforce. The purpose of this analysis is to determine the number of retiring employees per title,and identify employees who are eligible to participate in a mentorship program

## RESULTS
First is to filter the data on the birth_date column to retrieve the employees who were born between 1952 and 1955. This is the retirement_titles table. 
Since there are duplicate entries for some employees because they have switched titles over the years, I built another table to remove these duplicates.
This is the unique_titles table. Then create another table from the unique_titles table to retrieve the number of employees by their most recent job title
who are about to retire. This is the retiring_titles table listed below. ![retiring_table](https://user-images.githubusercontent.com/86200136/129483638-99f6fb73-b099-475a-8ed9-5bacb1e5e81e.png)

My next objective was to create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965. 
This table that holds the employees who are eligible to participate in a mentorship program. This table holds 1,549 employees who are eligible to participate in the mentorship program.

Analysis of the queries performed:
-About 30 percent of total workforce is about to retire.
-Almost 20 percent of Senior Engineer and Staff are about to retire.
-Two of the 9 Department Managers are about to retire. 
-Only 1549 of employees eligible to participare in mentorship program. 


## SUMMARY
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are 90,398 employees eligible to retire. 
![sum_retire_emp](https://user-images.githubusercontent.com/86200136/129484743-0b69358a-8276-40bf-ba42-70b68d2bc579.png)

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
From the tables listed you can see that there is not enough employees to fill the roles of each department in the mentorship program.
RETIRING EMPLOYEES BY DEPT

![retiring_table](https://user-images.githubusercontent.com/86200136/129485058-6968ce4b-9d8f-45e2-bf8d-966665f54e4b.png)




MENTORSHIP ELIGIBLE EMPLOYEES BY DEPT

![mentor_elig_emp_dept](https://user-images.githubusercontent.com/86200136/129485045-308d1ecc-2c97-463b-a7cf-3fd71bac2542.png)



