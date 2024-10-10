# School Management System

## Overview

The School Management System is a Java-based application that uses JPA (Java Persistence API) for Object-Relational Mapping (ORM) to manage various aspects of a school's operations, including student enrollment, course management, and department tracking. This project demonstrates the integration of a MariaDB database with a Java application, showcasing the use of JPA for data persistence, relationships, and the implementation of various database functionalities. The application is developed using **Eclipse IDE**.

## Features

- **Student Management**: Manage student records effectively.
- **Course Management**: Handle courses offered by the school and track enrollments.
- **Department Management**: Manage departments within the school.
- **Relationships**: Handle relationships between entities such as students, courses, and departments.
- **Triggers and Stored Procedures**: Implement database automation using triggers and stored procedures.
- **Optimistic Locking**: Ensure data consistency in concurrent environments.

## Technologies Used

- **Java**: Programming language used for the application.
- **JPA (Hibernate)**: ORM framework for managing database interactions.
- **MariaDB**: Database management system for storing application data.
- **Maven**: Dependency management tool for Java projects.
- **Eclipse IDE**: Development environment used for building and managing the application.

## Database Schema

The following tables are included in the database schema:

- **Student**: Stores information about students.
- **Teacher**: Stores information about teachers.
- **Course**: Stores information about courses.
- **Department**: Stores information about departments.
- **Enrollment**: Tracks the relationship between students and courses.

## Installation

### Prerequisites

- JDK 17 or later
- MariaDB
- Maven
- Eclipse IDE

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/student-course-app.git
   cd student-course-app

2. **Set up the database**:

  Run the provided SQL scripts in MariaDB to create the database and tables. **The text file includes all code commands for setupping MariaDB database and the code lines used.**
  Ensure that the database connection settings in persistence.xml are configured correctly.

3. **Import the project into Eclipse**:

  Open Eclipse IDE.
  Go to File > Import > Existing Maven Projects.
  Select the directory of the cloned repository and import it.
  
4. **Build the project**:
   ```bash
   mvn clean install

5. **Run the application**:

  Execute the Main class to start the application.

### Usage

Upon running the application, it will create a sample student and demonstrate the management of students and their enrollments.

### Future Enhancements

- Implement advanced query capabilities using JPQL and Criteria API.
- Add user authentication and authorization features.
- Extend the functionality to handle more complex relationships between entities.

