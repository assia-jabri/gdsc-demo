# Student Management API

This is a simple Spring Boot API for managing student information. It provides CRUD (Create, Read, Update, Delete) operations for students. The API uses MySQL as the database backend, so please ensure you have XAMPP or WAMP installed to run the API locally.

## Prerequisites

Before running the API, make sure you have the following installed:

- Java Development Kit (JDK) 17 or higher
- Apache Maven
- XAMPP or WAMP (for MySQL)

## Getting Started

1. Clone the repository:
```shell
   git clone https://github.com/assia-jabri/gdcs-demo.git


2. Configure the MySQL database:

- Install XAMPP or WAMP and start the Apache and MySQL services.
- Create a new database in phpMyAdmin (e.g., `studentdb`).
- Update the `application.properties` file in the `src/main/resources` directory with your MySQL configuration:

  ```properties
  spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
  spring.datasource.username=root
  spring.datasource.password=
  ```

3. Build and run the API:


The API will be running on `http://localhost:8080`.

## API Endpoints

The following endpoints are available:

- `GET /api/students`: Retrieves all students.
- `GET /api/students/{id}`: Retrieves a specific student by ID.
- `POST /api/students`: Creates a new student.
- `PUT /api/students/{id}`: Updates a student by ID.
- `DELETE /api/students/{id}`: Deletes a student by ID.

The student object has the following attributes:

- `id`: Unique identifier for the student.
- `name`: Name of the student.
- `age`: Age of the student.
- `email`: Grade of the student.

Please note that for POST and PUT requests, the request body should contain a JSON object representing the student with the required attributes.





