# Automated Attendance System with Facial Recognition
## Overview
This project implements an automated attendance system using facial recognition technology. The system captures live footage from a webcam, applies facial recognition using a Teachable Machine model, and records attendance in a Google Sheets document. Additionally, it features an Arduino Uno integration to automate classroom electrical appliances.

## Key Features
Facial Recognition: Utilizes a Teachable Machine model to recognize and mark attendance based on facial features.
Real-Time Monitoring: Captures live footage for real-time attendance tracking during class sessions.
Google Sheets Integration: Stores attendance data in a Google Sheets document via the Google Sheets API.
Arduino Uno Control: Allows automation of electrical appliances in the classroom using an Arduino Uno and relay module.

##Setup Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/automated-attendance-system.git
cd automated-attendance-system
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Configuration:

Set up the Google Sheets API credentials (refer to google_sheets_api_credentials.json).
Configure the Arduino Uno connection details.
Run the System:

bash
Copy code
python main.py
Directory Structure
models/: Contains the Teachable Machine model.
src/: Source code files.
data/: Data files and configuration.
docs/: Project documentation.
Contributing
If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.# Classroom-Automation
