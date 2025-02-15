# Car management service 

CarManagementService - is a RESTful web service built with Spring Boot, designed for managing cars and car models. The service provides an API for performing CRUD operations (Create, Read, Update, Delete) on cars, car models, and manufacturers.

---

## 📋 Key Features

- **Car management**: create, update, delete, retrieve a list of cars or a specific car
- **Car model management**: CRUD operations
- **Manufacturer management**: CRUD operations
- Pagination and filtering support
- Global exception handling
- Integration with Auth0 for authentication and authorization using OAuth2 and JWT
- API documentation with OpenAPI (Swagger)

--- 

## ⚙️ Technologies

- **Programming language**: Java 11
- **Framework**: Spring Boot, Spring Core, Spring Data Jpa 
- **Authorization**: Spring Security, JWT, Auth0
- **Database**: PostgeSQL
- **Migrations**: FlyWay
- **Testing**: JUnit, Mockito, Parametrized tests, Testcontainers, Postman
- **API Documentation**: OpenAPI (Swagger)
- **Containerization**: Docker

---

## 🚀 Getting Started  

### Prerequisites  

1. Java 11 or newer.  
2. Docker (for running the database and containerized application).  
3. A REST client like Postman (optional, for testing).

### Installation Steps  

1. Clone the repository:  
   ```bash
   git clone https://github.com/VladislavSaliuk/CourseLink.git
   cd CourseLink
2. Run the application:
   ```bash
   ./mvnw spring-boot:run
3. Start Docker containers:
   ```bash
   docker-compose up -d   
4. Access the OpenAPI at:
   ```bash
   localhost:8080/swagger-ui/index.html

---

## 📂 Project Structure

- **config/**: Contains configuration classes, such as beans, CORS settings, or application profiles.  
- **rest/**: Handles HTTP requests and returns responses.   
- **entity/**: Defines entities mapped to database tables.  
- **repository/**: Provides database access methods.
- **security/**: Contains security configuration, filters, and authentication-related logic.  
- **service/**: Contains business logic and service layer code.  
- **resources/**: Stores configuration files, templates, and migration scripts.
- **test/**: Contains test classes for unit and integration testing.  
- **docker-compose.yml**: Sets up the application and database containers.  
- **pom.xml**: Lists dependencies, plugins, and build configuration.

--- 

## 🛠 Contributing

If you want to contribute to this project, feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📜 License

This project is licensed under the [LICENSE](./LICENSE). You are free to use, modify, and distribute this software as described in the license.
