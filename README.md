# Project Management System

This project is a simple Project Management System implemented using Java, Spring Boot, and MySQL. It provides RESTful API endpoints for managing projects, including creating, retrieving, updating, and deleting project information.

## Getting Started

To get started with the project, follow these steps:

### Clone the Repository:

```bash
git clone https://github.com/him77anshu/project-management-system.git
```

### Set Up MySQL Database:

- Create a MySQL database named `projectDB`.
- Update the `application.properties` file with your MySQL database configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/projectDB
spring.datasource.username=admin
spring.datasource.password=123456
```

### Build and Run the Application:

```bash
./gradlew bootRun
```

### Access the API Endpoints:

Once the application is running, you can access the API endpoints using tools like Postman or cURL.

- **Base URL:** `http://localhost:8069/api/projects`

## API Endpoints

- `GET /api/projects`: Get all projects
- `GET /api/projects/{id}`: Get project by ID
- `POST /api/projects/add`: Create a new project
- `PUT /api/projects/{id}`: Update project by ID
- `DELETE /api/projects/{id}`: Delete project by ID

## Technologies Used

- Java 17
- Spring Boot
- MySQL
- Spring Data JPA
- Spring Validation

## Contributing

Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

