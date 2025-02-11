# Spring Boot Role-Based Access Control (RBAC) Application

This is a Spring Boot application that implements Role-Based Access Control (RBAC) with two roles: **Admin** and **User**. The application follows the MVC monolithic architecture and provides functionalities for users to view their enrolled courses and profile, while admins can manage courses, classes, and user-submitted contact information. The application uses **Spring Data JPA** for data persistence and **Spring Security** for form-based authentication. Pagination is implemented for displaying courses, classes, and contact messages.

---

## Features

### User Features
- **View Enrolled Courses**: Users can view the list of courses they are enrolled in.
- **View Profile**: Users can view their profile information.

### Admin Features
- **Manage Courses**: Admins can add, update, or delete courses.
- **Manage Classes**: Admins can manage classes associated with courses.
- **Manage Contact Information**: Admins can view and manage user-submitted contact messages.

### Common Features
- **Pagination**: Pagination is implemented for displaying courses, classes, and contact messages.
- **Form-Based Authentication**: Secure login using Spring Security.

---

## Technologies Used
- **Spring Boot**: Backend framework for building the application.
- **Spring Data JPA**: For data persistence and database operations.
- **Spring Security**: For authentication and authorization.
- **Thymeleaf**: Server-side Java template engine for rendering views.
- **MySQL**: Database used for storing application data.
- **Bootstrap**: Front-end framework for styling the user interface.

---

## Database Schema
The application uses the following tables:
1. **User**: Stores user information (username, password, role, etc.).
2. **Course**: Stores course details (course name, description, etc.).
3. **Class**: Stores class details associated with courses.
4. **Contact**: Stores user-submitted contact messages.

---

## Installation and Setup

### Prerequisites
- Java 17 or higher
- Maven
- MySQL

### Steps to Run the Application
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
