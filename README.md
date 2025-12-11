Nmap & Scapy Files
/nmap-scapy-project
│
├── README.md
├── nmap/
│   ├── nmap-basic-scans.md
│   ├── nmap-advanced-scans.md
│   ├── screenshots/
│   │   ├── scan1.png
│   │   ├── scan2.png
│   └── results/
│       └── nmap-output.txt
│
└── scapy/
    ├── scapy-scripts.py
    ├── packet-capture.md
    ├── screenshots/
    │   ├── scapy1.png
    │   ├── scapy2.png
    └── results/
        └── scapy-output.txt

       Objectives

Learn and demonstrate core network scanning techniques

Understand host discovery, port scanning, OS detection, version enumeration

Use Scapy to craft packets, send packets, and sniff network traffic

Document cybersecurity processes professionally

## 🧩 Tools Used
Tool	Purpose
Nmap	Network scanning, discovery, enumeration
Scapy	Packet creation, traffic sniffing & analysis
Kali Linux	Working environment
Python 3	Required for Scapy

## 🔍 1. Nmap Documentation
### 🚀 Basic Scans
Scan Type	Command	Purpose
Ping Scan	nmap -sn <target>	Check if host is up
Port Scan	nmap <target>	Default port scan
Service Version	nmap -sV <target>	Identify running services
OS Detection	nmap -O <target>	Detect OS

### ⚡ Advanced Scans
Scan	Command	Description
Stealth Scan	nmap -sS <target>	SYN scan (fast & stealthy)
Aggressive Scan	nmap -A <target>	OS, services, scripts

