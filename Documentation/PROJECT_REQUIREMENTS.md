# Smart Attendance Management System

## Project Type
College-Wide Smart Attendance System

## Users
- Student
- Faculty
- Admin

## Student Features
- Student login using valid Roll Number and password
- View timetable/classes
- Live QR code scanning using camera
- No QR upload from gallery
- Live location verification
- Face verification and liveness verification
- Attendance result
- Attendance history
- Subject-wise attendance percentage

## Faculty Features
- Faculty login using valid Faculty ID and password
- View assigned subjects and classes
- Start attendance for each individual class
- Generate temporary dynamic QR
- View live attendance
- Close attendance session
- View attendance history
- Generate attendance reports

## Admin Features
- Manage students
- Manage faculty
- Manage departments
- Manage subjects
- Manage sections
- Manage classrooms
- Manage timetable
- Assign faculty to subjects/classes
- View college-wide attendance
- Manage system users

## Attendance Verification
Attendance is marked only when:

1. Student has a valid account
2. Student scans the QR using the live camera
3. QR belongs to the current class session
4. QR has not expired
5. Student is within the permitted attendance location
6. Face matches the registered student
7. Liveness verification succeeds
8. Student has not already been marked for that class

## Attendance
Attendance is taken separately for every class/session.

## Technology
- Student App: Android
- Student App Language: Java
- Backend: Java + Spring Boot
- Database: MySQL
- Faculty Dashboard: Web
- Admin Dashboard: Web
- API: REST API
- Version Control: Git + GitHub

## Project Goal
Build a secure, scalable and reliable attendance system that can be used by the entire college.