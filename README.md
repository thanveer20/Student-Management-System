# Student Portal

## Overview
Student Portal is a full-stack application designed to streamline the management of student data for educational institutions. This platform offers a comprehensive suite of functionalities including the ability to add, update, delete, and view student information efficiently.

## Features
- **View All Students:** Browse a complete list of students.
- **Add New Student:** Form interface to input new student data.
- **Edit Student Details:** Update existing student information.
- **Delete Student:** Remove student data from the system.

## Technologies Used
- **Frontend:** React, Bootstrap
- **Backend:** Spring Boot, Java
- **Database:** MySQL
- **API Testing:** Postman

## Getting Started
### Prerequisites
- Node.js
- JDK 11
- MySQL

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thanveer20/Student-Portal.git

2. Navigate to the project directory and install dependencies:
   cd Student-Portal
   npm install

3. Start the backend server:
   ./mvnw spring-boot:run

4. In a new terminal, start the frontend:
   npm start

## API Endpoints

- **POST** `/api/students` - Add a new student
- **GET** `/api/students` - Retrieve all students
- **GET** `/api/students/{id}` - Retrieve a student by ID
- **PUT** `/api/students/{id}` - Update a student's details
- **DELETE** `/api/students/{id}` - Delete a student

## Contributions

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.
