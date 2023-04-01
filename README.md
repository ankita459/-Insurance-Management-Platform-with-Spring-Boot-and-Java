# Insurance-Management-Platform-with-Spring-Boot-and-Java
# Objective: 
Build an insurance management platform that allows users to manage insurance policies, clients, and claims using Spring Boot and Java.

# To run the Insurance Management Platform locally, follow the steps below:

Clone the project repository from GitHub to your local machine.
Ensure that you have the latest version of Java and Maven installed on your machine.
Open project in eclipse and navigate to the project directory.
Right click on project and run as Spring Boot App.
This will start the application on your local machine.
You can access the application by visiting http://localhost:8099/ in your web browser.

# Project Structure:
The Insurance Management Platform is a Spring Boot project that follows the Model-View-Controller (MVC) architecture. The project has the following structure:

src/main/java/com.insurancemanagementplatform: This package contains the main application class and the configuration classes.

src/main/java/com.insurancemanagementplatform.controller: This package contains the RESTful API controllers for managing clients, insurance policies, and claims.

src/main/java/com.insurancemanagementplatform.service: This package contains the service classes that interact with the repositories and perform business logic.

src/main/java/com.insurancemanagementplatform.repository: This package contains the repository interfaces that interact with the database.

src/main/java/com.insurancemanagementplatform.model: This package contains the domain models for the clients, insurance policies, and claims.

# Features:
The Insurance Management Platform is a full-fledged insurance management system that allows users to manage insurance policies, clients, and claims using RESTful APIs. The platform provides the following features:

Create, read, update, and delete clients, insurance policies, and claims.
Fetch all clients, insurance policies, and claims or get a specific client, policy, or claim by ID.
Each policy is associated with a client, and each claim is associated with a policy.
Spring Data JPA is used to interact with the embedded database or MySQL database.
Exception handling and validation are implemented to ensure proper API usage and data integrity.
