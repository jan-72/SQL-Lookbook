**Medium | SQL | Basic Join**

Julia asked her students to create some coding challenges. Write a query to print the hacker_id, name, and the total number of challenges created by each student. Sort your results by the total number of challenges in descending order. If more than one student created the same number of challenges, then sort the result by hacker_id. If more than one student created the same number of challenges and the count is less than the maximum number of challenges created, then exclude those students from the result.

Input Format

The following tables contain challenge data:<img width="169" height="115" alt="image" src="https://github.com/user-attachments/assets/07a2c1c8-0e7d-4d55-864a-d7687be3614b" />


Hackers: The hacker_id is the id of the hacker, and name is the name of the hacker. 

Challenges: The challenge_id is the id of the challenge, and hacker_id is the id of the student who created the challenge. 
<img width="186" height="117" alt="image" src="https://github.com/user-attachments/assets/86257fe2-169f-4046-a315-0ede9bc4d3a2" />


Sample Input 0

Hackers Table:  
<img width="174" height="221" alt="image" src="https://github.com/user-attachments/assets/bc4cbb07-101b-4eae-810b-e0cf3995e24a" />

Challenges Table: 
<img width="215" height="747" alt="image" src="https://github.com/user-attachments/assets/53d35b03-64ae-4a9e-bcba-cdd0f45084f6" />



Sample Output 0

21283 Angela 6
88255 Patrick 5
96196 Lisa 1
Sample Input 1

Hackers Table:  
<img width="174" height="222" alt="image" src="https://github.com/user-attachments/assets/fd01f554-affa-4602-bb84-98e0ca7231fd" />

Challenges Table: 
<img width="214" height="747" alt="image" src="https://github.com/user-attachments/assets/55656dfd-1ce7-4a68-aa50-7e1916026efb" />

Sample Output 1

12299 Rose 6
34856 Angela 6
79345 Frank 4
80491 Patrick 3
81041 Lisa 1
Explanation

For Sample Case 0, we can get the following details:
<img width="331" height="225" alt="image" src="https://github.com/user-attachments/assets/5e589a7e-735a-484a-af25-f3e568a4992c" />


Students  and  both created  challenges, but the maximum number of challenges created is  so these students are excluded from the result.

For Sample Case 1, we can get the following details:
<img width="331" height="222" alt="image" src="https://github.com/user-attachments/assets/2d5753fe-554e-419d-ac60-227209a0221b" />


Students  and  both created  challenges. Because  is the maximum number of challenges created, these students are included in the result.
