# Full Stack CRUD Application - Todo
Todo Full stack Application which done by angular and springboot



This project is a full-stack CRUD (Create, Read, Update, Delete) application built using Angular and Spring Boot.

Technologies Used
Frontend:

Angular
Bootstrap for styling
Backend:

Spring Boot
Spring Data JPA for CRUD operations
MySQL database
Functionality
This application allows users to manage tasks with basic CRUD operations:

Create Task: Add new tasks with details such as title, description, and status.
Read Task: View a list of all tasks with their details.
Update Task: Modify existing task details.
Delete Task: Remove tasks from the list.
Getting Started
To get a local copy up and running, follow these steps:

Prerequisites
Node.js (for Angular)
Java Development Kit (JDK)
IDE (Eclipse, IntelliJ IDEA) for Spring Boot development
MySQL installed and running
Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <project-folder>
Backend Setup:

Open the backend project in your IDE.
Configure the database settings in application.properties:
properties
Copy code
spring.application.name=todo
spring.datasource.url=jdbc:mysql://localhost:3307/todo
spring.datasource.username=root
spring.datasource.password=root123
#spring.datasource.driver-class-name=com.mysql.cj.jdbc.driver
#spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
Ensure MySQL is running on localhost:3307, and a database named todo is created.
Run the Spring Boot application.
Frontend Setup:

Navigate to the frontend project folder (cd frontend).
Install dependencies:
bash
Copy code
npm install
Start the Angular development server:
bash
Copy code
ng serve
Access the Application:

Open your browser and go to http://localhost:4200 to view the application.
Usage
Upon accessing the application, you will see the list of tasks.
Use the provided interface to add, edit, or delete tasks as needed.
Contributing
Contributions are welcome! Fork the repository and submit a pull request with your enhancements.
