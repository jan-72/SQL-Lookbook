**Medium | SQL | Advanced Join**

You are given three tables: Students, Friends and Packages. Students contains two columns: ID and Name. Friends contains two columns: ID and Friend_ID (ID of the ONLY best friend). Packages contains two columns: ID and Salary (offered salary in $ thousands per month).

<img width="318" height="499" alt="image" src="https://github.com/user-attachments/assets/f8765bfe-53aa-4242-9a6c-2a4088ef1398" />


Write a query to output the names of those students whose best friends got offered a higher salary than them. Names must be ordered by the salary amount offered to the best friends. It is guaranteed that no two students got same salary offer.

Sample Input
<img width="268" height="240" alt="image" src="https://github.com/user-attachments/assets/c39b9173-2ba9-4b79-9f6c-37bd608df016" />

<img width="268" height="492" alt="image" src="https://github.com/user-attachments/assets/20117c40-a7a9-4dab-be5c-c7fe7d5481c7" />

 

Sample Output

Samantha
Julia
Scarlet

Explanation

See the following table:
<img width="514" height="220" alt="image" src="https://github.com/user-attachments/assets/9cfa8446-43a9-49ee-8c5c-da8d0a992b1a" />

Now,

Samantha's best friend got offered a higher salary than her at 11.55
Julia's best friend got offered a higher salary than her at 12.12
Scarlet's best friend got offered a higher salary than her at 15.2
Ashley's best friend did NOT get offered a higher salary than her
The name output, when ordered by the salary offered to their friends, will be:

Samantha
Julia
Scarlet
