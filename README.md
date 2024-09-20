Overview
This repository contains a student management application developed by Aryan Kashyap as part of an Advanced Programming Project for Chandigarh University 2023. The project utilizes Java for the backend and Flutter for the mobile application. It offers functionalities for managing students, teachers, courses, and assignments.

Features
CLI Application
Admin Menu:
Add/Remove students, teachers, classes, and assignments
Modify assignments, classes, student, and teacher data
Teacher Menu:
Add/Remove students from classes
Add/Remove assignments from classes
Modify assignments and student data
Mobile Application
Welcome Page: Navigation to login and sign-up
Sign Up & Login: User authentication
User Info: Avatar upload, account deletion, and password change
Home Screen: Summary of student records and assignments
To-Do List: Task management for students
Classes: Class management interface for teachers
News: University news and announcements
Assignments: Detailed assignment listings
Backend
Server:
Handles multiple client requests using Socket connections and multithreading
Technologies
Backend: Java
Frontend: Flutter and Dart
Installation
Prerequisites
Java Development Kit (JDK)
Flutter SDK
Usage
Running the CLI
Compile and run the main application:
bash
Copy code
cd src
javac Main.java
java Main
Running the Backend
Compile and run the Java server:
bash
Copy code
cd src/Server
javac Server.java
java Server
Running the Mobile App
Open the Flutter project in an IDE (e.g., Android Studio).
Run the app on an emulator or a physical device.
