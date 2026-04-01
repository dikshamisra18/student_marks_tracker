# Student Mark Tracker
A responsive web application to manage and track student scores and details.
> Developed initially as part of a Web Programming lab assignment, with significant enhancements including UI redesign, improved user interactions, and additional features implemented independently.

## Overview
This project demonstrates practical usage of JavaScript, especially working with arrays and DOM manipulation.  
It includes validation, real-time feedback for scores, and interactive features to manage student data dynamically.

## Features
- Form Fields: Name, Roll Number, Score  
- Buttons:
  - Add Student
  - Sort (Ascending / Descending)
  - Filter (Failing Students Only)
  - Show All Students
  - Clear Table (with confirmation)
- Validation:
  - Input validation with error messages
  - Duplicate roll number detection
- Dynamic Table:
  - Add and delete student entries
  - Automatic grade and pass/fail status
- Statistics Panel:
  - Total students
  - Average score
  - Highest and lowest scores
  - Passing percentage
- Real-time Feedback:
  - Live pass/fail indication while typing score

## Tech Stack
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## Usage
1. Enter student details (Name, Roll No, Score)  
2. Click **Add Student** to insert into the table  
3. Use sorting and filtering buttons to manipulate data  
4. View real-time statistics in the statistics bar  
5. Use **Clear Table** to reset all data

## Learning Outcome
By developing this project, I learned:

- How to use **arrays as state storage** for dynamic data  
- Difference between **mutating methods (splice, sort)** and **non-mutating methods (map, filter, reduce)**  
- How to dynamically render UI using **map() and template literals**  
- How to compute values using **reduce() (sum, max, min, percentages)**  
- How to use **filter() for conditional views (e.g., failing students)**  
- How to handle **event-driven programming** using addEventListener  
- How to implement **form validation and real-time feedback**  
- How to **update the DOM efficiently** after every data change (render pattern)  
- How to manage **UI + data consistency** (change data → re-render UI)  
- Improved understanding of **JavaScript logic structuring and modular functions**

> This project was built as part of learning JavaScript. Most logic and implementation were written independently, with minimal debugging assistance.
