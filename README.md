# 🛡 Metasploitable 2 Penetration Testing Lab

## 📌 Overview
This project demonstrates a full penetration testing lifecycle conducted in a controlled lab environment using Kali Linux against Metasploitable 2.

The objective was to:
- Perform reconnaissance
- Identify vulnerable services
- Exploit a known vulnerability
- Gain shell access
- Escalate privileges to root

---

## 🖥 Lab Environment

| Machine | IP Address |
|----------|------------|
| Kali Linux | 192.168.56.4 |
| Metasploitable 2 | 192.168.56.3 |

Network Type: Host-Only (VirtualBox)

---

## 🔍 Phase 1: Reconnaissance

**Tool Used:** Nmap

```bash
nmap -sV 192.168.56.3
