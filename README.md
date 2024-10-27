# PSG eCAMPUS LITE

## Overview
The **PSG eCAMPUS LITE** project aims to recreate the functionality of the existing eCampus website of PSG College of Technology through a simplified, object-oriented software application. This implementation focuses on managing essential student information and academic activities, providing a user-friendly interface while adhering to core principles of **Object-Oriented Programming (OOP)**.

The project seeks to replicate the primary features of the original eCampus platform, including student information management, course enrollment, attendance tracking, and performance evaluation. By utilizing OOP concepts such as encapsulation, inheritance, and polymorphism, the application is designed to be modular and maintainable, facilitating future enhancements.

## Key Features

### Key Classes
- **Person Class**  
  This foundational class encapsulates attributes common to all users, such as roll number, name, email, phone number, department, resident status, and password management functions. It provides methods for displaying personal details and verifying passwords.

- **Student Class**  
  Inheriting from the Person class, this specialized class adds attributes specific to students, including batch and program details. It includes methods for viewing timetables, attendance records, continuous assessment marks (CA Marks), and semester results. This use of inheritance promotes code reuse and clarity in the hierarchy of attributes and functionalities.

### Core Features
- **Course Management**  
  The application dynamically assigns courses based on the student's roll number classification, ensuring that students can access relevant course information tailored to their specific department.

- **Attendance Tracking**  
  Attendance data is managed through file handling techniques that allow students to view their attendance records efficiently. The application reads from external files to retrieve attendance information linked to each student.

- **Performance Evaluation**  
  Students can view their CA Marks through dedicated methods that process data from external files.

## Conclusion
The **PSG eCAMPUS LITE** project recreates the key functions of the eCampus website for PSG College of Technology using object-oriented programming. It focuses on important academic features in a straightforward design, meeting current needs and allowing for future improvements.

---
