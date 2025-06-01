# Student Registration System

This is a simple **Student Registration System** implemented in Java. It simulates the process of student account creation, course management, and registration for academic courses.

## Features

- Register students with username and password
- Create academic courses
- Register students to courses
- Display all current course registrations

## Project Structure

The project contains the following Java classes:

- **`Account`**: Represents a student’s login account with username and password.
- **`Student`**: Contains student information and links to an `Account`.
- **`Course`**: Represents an academic course with an ID and name.
- **`Registration`**: Represents the registration of a student for a course.
- **`RegistrationManager`**: Handles the storage and management of students, courses, and registrations.
- **`StudentRegistrationSystem`**: Main class to demonstrate system functionality.

## How to Run

1. Make sure you have **Java installed** on your system (Java 8 or higher).
2. Save the code in a file named `StudentRegistrationSystem.java`.
3. Compile the code using:

   ```bash
   javac StudentRegistrationSystem.java
