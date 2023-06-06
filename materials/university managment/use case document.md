Use Case Document: University Management Application

1. Use Case: Student Enrollment

**Actor:** Student

**Description:** The student enrolls in a course through the university management application.

**Pre-conditions:**
- The student is authenticated and authorized to access the application.
- The student has selected a course to enroll in.

**Post-conditions:**
- The student is enrolled in the selected course.
- The student's enrollment is recorded in the system.

**Steps:**
1. The student logs in to the university management application.
2. The student navigates to the course enrollment page.
3. The student selects the course they want to enroll in.
4. The system displays the course information and enrollment requirements.
5. The student confirms their enrollment in the course.
6. The system verifies the student's eligibility and availability for the course.
7. If the student is eligible and the course is available, the system enrolls the student in the course.
8. The system sends a confirmation email to the student and updates the student's enrollment status in the system.

2. Use Case: Attendance Tracking

**Actor:** Faculty Member

**Description:** The faculty member tracks attendance for a class through the university management application.

**Pre-conditions:**
- The faculty member is authenticated and authorized to access the application.
- The class session is in progress.

**Post-conditions:**
- The attendance data is recorded in the system.

**Steps:**
1. The faculty member logs in to the university management application.
2. The faculty member navigates to the attendance tracking page.
3. The faculty member selects the class session they want to track attendance for.
4. The system displays a list of enrolled students in the class.
5. The faculty member marks each student as present or absent.
6. The system updates the attendance data for the selected class session.
7. The system sends a notification to the students who were marked absent.

3. Use Case: Course Grades Management

**Actor:** Faculty Member

**Description:** The faculty member manages course grades for a class through the university management application.

**Pre-conditions:**
- The faculty member is authenticated and authorized to access the application.
- The grading period for the course has started.

**Post-conditions:**
- The course grades are recorded in the system.

**Steps:**
1. The faculty member logs in to the university management application.
2. The faculty member navigates to the course grades page.
3. The faculty member selects the course they want to manage grades for.
4. The system displays a list of enrolled students in the course.
5. The faculty member enters the grades for each student in the course.
6. The system calculates and displays the course grade for each student.
7. The system updates the course grade data in the system.
8. The system sends a notification to the students regarding their updated course grade.

4. Use Case: View Course Material

**Actor:** Student

**Description:** The student accesses the course material provided by the lecturer.

**Pre-conditions:** The student is logged into their account and has enrolled in the course.

**Post-conditions:** The student has viewed the course material.

**Steps:**
1. The student navigates to the course dashboard.
2. The student selects the course they want to view the material for.
3. The student selects the "Course Material" tab.
4. The student browses the available material.
5. If desired, the student can download the material.

5. Use Case: Generate Reports

**Actor:** Administrator

**Description:** The administrator generates reports on student progress and enrollment.

**Pre-conditions:** The administrator is logged into their account and has access to the necessary permissions.

**Post-conditions:** The administrator has generated the desired report.

**Steps:**
1. The administrator navigates to the "Reports" section.
2. The administrator selects the type of report they want to generate.
3. The administrator selects the parameters for the report, such as the date range or specific courses.
4. The system generates the report and displays it to the administrator.
5. If desired, the administrator can download the report.