Student Management System 
A simple Python-based Student Management System developed as a capstone project for the 
RITA Africa Python Fundamentals Course. 
This application allows secure login, student record management (CRUD), report generation, 
and file-based data persistence.


 Features 
Authentication System – Secure login with user accounts stored in users.txt 
Student Data Management – Add, view, search, update, and delete student 
records 
Report Generation – Generate basic reports on total students and grade 
distribution 
Activity Logging – Tracks user logins, logouts, and actions in activity_log.txt 
File-Based Storage – Data is stored in text files (students.txt, users.txt) for 
persistence


 Technologies Used 
• Python 3.x 
• File Handling (TXT) 
• Datetime module (for logging timestamps) 
• Getpass module (for hidden password entry)



Project Structure 
student_management_system/ 

│── main.py              # Main program (menu-driven interface) 
│── users.txt            # Stores usernames and passwords 
│── students.txt         # Stores student records 
│── activity_log.txt     # Stores user activity logs

