**Easy | SQL (Basics)**

Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater than $2000 per month who have been employees for less than 10 months. Sort your result by ascending employee_id.

Input Format

The Employee table containing employee data for a company is described as follows: <br/>
<img width="191" height="187" alt="image" src="https://github.com/user-attachments/assets/e8958f72-d478-47d8-8c40-41e1be8abab8" />

where employee_id is an employee's ID number, name is their name, months is the total number of months they've been working for the company, and salary is the their monthly salary.

Sample Input <br/>
<img width="348" height="398" alt="image" src="https://github.com/user-attachments/assets/f07cfec3-effb-44ee-9c84-a02ba918706b" />

Sample Output

Angela <br/>
Michael <br/>
Todd<br/>
Joe<br/>

Explanation

Angela has been an employee for  month and earns $3443 per month.

Michael has been an employee for  months and earns $2017 per month.

Todd has been an employee for  months and earns $3396 per month.

Joe has been an employee for  months and earns $3573 per month.

We order our output by ascending employee_id.
