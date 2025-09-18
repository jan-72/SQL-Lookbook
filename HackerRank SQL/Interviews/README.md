**Hard | SQL | Advanced Join**

Samantha interviews many candidates from different colleges using coding challenges and contests. Write a query to print the contest_id, hacker_id, name, and the sums of total_submissions, total_accepted_submissions, total_views, and total_unique_views for each contest sorted by contest_id. Exclude the contest from the result if all four sums are 0.

Note: A specific contest can be used to screen candidates at more than one college, but each college only holds 1 screening contest.

Input Format

The following tables hold interview data:

Contests: The contest_id is the id of the contest, hacker_id is the id of the hacker who created the contest, and name is the name of the hacker. 
<img width="172" height="153" alt="image" src="https://github.com/user-attachments/assets/78405f0a-7adb-4104-9102-2ec67cc5a9c8" />

Colleges: The college_id is the id of the college, and contest_id is the id of the contest that Samantha used to screen the candidates. 
<img width="174" height="116" alt="image" src="https://github.com/user-attachments/assets/bcc93657-38c4-47e4-a548-5192b4d38d2e" />

Challenges: The challenge_id is the id of the challenge that belongs to one of the contests whose contest_id Samantha forgot, and college_id is the id of the college where the challenge was given to candidates. 
<img width="186" height="117" alt="image" src="https://github.com/user-attachments/assets/45b78407-4759-4af0-ab16-d4a8399ebdd2" />

View_Stats: The challenge_id is the id of the challenge, total_views is the number of times the challenge was viewed by candidates, and total_unique_views is the number of times the challenge was viewed by unique candidates. 
<img width="226" height="153" alt="image" src="https://github.com/user-attachments/assets/41199969-d3f6-4245-9be5-f6177ad9690f" />

Submission_Stats: The challenge_id is the id of the challenge, total_submissions is the number of submissions for the challenge, and total_accepted_submission is the number of submissions that achieved full scores. 
<img width="284" height="151" alt="image" src="https://github.com/user-attachments/assets/383c75e3-c527-4736-b522-23fc3dcfa07d" />

Sample Input

Contests Table:  
<img width="272" height="153" alt="image" src="https://github.com/user-attachments/assets/6d8e75ca-6d34-41d6-98ff-66c9df2e4b95" />

Colleges Table:  
<img width="205" height="152" alt="image" src="https://github.com/user-attachments/assets/15432674-f6f1-4bdf-9f4b-4a04331accab" />

Challenges Table:  
<img width="218" height="189" alt="image" src="https://github.com/user-attachments/assets/697883ce-4ed9-4b45-a6ad-60854ec35a07" />

View_Stats Table:  
<img width="383" height="328" alt="image" src="https://github.com/user-attachments/assets/d4fca371-9c5d-4775-94a8-6e5136fce647" />

Submission_Stats Table: 
<img width="489" height="329" alt="image" src="https://github.com/user-attachments/assets/cba2575f-ee2e-457d-8fa5-d120733e464e" />

Sample Output

66406 17973 Rose 111 39 156 56
66556 79153 Angela 0 0 11 10
94828 80275 Frank 150 38 41 15

Explanation

The contest 66406 is used in the college 11219. In this college 11219, challenges 18765 and 47127 are asked, so from the view and submission stats:

Sum of total submissions : 27 + 56 + 28 = 111

Sum of total accepted submissions  : 10 + 18 + 11 = 39

Sum of total views : 43 + 72 + 26 + 15 = 156

Sum of total unique views : 10 + 13 + 19 + 14 = 56

Similarly, we can find the sums for contests 66556 and 94828.
