# Study-Life-Management-System-C-
Study Life Management System (C++)  A console-based C++ application to help students manage their academic life.
Welcome to Student Manager 1.0! This guide will help you understand and use the program, whether you're a student, teacher, or administrator.
Getting Started
1.	Launch the Program: When you run the program, you'll see an animated title "STUDENT MANAGER 1.0" and a loading bar.
2.	Login Screen: After the loading bar, you'll be prompted to log in. You need to enter your role (admin, teacher, or student), your ID, and your password. 
o	If you are a new user: You will need to be registered by an administrator first.
Main Menu - Depending on Your Role
Once you log in, the program will present a menu specific to your role.
________________________________________
1. Student Menu
If you log in as a "student," you'll see these options:
•	1. View Assignment Reminders: 
o	What it does: This option checks for any assignments that are due within the next 24 hours. It's like having a digital reminder for your upcoming deadlines.
o	How to use: Select "1" and press Enter. The program will display any urgent assignments or tell you if you're all caught up.
•	2. Add Expense: 
o	What it does: This allows you to record your expenses. You can enter a description of what you spent money on and the amount.
o	How to use: Select "2" and press Enter. The program will ask for a "Description" (e.g., "Lunch," "Textbook") and then the "Amount" (e.g., "15.50").
•	3. Trip Manager: 
o	What it does: This helps you keep track of any trips you're planning. You can enter the destination and the date of your trip.
o	How to use: Select "3" and press Enter. You'll be prompted for the "Destination" (e.g., "Lahore") and the "Date (YYYY-MM-DD)" (e.g., "2025-06-15").
•	4. Show All Assignments: 
o	What it does: This option displays a list of all assignments that have been uploaded, regardless of their deadline.
o	How to use: Select "4" and press Enter. You'll see the title, deadline, and who uploaded each assignment.
•	0. Logout: 
o	What it does: This exits you from the student menu and takes you back to the main login screen.
o	How to use: Select "0" and press Enter.
________________________________________
2. Teacher Menu
If you log in as a "teacher," you'll see these options:
•	1. Upload Assignment: 
o	What it does: This is where teachers can add new assignments for students. You'll need to provide the assignment's title and its deadline.
o	How to use: Select "1" and press Enter. Enter the "Title" of the assignment (e.g., "Math Homework Chapter 5") and the "Deadline (YYYY-MM-DD HH:MM)" (e.g., "2025-06-10 17:00").
•	2. Show All Assignments: 
o	What it does: Similar to the student's option, this shows a list of all uploaded assignments.
o	How to use: Select "2" and press Enter.
•	0. Logout: 
o	What it does: This exits you from the teacher menu and takes you back to the main login screen.
o	How to use: Select "0" and press Enter.
________________________________________
3. Admin Menu
If you log in as an "admin," you have more control and will see these options:
•	1. Show All Assignments: 
o	What it does: Displays all uploaded assignments.
o	How to use: Select "1" and press Enter.
•	2. Show All Trips: 
o	What it does: This option shows a list of all trips that students have recorded in the system.
o	How to use: Select "2" and press Enter. You'll see the User ID, Destination, and Date for each trip.
•	3. Add Teacher: 
o	What it does: This allows an administrator to create a new teacher account. You'll need to provide a new ID and password for the teacher.
o	How to use: Select "3" and press Enter. Enter the "ID" and "Password" for the new teacher.
•	4. Add Student: 
o	What it does: This allows an administrator to create a new student account. You'll need to provide a new ID and password for the student.
o	How to use: Select "4" and press Enter. Enter the "ID" and "Password" for the new student.
•	0. Logout: 
o	What it does: This exits you from the admin menu and takes you back to the main login screen.
o	How to use: Select "0" and press Enter.
________________________________________
Important Notes:
•	Input Format: When entering dates, make sure to follow the specified format (e.g., YYYY-MM-DD for trips, YYYY-MM-DD HH:MM for assignment deadlines).
•	Case Sensitivity: User IDs and passwords are case-sensitive.
•	Saving Data: The program automatically saves your data to text files (e.g., users.txt, assignments.txt).
•	Exiting the Program: To completely exit the program from the main login screen, type "exit" when prompted for your role.
We hope this manual makes using Student Manager 1.0 easy and efficient for you!

