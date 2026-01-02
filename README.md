🎓 Student Management System – Java JDBC Project
A console-based Student Management System developed using Java, JDBC, MySQL and Maven.
This project helps in managing student records digitally and supports full CRUD operations.

📌 Features
Add new student
View all students
Update student details
Delete student record
Count total students
Calculate average age of students
Menu driven console interface
MySQL database connectivity using JDBC

🛠 Technologies Used
Technology	Description
Java	Core backend logic
JDBC	Database connectivity
MySQL	Database
Maven	Dependency management
GitHub	Version control
IntelliJ / Eclipse	IDE

🗂 Project Structure
Student-Management-System
│
├── src/main/java
│   ├── DBConnection.java
│   ├── Student.java
│   ├── StudentDAO.java
│   └── Main.java
│
├── database_script.sql
├── pom.xml
└── README.md

🧩 Database Setup
Create database in MySQL:

CREATE DATABASE studentdb;
USE studentdb;

CREATE TABLE student (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100),
    email VARCHAR(100)
);

⚙ How to Run the Project
Clone the repository:
git clone
Open project in IntelliJ / Eclipse

Update MySQL credentials in DBConnection.java:
String url = "jdbc:mysql://localhost:3306/studentdb";
String user = "root";
String password = "your_password";
Run Main.java

📸 Sample Output
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Count Students
6. Average Age
7. Exit

📈 Future Enhancements
GUI using JavaFX

User authentication

Export data to Excel / PDF

Convert to web application using Spring Boot

Cloud database support

👨‍💻 Author
Satvir Singh
B.Tech Student









