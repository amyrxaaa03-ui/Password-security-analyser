# Password-security-analyser
Password Security Analyzer
A comprehensive Python application to analyze and evaluate password strength with detailed feedback and analytics.
📋 Project Overview
The Password Security Analyzer is a command-line tool designed to help users understand and improve their password security. It evaluates passwords based on multiple security criteria and provides actionable recommendations to create stronger, more secure passwords.
✨ Features
●	Real-time Password Strength Evaluation - Instantly check password security
●	Detailed Scoring System - Scores from 0-100 based on multiple criteria
●	Four Strength Levels - Weak, Moderate, Strong, Very Strong
●	User Registration & Login - Track individual user password history
●	Password History Tracking - Maintain records of all password checks
●	Analytics & Reports - View statistics on password patterns
●	Common Pattern Detection - Identifies weak/common passwords
●	Repeated Character Detection - Warns about repeated patterns (aaa, 111)
●	Sequential Pattern Detection - Detects sequential inputs (abc, 123)
●	Comprehensive Feedback - Specific suggestions for improvement
●	Input Validation - Robust error handling and validation
●	Logging System - Complete audit trail of all activities
●	SQLite Database - Persistent data storage
🛠️ Technologies/Tools Used
Language: Python 3.7+
Database: SQLite3
Key Libraries:
●	re (Regular Expressions) - Pattern matching
●	sqlite3 - Database management
●	logging - Application logging
●	Built-in Python libraries only (no external dependencies)
📦 Requirements
●	Python 3.7 or higher
●	Windows, macOS, or Linux
●	No external dependencies required
🚀 Installation & Setup
Step 1: Download/Clone Repository
git clone https://github.com/sanchiita26bce1054-hue/password-security-analyzer
cd password-security-analyzer
Step 2: Verify Python Installation
python --version
(Should be 3.7 or higher)
Step 3: No Additional Setup Required!
All dependencies are built-in Python modules.
💻 How to Run
Start the Application
python main.py
Main Menu Options
1. Register New User - Create a new user account
2. Login - Access existing user account
3. Exit - Close the application
After Login Options
1. Check Password Strength - Analyze a password
2. View Password History - See previous checks
3. View Analytics Report - Get statistics
4. Logout - Exit user session
📊 Scoring System
Passwords are evaluated on multiple criteria:
Criterion	Points	Description
Length (8+ chars)	20	Minimum password length
Lowercase Letters	10	Contains a-z
Uppercase Letters	10	Contains A-Z
Numbers	10	Contains 0-9
Special Characters	15	Contains !@#$%^&*()
No Common Patterns	20	Avoids weak passwords
No Repeated Chars	15	Avoids aaa, 111 patterns
Total	100	Maximum Score
🎯 Strength Levels
🔴 Weak: 0-39 points (High risk)
🟡 Moderate: 40-59 points (Medium risk)
🟢 Strong: 60-79 points (Low risk)
🟢 Very Strong: 80-100 points (Excellent security)
📁 Project Structure
password-security-analyzer/
├── main.py
├── analyzer.py
├── validators.py
├── storage.py
├── feedback.py
├── generator.py
├── reports.py
├── tests/
├── data/
├── README.md
└── requirements.txt
📞 Support & Contact
●	GitHub Repository
https://github.com/sanchiita26bce1054-hue/password-security-analyzer
●	Report Issues
Use GitHub Issues for bug reports and feature requests
●	Contact
Contact through GitHub profile
📄 License & Version
MIT License - Free to use and modify
Version: 1.0.0
Release Date: September 2026
Status: ✅ Production Ready
---
For more information, visit the GitHub repository or check the documentation files.
Password Security Analyzer © 2026 | All Rights Reserved
