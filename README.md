# Cybersecurity-Lab-Journal
Cybersecurity lab journal with Linux, Splunk, Hydra, SSH, threat detection, and Blue Team exercises.

Welcome to my hands-on cybersecurity learning journal. This repo documents my lab progress, tools explored, challenges faced, and real-world skills developed as I pursue a career in cybersecurity.

> 🚀 Currently enrolled in: **CyberWarrior Program @ MyComputerCareer (Start: August 12, 2025)**  
> 🎯 Goal: Land a $100K+ role in cybersecurity by combining certifications, hands-on labs, and portfolio projects.

---

## 📅 Weekly Lab Tracker

| Date       | Topic / Tool             | Key Takeaways                           | Status |
|------------|--------------------------|------------------------------------------|--------|
| 2025-08-06 | Hydra + SSH + Splunk     | Simulated brute-force, log analysis      | ✅ Done |

---

## 🔐 Lab Entry – August 6, 2025

### 🧪 Objective:
Simulate an SSH brute-force attack using **Hydra**, detect it using log analysis, and ingest data into **Splunk**.

### 🛠️ Tools Used:
- Hydra
- OpenSSH
- Splunk Universal Forwarder
- Linux CLI

### 📜 Steps:
1. Installed and ran Hydra against localhost SSH (`127.0.0.1`)
2. Investigated authentication logs at `/var/log/auth.log`
3. Attempted ingestion of logs into Splunk (issue with file permissions)
4. Troubleshot Splunk forwarder connection and data source visibility

### ⚠️ Issues Faced:
- File permission errors when configuring `/var/log/auth.log` as a Splunk data input
- Splunk search returned “No results” despite other logs appearing

### 🧠 Lessons Learned:
- Hydra produces real authentication failures visible in `auth.log`
- SSH brute-force detection requires understanding log structure and user lockouts
- Splunk permissions and forwarder config are critical for successful ingestion

---

## 📚 Certifications In Progress

- [x] CompTIA Security+ (Studying Module 2: Threats, Vulnerabilities & Mitigations)
- [ ] CompTIA CySA+ (planned)
- [ ] AWS Certified Cloud Practitioner (planned)

---

## 📌 Goals

- Build a job-ready cybersecurity portfolio by November 2025
- Publish weekly updates to GitHub
- Complete 12+ hands-on labs with real detection or mitigation focus

---

## 📬 Connect

- 📧 Email: [dlucas1102@gmail.com]

---

> 🔒 “Security is not a product, but a process.” – Bruce Schneier

