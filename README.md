# Student Attendance Tracker

This project is a simple web application for tracking student attendance. It allows the user to mark attendance for students, view a report of attendance statuses, and export the attendance data as an Excel file.

## Features

- *Mark Attendance*: Allows the user to mark whether a student is "Present" or "Absent" using a dropdown menu.
- *Attendance Report*: Displays a table showing the student ID, name, and their attendance status (Present or Absent).
- *Export to Excel*: Provides an option to export the attendance report as an Excel file for further use.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. *Mark Attendance*: 
   - Go to the "Mark Attendance" section.
   - For each student, select either "Present" or "Absent" from the dropdown menu.
   
2. *View Attendance Report*: 
   - After marking attendance, go to the "Attendance Report" section to view the current attendance status for each student.

3. *Export Attendance*: 
   - Click the "Export as Excel" button in the "Attendance Report" section to download the attendance data as an Excel file.

## Code Explanation

- The markAttendance(studentId, status) function is called whenever the attendance status of a student is changed.
- The updateReport() function dynamically updates the attendance report by reading the attendanceData object, which stores each student's attendance status.
- The exportToExcel() function generates an Excel file from the HTML table containing the attendance report.
