# 🔎 PM1 — Footprinting & Reconnaissance

<p align="center">
  --NetworkWalks Cybersecurity Internship · Week 02--
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Module-PM1-blue?style=for-the-badge" alt="PM1">
  <img src="https://img.shields.io/badge/Focus-Reconnaissance-0A8F8F?style=for-the-badge" alt="Reconnaissance">
  <img src="https://img.shields.io/badge/Platform-Kali%20Linux-black?style=for-the-badge" alt="Kali Linux">
</p>

## 🎯 Module Overview

This module focuses on practical footprinting and reconnaissance techniques used during the initial stages of a cybersecurity assessment.

The exercises explore how publicly observable domain information, DNS records, website technologies, HTTP responses and security infrastructure indicators can help build an understanding of a target's digital presence.

Six reconnaissance tools were used to perform the exercises, with command outputs and screenshots maintained as supporting evidence.

## 🧪 Tools & Practical Activities

| No. | Tool | Purpose |
|---|---|---|
| 01 | **WHOIS** | Gather domain registration information |
| 02 | **WhatWeb** | Identify website technologies and technology indicators |
| 03 | **Nslookup** | Perform DNS queries and name resolution |
| 04 | **cURL** | Inspect HTTP responses and response headers |
| 05 | **wafw00f** | Check for Web Application Firewall indicators |
| 06 | **DNSRecon** | Perform DNS reconnaissance and enumeration |

## 🔬 Practical Exercises & Evidence

### 01 — WHOIS

**Objective:** Understand domain registration information and examine available registration details.

- Executed WHOIS queries.
- Reviewed the available domain registration information.
- Saved command output and screenshots.

**Evidence:**
- [WHOIS command output](WHOIS/01-whois.txt)
- [WHOIS screenshots](WHOIS/Screenshots/)

### 02 — WhatWeb

**Objective:** Identify technologies and publicly observable information associated with a website.

- Executed WhatWeb against the selected website.
- Examined identified technologies and server-related indicators.
- Documented the observed results.

**Evidence:**
- [WhatWeb command output](WhatWeb/02-whatweb.txt)
- [WhatWeb screenshot](WhatWeb/Screenshots/whatweb_result_screenshot.png)

### 03 — Nslookup

**Objective:** Understand DNS queries and domain name resolution.

- Performed DNS lookup commands.
- Examined the returned DNS information.
- Saved the results for documentation.

**Evidence:**
- [Nslookup command output](Nslookup/03-nslookup.txt)
- [Nslookup screenshot](Nslookup/Screenshots/nslookup_result_screenshot.png)

### 04 — cURL

**Objective:** Inspect HTTP responses and understand information exposed through response headers.

- Executed cURL requests.
- Examined HTTP response information and headers.
- Recorded the command output.

**Evidence:**
- [cURL command output](cURL/04-curl-headers.txt)
- [cURL screenshot](cURL/Screenshots/curl_result_screenshot.png)

### 05 — wafw00f

**Objective:** Check whether a website provides indications of Web Application Firewall protection.

- Executed wafw00f against the selected website.
- Reviewed the tool's reported findings.
- Saved the results and screenshot.

**Evidence:**
- [wafw00f command output](Wafw00f/05-wafw00f.txt)
- [wafw00f screenshot](Wafw00f/Screenshots/wafwoof_result_screenshot.png)

### 06 — DNSRecon

**Objective:** Explore DNS reconnaissance and examine available DNS information.

- Executed DNSRecon for DNS information gathering.
- Reviewed the returned records and findings.
- Saved the output and supporting screenshot.

**Evidence:**
- [DNSRecon command output](DNSRecon/06-dnsrecon.txt)
- [DNSRecon screenshot](DNSRecon/Screenshots/dnsrecon_result_screenshot.png)

## 🛠️ Tools & Environment

| Category | Technology |
|---|---|
| Operating System | Kali Linux |
| Domain Information | WHOIS |
| Website Fingerprinting | WhatWeb |
| DNS Queries | Nslookup |
| HTTP Analysis | cURL |
| WAF Detection | wafw00f |
| DNS Reconnaissance | DNSRecon |

## 📚 Key Learning Outcomes

Through this module, I gained practical exposure to:

- Understanding footprinting and reconnaissance methodologies.
- Gathering domain registration information.
- Identifying publicly observable website technologies.
- Performing DNS queries and interpreting DNS information.
- Examining HTTP response headers.
- Checking for Web Application Firewall indicators.
- Performing DNS reconnaissance.
- Recording technical findings using command outputs and screenshots.

## 📁 Evidence Directory

```text
PM1-Footprinting-Reconnaissance/
│
├── README.md
│
├── WHOIS/
│   ├── 01-whois.txt
│   └── Screenshots/
│
├── WhatWeb/
│   ├── 02-whatweb.txt
│   └── Screenshots/
│
├── Nslookup/
│   ├── 03-nslookup.txt
│   └── Screenshots/
│
├── cURL/
│   ├── 04-curl-headers.txt
│   └── Screenshots/
│
├── Wafw00f/
│   ├── 05-wafw00f.txt
│   └── Screenshots/
│
└── DNSRecon/
    ├── 06-dnsrecon.txt
    └── Screenshots/
```

## 🔒 Authorization & Responsible Use

These exercises were conducted for educational cybersecurity training purposes. Reconnaissance activities should only be performed against systems and domains within an authorized scope.

The findings documented here are intended for learning, security awareness and authorized assessment purposes.

---

<p align="center">
  **NETWORKWALKS · CYBERSECURITY INTERNSHIP · PM1**
  <br>
  Prepared by **IRFAN RS**
  <br>
  <sub>Learn · Observe · Analyze · Document</sub>
</p>
