Student Management System
  A Spring Boot based Student Management System designed to manage student information, including registration, details view, update, and deletion functionalities.
This application is built using Spring Boot, Spring MVC, Thymeleaf, HTML, CSS, and Bootstrap for a modern and responsive user interface.

Technologies Used
Spring Boot – Framework used to create the back-end logic of the application.
Spring MVC – Used for creating RESTful web services and managing requests.
Spring Web – Used to handle web-related functionalities.
Thymeleaf – Template engine used to render dynamic HTML pages.
HTML/CSS/Bootstrap – For building responsive, user-friendly front-end pages.
MySQL – Database used for storing student records.
Maven – Dependency management and build tool.

Features
Home page- Displays information of student management system as well as teacher login button . 
Student Registration – Users can add new student records.
View Students – View a list of all registered students.
Update Student Information – Edit details of a specific student.
Delete Student Record – Remove a student from the database.
Responsive UI – Bootstrap-based design for mobile and desktop compatibility.

Prerequisites
Java 8 or higher
Maven
MySQL
Spring Tool Suite (STS) or any IDE supporting Spring Boot

Configuration Instructions
To run this project, update the application.properties file with your database credentials.
1)Create database with name "sms" in your local machine.
2)Database Username: Add your username in the spring.datasource.username property.
3)Database Password: Add your password in the spring.datasource.password property.
For security purposes, only the sample username and password have been provided. Ensure you modify these fields to match your local setup.

Steps to execute project:
1) Open the application in your browser at http://localhost:8080/home.
2) You will be presented with home page which contains information about student management system also contains button for teacher login.
3) After clicking login you can login with username and password or register as new teacher.
4) After successful login you will be presented with a list of students. 
  You can:
  i)Add a new student using the Add Student button.
  ii)Edit or delete existing students by selecting the corresponding buttons next to each student.
