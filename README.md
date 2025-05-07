# CYB333 Final Project: Cybersecurity Automation Toolkit

## 👨‍💻 Project Objectives

This project was developed to automate key security tasks for Linux-based server environments. The goal is to assist system administrators in detecting threats, identifying open ports, and tracking outdated software packages that may contain known vulnerabilities.

## 🧰 Project Features

- **Log Monitoring Script**: Detects brute-force attempts, root logins, and suspicious IP access; includes automated email alerts and IP blocking.
- **Port Scanner**: Scans for unauthorized open ports and flags unusual traffic to authorized ports.
- **Vulnerability Checker**: Identifies outdated packages and checks for known CVEs via the NIST NVD API.
- **Email Alerting**: Notifies administrators in real time when threats or vulnerabilities are detected.

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/cyb333-security-automation.git
cd cyb333-security-automation
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Credentials
Update the `SMTP_USERNAME`, `SMTP_PASSWORD`, and `ADMIN_EMAIL` placeholders in the scripts with your secure values (do not commit real secrets to GitHub).

## 🛠️ How to Run

```bash
sudo python log_monitor.py
python port_scanner.py
sudo python vulnerability_checker.py
```

## 📦 Dependencies

Listed in `requirements.txt`:
- requests
- urllib3
- certifi
- idna
- charset-normalizer

## 📄 Files Included

- `log_monitor.py`
- `port_scanner.py`
- `vulnerability_checker.py`
- `requirements.txt`
- `README.md`
- `Time_Management_Summary.docx`
- `ProjectUpdate_Limamoi_Paragraph.docx`
- `CYB333_Final_Project_Report_Limamoi_Expanded.docx`
