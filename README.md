Timetable Management System
A comprehensive web-based application for managing and generating university or college timetables using Flask and MongoDB. This system streamlines the process of scheduling classes, managing faculty availability, and communicating schedule changes to students and staff.

Features
For Administrators
Resource Management: CRUD operations for teachers, courses, labs, rooms, and student batches
Constraint Management: Define hard and soft constraints such as faculty availability and room usage rules

Timetable Generation
Heuristic Scheduler: Quick timetable generation based on predefined rules
Optimization Engine: Advanced scheduling using Genetic Algorithms (GA) to minimize conflicts and optimize resource usage
Batch Generation: Generate timetables for multiple batches simultaneously
Monitoring: Real-time monitoring of timetable generation tasks
Substitution Management: Handle temporary timetable changes and faculty substitutions

For Faculty
Dashboard: View daily teaching schedule and total lecture count
Advisorship: View details of the batch they are advising

For Students
Personalized Portal: View assigned batch timetable
Real-time Updates: View temporary substitutions and schedule changes with clear visibility
Profile Management: Student registration with batch selection

Tech Stack
Backend: Python, Flask
Database: MongoDB using pymongo
Authentication: bcrypt for password hashing and session-based authentication

Frontend: HTML5, CSS3, JavaScript with Jinja2 templates

Logic: Custom Genetic Algorithm implementation for timetable scheduling optimization
