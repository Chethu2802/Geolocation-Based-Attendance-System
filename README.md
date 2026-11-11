# Geolocation-Based Attendance Tracking System

## Project Overview
A smart attendance management system that uses GPS geofencing and facial recognition to prevent proxy attendance in colleges. Developed as part of academic project at ATME College of Engineering, Mysuru.

This system ensures students can only mark attendance when they are physically present inside the campus and their face is verified.

## Problem Statement
In many colleges, attendance is marked manually or using simple apps which leads to:
- Proxy attendance by friends
- Fake attendance from outside campus
- No proper verification of student identity
- Time consuming manual reports for staff

Our system solves this by combining location verification + face verification.

## Technologies Used
- **Backend:** Python, Django 4.2.7, Django REST Framework
- **Database:** MongoDB (using djongo), MySQL
- **Face Recognition:** OpenCV, dlib, face-recognition, face-recognition-models
- **Frontend:** HTML, CSS, JavaScript
- **GPS:** Browser Geolocation API / GPS APIs
- **Tools:** Git, GitHub, VS Code

## Key Features
1.  **Geofencing:** Attendance allowed only inside college campus boundaries
2.  **Facial Recognition:** Verifies student identity using face matching
3.  **Role-Based Dashboards:**
    - Student: Mark attendance, view attendance history
    - Staff: View class attendance, download reports
    - Admin: Manage students, staff, subjects, geofence settings
4.  **Automated Reporting:** Daily, monthly attendance reports
5.  **Real-Time Verification:** Instant validation of location and face
6.  **Secure Authentication:** Login for all roles

## Project Structure

Geolocation-Attendance-System/
├── attendance/          # Attendance logic and views
├── authentication/      # Login and user auth
├── manage.py
├── requirements.txt
├── db.sqlite3 / MongoDB
└── README.md




    
