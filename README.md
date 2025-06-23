# cybersecurity-Task01

## 📌 Project Title
**Vulnerability Assessment & Reporting on a Local Web Application**  
_Subtask: Network Port Scanning using Nmap_

---

## 🎯 Objective
To identify active hosts and open TCP ports in the local network `172.20.10.0/24` using a stealthy SYN scan with Nmap.

---

## 💻 Command Used
```bash
nmap -sS 172.20.10.0/24 -oN port_scan_results.txt

📁 Output File
See: port_scan_results.txt
