# Pewlett-Hackard-Analysis

1.	Overview of the analysis: 

Pewlett Hackard has fallen a bit behind in the database department, we will help them to add their data into a database and do some analysis based on the management requirement. We created tables based on the entity relationship diagram (ERD), and successfully imported the data to each table. We will need to dive into the data and perform queries to learn when employees were hired as well as their age and to search for those who are retiring and when they are retiring. We also need to break down some large list into smaller pieces. We need to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. 

2.	Results: 

After looking deep into the analysis, we found out that a lot of employees are retired based on the age and the date they got hired.

•	We retrieve the employees who were born between 1952 and 1955. Then, order by the employee number. 

![image](https://user-images.githubusercontent.com/49285767/198912034-42dfd860-1b97-4071-b4da-9ed26e1d8758.png)

•	We then counted the number of employees based on the title:

![image](https://user-images.githubusercontent.com/49285767/198912536-ad59d7a8-4090-4266-b27a-02b88a2a04be.png)

•	We then counted the number of employees based on the title:

![image](https://user-images.githubusercontent.com/49285767/198911882-a5a3f622-48e8-480a-9db2-6a12217e60e9.png)

•	Finally, we have created a new table which has the list of all current employees. This table lists all the employees whose birth dates are between January 1, 1965 and December 31, 1965.

![image](https://user-images.githubusercontent.com/49285767/198913374-73129623-8545-4315-9a86-929a2220f634.png)

3.	Summary: 

o	How many roles will need to be filled as the "silver tsunami" begins to make an impact?

   • Based on the calculated retirement employees, we see that 72458 people are on the list to get retired out of 499996 total employees in the tables created. so the manger needs to fill out 72458 new roles.
   
o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

    we calculated the total employees to see if there is enough qualified retirement employees in departments to mentor the next generation of Pewlett Hackard employees
    
![image](https://user-images.githubusercontent.com/49285767/198915072-4544c61f-787e-4e03-bc09-e919b98396f6.png)

Based on the calculation above, we conclude that although there are a lot of employees getting retired, but there is still enought qualified retirement employees in departments to mentor the next generation of Pewlett Hackard employees. 

    




