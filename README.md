# Student Report Card Management System
Description
This is a C++ console-based application for managing student records and generating report cards. The program allows you to:

Create student records.
View individual or class results.
Modify existing records.
Delete specific student records.
Display all student records in a tabular format.
The data is stored persistently using binary files.

# Features
1. Add Student Record: Add new student details including marks for five subjects.
2. Display All Records: View all student records.
3. Search Specific Student: Retrieve data of a specific student using their roll number.
4. Modify Student Record: Update the details of an existing record.
5. Delete Student Record: Remove a student record permanently.
6. View Class Results: Display the grades and percentages for all students.
7. Student Report Card: Generate a detailed report card for a specific student.
8. User-Friendly Menus: Intuitive navigation for accessing features.

# File Structure
The program uses a binary file named student.dat to store student information. When deleting records, a temporary file (Temp.dat) is used for data restructuring.

# Program Workflow
Main Menu:

Access the result menu or entry/edit menu.
Exit the program.

Result Menu:

View class results.
Generate a specific student's report card.

Entry/Edit Menu:

Add new records.
Modify, delete, or view existing records.

# Class Details

Attributes:
1. rollno: Student's roll number.
2. name: Student's name.
3. Marks for Physics, Chemistry, Maths, English, and Computer Science.
4. per: Percentage.
5. grade: Grade assigned based on percentage.

Methods:
getdata(): Accepts student data input from the user.
showdata(): Displays a student's full details.
show_tabular(): Displays data in tabular format.
retrollno(): Returns the roll number of the student.
calculate(): Calculates the percentage and grade.
