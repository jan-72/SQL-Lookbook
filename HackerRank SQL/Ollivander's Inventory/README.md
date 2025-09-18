**Medium | SQL | Basic Join**

Harry Potter and his friends are at Ollivander's with Ron, finally replacing Charlie's old broken wand.

Hermione decides the best way to choose is by determining the minimum number of gold galleons needed to buy each non-evil wand of high power and age. Write a query to print the id, age, coins_needed, and power of the wands that Ron's interested in, sorted in order of descending power. If more than one wand has same power, sort the result in order of descending age.

Input Format

The following tables contain data on the wands in Ollivander's inventory:

Wands: The id is the id of the wand, code is the code of the wand, coins_needed is the total number of gold galleons needed to buy the wand, and power denotes the quality of the wand (the higher the power, the better the wand is). 

<img width="200" height="190" alt="image" src="https://github.com/user-attachments/assets/b0275d5a-daaa-4d2d-bdee-c719e24b29b2" />


Wands_Property: The code is the code of the wand, age is the age of the wand, and is_evil denotes whether the wand is good for the dark arts. If the value of is_evil is 0, it means that the wand is not evil. The mapping between code and age is one-one, meaning that if there are two pairs (code1,age1) and (code2,age2) then  code1 <> code2 and age1 <> age2.

<img width="164" height="153" alt="image" src="https://github.com/user-attachments/assets/50925f8e-9ac4-4377-966e-bd72df3f625d" />


Sample Input

Wands Table:

<img width="305" height="752" alt="image" src="https://github.com/user-attachments/assets/ad20729a-0a94-46fc-9179-0b41aa67addd" />

Wands_Property Table: 

<img width="194" height="227" alt="image" src="https://github.com/user-attachments/assets/56644fe2-6d22-4ef1-a5fe-f2643a31dba0" />


Sample Output

9 45 1647 10
12 17 9897 10
1 20 3688 8
15 40 6018 7
19 20 7651 6
11 40 7587 5
10 20 504 5
18 40 3312 3
20 17 5689 3
5 45 6020 2
14 40 5408 1
Explanation

The data for wands of age 45 (code 1): 

<img width="295" height="120" alt="image" src="https://github.com/user-attachments/assets/51812bd3-0d81-4730-bf93-dd210c116012" />

The minimum number of galleons needed for wand (Age=45, power=2) = 6020

The minimum number of galleons needed for wand (Age=45, power=10) = 1647

The data for wands of age 40 (code 2): 

<img width="295" height="259" alt="image" src="https://github.com/user-attachments/assets/8c9672bf-5eca-450c-ae26-50cf10d1b8b3" />


The minimum number of galleons needed for wand (Age=40, power=1) = 5408

The minimum number of galleons needed for wand (Age=40, power=3) = 3312

The minimum number of galleons needed for wand (Age=40, power=5) = 7587

The minimum number of galleons needed for wand (Age=40, power=7) = 6018

The data for wands of age 20 (code 4): 

<img width="295" height="187" alt="image" src="https://github.com/user-attachments/assets/94008d1b-d227-4141-b68b-6e026d5504dc" />


The minimum number of galleons needed for wand (Age=20, power=5) = 504

The minimum number of galleons needed for wand (Age=20, power=6) = 7651

The minimum number of galleons needed for wand (Age=20, power=8) = 3688

The data for wands of age 17 (code 5): 

<img width="294" height="119" alt="image" src="https://github.com/user-attachments/assets/98f03e0e-bc93-4973-8e4c-d39ae3187dc0" />


The minimum number of galleons needed for wand (Age=17, power=3) = 5689

The minimum number of galleons needed for wand (Age=17, power=10) = 9897
