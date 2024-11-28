Student Report Card Management System

This project is a console-based application written in C++ to manage and process student report cards. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student records stored in a binary file. It is a functional and practical example of file handling, class structures, and object-oriented programming concepts.

Features

Add Student Records

Input student details including name, roll number, and marks in various subjects.

Display All Records

View details of all students stored in the file.

Search for a Specific Student

Fetch a student record by roll number.

Modify Student Records

Update an existing student’s details by their roll number.

Delete Student Records

Remove a student’s record from the database.

Display Class Results

Show all student records in a tabular format, including grades and percentages.

Result Menu

View the result of a single student or the entire class.

Interactive Entry Menu

User-friendly menu system for adding, modifying, and deleting records.

Technologies Used

Language: C++

Concepts: Object-Oriented Programming, File Handling

How It Works

Class Structure

The application revolves around a student class that encapsulates:

Data Members:

Roll number, name, marks for five subjects (Physics, Chemistry, Math, English, Computer Science), percentage, and grade.

Member Functions:

getdata(): Inputs student details.

showdata(): Displays student details.

calculate(): Calculates percentage and grade based on marks.

show_tabular(): Displays student details in a tabular format.

retrollno(): Returns the roll number of the student.

File Handling

Binary Files: Used to store and retrieve student records persistently.

Functions:

write_student(): Writes a new student record to the file.

display_all(): Reads and displays all records from the file.

display_sp(int): Reads and displays a specific student record.

modify_student(int): Updates a student record.

delete_student(int): Deletes a student record from the file.

class_result(): Displays all students’ results in a tabular format.

Menus

Main Menu:

Navigate to the Result Menu, Entry Menu, or exit the program.

Result Menu:

View the class result or a specific student’s report card.

Entry Menu:

Perform CRUD operations on student records.

Getting Started

Prerequisites

A C++ compiler (e.g., GCC, MSVC).

Basic understanding of C++ file handling and OOP concepts.


