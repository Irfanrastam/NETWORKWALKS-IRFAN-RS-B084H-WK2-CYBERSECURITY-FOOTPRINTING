# 🌐 PM5 — Network Scanning with Zenmap

<p align="center">
  <strong>NetworkWalks Cybersecurity Internship · Week 02</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Module-PM5-blue?style=for-the-badge" alt="PM5">
  <img src="https://img.shields.io/badge/Focus-Network%20Scanning-0A8F8F?style=for-the-badge" alt="Network Scanning">
  <img src="https://img.shields.io/badge/Scope-Authorized%20Lab-success?style=for-the-badge" alt="Authorized Lab">
</p>

## 🎯 Module Overview

This module focuses on network discovery and scanning using **Zenmap**, the graphical interface for Nmap.

The practical exercises were conducted within an authorized local virtual network lab using Kali Linux and Oracle VirtualBox.

The objective was to understand how network scanning helps identify active hosts, examine reported open ports and services, and visualize discovered network information.

Scan outputs, XML data, topology information and screenshots are included as supporting evidence.

## 🖥️ Testing Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Virtualization Platform | Oracle VirtualBox |
| Network Scope | Authorized local virtual network lab |
| Network Scanning Tool | Nmap |
| Graphical Interface | Zenmap |
| Evidence Formats | TXT, XML, PDF and PNG |

## 🔬 Practical Activities

### 01 — Network Discovery

**Objective:** Identify active hosts within the authorized local network.

- Performed network discovery using Zenmap.
- Examined the hosts reported by the scan.
- Observed available network information.

**Evidence:**

- [Network discovery screenshot](Screenshots/zenmap_ping_screenshot.png)
- [Saved scan output](Scan-Results/zenmap_scan_result.txt)

### 02 — Host Identification

**Objective:** Understand how scanning results provide information about discovered network hosts.

- Reviewed the hosts reported during scanning.
- Examined available host information.
- Documented relevant observations.

### 03 — Port Scanning

**Objective:** Examine ports and services reported by the network scanning tool.

- Performed port scanning using Zenmap.
- Reviewed the scan results.
- Examined reported open ports and associated service information.

**Evidence:**

- [Port scanning screenshot](Screenshots/zenmap_port_screenshot.png)
- [Scan results](Scan-Results/zenmap_scan_result.txt)

### 04 — Intense Scanning

**Objective:** Explore the results produced by an Intense Scan profile in Zenmap.

- Executed the Intense Scan profile.
- Reviewed the resulting scan information.
- Saved supporting evidence.

**Evidence:**

- [Intense Scan screenshot](Screenshots/zenmap_intense_scan_screenshot.png)

### 05 — Network Topology Visualization

**Objective:** Understand the visual representation of discovered network information through Zenmap's topology feature.

- Reviewed the generated network topology.
- Examined the relationships represented in the visualization.
- Exported topology information for documentation.

**Evidence:**

- [Zenmap topology PDF](Network-Topology/zenmap_topology.pdf)
- [Zenmap topology screenshot](Screenshots/zenmap_topology_screenshot.png)
- [Zenmap XML results](Network-Topology/zenmap_results.xml)

## 📊 Scan Documentation

The following files preserve the results and supporting information from the practical exercises.

| File | Description |
|---|---|
| `zenmap_scan_result.txt` | Saved scan output |
| `zenmap_results.xml` | XML scan results |
| `zenmap_topology.pdf` | Exported network topology |
| `zenmap_intense_scan_screenshot.png` | Intense Scan evidence |
| `zenmap_ping_screenshot.png` | Network discovery evidence |
| `zenmap_port_screenshot.png` | Port scanning evidence |
| `zenmap_topology_screenshot.png` | Topology visualization evidence |

## 🛠️ Tools & Technologies

- **Kali Linux** — Linux-based cybersecurity testing environment.
- **Oracle VirtualBox** — Virtualization platform used for the lab.
- **Nmap** — Network discovery and security scanning tool.
- **Zenmap** — Graphical interface for running and reviewing Nmap scans.

## 📚 Key Learning Outcomes

Through this module, I gained practical exposure to:

- Understanding network discovery techniques.
- Identifying active hosts within a lab network.
- Examining network scanning results.
- Understanding reported open ports and services.
- Working with Zenmap scan profiles.
- Interpreting Nmap scan output.
- Visualizing network information using Zenmap topology.
- Exporting and organizing scan evidence in TXT, XML and PDF formats.
- Documenting practical network assessment activities.

## 📁 Repository Structure

```text
PM5-Zenmap-Network-Scanning/
│
├── README.md
│
├── Scan-Results/
│   └── zenmap_scan_result.txt
│
├── Network-Topology/
│   ├── zenmap_results.xml
│   ├── zenmap_topology.pdf
│   └── zenmap_topology_screeenshot.png
│
└── Screenshots/
    ├── zenmap_intense_scan_screenshot.png
    ├── zenmap_ping_screenshot.png
    ├── zenmap_port_screenshot.png
    └── zenmap_topology_screenshot.png
```

## 🔒 Authorization & Responsible Use

All network scanning activities documented in this module were conducted within the authorized local virtual network

---
NETWORKWALKS · CYBERSECURITY INTERNSHIP · PM1

Prepared by IRFAN RS

Learn · Observe · Analyze · Document

---
