# Vulnerability Report: vsftd 234

## Executive Summary
A vulnerability was identified on the target system that allows <brief impact>.
This could lead to <impact like unauthorized access, data leak, etc>.

---

## Target Information
- Target IP: 192.168.1.3
- Machine: Metasploitable2
- Environment: VLab
- Date: <01-04-2026>

---

## Methodology
1. Reconnaissance
2. Scanning
3. Exploitation
4. Post-Exploitation

---

## Reconnaissance

```bash
nmap -sV -A -vv -sC 192.168.1.3 -oN metasploitable2-010426.txt

