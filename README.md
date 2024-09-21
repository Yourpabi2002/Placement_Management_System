# Placement Management System

## Overview
The **Placement Management System** is a simple Java-based application that helps manage student placements in various companies. This system is designed using **Object-Oriented Programming (OOP)** principles and allows users to manage students, companies, schedule interviews, and record placement details.

## Features
- **Student Management**: Add, update, delete, and view students.
- **Company Management**: Add, update, delete, and view companies.
- **Placement Scheduling**: Schedule interviews and record placement results (Placed/Not Placed).
- **View Placements**: See a list of all students and their placement results.

## Technologies Used
- **Java**: The core programming language used to build the application.
- **Object-Oriented Programming (OOP)**: Key design principle for organizing and structuring the system.
  
## Class Structure

1. **Student Class**:
   - Stores information about students like `id`, `name`, `department`, and `cgpa`.
   
2. **Company Class**:
   - Stores information about companies like `companyId`, `companyName`, and `jobRole`.

3. **Placement Class**:
   - Associates a student with a company and tracks the placement status (e.g., "Placed" or "Not Placed").

4. **PlacementManagementSystem Class**:
   - Manages all operations related to students, companies, and placements. Provides functionality for adding students and companies, scheduling interviews, and viewing all the information.

## Installation and Running the Application

### Prerequisites:
- **Java**: Ensure that Java (JDK 8 or later) is installed on your system.
- **IDE**: Use an IDE like **IntelliJ IDEA**, **Eclipse**, or **NetBeans**.

### Steps to Run:

1. Clone this repository or download the code.
2. Open the project in your preferred IDE.
3. Compile the project.
4. Run the `PlacementManagementSystem.java` file.
5. Use the terminal/console to interact with the system using the available menu options.

### Menu Options:
1. **Add Student**: Allows you to add student details such as ID, name, department, and CGPA.
2. **Add Company**: Allows you to add company details such as ID, name, and job role.
3. **Schedule Interview**: Schedule an interview for a student with a company and record the placement status.
4. **Show All Students**: Displays all the students in the system.
5. **Show All Companies**: Displays all the companies in the system.
6. **Show All Placements**: Displays the results of all scheduled placements.
7. **Exit**: Exit the application.

### Example Usage:

1. Add a student with the following details:
   - ID: 1
   - Name: John Doe
   - Department: Computer Science
   - CGPA: 8.5
   
2. Add a company:
   - ID: 101
   - Name: Google
   - Job Role: Software Engineer

3. Schedule an interview for John Doe with Google, and mark the status as "Placed".

4. View all placements to check the result.


## Future Improvements
- Implement functionality for updating and deleting students/companies.
- Add file persistence so that data remains stored even after the program exits.
- **Graphical Interface**: Replace the console-based interface with a user-friendly graphical interface.
- **Backend with Spring Boot**: Migrate the backend to **Spring Boot** for better scalability and RESTful services.
- **Database Integration**: Use **MySQL** for persistent data storage, replacing the in-memory data storage currently in use.

## Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.


## Contact
If you have any questions or need further clarification, feel free to reach out:

- **Name**: Prabitra Sarkar
- **Email**: sarkarprabitra2019@gmail.com

