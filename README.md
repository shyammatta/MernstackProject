EmployeeHub

Description:

The Employee Management System is a web application built using the MERN stack (React, Node.js, Express.js, and MongoDB). It provides an intuitive interface for managing employees. Key features include employee login, a dashboard with various sections, and options to create, view, edit, and delete employee details.

Key Features:
Employee Login: Secure login for employees.
Dashboard: Displays the employee username and provides access to key sections like Home, Employee List, and Logout.
Employee List: View all employee details in a structured list.
Create Employee: Add a new employee using a simple form.
Edit Employee: Update existing employee details.
Delete Employee: Remove an employee from the system.

Table of Contents:
Installation
Usage
Features
Technologies Used
Contributing
License

Installation:

Prerequisites
Node.js (v14 or higher)
MongoDB

Steps:

1. Clone the repository:
   git clone https://github.com/shyammatta/MernstackProject
   cd employee-management-system
2. Install backend dependencies:
   cd server
   npm install
3. Install frontend dependencies:
   cd ../client
   npm install
4. Configure environment variables:
   Create a .env file in the server directory with the following:
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
5. Start the backend server:
   cd ../server
   npm start

Start the frontend development server:
cd ../client
npm start 7. Access the application at http://localhost:3000.

Usage:

1. Login: Enter employee credentials to log in.
   Dashboard: Navigate to the home page, employee list, or logout.
2. Employee List:
   View all employees in a table format.
   Use the Create Employee button to add a new employee.
   Click Edit to modify employee details.
   Click Delete to remove an employee.

Features:
Secure login system.
Employee dashboard with intuitive navigation.
Add, view, edit, and delete employee details.
Responsive design for seamless use across devices.
Technologies Used
Frontend: React, React Router, Axios
Backend: Node.js, Express.js
Database: MongoDB
Other Tools: JSON Web Token (JWT) for authentication

Contributing:

1. Fork the repository.
2. Create a new branch: git checkout -b feature-name.
3. Make changes and commit: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.

License:

This project is licensed under the MIT License. See the LICENSE file for more details.
