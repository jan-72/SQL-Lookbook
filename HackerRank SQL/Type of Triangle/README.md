**Easy | SQL | Advanced Select**

Write a query identifying the type of each record in the TRIANGLES table using its three side lengths. Output one of the following statements for each record in the table:

Equilateral: It's a triangle with 3 sides of equal length.
Isosceles: It's a triangle with 2 sides of equal length.
Scalene: It's a triangle with 3 sides of differing lengths.
Not A Triangle: The given values of A, B, and C don't form a triangle.
Input Format

The TRIANGLES table is described as follows:

<img width="319" height="181" alt="image" src="https://github.com/user-attachments/assets/5cc74a72-0e6d-4bc4-b3fc-c585bc6b3225" />


Each row in the table denotes the lengths of each of a triangle's three sides.

Sample Input

<img width="313" height="219" alt="image" src="https://github.com/user-attachments/assets/30307511-fea8-4dd0-84ca-7d1a28875710" />

Sample Output

Isosceles <br/>
Equilateral <br/>
Scalene <br/>
Not A Triangle <br/>
Explanation <br/>

Values in the tuple (20,20,23) form an Isosceles triangle, because A = B . <br/>
Values in the tuple (20,20,20) form an Equilateral triangle, because A = B = C . <br/>
Values in the tuple (20,21,22) form a Scalene triangle, because A <> B <> C .<br/>
Values in the tuple (13,14,30) cannot form a triangle because the combined value of sides A and A is not larger than that of side C.
