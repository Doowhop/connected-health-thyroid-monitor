# connected-health-thyroid-monitor
A Python-based simulation of a real-time thyroid health monitoring system that integrates wearable data collection, anomaly detection, secure encryption, and user-friendly interface design. Developed as a capstone project for the MS in Computer Science program.

## Technologies Used

- **Python 3.9+** — Core programming language  
- **cryptography (Fernet)** — Symmetric encryption for securing data  
- **hashlib** — Secure password hashing  
- **getpass** — Secure password input without echo  
- **random, time** — Simulated data generation and realistic timing  
- **Standard Python libraries** — For input/output and control flow  

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/connected-health-thyroid-monitor.git

2. **Navigate to the project directory:**
   cd connected-health-thyroid-monitor

3. **Create and activate a virtual environment:**
python -m venv venv
venv\Scripts\activate

4. **Create a requirements.txt file with the following content:**
   cryptography

5. **Install dependencies:**

## How to Run the Code 
Run the main script to start the Connected Health app: python main.py

The app starts with a login prompt. Use the default credentials:

Username: admin

Password: password123

After login, choose from the menu options to:

1. Scan and collect simulated wearable data

2. Calibrate baseline readings

3. Enter health data manually

4. Access Bluetooth settings (simulated)

5. Connect with Primary Care Physician (simulated)

6. View health summary with alerts

7. Exit the application

The app securely encrypts and decrypts data using symmetric encryption for demonstration purposes.

## Notes
Passwords are securely hashed, but the use of eval() to parse decrypted data is not secure for production — only for simulation/demo purposes.

The app currently simulates Bluetooth and PCP connectivity as placeholders.

For real-world use, extensive security, validation, and UI improvements would be needed.


Molly Richardson
July 2025



   
