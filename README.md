# 🛡️ Task 3: Perform a Basic Vulnerability Scan on Your PC

## ✅ Objective:
Identify potential vulnerabilities in your system using a security scanner like **OpenVAS** or **Nessus Essentials**. Analyze the results and explore basic mitigation strategies.

---

## 🧪 Steps Performed:

1. **Installed** OpenVAS using Docker on my local system.
2. **Configured** the scan target using `localhost` (127.0.0.1).
3. **Launched** a full vulnerability scan.
4. **Waited** for the scan to complete (approximately 45–60 minutes).
5. **Reviewed** the report for vulnerabilities categorized by severity.
6. **Researched** basic solutions or fixes for identified issues.
7. **Documented** the most critical vulnerabilities found.
8. **Captured** screenshots of the scan results and saved them in the `images/` folder.

---

## 🖥️ Tools Used:

- **OpenVAS (Greenbone Vulnerability Manager)**
  - Installed via Docker for simplicity.
- **Localhost** as the scan target.

---

## 🔍 Vulnerability Summary (Sample)

| Vulnerability Description         | Severity | Recommended Action                          |
|----------------------------------|----------|---------------------------------------------|
| Open SSH port (22)               | Medium   | Use key-based authentication or close port. |
| Self-signed SSL certificate      | Low      | Use a valid SSL certificate.                |
| Outdated system packages         | Medium   | Update using `apt upgrade`.                 |

> Note: Vulnerabilities vary depending on system setup. These are just examples.

---

## 🖼️ Screenshot Evidence

All scan screenshots are saved in the `/images` directory.

Example:

![Scan Screenshot](images/scan_result.png)

---

## 📂 Project Structure






