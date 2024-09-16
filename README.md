# Petmania

Petmania is an e-commerce platform, and this project represents a comprehensive implementation of a backend application for a shopping cart using Spring Boot and Spring Security. It is designed to help you master these technologies while building a fully functional backend system.

The project guides you through the entire process of creating a shopping cart backend, starting from scratch and advancing through various stages of development. 

- Creating and mapping entity classes
- Implementing CRUD operations
- Developing services and controllers for products, categories, and carts
  
By the end of this project, you will have understanding of key Spring technologies.

### Key Technologies Used

- **Spring Boot**: A powerful framework that simplifies the process of building production-ready applications. Provides auto-configuration and an embedded server, making development faster and easier.
- **Spring Security**: A comprehensive framework for addressing authentication and authorization concerns. Ensures that your application is protected against common security threats.
- **JWT (JSON Web Tokens)**: A compact, URL-safe means of representing claims between parties. Used for secure user authentication and effective session management.

## Highlights

- **Project Generation**: Setting up a new Spring Boot project and configuring it for development.
- **Entity Classes and CRUD Operations**: Creating and mapping entity classes, and implementing CRUD operations for managing products, categories, and carts.
- **Service and Controller Development**: Developing services and controllers to handle business logic and API requests.
- **Security Integration**: Integrating Spring Security and JWT to secure the application, implementing user authentication and authorization.
- **Testing and Debugging**: Testing APIs and fixing errors to ensure the application runs smoothly.
- **Project Wrap-Up**: Final project cleanup and security testing.

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

Ensure you have the following installed:

- **Java Development Kit (JDK)**: Version 22. You can download it from [AdoptOpenJDK](https://adoptium.net/) or the [OpenJDK website](https://openjdk.java.net/install/).
- **Maven**: For building and managing dependencies. Download and install Maven from the [Apache Maven website](https://maven.apache.org/download.cgi).
- **IDE**: An Integrated Development Environment like [IntelliJ IDEA](https://www.jetbrains.com/idea/) or [Eclipse](https://www.eclipse.org/).

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

Build the Project
Navigate to the project directory and build the project using Maven:

```bash
mvn clean install
```

Run the Application
After building the project, you can run the application using the following command:

```bash
mvn spring-boot:run
```

This will start the Spring Boot application on the default port (usually 8080).

### Access the API

You can interact with the API using tools like Postman or curl. The application will be accessible at http://localhost:8080.
