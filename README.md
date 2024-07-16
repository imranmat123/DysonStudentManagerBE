# DysonStudentManagerBE

The DysonStudentManager Backend is a robust and scalable server-side application designed to support the management of student information for educational institutions. This project provides a RESTful API for handling various operations related to student profiles, courses, attendance, and meetings. Below is a brief description of the project's key features and technologies:

Key Features:

Student Profiles: Create, retrieve, update, and delete detailed student profiles, including personal information, academic records, and contact details.

Course Management: Manage courses by assigning students, tracking progress, and handling course schedules.

Attendance Tracking: Record and monitor student attendance, with capabilities to generate reports and insights.

One-on-One Meetings: Schedule and document one-on-one meetings between students and supervisors, tracking discussion points, action items, and follow-up tasks.

Grade Tracking: Maintain and update student grades, generating progress reports and analyzing academic performance.

User Authentication and Authorization: Implement secure login and role-based access control for administrators, teachers, and students using JWT (JSON Web Tokens).

Technologies Used:

Java: The primary programming language used for developing the backend services.

Spring Boot: A powerful framework for building production-ready applications in Java, used to create the RESTful API and manage the application's lifecycle.

Spring Security: A security framework that provides authentication and authorization services, integrated with JWT for secure user sessions.

Hibernate: An ORM (Object-Relational Mapping) framework for managing the database interactions in a more efficient and abstract way.

MySQL: A relational database management system used to store and manage student information, course details, attendance records, and meeting notes.

JWT (JSON Web Tokens): Used for secure user authentication and authorization, enabling safe transmission of user credentials and session information.

Maven: A build automation tool used for managing project dependencies and building the application.
