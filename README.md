# Workforce Navigator

The Workforce Navigator is a comprehensive Employee Management System built using Java and Swing library. This application allows users to add, view, update, and remove employees. The system also includes a secure login mechanism and a splash screen for initial loading. SQL is used as the backend database to store and manage employee information securely.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Files](#files)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

## Features

- **Add Employee:** Add new employees to the system with detailed information.
- **View Employee:** View and search for existing employee details.
- **Update Employee:** Modify and update employee information.
- **Remove Employee:** Remove employees from the system securely.
- **Login System:** Secure login mechanism to protect the application.
- **Splash Screen:** An engaging splash screen during application load.
- **SQL Backend:** Uses SQL for backend database management to store and retrieve employee data.

## Usage

1. **Launch the Application:**
   - Run the `Main` class to start the application.
   - The splash screen will appear during the initial loading.

2. **Login:**
   - Enter your credentials on the login screen to access the application.

3. **Manage Employees:**
   - Use the provided menu options to add, view, update, or remove employees.

## Files

- **AddEmployee.java:** Handles the addition of new employees.
- **conn.java:** Manages the database connection using SQL.
- **Login.java:** Manages the login functionality with authentication.
- **Main.java:** The main entry point of the application.
- **RemoveEmployee.java:** Handles the removal of employees.
- **Splash.java:** Displays the splash screen during application load.
- **Update_Employee.java:** Manages the update of employee information.
- **View_Employee.java:** Displays the details of existing employees.

### Database Integration

The application uses SQL as the backend database to store employee information. The `conn.java` file manages the connection to the SQL database, ensuring secure and efficient data transactions. Each feature (add, view, update, remove) interacts with the database to perform the required operations.

- **Database Setup:** Ensure that you have a running SQL database and update the connection details in the `conn.java` file.
- **Database Operations:** The application performs CRUD (Create, Read, Update, Delete) operations on the employee data stored in the SQL database.

## Future Enhancements

To make the Workforce Navigator even more impressive, consider adding the following features in future updates:

- **Role-Based Access Control (RBAC):** Implement different user roles (e.g., Admin, Manager, Employee) with specific permissions and access levels.
- **Employee Attendance Tracking:** Add functionality to track and manage employee attendance, including clock-in and clock-out times.
- **Performance Reviews:** Include a module for conducting and storing performance reviews and feedback for employees.
- **Payroll Management:** Integrate payroll management features to handle salary calculations, deductions, and pay slips.
- **Reporting and Analytics:** Add detailed reporting and analytics to provide insights into employee data, attendance, and performance metrics.
- **Email Notifications:** Implement email notifications for important actions, such as adding a new employee or upcoming performance reviews.
- **Mobile Application:** Develop a companion mobile app to allow employees to access the system on the go.
- **Data Backup and Recovery:** Implement automated data backup and recovery solutions to protect against data loss.

## Contact

For any questions or suggestions, please contact:

- **Name:** Shamin Yasar
- **Email:** shaminyasar2001@gmail.com
- **Portfolio:** [here](https://shamin-portfolio.netlify.app/)
