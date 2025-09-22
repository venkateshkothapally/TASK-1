# Scan-Your-Local-Network-for-Open-Ports
- Task 1: Scan Your Local Network for Open PortsElevate Lab

# tools used 
- **Nmap** (nmap -sS 172.20.10.0/24)


# Steps
Identified my local IP range:  10.118.142.156.
Ran a TCP SYN scan: nmap -sS  10.118.142.156.
Saved results to  scan_result.txt.
caputre the packets
# Network Scan Report

This document contains the results of an **Nmap** scan performed on the local network.

---

## 📌 Scan Details
- **Tool Used:** Nmap 7.98  
- **Command Executed:**
  ```bash
  "C:\Program Files (x86)\Nmap\nmap.exe" -sS -oN scan_result.txt 10.118.142.156
