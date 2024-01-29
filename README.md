Task Bliz Application
Task Bliz is a task management application with CRUD functionalities, user authentication, and roles built using Next.js, TypeScript, and Spring Boot. This README file provides detailed instructions on how to set up and run the application locally.

Table of Contents

Features
Technologies Used
Project Structure
Database Schema
Security Measures
Setup Instructions
Frontend Setup
Backend Setup
Running the Application

Features
CRUD Operations: Create, Read, Update, and Delete tasks.
User Authentication: Two roles - admin and regular user.
Role-Based Access Control: Admins can manage all tasks, regular users can manage their own tasks.
Error Handling and Validation: Proper mechanisms in place with meaningful error messages.
Sorting/Filtering Options: Enhance user experience with sorting or filtering tasks.

Technologies Used

Frontend
Next.js: React framework for frontend development.
TypeScript: Adds static typing to the JavaScript language.

Backend
Spring Boot: Java-based framework for backend development.
H2 Database: Lightweight, in-memory database for storing task data.

Project Structure

task-bliz-app
|-- frontend
|   |-- // Frontend source code
|
|-- backend
|   |-- // Backend source code
|
|-- // Other project files

Database Schema

Security Measures

Setup Instructions
Follow the steps below to set up and run the Task Bliz Application locally.

Frontend Setup
Navigate to the frontend directory.

cd frontend
Install dependencies.

npm install
Backend Setup
Navigate to the backend directory.


cd backend
Open the project in your preferred IDE.

Set up your database configuration in application.properties.

properties

# Database Configuration
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=your-username
spring.datasource.password=your-password
Replace your-username and your-password with your database credentials.

Running the Application
Run the Spring Boot application from your IDE.

Navigate to the frontend directory.


cd frontend
Run the Next.js application.

npm run dev
Open your browser and access the application at http://localhost:3000.
