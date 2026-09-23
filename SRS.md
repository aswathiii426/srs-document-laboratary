# Software Requirements Specification

## 1. Introduction

### 1.1 Purpose

### 1.2 Scope

### 1.3 Definitions and Abbreviations

### 1.4 References

## 2. Overall Description

### 2.1 Product Perspective

### 2.2 Product Functions

### 2.3 User Classes

### 2.4 Operating Environment

### 2.5 Constraints

### 2.6 Assumptions and Dependencies

## 3. Specific Requirements

### 3.1 Functional Requirements

### 3.2 Non-Functional Requirements

### 3.3 External Interface Requirements

## 4. System Requirements

### 4.1 Hardware Requirements

### 4.2 Software Requirements

## 

## 5. System Models

## 6. Conclusion
# Software Requirements Specification

## 1. Introduction

### 1.1 Purpose

The purpose of this Software Requirements Specification (SRS)
document is to describe the requirements of the Student Management
System. The document identifies the functional and non-functional
requirements, users, system constraints, and other requirements
needed for developing the proposed system.

### 1.2 Scope

The Student Management System is designed to manage student
information in an organized and efficient manner. The system
provides facilities for storing, updating, searching and retrieving
student details. It can also manage academic information such as
attendance and marks.

The system is intended to reduce manual record keeping and make
student information easier to manage and access by authorized users.

### 1.3 Definitions and Abbreviations

SRS – Software Requirements Specification

SMS – Student Management System

User – A person who interacts with the system.

Administrator – A person responsible for managing the system.
## Problem Statement

Managing student information manually can be time-consuming and
may lead to difficulties in storing, updating and retrieving
records. Maintaining student details, attendance and marks using
manual records can also make information management inefficient.

Therefore, a Student Management System is proposed to provide an
organized method for storing, managing and retrieving student
information. The system will help authorized users manage student
records efficiently.
### 3.1 Functional Requirements

The functional requirements describe the functions that the
Student Management System shall provide to its users.

#### FR1 – User Login

The system shall allow authorized users to log in using a valid
username and password.

#### FR2 – Add Student

The system shall allow the administrator to add new student
information such as student name, roll number, course and contact
details.

#### FR3 – Update Student

The system shall allow the administrator to update existing
student information.

#### FR4 – Delete Student

The system shall allow the administrator to delete student
records when required.

#### FR5 – View Student Details

The system shall allow authorized users to view student
information.

#### FR6 – Search Student

The system shall allow users to search for student records using
details such as student ID or name.

#### FR7 – Manage Attendance

The system shall allow authorized teachers or administrators to
record and update student attendance.

#### FR8 – Manage Marks

The system shall allow authorized teachers or administrators to
enter and update student marks.

#### FR9 – View Academic Information

The system shall allow students to view their marks and attendance
information.

#### FR10 – Generate Reports

The system shall allow authorized users to generate student
academic and attendance reports.
### 2.3 Stakeholders

The main stakeholders of the Student Management System are:

#### 1. Administrator

The administrator manages the overall system. The administrator
can add, update, delete and view student information and manage
user access.

#### 2. Teacher

The teacher uses the system to manage student academic information,
including attendance and marks.

#### 3. Student

The student uses the system to view personal information, marks,
attendance and other academic details.

#### 4. System Administrator

The system administrator is responsible for maintaining the
software system, database and user access.
### 2.4 Stakeholder Requirements

- The administrator shall be able to manage student records.
- The teacher shall be able to manage attendance and marks.
- The student shall be able to view academic information.
- The system administrator shall be able to maintain the system
  and manage authorized access
  Performance

### 3.2 Non-Functional Requirements

Non-functional requirements describe the quality, performance,
security and other characteristics of the Student Management System.

#### NFR1 – Performance

The system shall respond to user requests within a reasonable
amount of time and should provide quick access to student records.

#### NFR2 – Security

The system shall provide secure login and authentication.
Only authorized users shall be allowed to access restricted
student information.

#### NFR3 – Usability

The system shall provide a simple, clear and user-friendly
interface so that students, teachers and administrators can
use the system easily.

#### NFR4 – Reliability

The system shall operate reliably and should minimize data loss
during normal operation.

#### NFR5 – Availability

The system should be available to authorized users whenever
the system is required for normal academic activities.

#### NFR6 – Maintainability

The system shall be designed so that software updates,
maintenance and modifications can be performed easily.

#### NFR7 – Scalability

The system should be capable of handling an increasing number
of students, users and academic records.

#### NFR8 – Data Integrity

The system shall maintain accurate and consistent student,
attendance and academic information.

#### NFR9 – Backup and Recovery

The system should provide suitable mechanisms for backing up
important data and recovering information in case of data loss.

#### NFR10 – Compatibility

The system should be compatible with the required operating
system, database and web browser or application environment.

## 4. System Requirements

### 4.1 Hardware Requirements

The minimum hardware requirements required for the Student
Management System are:

| Component | Minimum Requirement |
|-----------|---------------------|
| Processor | Intel Core i3 or equivalent |
| RAM | 4 GB |
| Storage | 10 GB available space |
| Keyboard | Standard keyboard |
| Mouse | Standard mouse |
| Display | 1366 × 768 resolution or above |
| Network | Internet/LAN connection when required |
### 4.2 Software Requirements

The software requirements for the Student Management System are:

| Software | Requirement |
|----------|-------------|
| Operating System | Windows / Linux |
| Programming Language | Java / Python / PHP |
| Database | MySQL |
| Web Browser | Google Chrome / Mozilla Firefox |
| Development Environment | VS Code / IntelliJ IDEA / Eclipse |
| Database Management Tool | MySQL Workbench / phpMyAdmin |
## 5. Constraints and Assumptions

### 5.1 Constraints

The following constraints apply to the Student Management System:

1. **Authentication Constraint**  
   Only authorized users shall be allowed to access protected
   student information.

2. **Data Accuracy Constraint**  
   The information entered into the system should be accurate
   and complete.

3. **Hardware Constraint**  
   The system requires a computer or suitable device with the
   minimum hardware configuration specified in the SRS.

4. **Software Constraint**  
   The system depends on the specified operating system,
   programming environment, database and other required software.

5. **Database Constraint**  
   The system requires a properly configured database for storing
   student information.

6. **Network Constraint**  
   If the system is implemented as a web-based or network-based
   application, a reliable network connection may be required.

7. **Access Constraint**  
   Users can access only the features and information permitted
   according to their roles.

8. **Maintenance Constraint**  
   Regular maintenance and database management may be required
   to ensure proper operation of the system.
### 5.2 Assumptions

The following assumptions are made for the Student Management System:

1. Users have basic knowledge of using computers and the system.

2. Authorized users have valid login credentials.

3. The student information entered into the system is correct.

4. The required hardware and software are available.

5. The database is properly configured and accessible.

6. Regular backups of important student information are maintained.

7. The system administrator is responsible for maintaining user
   accounts and system resources.

8. Teachers and administrators enter academic information correctly.

9. Students use the system only for authorized purposes.

10. The system will be used according to the defined requirements
    and user roles.
1.4 References 
Software Requirements Specification guidelines
Software Engineering course materials
Laboratory requirements and project specifications
