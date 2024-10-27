# PSG eCAMPUS LITE

## Overview
The **PSG eCAMPUS LITE** project aims to streamline and enhance the essential features of the existing eCampus website at PSG College of Technology. Our goal is to simplify how students and faculty manage academic information and activities while embracing the principles of **Object-Oriented Programming (OOP)** to ensure a robust and maintainable system.

## Objective
We set out to recreate the core functionalities of the original eCampus platform, such as managing student information, enrolling in courses, tracking attendance, and evaluating academic performance. By leveraging OOP concepts like encapsulation, inheritance, and polymorphism, we've crafted an application that is modular and flexible enough for future enhancements.

## Object-Oriented Design
### Key Classes
- **Person Class**  
  At the heart of our system, the Person class holds common attributes for all users—such as roll number, name, email, phone number, department, resident status, and password management. It includes methods for displaying personal details and verifying passwords, making it easy for users to manage their information.

- **Student Class**  
  Building on the Person class, this specialized class adds specific details for students, including batch and program information. It features methods that allow students to check their timetables, attendance records, continuous assessment marks, and semester results. This design promotes clarity and reusability, making our codebase cleaner and more intuitive.

## Core Features
- **Course Management**  
  Our application intelligently assigns courses based on a student’s roll number and department, ensuring that each student has access to relevant courses tailored to their academic journey.

- **Attendance Tracking**  
  Managing attendance is made simple through effective file handling techniques. Students can easily view their attendance records, with the application efficiently retrieving this data from external files.

- **Performance Evaluation**  
  Students can check their Continuous Assessment (CA) Marks through user-friendly methods that process information seamlessly from external sources.

## Conclusion
The **PSG eCAMPUS LITE** project represents a significant step forward in modernizing the academic experience at PSG College of Technology. By focusing on essential management features within a modular design, we address the current needs of students and administrators while laying the groundwork for future innovations in educational software. We are excited about the possibilities ahead and committed to creating a platform that enhances learning and administrative efficiency.
