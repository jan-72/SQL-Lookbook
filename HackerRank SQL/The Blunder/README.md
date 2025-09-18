**Easy | SQL | Aggregation**

Samantha was tasked with calculating the average monthly salaries for all employees in the EMPLOYEES table, but did not realize her keyboard's 0 key was broken until after completing the calculation. She wants your help finding the difference between her miscalculation (using salaries with any zeros removed), and the actual average salary.

Write a query calculating the amount of error (i.e.: (actual-miscalculated) average monthly salaries), and round it up to the next integer.

Input Format

The EMPLOYEES table is described as follows:

<img width="313" height="179" alt="image" src="https://github.com/user-attachments/assets/286eb69b-4b6d-447c-9b53-58309132a23a" />


Note: Salary is per month.

Constraints

1000 < Salary < 10^5

Sample Input

<img width="318" height="225" alt="image" src="https://github.com/user-attachments/assets/7b673e22-e636-485c-a8a6-3680a7336010" />

Sample Output

2061

Explanation

The table below shows the salaries without zeros as they were entered by Samantha:

<img width="316" height="224" alt="image" src="https://github.com/user-attachments/assets/84b344ff-f49e-46e0-9ceb-72b738fb697b" />

Samantha computes an average salary of 98.00. The actual average salary is 2159.00.

The resulting error between the two calculations is 2159.00 - 98.00 = 2061.00 . Since it is equal to the integer 2061 , it does not get rounded up.
