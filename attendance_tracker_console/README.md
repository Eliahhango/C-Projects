# Attendance Tracker Console

## Description
Menu-driven C program to register students, mark daily attendance, and show attendance percentage reports.

## Concepts Covered
- Input/Output (scanf, fgets, printf)
- Conditionals (if/else)
- Loops (while, for)
- Arrays and structs
- Functions and modular design
- Input validation

## Build
```bash
gcc main.c -o attendance_tracker_console
```

## Run
```bash
# Windows
.\attendance_tracker_console.exe
# Linux/macOS
./attendance_tracker_console
```

## Sample Output
```text
=== Attendance Tracker Console ===
1. Add Student
2. Mark Daily Attendance
3. View Attendance Report
4. Exit
Choose an option: 1
Enter student name: John Doe
Student added successfully.
Choose an option: 3
No.  Name                 Present    Total      Percent
1    John Doe             1          1          100.00%
```