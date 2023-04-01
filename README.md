# Insurance-Management-Platform-with-Spring-Boot-and-Java
# Objective: 
Build an insurance management platform that allows users to manage insurance policies, clients, and claims using Spring Boot and Java.

# To run the Insurance Management Platform locally, follow the steps below:

1. Clone the project repository from GitHub to your local machine.

2. Ensure that you have the latest version of Java and Maven installed on your machine.

3. Open project in eclipse and navigate to the project directory.

4. Right click on project and run as Spring Boot App.

5. This will start the application on your local machine.

6. You can access the application by visiting http://localhost:8099/ in your web browser.


# Project Structure:

The Insurance Management Platform is a Spring Boot project that follows the Model-View-Controller (MVC) architecture. The project has the following structure:

1. src/main/java/com.insurancemanagementplatform: This package contains the main application class and the configuration classes.

2. src/main/java/com.insurancemanagementplatform.controller: This package contains the RESTful API controllers for managing clients, insurance policies, and claims.

3. src/main/java/com.insurancemanagementplatform.service: This package contains the service classes that interact with the repositories and perform business logic.

4. src/main/java/com.insurancemanagementplatform.repository: This package contains the repository interfaces that interact with the database.

5. src/main/java/com.insurancemanagementplatform.model: This package contains the domain models for the clients, insurance policies, and claims.

# Features:

The Insurance Management Platform is a full-fledged insurance management system that allows users to manage insurance policies, clients, and claims using RESTful APIs. The platform provides the following features:

1. Create, read, update, and delete clients, insurance policies, and claims.

2. Fetch all clients, insurance policies, and claims or get a specific client, policy, or claim by ID.

3. Each policy is associated with a client, and each claim is associated with a policy.

4. Spring Data JPA is used to interact with the embedded database or MySQL database.

5. Exception handling and validation are implemented to ensure proper API usage and data integrity.
