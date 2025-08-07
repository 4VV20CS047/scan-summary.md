# OpenVAS Basic Scan
# ✅ OpenVAS Basic Scan using Docker

This project documents the process of setting up OpenVAS using Docker on a Linux system (notably Parrot OS) and performing a basic vulnerability scan on the local system.

---

## 📌 Objective

The objective of this task was to:
- Set up OpenVAS (Greenbone Vulnerability Management) using Docker.
- Run a containerized instance of OpenVAS.
- Perform a basic scan on the localhost.
- Generate and analyze the report.
- Push the results and screenshots to a GitHub repository.

---

## 🐳 Environment Setup (Docker)

Before running the scan, Docker was installed with the following commands:

```bash
sudo apt update
sudo apt install docker.io -y
🖥️ Accessing the OpenVAS Web Interface
Once the container is running, OpenVAS (GSA) can be accessed via:
https://localhost
🔍 Scan Configuration
After logging into the GSA dashboard:

Go to Scans → Tasks

Click on "Create Task"

Configure the scan with:

Name: Localhost Scan

Target: My Localhost (Created earlier using your system's local IP)

Scanner: Default

Schedule: Run Immediately

Click Create, then click the ▶️ Start button

📊 Report Summary
After completion, navigate to Scans → Reports

You will see a breakdown of the findings by severity:

High

Medium

Low

Log

False Positive

The attached screenshot shows a Medium severity vulnerability was detected.

🖼️ Screenshots
Scan Report by Severity

(Make sure to upload your screenshot to a folder like /images in your repo and update the image path accordingly.)

✅ Outcome
Successfully:

Installed OpenVAS via Docker

Ran a basic scan on localhost

Identified potential vulnerabilities

Documented the process and results




