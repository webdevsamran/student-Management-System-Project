Student Management System Project in Codeigniter

Free Download Student Management System Project in Codeigniter
College Management System project is a smart and effective way to store records of the student on the basis of college and moderators of that college. The main target of this project is to target the student information according to the college moderators i.e. Moderator of different colleges have different students with different courses.
It's just like college is having different branches of college and those branches having college moderators. Admin is the overall head in the hierarchy and controls all the record and builds up the data and maintains it.


Project Overview
This project completely functions for showing it as a prototype to anyone or to showcase in college projects. Features in the project include registering the Admin, Login Features, Adding Co-admin/moderators, Adding College, Adding Student, View Students of particular college which is governed by the moderator, View Students details, Edit/Modify the student, Delete Student from the record. The main activity is focused for the admin only who is like a chairman to all the organization and setup the data.



Features Hierarchy
Admin Control Structure

Add Co-Admin / Moderator
View Moderators
Add College
Add Student
View College Students
View Students Details
Edit Students Details
Delete Student
Login/Logout
Moderator Control Structure




Login
View all students Record added by admin
Logout
Control Structure and Working:
Administrator is like a head for all this who is managing up all the details in the work and managing the records actively. Admin can be registered from the home page i.e. the first page of the project. After Registering, admin can login to the web and is displayed with a dashboard which includes a navbar having a settings dropdown menu. In the dropdown menu, three links are provided.

Dashboard: Which takes admin back to the admin dashboard where ever admin is.
Moderator: To view all moderators added for particular college.
Logout: Logout from the dashboard.
After the navbar link Admin is displayed with a welcome message and under welcome message there include three buttons.

Add College : Add college to the database so that it can be dynamically fetched from the database for student college information. Add College Form input includes:
Adding college name
Adding college branch
Add Moderator : Add a moderator for a particular college that means a head of that college. Add Moderator form input includes:
Add Username
Add College name(Dynamically loaded from database)
Email
Gender
Role(Dyanamically loaded from database with role id)
Password
Confirm Password
Add Student : Add Student to the record with different college. Add Student form input includes:
Add Student Name
Add College name(Dynamically loaded from database)
Email
Gender
Course