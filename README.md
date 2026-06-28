<div align="center">

# 🛡️ Splunk XSS Detection Lab

### End-to-End SOC Project for Detecting Cross-Site Scripting (XSS) Attacks using Splunk Enterprise

<p>

<img src="https://img.shields.io/badge/SIEM-Splunk-success?style=for-the-badge"/>

<img src="https://img.shields.io/badge/SOC-Blue%20Team-blue?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Attack-XSS-red?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Debian%20%7C%20Kali-orange?style=for-the-badge"/>

</p>

[🎥 Watch Demo](https://youtu.be/-MvQjQNHAwM) •
[📄 Documentation](Documentation/Splunk-XSS-Detection-Lab%20-28%20June%202026.pdf)

</div>

---
# 📖 Project Overview

This project demonstrates an end-to-end Security Operations Center (SOC) workflow for detecting Cross-Site Scripting (XSS) attacks using Splunk Enterprise.

A realistic attack was simulated from Kali Linux against a vulnerable BlackPearl web application. The generated Nginx logs were collected using Splunk Universal Forwarder, analyzed with SPL queries, and transformed into actionable security alerts for investigation.

---
## ⭐ Project Highlights

- Built a complete SOC lab environment
- Simulated a real XSS attack
- Centralized Nginx log collection
- Developed custom SPL detection queries
- Configured real-time security alerts
- Performed incident investigation
- Produced complete technical documentation

---
## 🏗️ Lab Architecture

<p align="center">

<img src="Images/Architecture.png" width="900">

</p>


---
## 🖥️ Lab Environment

| Machine | Operating System | Role |
|---------|------------------|------|
| Splunk Enterprise | Windows Server | SIEM Platform |
| BlackPearl | Debian Linux | Vulnerable Web Server |
| Kali Linux | Kali Linux | Attacker Machine |

---

## 🔄 Attack Workflow

```text
Kali Linux
      │
      ▼
BlackPearl Web Server
      │
      ▼
Nginx Access Logs
      │
      ▼
Splunk Universal Forwarder
      │
      ▼
Splunk Enterprise
      │
      ▼
SPL Detection
      │
      ▼
Real-Time Alert
      │
      ▼
SOC Analyst Investigation
```
---

## 📸 Project Screenshots

### Architecture

<img src="Images/Architecture.png">

---

### Splunk Login

<img src="Images/Splunk Login.png">

---

### Search Results

<img src="Images/Search.png">

---

### XSS Detection Alert

<img src="Images/XSS Detection Alert.png">

---

### Triggered Alerts

<img src="Images/Triggered Alerts.png">

---

## ⚙️ Technologies Used

- Splunk Enterprise
- Splunk Universal Forwarder
- Kali Linux
- Search Processing Language (SPL)
- SIEM

---

## 💡 Skills Demonstrated

- SIEM Deployment
- Security Monitoring
- Log Analysis
- SPL Query Development
- Alert Configuration
- Incident Investigation
- Linux Administration
- Windows Administration
- SOC Workflow
- XSS Detection

---
## 📄 Documentation

📥 Download the complete project documentation here:

➡️ **[📄 Splunk XSS Detection Lab Documentation](Documentation/Splunk-XSS-Detection-Lab%20-28%20June%202026.pdf)**

---
## 🎥 Video Demonstration

📺 Watch the complete project demonstration:

[![Watch on YouTube](https://img.shields.io/badge/▶-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/-MvQjQNHAwM)

---

## 🚀 Future Improvements

- SQL Injection Detection
- Brute Force Detection
- Correlation Searches
- Interactive Dashboards
- Email Alerting
- Threat Intelligence Integration
  
---

<div align="center">

## 👩‍💻 Author

# Shaymaa Hisham

Cybersecurity Enthusiast | SOC Analyst | SIEM | Splunk

⭐ If you found this project useful, don't forget to star the repository.

</div>

