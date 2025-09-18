**Medium | SQL | Advanced Select**

Generate the following two result sets:

Query an alphabetically ordered list of all names in OCCUPATIONS, immediately followed by the first letter of each profession as a parenthetical (i.e.: enclosed in parentheses). For example: AnActorName(A), ADoctorName(D), AProfessorName(P), and ASingerName(S).
Query the number of ocurrences of each occupation in OCCUPATIONS. Sort the occurrences in ascending order, and output them in the following format:

There are a total of [occupation_count] [occupation]s. <br/>
where [occupation_count] is the number of occurrences of an occupation in OCCUPATIONS and [occupation] is the lowercase occupation name. If more than one Occupation has the same [occupation_count], they should be ordered alphabetically.

Note: There will be at least two entries in the table for each type of occupation.

Input Format

The OCCUPATIONS table is described as follows: 

<img width="313" height="139" alt="image" src="https://github.com/user-attachments/assets/cee6e769-34d9-4cbc-b9e1-155e02cfb3d6" />

Occupation will only contain one of the following values: Doctor, Professor, Singer or Actor.

Sample Input

An OCCUPATIONS table that contains the following records:

<img width="317" height="469" alt="image" src="https://github.com/user-attachments/assets/68c7dd8c-963c-4fbc-bcba-9a3d2820426b" />


Sample Output

Ashely(P) <br/>
Christeen(P) <br/>
Jane(A) <br/>
Jenny(D) <br/>
Julia(A) <br/>
Ketty(P) <br/>
Maria(A) <br/>
Meera(S) <br/>
Priya(S) <br/>
Samantha(D)<br/>

There are a total of 2 doctors.<br/>
There are a total of 2 singers.<br/>
There are a total of 3 actors.<br/>
There are a total of 3 professors.<br/>

Explanation

The results of the first query are formatted to the problem description's specifications.
The results of the second query are ascendingly ordered first by number of names corresponding to each profession (2<=2<=3<=3), and then alphabetically by profession (doctor<=singer, and actor<=professor ).
