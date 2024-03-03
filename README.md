Menu:
a) Mark Attendance
b) Manage Timetables
c) Submit/Check Assignments
d) Display
e) Exit

Mark Attendance: User_Input == 'a'
-	Enter Course_ID (check if Course_ID is correct)
-	Enter Student_ID (check if Student_ID is correct)(check if Student_ID exists inside the course file)
-	Check time (if within 15 minutes after class time, present)

Manage Timetables: User_Input == 'b'
-	Creat timetable (Select Course and time)
-	Update timetable (Change Course time)
-	Delete timetable (Drop classes)

Submit/Check Assignments: User_Input == 'c'
-	Enter Course_ID and Student_ID (check if student is in the course)
-	Show status/Submit assignment/Edit status
-	IF Edit status, enter Staff_ID (check if ID exists)

Display: User_Input == 'd'
-	Enter Student_ID to get:
•	Attendance percentage
•	Timetable
•	Submission status (for each course)

Exit:
-	Loop until User_Input == 'e'
