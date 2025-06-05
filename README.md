# Task Manager Backend

A Spring Boot backend for a Task Management System, providing REST APIs for CRUD operations on tasks.

## Features
- Create, read, update, and delete tasks
- Toggle task completion status
- H2 in-memory database for storage
- CORS enabled for integration with React frontend

## Setup
1. Clone the repository: `git clone https://github.com/your-username/task-manager-backend.git`
2. Ensure Java 17 and Maven are installed.
3. Navigate to the project folder: `cd task-manager-backend`
4. Run the application: `mvn spring-boot:run`
5. Access the API at `http://localhost:8080/api/tasks`
6. View the H2 database console at `http://localhost:8080/h2-console` (JDBC URL: `jdbc:h2:mem:testdb`, Username: `sa`, Password: blank)

## Frontend
The React frontend is hosted at: [link to your frontend GitHub repo]

## Technologies
- Spring Boot
- Spring Data JPA
- H2 Database
- REST