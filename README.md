**Project Overview**

The Dynamic Timetable Generator is a web-based application built with .NET Core and Entity Framework. It allows users to create customizable timetables by entering basic information like working days, subjects per day, and total subjects. The app dynamically calculates total hours and ensures proper subject distribution.

**Features**

Input validation for working days, subjects per day, and total subjects.

Dynamic calculation of total weekly hours.

Validation to ensure subject hours match the total calculated weekly hours.

Dynamic form generation for subject inputs.

Generates a randomized timetable based on user inputs.

**Technologies Used**

.NET Core MVC

Entity Framework Core

HTML, CSS, JavaScript

SQL Server

**How to Use**

Step 1: Basic Information

Enter Class Name.

Input Working Days (1-7).

Input Subjects per Day (1-8).

Input Total Subjects.

Total Weekly Hours auto-calculates.

Click Next.

Step 2: Subject Hours Allocation

Enter each Subject Name and its Total Hours.

Ensure that the total hours match the weekly hours.

The Generate Timetable button will enable once the hours match.

Step 3: View Timetable

A dynamic timetable will be generated and displayed.

**Validation Rules**

Working Days: Accepts only numbers between 1 and 7.

Subjects per Day: Accepts only numbers between 1 and 8.

Total Subjects: Accepts only positive numbers.

Total Subject Hours must equal the calculated total weekly hours.

**Example Input**

Class Name: 1 A

Working Days: 5

Subjects per Day: 4

Total Subjects: 4

**Subjects:**

Gujarati: 5

English: 5

Science: 5

Maths: 5

Total Hours = 5 x 4 = 20





