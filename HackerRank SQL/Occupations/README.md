**Medium | SQL | Advanced Select**

Pivot the Occupation column in OCCUPATIONS so that each Name is sorted alphabetically and displayed underneath its corresponding Occupation. The output should consist of four columns (Doctor, Professor, Singer, and Actor) in that specific order, with their respective names listed alphabetically under each column.

Note: Print NULL when there are no more names corresponding to an occupation.

Input Format

The OCCUPATIONS table is described as follows:

<img width="313" height="139" alt="image" src="https://github.com/user-attachments/assets/e3544a4b-f947-49d0-ad4f-d8b6467eaea7" />


Occupation will only contain one of the following values: Doctor, Professor, Singer or Actor.

Sample Input

<img width="314" height="468" alt="image" src="https://github.com/user-attachments/assets/7389f875-d1cd-4048-8528-6b82b9e4888c" />


Sample Output

Jenny    Ashley     Meera  Jane
Samantha Christeen  Priya  Julia
NULL     Ketty      NULL   Maria
Explanation

The first column is an alphabetically ordered list of Doctor names.
The second column is an alphabetically ordered list of Professor names.
The third column is an alphabetically ordered list of Singer names.
The fourth column is an alphabetically ordered list of Actor names.
The empty cell data for columns with less than the maximum number of names per occupation (in this case, the Professor and Actor columns) are filled with NULL values.
