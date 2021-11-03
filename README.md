# Pewlett-Hackard-Analysis
## Overview
The purpose of this analysis was to find the  employees who may be eligible to retire soon at a large company called Pewlett-Hackard. This will help the company estimate the number of retirement packages they might have to offer, along with identifying which positions will need to be filled. Due to the company's size, a sudden surge in retiring employees could leave huge portions of their workforce vacant. Conducting this analysis now helps Pewlett-Hackard plan and protect themselves from sudden shocks to their business.

## Resources
To conduct the analysis, we were provided six CSV files containing all necessary information. 
The CSV files were reviewed to identify the primary keys, data types, and foreign keys. An entity relationship diagram was created to visualize the relationships between the files. From there, the files were imported into a PostgreSQL database, where we conducted our analysis. The analysis will be covered in more detail in section 2. Below is a copy of the ERD that was created.
![QuickDBD-export](https://user-images.githubusercontent.com/89148689/140103873-689720f8-fcd7-491e-82fa-db7ea7c6772c.png)

## Results
  * Based on the first analysis there are huge number of Retiring Employees by Title. The data retrieved from the first deliverable gives the Pewlett Hackard the number of roles that needs to be filled in each department.
  * This data helps Pewlett Hackard future-proof the company by plannign ahead and start with the recruting process before the employees retire or take voluntary retirement.
  * The Second analysis was to identify employees who are eligible to participate in a mentorship program based on the title and their experience, This data would give a better idea to plan on the mentoriship program when new employees are hired.
  * retirement_titles, unique_titles, retiring_titles, and mentorship_eligibilty table would provide all the information thats needed for the management to make a plan to future proof the company

## Summary

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Pewlett-Hackard will need to fill 90,398 positions over the course of the "Silver Tsunami".

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There are enough qualified, retirement-ready employees ready to mentor the next generation of Pewlett-Hackard employees. 98% of the employees retiring are senior or mid-level based on their titles. However, the pool of employees eligible for mentorship is far too small to fill all the positions that would be vacated.
