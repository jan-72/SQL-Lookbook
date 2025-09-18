**Medium | SQL | Basic Join**

You are given two tables: Students and Grades. Students contains three columns ID, Name and Marks.

<img width="313" height="181" alt="image" src="https://github.com/user-attachments/assets/1aa68030-60cd-4934-ab7d-a42db52fcd78" />

Grades contains the following data:

<img width="317" height="470" alt="image" src="https://github.com/user-attachments/assets/b30a771d-b472-4a65-8079-c7cee03fd8e2" />

Ketty gives Eve a task to generate a report containing three columns: Name, Grade and Mark. Ketty doesn't want the NAMES of those students who received a grade lower than 8. The report must be in descending order by grade -- i.e. higher grades are entered first. If there is more than one student with the same grade (8-10) assigned to them, order those particular students by their name alphabetically. Finally, if the grade is lower than 8, use "NULL" as their name and list them by their grades in descending order. If there is more than one student with the same grade (1-7) assigned to them, order those particular students by their marks in ascending order.

Write a query to help Eve.

Sample Input

<img width="313" height="302" alt="image" src="https://github.com/user-attachments/assets/a7487ba0-f411-495c-8b4b-cc96d6543e4b" />


Sample Output

Maria 10 99 <br/>
Jane 9 81<br/>
Julia 9 88 <br/>
Scarlet 8 78<br/>
NULL 7 63<br/>
NULL 7 68<br/>

Note

Print "NULL"  as the name if the grade is less than 8.

Explanation

Consider the following table with the grades assigned to the students:

<img width="314" height="304" alt="image" src="https://github.com/user-attachments/assets/b8124c6c-e547-431c-ab4a-2b5b53b9f784" />

So, the following students got 8, 9 or 10 grades:

Maria (grade 10)<br/>
Jane (grade 9)<br/>
Julia (grade 9)<br/>
Scarlet (grade 8)
