 

Names: Docban Olaw Sabina Kon 26041
               Angelique NYIRAHABIMANA    21463
                Akize Israel 25883
                Nshimiyimana Theophile 25425
                 Umutoni Annaxelle 26067

Date: 24/11/2025
Subject: Dot Net Group Project 


Project Name: School Management System


1.	Problem Statement
Educational institutions (schools, colleges, training centers) need a centralized system to manage users (administrators, teachers, students), classes, and subjects, and to handle routine academic operations (enrolment, scheduling, basic administration). Manual record-keeping or scattered spreadsheets cause data duplication, inconsistent records, and time wasted on administrative tasks.

This School Management System provides a web-based platform to centralize user accounts, manage classes and subjects, and provide authenticated access for administrative workflows—reducing errors, improving data access, and saving staff time.


2.	Project Objectives
Primary Objectives
•	Provide authenticated access (register / login) for users (admins/teachers/students).
•	Allow administrators to create, view, update, and delete classes and subjects.
•	Store user and academic data in a relational database via Entity Framework Core.
•	Provide a clean web interface (Razor Pages) for core school administration tasks.

Secondary Objectives
•	Expose simple API-like request/response DTOs for future integration.
•	Keep the app cross-platform using ASP.NET Core (.NET 8) and EF Core.
•	Provide clear separation of concerns (Models, Data, Pages/Controllers).


3.	Functional Requirements

1.	User registration.
2.	User login/authentication.
3.	User management (CRUD).
4.	Class management (CRUD).
5.	Subject management (CRUD).
6.	Data persistence using EF Core.
7.	List and search functionality.
8.	Role-based access control.
9.	API/DTO responses for operations.
10.	Error handling and validation.
 
4.	Non-Functional Requirements

1.	Platform: Run on .NET 8 and hostable on Windows/Linux.
2.	Performance: CRUD operations should respond under 2 seconds for datasets up to several thousand records.
3.	Security: Passwords must be stored hashed; authentication sessions must be secure.
4.	Scalability: Database-backed architecture allows scaling to a larger RDBMS.
5.	Maintainability: Clear MVC/Razor Pages structure for future enhancements.
6.	Availability: System should be available during school hours with scheduled maintenance windows.


5.	Use Case Diagram

Use Case Diagram

Use Cases: - Actors: Administrator, Teacher, Student - Administrator: Register User, Login, Manage Users, Manage Classes, Manage Subjects, View Reports - Teacher: Login, View Assigned Classes, Manage Grades (inferred) - Student: Login, View Enrolled Classes
<img width="975" height="975" alt="image" src="https://github.com/user-attachments/assets/824be53e-c027-4c0d-adbc-50e2a229db73" />


