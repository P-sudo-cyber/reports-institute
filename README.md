# reports-institute

Marking attendance in any classroom environment (face-to-face or online) is a critical requirement which is
often paper-based and prone to errors. Ensuring attendance of students are marked accurately is a legal and
social responsibility of the educational institution. With online learning becoming more and more popular,
managing students’ attendance (who is online, what time students joined the class, what time they left,
participation marks etc) has never been more important.   
 
You are required to create an Attendance System either as a website or as an App. The Attendance System
should have the following functionalities:  
1. Login option for Systems Administrators (E.g. Teachers, Admin Officers)
2. System Administrators can perform the following:
a) Create New class: Class details should include as a minimum: Class Id, Class Name, Class Start Time,
Class End Time, Class Break Duration, Class Teacher Id and Name
b) Edit class details
c) Create Students: Student details should include as a minimum: Student Id, Student First Name,
Student Last Name
d) Edit student details
e) Assigning teachers to classes
▪ A class can have only 1 teacher
▪ A teacher can be assigned to more than 1 classes but not at the same time. 
▪ If a teacher is assigned to more than 1 class at the same time, an error message will needto be displayed.
f) Assigning students to classes
▪ A class must have more than 1 student
▪ A student can be assigned to more than 1 class, but not at the same time. 
▪ If a student is assigned to more than 1 class at the same time, an error message will need
to be displayed.
g) Marking attendance
  ▪ System administrators should be able to mark attendance of students in classes. 
  ▪ Attendance should be marked by first searching for the class and then marking the attendance of the students in that class. 
  ▪ Once a class is searched, the following details should appear:
  ▪ The class details: ID, Start Time, End Time, Break Duration, Teacher ID, Teacher Name
  ▪ A list of students in the class with the class start time and end time next to each student. 
  ▪ The Start Time and End Time should default to the class Start Time and End Time. 
  ▪ The System Administrator should be able to edit the Start Time and End Time against each student. 
  ▪ Attendance can be marked as follows:
  ▪ Full attendance for the whole class. 
  This option allows the system administrator to select all students in one go in the class and mark them all as present.
  ▪ Full attendance for some students only. 
This option allows the system administrator to select specific students in the class and
mark them as present.
▪ Partial attendance for some students only. 
This option allows the system administrator to select specific students in the class and
mark them as partially present. 
For such attendance type, the start time and/or end time of the student must be changed.
This is because students either arrived late or left early or both. 
h) Reports
• A section for Reports should be available. In this section, System Administrators can access a
number of simple reports for e.g. 
▪ A list of students per class and their attendance details. 
▪ A list of classes assigned to each teacher including the Start Time and End Time of each
class.   
• System Administrators should either be able to have a print option for these reports. 
3. Validation rules should apply where possible. These could include
a) Checking that a teacher is assigned to only 1 class at a time. 
b) A student is only assigned to 1 class at a time. 
c) If a class cannot be found when searching. 
d) Appropriate messages need to be displayed for all validation checks. 
4. Additional tips: Make sure a proper name is given to your program. Keep it simple and neat. 
