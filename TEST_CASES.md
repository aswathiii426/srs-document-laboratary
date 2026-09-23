# Test Cases – Student Management System

## 1. Introduction

The following test cases are prepared for the Student Management System to verify whether the specified system functions work as expected.

## 2. Test Case Table

| Test Case ID | Test Case                     | Input                                              | Expected Result                                         | Status |
| ------------ | ----------------------------- | -------------------------------------------------- | ------------------------------------------------------- | ------ |
| TC01         | Valid User Login              | Valid username and password                        | User should be successfully logged in                   | Pass   |
| TC02         | Invalid User Login            | Invalid username or password                       | System should display an error message                  | Pass   |
| TC03         | Add Student                   | Valid student ID, name, course and contact details | New student record should be added                      | Pass   |
| TC04         | Add Student with Missing Data | Student details with required field empty          | System should display a validation message              | Pass   |
| TC05         | Update Student                | Existing student details with updated information  | Student record should be updated successfully           | Pass   |
| TC06         | Delete Student                | Select an existing student record                  | Student record should be deleted                        | Pass   |
| TC07         | View Student Details          | Select a valid student                             | Student information should be displayed                 | Pass   |
| TC08         | Search Student by ID          | Enter valid student ID                             | Corresponding student record should be displayed        | Pass   |
| TC09         | Search Student by Name        | Enter valid student name                           | Matching student record should be displayed             | Pass   |
| TC10         | Search Invalid Student        | Enter an invalid student ID or name                | System should display "Student not found"               | Pass   |
| TC11         | Record Attendance             | Enter valid attendance information                 | Attendance should be stored successfully                | Pass   |
| TC12         | Update Attendance             | Modify an existing attendance record               | Updated attendance should be saved                      | Pass   |
| TC13         | Enter Marks                   | Enter valid marks for a student                    | Marks should be stored successfully                     | Pass   |
| TC14         | Invalid Marks                 | Enter marks outside the permitted range            | System should display a validation message              | Pass   |
| TC15         | View Marks                    | Student logs in and selects marks                  | Student's marks should be displayed                     | Pass   |
| TC16         | View Attendance               | Student logs in and selects attendance             | Student's attendance should be displayed                | Pass   |
| TC17         | Generate Report               | Select required student/academic information       | Appropriate report should be generated                  | Pass   |
| TC18         | Unauthorized Access           | User attempts to access restricted information     | System should deny unauthorized access                  | Pass   |
| TC19         | Logout                        | Logged-in user selects logout                      | User should be logged out successfully                  | Pass   |
| TC20         | Empty Search                  | Search without entering a value                    | System should display an appropriate validation message | Pass   |

## 3. Conclusion

The test cases verify the major functional requirements of the Student Management System. They can be used to check login, student record management, attendance, marks, searching, reporting and access control functions.
