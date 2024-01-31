# Full-Stack Customer Management Service

## Overview

The Full-Stack Customer Management Service is a comprehensive application designed to facilitate the efficient management of customer data for authorized users. This application consists of both a backend and a frontend, providing a seamless experience for adding, updating, deleting, and searching customer information.

## Features

1. **User Authentication:**
   - Secure user registration and login.
   - Token-based authentication using JSON Web Tokens (JWT).
   - Protection of sensitive information with Spring Security.

2. **Customer Management:**
   - Add, view, update, and delete customer records.
   - Customized search functionalities for customers based on name, email, city, and phone.
   - Pagination support for efficiently managing a large number of customer records.
   - Integration with a relational database (MySQL) for persistent data storage.

3. **Role-Based Access Control:**
   - Differentiate between roles like admin and regular users.
   - Admins have full access to customer management functionalities, while regular users have limited access.

4. **Backend Technologies:**
   - **Java Spring Boot:**
     - Powerful and flexible framework for building Java-based web applications.
     - RESTful API endpoints for communication between frontend and backend.
   - **MySQL:**
     - Relational database for storing and managing customer data.
     - Integration with Spring Data JPA for seamless database operations.

5. **Frontend Technologies:**
   - **HTML, CSS, and Bootstrap:**
     - Standard web technologies for structuring, styling, and enhancing the user interface.
     - Bootstrap for responsive and visually appealing designs.
   - **JavaScript:**
     - Dynamic behavior for frontend interactions.
     - Integration with backend APIs for seamless data exchange.

6. **JWT for Secure Communication:**
   - Token-based authentication to ensure secure communication between frontend and backend.
   - Protection against unauthorized access and data tampering.

7. **Deployment and Dockerization:**
   - Dockerized backend application using the Jib plugin for easy containerization.
   - Frontend deployment on a web server, ensuring accessibility to users.

## Project Structure

1. **Backend:**
   - **Controllers:** Define RESTful endpoints for handling customer-related operations.
   - **Services:** Implement business logic, integrate with repositories, and perform CRUD operations.
   - **Repository:** Interact with the database using Spring Data JPA.
   - **Security:** Implement security configurations for user authentication.

2. **Frontend:**
   - **HTML, CSS, and Bootstrap:** Create a visually appealing and responsive user interface.
   - **JavaScript:** Implement dynamic behavior and API interactions.

## Deployment

   - Deployment involves hosting the backend on a server, accessible through API endpoints.
   - Frontend deployment on a web server, allowing users to access the application via a web browser.

# Please refer to front-end and backend repo for further details
