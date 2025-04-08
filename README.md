# [Finals Lab Task 1 - Creating a Database Using MySQL Workbench](https://github.com/user-attachments/files/19641889/Finals.Lab.Task.1-.Manarang.docx)

## Step by Step Process
1. Create the `employees` table:
   - Define `employee_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_name` as a VARCHAR (up to 255 characters), and make it not null.
   - Define `manager_id` as an integer, which will be a foreign key referencing `employee_id` from the same table.

2. Create the `departments` table:
   - Define `department_id` as a unique integer, auto-increment, and primary key.
   - Define `department_name` as a VARCHAR (up to 255 characters), and make it not null.

3. Create the `employee_departments` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `department_id` as an integer, which will be a foreign key referencing `department_id` in the `departments` table.
   - Set a composite primary key on the combination of `employee_id` and `department_id`.

4. Create the `employee_projects` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `project_name` as a VARCHAR (up to 255 characters), and make it not null.

5. Create the `managers` table:
   - Define `manager_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.

# Screenshots
## Query Statements
1. Employee Table
- ![Image](https://github.com/user-attachments/assets/369fd8f4-553d-45b4-b587-7b2b21d2ad25)
   
2. Department Table
- ![Image](https://github.com/user-attachments/assets/765c90aa-5ec1-4dbd-a097-8fa0de8bd384)
   
3. Employee Department Table
- ![Image](https://github.com/user-attachments/assets/1ef78648-8100-472c-b45b-c608a1c1f38f)
  
4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/09509270-eb47-4b99-a136-d9f406fd6013)
   
5. Manager Table
- ![Image](https://github.com/user-attachments/assets/2c8f3382-4bb1-4cae-abf7-0b7d98b44026)

## Table Structure
1. Employee Table
- ![Image](https://github.com/user-attachments/assets/43bfdb48-14ee-40de-97a8-da5fab310119)
   
2. Department Table
- ![Image](https://github.com/user-attachments/assets/f4a9f09e-ee14-44cd-a0a8-721ef7f0aed7)
   
3. Employee Department Table
- ![Image](https://github.com/user-attachments/assets/8d4e977d-808a-478d-8e45-908475ef4316)
   
4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/533b25c9-f0cf-4626-abe0-cfa48d28b128)
   
5. Manager Table
- ![Image](https://github.com/user-attachments/assets/1d01e9ee-1bde-4906-9544-279bbd4b302a)

## EER Diagram 
- ![Image](https://github.com/user-attachments/assets/4e949ab5-55e8-404b-a476-4fdc07cfc11d)
