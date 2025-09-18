**Easy | SQL (Basics)**

Query the Name of any student in STUDENTS who scored higher than 75 Marks. Order your output by the last three characters of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.

Input Format
<img width="321" height="191" alt="image" src="https://github.com/user-attachments/assets/1e7267de-8815-458c-82cf-af0428068d4c" />

The STUDENTS table is described as follows:  The Name column only contains uppercase (A-Z) and lowercase (a-z) letters.

Sample Input
<img width="318" height="223" alt="image" src="https://github.com/user-attachments/assets/6cd16bdf-baad-4227-b935-21d3abbcb0c2" />

Sample Output

Ashley
Julia
Belvet
Explanation

Only Ashley, Julia, and Belvet have Marks > 75. If you look at the last three characters of each of their names, there are no duplicates and 'ley' < 'lia' < 'vet'.
