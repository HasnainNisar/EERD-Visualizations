University Management System
This project implements a comprehensive University Management System to efficiently handle various university operations. The system includes features for managing departments, employees, students, courses, and enrollments.

Key Components
Entities:
Department: Represents university departments. Attributes include department ID, name, and manager (employee ID).
Employee: Stores employee information (employee ID, name, position, contact details).
Student: Captures student details (student ID, name, major, enrollment date).
Course: Tracks course information (course ID, title, credits, instructor).
Enrollment: Records student enrollment in courses (enrollment ID, student ID, course ID).
Relationships:
Department manages Employees: One-to-many relationship. A department has one manager (employee) who oversees it.
Employee teaches Courses: One-to-many relationship. An employee (instructor) can teach multiple courses.
Student enrolls in Courses: Many-to-many relationship. Students can enroll in multiple courses, and each course has multiple students.
Constraints:
Ensure unique IDs for Departments, Employees, Students, and Courses.
Validate enrollment limits for courses.
Track student progress (completed courses, GPA).
System Users:
Admin User: Manages system-wide settings, user accounts, and course offerings.
Faculty User: Represents instructors who teach courses.
Student User: Accesses course registration, grades, and academic information.
Usage
Clone this repository.
Set up your database (MySQL, PostgreSQL, etc.).
Import the provided SQL schema.
Customize the system according to your university’s requirements.