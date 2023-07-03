# College-ManagementThis is a College Management System built using Python and MySQL. It provides functionalities for administrators, teachers, and students to manage various aspects of college operations, including user registration, account deletion, and login authentication.

Prerequisites
Python 3.x
MySQL

Setup

Clone the repository:
git clone https://github.com/your-username/college-management-system.git
Import the college.sql file into your MySQL database to create the required tables and schema.

Update the MySQL connection details in the code:

host = "localhost"
user = "your-username"
password = "your-password"
database = "college"
Replace your-username and your-password with your MySQL credentials.

Run the main Python script:

python college_management_system.py

Features
Student Registration: Administrators can register new students by providing a username and password. The student is then added to the database.
Teacher Registration: Administrators can register new teachers by providing a username and password. The teacher is then added to the database.
Student Account Deletion: Administrators can delete existing student accounts by specifying the student's username. The corresponding record is removed from the database.
Teacher Account Deletion: Administrators can delete existing teacher accounts by specifying the teacher's username. The corresponding record is removed from the database.
Admin Login: Administrators can log in with the admin credentials to access administrative functionalities.
Student and Teacher Login: Students and teachers can log in to the system using their respective credentials (not implemented yet).

Usage

Upon running the script, you will be prompted with a menu to select your user type.
Select option 1 to log in as a student (not implemented yet).
Select option 2 to log in as a teacher (not implemented yet).
Select option 3 to log in as an admin. You will be prompted to enter the admin username and password. Use "admin" for both username and password.
Once logged in as an admin, you will have access to the admin functionalities.
Follow the prompts to register new students, register new teachers, delete existing student accounts, or delete existing teacher accounts.
To exit the admin session, select option 5.

Contribution

Contributions to the College Management System are welcome. If you encounter any issues or have suggestions for improvements, please create a new issue or submit a pull request.

License
This project is licensed under the MIT License.
