# nmap-network-scan-task

# 🔐 Cyber Security Internship Task 1 - Network Port Scanning

## 🧠 Objective
To scan my local network and identify open ports on devices using **Nmap**, gaining insight into **network exposure** and basic reconnaissance techniques.

---

## 🛠 Tools Used
- [Nmap](https://nmap.org)
- Windows 10 Command Prompt / PowerShell

---

## 🧪 Steps Followed

1. **Identified Local IP Range:**
   Ran:
   ```powershell
   ipconfig
Found my IP: 10.238.206.148 with subnet mask 255.255.255.0 → network range: 10.238.206.0/24.

2. Performed TCP SYN Scan:

    nmap -sS 10.238.206.0/24 -oN nmap_scan_results.txt
  
Saved Results:
    Scan results were saved in nmap_scan_results.txt.
