# 🛡️ SHANKS Security Audit Tool

**SHANKS** is a Linux-based security auditing and system monitoring tool designed to help identify basic security issues, inspect system configurations, analyze logs, monitor network activity, and generate security audit reports.

> **S**ecurity **H**ardening & **A**udit **N**etwork **K**it for **S**ystems

---

## 🚀 Features

### 🖥️ System Information

Collects important information about the system, including:

* Operating system details
* Kernel information
* Hostname
* CPU information
* Memory usage
* Disk usage
* System uptime

### 👤 User Audit

Checks user and account-related information:

* Current logged-in users
* System users
* User account information
* Privileged/root users
* Basic account security checks

### 🌐 Network Audit

Performs basic network security checks:

* Active network interfaces
* IP configuration
* Listening ports
* Active network connections
* TCP/UDP connections
* Network-related system information

Uses commands such as:

```bash
ss -tunap
```

### 📋 Log Analysis

Analyzes security-related system logs to identify potentially suspicious activity.

The tool can inspect:

* Authentication logs
* System logs
* Firewall logs
* Failed login attempts
* Security-related events

### 🔥 Firewall Monitoring

Checks firewall configuration and status.

Supports Linux firewall auditing using:

```bash
ufw status
```

and can inspect firewall logs when available.

### 🌍 Internet Connectivity Check

Tests whether the system has internet connectivity and verifies basic network accessibility.

### 📊 Activity Logging

Records important audit activities performed by the tool, making it easier to review what checks were executed.

### 📄 Security Report

Generates a consolidated security audit report containing the results of the performed checks.

---

## 🏗️ Project Structure

```text
security-automation-tool/
│
├── shanks.py
├── README.md
├── requirements.txt
└── reports/
```

> File names may vary depending on your current project structure.

---

## ⚙️ Requirements

* Linux-based operating system
* Python 3.x
* Bash/Linux security utilities
* Root/sudo privileges for certain checks

Recommended environments:

* Kali Linux
* Ubuntu
* Debian
* Parrot OS

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/adhisiddharth724-sketch/security-automation-tool.git
```

Navigate into the project:

```bash
cd security-automation-tool
```

If a virtual environment is used:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip3 install -r requirements.txt
```

---

## ▶️ Usage

Run the tool using:

```bash
python3 shanks.py
```

The tool provides a menu-driven interface for performing different security audits.

Example:

```text
========================================
       SHANKS SECURITY AUDIT TOOL
========================================

[1] System Information
[2] User Audit
[3] Network Audit
[4] Log Analysis
[5] Security Report
[6] Internet Check
[7] Activity Log
[8] Firewall Monitor
[0] Exit

Enter your choice:
```

Select the required audit option and follow the instructions displayed by the tool.

---

## 🔍 Security Checks

SHANKS performs several basic security checks, including:

| Category     | Checks                                |
| ------------ | ------------------------------------- |
| System       | OS, Kernel, CPU, RAM, Disk            |
| Users        | Logged-in users, Accounts, Privileges |
| Network      | Interfaces, Ports, Connections        |
| Logs         | Authentication & Security Events      |
| Firewall     | Firewall Status & Logs                |
| Connectivity | Internet Availability                 |
| Activity     | Audit Activity Tracking               |
| Reports      | Security Audit Summary                |

---

## 🛠️ Technologies Used

* **Python**
* **Linux**
* **Bash/System Utilities**
* **UFW**
* **SS**
* **Linux System Logs**

---

## 🎯 Project Objective

The main objective of SHANKS is to automate common Linux security auditing tasks through a single command-line interface.

Instead of manually executing multiple commands, users can perform several security checks from one centralized tool.

This project was developed as a **cybersecurity learning and security automation project**.

---

## 🔮 Future Improvements

Planned improvements include:

* [ ] Web-based security dashboard
* [ ] Real-time firewall monitoring
* [ ] Automated vulnerability detection
* [ ] CVE integration
* [ ] Advanced log analysis
* [ ] Suspicious process detection
* [ ] Port risk classification
* [ ] Email security alerts
* [ ] PDF report generation
* [ ] Scheduled automated audits
* [ ] SIEM integration
* [ ] Threat intelligence integration

---

## ⚠️ Disclaimer

SHANKS is intended for **educational, defensive security auditing, and authorized system administration purposes only**.

Do not use this tool to scan, monitor, or audit systems without proper authorization.

The developer is not responsible for misuse of this software.

---

## 👨‍💻 Author

**Adhi Siddharth**

B.Sc. Digital Cyber Forensic Science
Cybersecurity & Digital Forensics Student

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Happy Hacking — Stay Ethical & Secure! 🔐**
