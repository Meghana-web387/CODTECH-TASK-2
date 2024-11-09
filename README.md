Name:Meghana
Company:CODTECH IT SOLUTIONS 
ID:CT08DS9111 Domain:C++ Programming
Duration:October to November 2024 
Mentor:Neela Santhosh Kumar

Overview of this Project:

Project Structure
Student Class: This class represents each student, containing attributes for student ID, name, and grades, along with methods to manage and display individual student data.
StudentManagementSystem Class: Acts as the system’s controller, managing a list of students and providing functions to add, edit, delete, and view students.
Key Features
Add Students: Users can add a student by providing a unique ID and name. This information is stored in the system's student list.
Edit Student Information: Allows editing of a student’s name based on their ID, ensuring up-to-date records.
Delete Students: Users can delete a student’s record by their ID.
Manage Grades:
Add Grades: Adds individual grades for a student.
Calculate Average: Automatically calculates the average grade for each student when their information is displayed.
Display Student Records: Shows all student records in a formatted list, including IDs, names, and average grades. If there are no students, the system notifies the user.
User Interaction
The main interaction takes place in a command-line menu, which offers options to add, edit, delete, and view student records. Users can select an option by typing the corresponding number.

Example Use Cases
School or Classroom Management: Useful for small-scale student record-keeping in schools or individual classrooms.
Simple Grade Tracking: Allows teachers to keep track of grades for each student, automatically calculating the average for quick reference.
Key Benefits and Limitations
Benefits:
Simple, easy-to-use CLI interface.
Flexible and modifiable base for further enhancements.
Quick calculations of average grades.
Limitations:
Limited to command-line interface; lacks graphical features.
Basic functionality (no advanced search or sorting options).
Single-user access with no authentication or role management.
This project serves as a foundational program for managing student data and can be extended to include more sophisticated features, such as file storage, sorting options, or a graphical user interface (GUI).

OUTPUT:
Welcome to the Student Management System

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 1
Enter student ID: 101
Enter student name: Alice
Student added successfully.

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 1
Enter student ID: 102
Enter student name: Bob
Student added successfully.

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 4
Enter student ID to add grade: 101
Enter grade: 85
Grade added successfully.

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 4
Enter student ID to add grade: 102
Enter grade: 90
Grade added successfully.

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 5
Student List:
ID: 101, Name: Alice, Average Grade: 85
ID: 102, Name: Bob, Average Grade: 90

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 3
Enter student ID to delete: 101
Student deleted successfully.

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 5
Student List:
ID: 102, Name: Bob, Average Grade: 90

1. Add Student
2. Edit Student
3. Delete Student
4. Add Grade
5. Display All Students
6. Exit

Enter your choice: 6
Exiting the program.
