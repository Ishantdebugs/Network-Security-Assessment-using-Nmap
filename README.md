# Basic Network Security Assessment using Nmap

## Overview
This project demonstrates a basic network security assessment performed using Nmap.  
The goal is to identify open ports, running services, and evaluate the security posture of the target system.

---

## Objectives
- Identify open ports
- Detect running services
- Analyze security configurations
- Check for potential vulnerabilities

---

## Tools Used
- Nmap
- Kali Linux

---

## Methodology
The following steps were performed:

1. Basic Port Scan  
2. Service Version Detection  
3. Default Script Scanning  
4. SMB Enumeration  
5. Vulnerability Scanning  

---

## Key Findings

### Open Ports
- 135 (Microsoft Remote Procedure Call)
- 139 (NetBIOS Session Service)
- 445 (Server Message Block - SMB)

---

### System Analysis
The target appears to be a Windows-based system based on detected services.

---

### Security Observations
- Majority of ports are filtered, indicating firewall protection
- SMB requires authentication
- Message signing is enabled and enforced
- No anonymous access allowed

---

### Vulnerability Scan
- No confirmed vulnerabilities found
- Some checks could not be completed due to access restrictions

---

## Screenshots

![Basic Scan](screenshots/nmap-basic.png)
![Service Detection](screenshots/nmap-service.png)
![SMB Enumeration](screenshots/smb-scan.png)

---

## Detailed Report
See full report here:  
Basic-Network-Security-Assessment-using-Nmap.md

---


## Conclusion
The system appears relatively secure based on the performed assessment.  
Security controls such as authentication and message signing are properly implemented.

---

## Future Improvements
- Perform authenticated scanning
- Conduct deeper vulnerability analysis
- Expand to additional network services
