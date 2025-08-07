# Cybersecurity-Lab-Journal

Cybersecurity lab journal with Linux, Splunk, Hydra, SSH, threat detection, and Blue Team exercises.

# 🔍 SSH Brute Force Detection Lab

### 📅 Date
August 6, 2025

### 🧠 Objective
Simulate an SSH brute-force attack using Hydra and monitor authentication attempts via system logs and Splunk.

### 🛠️ Tools Used
- Kali Linux
- OpenSSH
- Hydra
- Splunk
- /var/log/auth.log

### 🧪 What I Did
- Enabled and configured SSH service.
- Ran Hydra brute-force attack on 127.0.0.1.
- Monitored logs and authentication failures.
- Troubleshooted Splunk data ingestion issues and verified system permissions.

### 📚 Key Takeaways
- Learned to parse auth.log for brute-force patterns.
- Identified the need for system log permissions when configuring Splunk.
- Discovered issues related to pam_winbind errors and authentication retry limits.

### 🚀 Next Steps
- Enable real-time alerting in Splunk.
- Expand to detect FTP or web login brute-force attempts.
- Automate log parsing with Python.
