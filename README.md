# Pewlett-Hackard-Analysis

## Overview of the analysis

Our analysis consists of determining, from the data provided by Pewlett Hackard, which employee will retire in the next few years and how many positions the company will need to fill. We determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. This analysis will prepare Pewlett Hackard for the future by generating a list of all employees eligible for the retirement plan. We build an employee database with SQL by applying data modelling, engineering and analysis skills. 


## Results

- The Retirement Titles table shows each employee who is the appropriate age to retire and the various titles they have had with the company since their first day. 

   <img width="1440" alt="retirement_titles" src="https://user-images.githubusercontent.com/77806210/175451436-c1be632d-87c1-48cd-a815-b48abe4fec37.png">

- The Unique Titles table is a clearer version of the retirement titles. In this chart, each employee's name is listed along with the most recent title they have held.

    <img width="1440" alt="Unique_titles" src="https://user-images.githubusercontent.com/77806210/175451499-395fed3d-b0ca-4003-b812-79a3b545588e.png">
    
- The Retiring Titles table tells us the total number of retirement titles. 

   <img width="1440" alt="retiring_titles" src="https://user-images.githubusercontent.com/77806210/175451540-1524eddf-dbad-4b2d-8ba2-98c4ba3e0be8.png">
 
- The Mentoring Eligibility table tells us the employee number, first and last name, date of birth, title, and length of employment of employees who are eligible to participate in a mentoring program.

   <img width="1440" alt="Mentorship_eligibility" src="https://user-images.githubusercontent.com/77806210/175451592-7d430008-266d-4903-a0c9-989e70909b9f.png">
 
 ## Summary
 
 - How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  The retiring titles table shows us the total number of retirement per titles. If we add all those numbers, we have a total of 259,184,108 roles that      will need to be filled. 
 - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
 Based on the mentoring eligibility table, there are a total of 1548 retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. Therefore, there are not enough qualified employee to mentor the next generation.
 - To have more insight into the upcoming "silver tsunami.", it will be useful to have a query/table that shows us the total retirement-ready employees in the departments to mentor the next generation per title.
 - It also be useful to use to have the total retirement-ready employees in the departments to mentor the next generation per title and per department. 
 
   
  
 
