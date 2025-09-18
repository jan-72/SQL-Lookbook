**Medium | SQL | Advanced Select**

Amber's conglomerate corporation just acquired some new companies. Each of the companies follows this hierarchy: 

<img width="113" height="199" alt="image" src="https://github.com/user-attachments/assets/eddace3c-f015-46ac-b823-cf0348fbf0b8" />

Given the table schemas below, write a query to print the company_code, founder name, total number of lead managers, total number of senior managers, total number of managers, and total number of employees. Order your output by ascending company_code.

Note:

The tables may contain duplicate records.
The company_code is string, so the sorting should not be numeric. For example, if the company_codes are C_1, C_2, and C_10, then the ascending company_codes will be C_1, C_10, and C_2.
Input Format

The following tables contain company data:

Company: The company_code is the code of the company and founder is the founder of the company. 

<img width="196" height="117" alt="image" src="https://github.com/user-attachments/assets/3884996f-99d4-47b8-b34a-8b4ff020456e" />

Lead_Manager: The lead_manager_code is the code of the lead manager, and the company_code is the code of the working company. 

<img width="230" height="119" alt="image" src="https://github.com/user-attachments/assets/b3d4879c-c510-44b0-a500-90c5acce689a" />

Senior_Manager: The senior_manager_code is the code of the senior manager, the lead_manager_code is the code of its lead manager, and the company_code is the code of the working company. 

<img width="242" height="152" alt="image" src="https://github.com/user-attachments/assets/72b3b102-c779-46b1-be4b-445dbb4c366d" />

Manager: The manager_code is the code of the manager, the senior_manager_code is the code of its senior manager, the lead_manager_code is the code of its lead manager, and the company_code is the code of the working company. 

<img width="243" height="190" alt="image" src="https://github.com/user-attachments/assets/3aab466e-3efe-41a2-bc11-3792f2f9e2fb" />

Employee: The employee_code is the code of the employee, the manager_code is the code of its manager, the senior_manager_code is the code of its senior manager, the lead_manager_code is the code of its lead manager, and the company_code is the code of the working company. 

<img width="242" height="223" alt="image" src="https://github.com/user-attachments/assets/1deb2580-cfb4-42f3-9ba3-7bc8b9427b70" />

Sample Input

Company Table: 
<img width="232" height="117" alt="image" src="https://github.com/user-attachments/assets/541040c1-6466-4786-8f38-e8a78f4c7cbb" />

 Lead_Manager Table: 
 <img width="299" height="116" alt="image" src="https://github.com/user-attachments/assets/c668dfdc-1438-4d0e-b35a-e7f810895072" />
 
 Senior_Manager Table: 
 <img width="478" height="152" alt="image" src="https://github.com/user-attachments/assets/a4678c19-43c4-499c-8792-8380890d33e3" />
 
 Manager Table: 
 <img width="604" height="152" alt="image" src="https://github.com/user-attachments/assets/978d578a-949b-40f1-8a5a-d1a213b3e46d" />
 
 Employee Table: 
 <img width="738" height="187" alt="image" src="https://github.com/user-attachments/assets/b5d90326-600f-4331-94cf-19ff5a705d8a" />


Sample Output

C1 Monika 1 2 1 2
C2 Samantha 1 1 2 2
Explanation

In company C1, the only lead manager is LM1. There are two senior managers, SM1 and SM2, under LM1. There is one manager, M1, under senior manager SM1. There are two employees, E1 and E2, under manager M1.

In company C2, the only lead manager is LM2. There is one senior manager, SM3, under LM2. There are two managers, M2 and M3, under senior manager SM3. There is one employee, E3, under manager M2, and another employee, E4, under manager, M3.
