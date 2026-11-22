
<div align="center">

<h2>
🗓️ Week 2 · 📁 PM1 Footprinting & Reconnaissance · 📁 PM5 Network Scanning with Zenmap · 🏷️ Batch B084
<br>
🎓 NetworkWalks Academy
</h2>

<br>

<img src="https://img.shields.io/badge/KALI_LINUX-2026.3-5689A8?style=for-the-badge&logo=kalilinux&logoColor=white">
<img src="https://img.shields.io/badge/VIRTUALBOX-LAB-173C70?style=for-the-badge&logo=virtualbox&logoColor=white">
<img src="https://img.shields.io/badge/NMAP_/_ZENMAP-7.993-3269F6?style=for-the-badge">
<img src="https://img.shields.io/badge/SCOPE-AUTHORIZED_ONLY-19C65B?style=for-the-badge">

<br><br>

<img src="https://img.shields.io/badge/ZENMAP_LAB-100%25-36CC16?style=for-the-badge">

</div>

---

## 👨‍💻 AUTHOR INFORMATION

| Details | Information |
|:---|:---|
| **Author** | Okon Inemesit Udo |
| **Program** | Cybersecurity & Ethical Hacking – NetworkWalks Academy |
| **Batch** | B084 |
| **Week** | 02 |
| **LinkedIn** | [Okon Inemesit Udo](https://www.linkedin.com/in/inemesit-okon-949b76239) |

---

## 📋 WEEK 2 PRACTICAL REPORT
### FOOTPRINTING & NETWORK SCANNING

**Modules Covered:**
- PM1 – Footprinting & Reconnaissance
- PM5 – Network Scanning with Zenmap

**Lab Environment:** Kali Linux on Oracle VirtualBox (NAT Network).

---

## 📄 FULL REPORT

📥 **[Download / View Full Practical Report (PDF)](./Cybersecurity_Practical_Report_Week2_Okon_Inemesit_Udo.pdf)**

---

## 🛠️ ACTIVITIES & TOOLS SUMMARY

### 🔎 PM1 – PASSIVE FOOTPRINTING & RECONNAISSANCE

**Target:** `networkwalks.com`

| Tool | Activity / Findings |
|:---|:---|
| **WHOIS** | Retrieved domain registration, registrar details, and authoritative name servers (NS6135 / NS6136). |
| **WhatWeb** | Identified web server (Apache), CMS (WordPress 7.1.4), and active plugins (WordPress Download Manager 3.3.76). |
| **Nslookup** | Verified DNS resolution (192.232.216.135). |
| **cURL (curl -I)** | Inspected HTTP/2 response headers, security policies, and REST API endpoints. |
| **WAFW00F** | Confirmed active Web Application Firewall protection (ModSecurity / SpiderLabs). |
| **DNSRecon** | Enumerated SOA, NS, MX, A, TXT (SPF & site verification), and SRV autodiscover records. |

---

### 🌐 PM5 – NETWORK DISCOVERY WITH ZENMAP

**Tool:** Zenmap / Nmap

**Troubleshooting:**

Resolved the Windows launch error (0xc000007b) by executing scans inside the Kali Linux virtual lab.

**Ping Scan:**

```bash
nmap -sn 10.0.0.2/24
```

**Scan Results:**
- Discovered **2 live hosts**.
- `10.0.0.1` – Network Gateway.
- `10.0.0.2` – Host machine.
- Scanned 256 IP addresses.
- Scan completed in **2.99 seconds**.
- No intrusive port probing was performed.

---

## 📸 EVIDENCE SCREENSHOTS

The following screenshots document the practical activities performed during the two modules.

### 🔎 PM1 – FOOTPRINTING & RECONNAISSANCE

| Tool / Activity | Evidence |
|:---|:---|
| WHOIS Lookup | [📸 View Screenshot](01_whois.png) |
| WhatWeb Enumeration | [📸 View Screenshot](02_whatweb.png) |
| Nslookup Resolution | [📸 View Screenshot](03_nslookup.png) |
| cURL Header Inspection | [📸 View Screenshot](04_curl_headers.png) |
| WAFW00F Firewall Detection | [📸 View Screenshot](05_wafw00f.png) |
| DNSRecon Enumeration | [📸 View Screenshot](06_DNSRecon.png) |

### 🌐 PM5 – NETWORK SCANNING WITH ZENMAP

| Tool / Activity | Evidence |
|:---|:---|
| Zenmap Ping Scan Results | [📸 View Screenshot](Zenmap1.png) |
| Zenmap Network Topology | [📸 View Screenshot](Zenmap2.png) |

---

## 🎯 KEY LEARNING OUTCOMES

- Gained practical experience with passive footprinting and reconnaissance.
- Learned how to retrieve domain registration and DNS information.
- Practised identifying web technologies and security configurations.
- Gained experience with DNS enumeration tools.
- Learned network discovery and host identification using Nmap and Zenmap.
- Practised troubleshooting within a virtual cybersecurity lab environment.

---

## 🔐 SCOPE & AUTHORIZATION

<img src="https://img.shields.io/badge/STATUS-AUTHORIZED_EDUCATIONAL_LAB-19C65B?style=for-the-badge">

All tasks documented in this repository were conducted strictly for educational purposes as part of the NetworkWalks Cybersecurity Internship.

No unauthorized access, exploitation, or intrusive vulnerability testing was performed.

---

<div align="center">

**NETWORKWALKS CYBERSECURITY INTERNSHIP**

Cybersecurity & Ethical Hacking | Batch B084

**Week 02 – Practical Documentation**

[LinkedIn](https://www.linkedin.com/in/inemesit-okon-949b76239)

</div>
