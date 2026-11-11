# Geolocation-Based Attendance System

### Project Overview
A smart attendance system that marks attendance based on user's real-time geolocation. Prevents proxy attendance by validating if user is within defined office/college radius.

### Problem Statement
Traditional attendance systems allow proxy marking and lack location verification. Organizations need a secure, location-aware solution to ensure employees/students are physically present.

### Technologies Used
- **Language:** Python
- **Libraries:** Geopy, Flask, SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Tools:** Git, VS Code, Geolocation API

### Key Features
- Real-time location tracking and validation
- Radius-based attendance marking (e.g., 100m from office)
- Secure login for admin and users
- Attendance history and reporting dashboard
- Proxy prevention with geofencing

### Installation Instructions
1. Clone repo: `git clone https://github.com/Chethu2802/Geolocation-Based-Attendance-System.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`
4. Open browser: `http://localhost:5000`

### Screenshots
Add your project dashboard screenshots here.

### Future Enhancements
- Face recognition integration
- Mobile app version
- Email notification for late attendance
- Analytics dashboard for HR
