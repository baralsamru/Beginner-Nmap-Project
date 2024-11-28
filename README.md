# Beginner Nmap Scanning Project

## Overview
As a beginner cybersecurity student, I used **Nmap**, a powerful network scanning tool, to learn how to analyze networks and gather important information about devices, services, and operating systems. This project includes scans for:
- Host discovery (`-sn`),
- Service version detection (`-sV`),
- Aggressive scanning for detailed analysis (`-A`), and
- Operating system detection (`-O`).

## Project Goals
1. Understand the basics of network scanning and reconnaissance.
2. Learn how to identify open ports, services, and operating systems.
3. Practice interpreting Nmap scan outputs for security assessment.

---

## Commands and Scans
1.Host Discovery (Ping Scan)
Command: 
   ```bash
   nmap -sn <target-ip-range>
```
2. Service Version Detection
Command:
```bash
nmap -sV <target-ip>
```
3. Aggressive Scan
Command:
```bash
nmap -A <target-ip>
```
4. Detect the operating system:
```bash
nmap -O <target-ip>
```
