# 🛡️ Splunk XSS Detection Lab

## Overview

This project demonstrates an end-to-end Security Operations Center (SOC) workflow for detecting Cross-Site Scripting (XSS) attacks using Splunk Enterprise.

The lab simulates a realistic attack scenario using Kali Linux against a vulnerable BlackPearl web server. Logs are collected through Splunk Universal Forwarder, analyzed using SPL queries, and transformed into actionable security alerts.

---

## 🎥 Video Demonstration

Watch the full project demo:

https://youtu.be/-MvQjQNHAwM

---

## 🏗️ Lab Architecture

![Architecture](Images/Architecture.png)

---

## 🖥️ Lab Environment

| Machine | Role |
|----------|----------|
| Windows Server | Splunk Enterprise |
| Debian Linux | BlackPearl Web Server |
| Kali Linux | Attacker Machine |

---

## 🔄 Attack Workflow

1. Launch an XSS attack from Kali Linux.
2. The vulnerable BlackPearl server receives the malicious payload.
3. Nginx logs capture the request.
4. Splunk Universal Forwarder collects the logs.
5. Logs are forwarded to Splunk Enterprise.
6. SPL queries identify suspicious activity.
7. Splunk generates a security alert.
8. The SOC analyst investigates the event.

---

## 📸 Screenshots

### Splunk Login

![Splunk Login](Images/Splunk%20Login.png)

### Search Results

![Search Results](Images/Search.png)

### XSS Detection Alert

![XSS Detection Alert](Images/XSS%20Detection%20Alert.png)

### Triggered Alerts

![Triggered Alerts](Images/Triggered%20Alerts.png)



---

## 🛠️ Technologies Used

- Splunk Enterprise
- Splunk Universal Forwarder
- Kali Linux
- Debian Linux
- Nginx
- PHP
- SPL (Search Processing Language)
- SIEM

---

## 💡 Skills Demonstrated

- Security Monitoring
- Log Analysis
- SPL Query Development
- Incident Investigation
- Alert Configuration
- SOC Operations
- SIEM Administration
- Linux Administration
- Windows Administration
- XSS Detection

---

## 📄 Documentation

Detailed project documentation is available in:

`Documentation/Splunk-XSS-Detection-Lab-Documentation.pdf`

---

## 🚀 Future Improvements

- SQL Injection Detection
- Brute Force Detection
- Correlation Searches
- Advanced Dashboards
- Email Alerting

---

## 👩‍💻 Author

**Shaymaa Hisham**

Cybersecurity | SOC Analyst | Splunk Enthusiast
