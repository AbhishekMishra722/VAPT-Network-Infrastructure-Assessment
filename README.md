# 🔐 VAPT – Network Infrastructure Assessment

## 👨‍💻 Overview
This project demonstrates a Vulnerability Assessment and Penetration Testing (VAPT) engagement on internal network systems. The goal was to identify security weaknesses, assess risks, and recommend remediation strategies.

---

## 🎯 Scope
- **Windows System:** 172.31.32.114  
- **Debian Linux System:** 172.31.42.236  

---

## 🛠️ Tools Used
- Nmap (Zenmap) – Network Scanning & Enumeration  
- Nessus – Vulnerability Assessment  

---

## 🔎 Methodology
The assessment followed standard VAPT phases:
1. Reconnaissance  
2. Scanning & Enumeration  
3. Vulnerability Assessment  
4. Risk Analysis  
5. Reporting  

---

## 🌐 Key Findings

### 🔹 Windows System
- Open Ports: 135, 139, 445 (SMB), 3389 (RDP)  
- Risks: SMB exploitation, RDP brute-force attacks  

### 🔹 Debian System
- Open Ports: 21 (FTP), 22 (SSH), 80 (HTTP)  
- Risks: FTP exposure, outdated web server vulnerabilities  

---

## 🚨 Identified Vulnerabilities

| Vulnerability | System | Severity | Impact |
|--------------|--------|----------|--------|
| SMB Exposure | Windows | High | Remote exploitation risk |
| RDP Exposure | Windows | High | Unauthorized access |
| FTP Exposure | Debian | Medium | Data leakage |
| Outdated Apache | Debian | Medium | Web-based attacks |

---

## 🛡️ Recommendations
- Disable unnecessary services (SMB, FTP)  
- Enforce strong authentication & account lockout  
- Apply regular security patches  
- Restrict RDP access (VPN + MFA)  
- Harden SSH configuration  

---

## 📌 Conclusion
The assessment revealed multiple vulnerabilities, with the Windows system posing higher risk due to exposed SMB and RDP services. Timely remediation is essential to reduce attack surface and prevent exploitation.

---

## 🧠 Key Learnings
- Practical exposure to network scanning and vulnerability assessment  
- Understanding of real-world attack vectors  
- Risk prioritization and remediation strategies  
