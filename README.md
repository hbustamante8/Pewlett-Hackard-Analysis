# Pewlett-Hackard-Analysis

## Overview of the analysis 

Pewlett Hackard is starting to think about which positions need to be filled in the future as well as putting together retirement packages for those who qualify. There will be a tremendous amount of job openings in the coming year or so and the company would like to prepare for the vacancies. The purpose of this project is to find out which employees will be retiring to plan for new staff and create a list for the  mentorship initiative. Using PostgreSQL and data engineering, findings are provided to Pewlett Hackard. This will aid in preparing for the "silver tsunami" as many current employees reach retirement age.

Below is an Entity relationship diagram to visualize the relationship between the different data sources to complete this analysis.

![image](https://user-images.githubusercontent.com/96553992/154599906-46856a35-c063-4d5f-b8b8-427c7a9b1d84.png)



## Results 

### Tables 

View of retirement titles table breakdown. Table shows the count of each position title that is going to retire in the near future.

![image](https://user-images.githubusercontent.com/96553992/154606662-bf4c340b-775c-429d-a05f-e1bfdbf64177.png)

View of first 20 rows of mentorship table that contains information about the employees eligible for the mentorship initiative. 

![image](https://user-images.githubusercontent.com/96553992/154718261-a3ae7052-0f11-4a65-852b-8671464b8964.png)

## Results of tables
* Senior roles account for 70.2 % (50,842 of 72,458) of staff that is going to retire.
* There are 72,458 employees that have birthdays between 01-01-1952 and 12-31-1955
* There are only 2 managers that will be expected to retire within the very near future
* There are 1549 employees that could be considered for the mentorship program Pewlett-Hackard is planning to launch.

## Summary

### Questions Answered

1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  * There will need to be 72,458 roles that will need to be filled in the next three years
2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  * The 1549 employees that are eligible to participate in the mentorship program. Assuming that not everyone would agree to be a part of the mentorship program, I do not think there are enough employees to properly mentor the next generation of employees at Pewlett Hackard.

### Further Observations


1) A new table created by a query highlights the mentorship program's senior staff and senior engineers would have the greatest number of mentors compared to the other titles. Assistant Engineer has the lowest number of individuals for the mentorship program in those roles.

The mentorship title count table is shown below.

![image](https://user-images.githubusercontent.com/96553992/154696503-009f2cba-9488-479e-84b1-264bdc05921c.png)

2) Another observation is made from another query that gives a table of employees retiring by their birth year. The numbers are similar for each year but are significantly lower for the employees born in 1952. The table is valuable because it reveals that similar number of employees will need to be hired after the current calendar year.

Below this table that resulted from the query.

![Screen Shot 2022-02-18 at 10 00 04 AM](https://user-images.githubusercontent.com/96553992/154707313-fb132c74-60f1-4d57-84bf-fec006b617d1.png)

