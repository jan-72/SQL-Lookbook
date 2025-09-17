**Medium | SQL | Basic Join**

You did such a great job helping Julia with her last coding contest challenge that she wants you to work on this one, too!

The total score of a hacker is the sum of their maximum scores for all of the challenges. Write a query to print the hacker_id, name, and total score of the hackers ordered by the descending score. If more than one hacker achieved the same total score, then sort the result by ascending hacker_id. Exclude all hackers with a total score of  from your result.

Input Format

The following tables contain contest data:

Hackers: The hacker_id is the id of the hacker, and name is the name of the hacker. 
<img width="170" height="117" alt="image" src="https://github.com/user-attachments/assets/6f2dd208-57e2-4163-a6d8-b003102d3bb6" />


Submissions: The submission_id is the id of the submission, hacker_id is the id of the hacker who made the submission, challenge_id is the id of the challenge for which the submission belongs to, and score is the score of the submission. 
<img width="197" height="188" alt="image" src="https://github.com/user-attachments/assets/7c1e6162-7ecc-406c-afbe-c028efcbe5c2" />

Sample Input

Hackers Table: 
<img width="187" height="399" alt="image" src="https://github.com/user-attachments/assets/08d93bbb-bbcc-46a7-bac3-d9ede72967f3" />

Submissions Table: 
<img width="407" height="785" alt="image" src="https://github.com/user-attachments/assets/201ca792-afcc-4d95-832d-90497288968b" />

Sample Output

4071 Rose 191
74842 Lisa 174
84072 Bonnie 100
4806 Angela 89
26071 Frank 85
80305 Kimberly 67
49438 Patrick 43
Explanation

Hacker 4071 submitted solutions for challenges 19797 and 49593, so the total score .

Hacker 74842 submitted solutions for challenges 19797 and 63132, so the total score 

Hacker 84072 submitted solutions for challenges 49593 and 63132, so the total score .

The total scores for hackers 4806, 26071, 80305, and 49438 can be similarly calculated.
