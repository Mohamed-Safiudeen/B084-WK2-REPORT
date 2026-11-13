# B084-WK2-REPORT
Completed authorized footprinting of networkwalks.com and local network host discovery using Kali Linux tools and Zenmap Ping Scan with network topology visualization.
# Week 2 – Cybersecurity Internship | NETWORKWALKS

## Project Overview
This repository contains the work completed during Week 2 of my Cybersecurity Internship at NETWORKWALKS (Batch B084).

The project focuses on **Footprinting and Network Scanning**, covering two practical modules.

## Modules Completed

### 1. W2-PM1 – Footprinting Using Six Kali Linux Tools

Performed authorized footprinting of `networkwalks.com` using the following tools:

| Tool | Purpose |
|---|---|
| WHOIS | Collected domain registration information |
| WhatWeb | Identified website technologies |
| Nslookup | Retrieved domain IP information |
| Curl | Inspected HTTP response headers |
| Wafw00f | Detected Web Application Firewall technology |
| DNSRecon | Enumerated DNS records |

**Key observations:**
- Identified domain registrar and name servers.
- Detected Apache and WordPress technologies.
- Retrieved DNS records and HTTP response information.
- Wafw00f detected ModSecurity (SpiderLabs) WAF.

### 2. W2-PM5 – Network Scanning Using Zenmap

Performed a Ping Scan on my own local network using Zenmap (Nmap 7.993) on Windows.

**Scan details:**
- Scan type: Ping Scan
- Command: `nmap -sn 10.38.230.0/24`
- Network range: `10.38.230.0/24`
- Total IP addresses scanned: 256
- Active hosts discovered: 3
- Scan duration: 9.57 seconds

**Discovered hosts:**

| IP Address | Status | MAC Address |
|---|---|---|
| 10.38.230.61 | Up | 86:B1:8A:87:56:FB |
| 10.38.230.167 | Up | AE:E6:65:3B:DE:95 |
| 10.38.230.102 | Up | Not obtained |

The discovered hosts were also visualized using Zenmap Network Topology.

## Tools and Technologies
- Kali Linux
- WHOIS
- WhatWeb
- Nslookup
- Curl
- Wafw00f
- DNSRecon
- Zenmap
- Nmap
- Windows Command Prompt

## Key Learnings
- Understanding domain footprinting and reconnaissance.
- Identifying web technologies and DNS information.
- Inspecting HTTP response headers.
- Understanding Web Application Firewall detection.
- Discovering active hosts in a local network.
- Visualizing discovered hosts using network topology.

## Project Report
The detailed practical report includes commands, observed outputs, risk analysis, recommendations and evidence screenshots.

## Authorization and Disclaimer
The footprinting activity on `networkwalks.com` was performed with permission from Networkwalks. The network scan was conducted on my own local network.

These activities were performed for educational purposes within the stated authorized scope. No exploitation or vulnerability validation was carried out.

## Details
- **Program:** Cybersecurity Internship – NETWORKWALKS
- **Batch:** B084
- **Week:** 02
- **Intern:** Mohamed Safiudeen N

---

**Repository:** [B084-WK2-REPORT](https://github.com/Mohamed-Safiudeen/B084-WK2-REPORT)

*Learning, practicing and improving my cybersecurity skills step by step.*
