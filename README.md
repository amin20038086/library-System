# Library Management System

Welcome to the **Library Management System**, a web-based platform designed to simplify and enhance library operations. This project consists of an Angular frontend integrated with a Spring Boot backend to provide a seamless user experience.

---

## Features

- 📚 **Manage Books**:
  - Add, Edit, Delete, and View books.
- 👥 **Manage Authors and Categories**:
  - Add, Edit, and Delete authors and book categories.
- 📈 **Reports and Insights**:
  - View detailed reports and gain insights about library performance.
- 🔒 **User Authentication**:
  - Secure login portal for administrators.

---

## Technologies Used

- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: MySQL (or H2 for testing)
- **CSS**: Custom design for a professional look
- **Version Control**: Git and GitHub

---

## Installation and Usage

### **Prerequisites**
Ensure you have the following installed:
1. **Node.js** (v14 or higher): [Download Node.js](https://nodejs.org)
2. **Angular CLI** (latest):
   ```bash
   npm install -g @angular/cli
Java JDK (v17 or higher): Download JDK
Maven (latest): Download Maven
How to Run the Application
1. Clone the Repository
Clone this repository to your local machine:


git clone https://github.com/<your-username>/LibraryManagementSystem.git
cd LibraryManagementSystem
2. Run the Backend (Spring Boot)
Navigate to the backend folder:

cd backend
Open the backend in your IDE (e.g., IntelliJ IDEA, Eclipse) and configure the database:

spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.h2.console.enabled=true
Build and run the Spring Boot application:

mvn spring-boot:run
Verify the backend is running by visiting:

http://localhost:9080/login

3. Run the Frontend (Angular)
Navigate to the frontend folder:


cd ../frontend
Install the required dependencies:


npm install
Start the Angular development server:

ng serve
Open your browser and visit:
arduino

http://localhost:4200



4. Access the Application
The frontend home page will display features and a button to access the backend login.
Click "Access Library Portal", and it will redirect you to:

http://localhost:9080/login

Log in with the default admin credentials:
Username: admin@admin.in
Password: Temp123
Folder Structure

LibraryManagementSystem/
├── backend/               # Spring Boot backend code
│   ├── src/
│   └── pom.xml            # Maven configuration file
├── frontend/              # Angular frontend code
│   ├── src/
│   └── angular.json       # Angular configuration file
└── README.md              # Documentation

Future Enhancements
🌟 User Roles:
Add different user roles (e.g., Librarian, Member).
📊 Advanced Reporting:
Include graphical reports for better insights.
🌐 Cloud Deployment:
Deploy the app on AWS, Azure, or Heroku.


Troubleshooting
Backend Issues
Port Conflict: Ensure no other application is using port 9080.
Database Connection: Check the database configuration in application.properties.
Frontend Issues
Dependencies: Ensure all dependencies are installed with npm install.
CORS Error: Verify that CORS is enabled in the backend.
