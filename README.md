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

