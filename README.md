# Attendance & CGPA Management System

This project is a student data dashboard built with HTML, CSS, and JavaScript. It helps track and visualize student attendance, performance, and CGPA trends in a simple web interface.

## Project Overview

The application is designed for educational use and includes:
- Student login and registration pages
- Attendance tracking dashboard
- Subject-wise attendance reporting
- CSV import and export
- CGPA calculator and semester-wise analysis
- Student performance visualization

## Project Structure

- `attendance_dashboard.html` — main attendance dashboard / home page for the system
- `landing_page.html` — landing page for Data Visualizer
- `features_page.html` — feature showcase page
- `student_login.html` — login form for registered users
- `student_register.html` — registration form for new users
- `cgpa_calculator.html` — semester-wise CGPA tracker and analysis dashboard

## Main Features

### 1. Student Registration and Login
Users can create an account with username, email, and password. Login uses browser localStorage to validate the stored credentials.

### 2. Attendance Management System
The attendance dashboard allows users to:
- Add student records
- Enter roll number and student name
- Select date and subject
- Mark attendance as present or absent
- Search students by roll number
- Bulk mark attendance for a subject
- Download attendance data as CSV
- Import CSV files into the system
- Clear all stored data when needed

### 3. Reports and Statistics
The system calculates:
- Total students
- Present and absent counts
- Attendance percentages
- Subject-wise totals
- Defaulter analysis
- Visual charts for attendance insights

### 4. CGPA Tracker
The CGPA calculator supports:
- Adding student names and GPA values by semester
- Automatic cumulative CGPA calculation
- Trend comparison across semesters
- Best semester highlight
- Overall progress percentage
- Line chart visualization for SGPA and CGPA
- CSV template download and JSON export

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Chart.js (for charts in the CGPA tracker)
- LocalStorage for saving login/registration data and app state in browser

## How to Run the Project

1. Download or clone the project folder.
2. Open the project in any modern browser.
3. Start with `attendance_dashboard.html` or `landing_page.html`.
4. Use the registration page to create an account.
5. Log in and use the dashboard features.

## Example Usage Flow

1. Open `student_register.html`
2. Create a username and password
3. Open `student_login.html`
4. Log in successfully
5. Access the dashboard from `attendance_dashboard.html`
6. Add students and mark attendance
7. Open `cgpa_calculator.html` for GPA tracking

## Notes

- This project is a frontend-only prototype.
- It uses browser-based storage, so data is saved in the local browser and may not persist across devices.
- It is suitable for learning, demo purposes, and college project presentations.

## Project Goal

The goal of the project is to simplify student data tracking and provide a clear, visual way to monitor academic progress and attendance using a user-friendly interface.

## License

This project is for educational and demonstration purposes.
