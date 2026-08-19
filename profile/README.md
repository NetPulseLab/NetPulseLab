# NetPulseLab

## Unified Logical-Physical Network Assurance: An AI-Guided System for Network Analysis, Optimization, and Rebuild in Cost-Constrained SME and Government Environments

> This organization hosts the research and development work for our final-year undergraduate project at the **University of Sri Jayewardenepura, Faculty of Technology (BICT Honours Degree Specialise in Networking)**.

---

## The Problem

Networks in SME and government environments tend to get messier as they age. Ad-hoc changes, undocumented relocations, and staff turnover mean the real physical and logical layout of the network is rarely reflected anywhere on paper — making it hard for a new engineer to understand the actual architecture, especially when a rack relocation or device swap needs to happen under time pressure.

Cost compounds the problem in different ways for each environment. Government organizations often continue running older devices and legacy firmware/software versions well past their typical refresh cycle. SMEs, meanwhile, are usually budget-constrained from the start and default to the cheapest available equipment and tooling.

In both cases, proprietary intelligent patch panel solutions such as **Cisco SD-Access, Panduit PearView iQ, CommScope imVision, and Siemon MapIT** are effectively out of reach — they solve the physical-logical mapping problem, but at a hardware cost these organizations can't justify.

This project builds a **software-based, commodity-infrastructure alternative** that infers physical connectivity through event correlation — **SNMP trap timing cross-referenced with CDP/LLDP and MAC address tables** — giving cost-constrained organizations the same visibility without proprietary hardware.

---

## System Architecture — Three Pillars

### 🔍 Analyzer

Discovers and maps the network's logical and physical topology using automated configuration retrieval (**Netmiko/NAPALM**) and structured parsing (**TextFSM**).

### ⚙️ Optimizer

Provides AI-guided recommendations for network configuration and performance improvements within cost constraints.

### 🔧 Rebuilder

Supports guided, human-in-the-loop physical layer verification and recovery, with closed-loop confirmation of changes.

---

## Team

### Group 05

| Role               | Name                           |
| ------------------ | ------------------------------ |
| Member — Team Lead | **Gammanpila G I I**           |
| Member             | **Thiwanka S M T P**           |
| Member             | **Ariyarathna U.M.G.D.R**      |
| Main Supervisor    | **Dr. Nuwan Kuruwitaarachchi** |
| Co-Supervisor      | **Dr. Nimal Skandakumar**      |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Netmiko](https://img.shields.io/badge/Netmiko-2C3E50?style=flat-square)
![NAPALM](https://img.shields.io/badge/NAPALM-2C3E50?style=flat-square)
![TextFSM](https://img.shields.io/badge/TextFSM-2C3E50?style=flat-square)
![EVE-NG](https://img.shields.io/badge/EVE--NG-1F2937?style=flat-square)
![SNMP](https://img.shields.io/badge/SNMP-1F2937?style=flat-square)
![CDP](https://img.shields.io/badge/CDP-1F2937?style=flat-square)
![LLDP](https://img.shields.io/badge/LLDP-1F2937?style=flat-square)
![GNS3](https://img.shields.io/badge/GNS3-1F2937?style=flat-square)
![Claude](https://img.shields.io/badge/Claude-D97706?style=flat-square)

**Python · Netmiko · NAPALM · TextFSM · EVE-NG · SNMP · CDP/LLDP · GNS3 · Claude**

---

## Research & Development

This project is being developed as part of our final-year undergraduate research project at the **University of Sri Jayewardenepura, Faculty of Technology**.

The project focuses on developing a practical and cost-conscious approach to combining **logical network analysis, physical connectivity inference, AI-guided optimization, and network rebuilding** within a single framework.

---

## Project Focus

* Logical network topology discovery
* Physical connectivity inference
* Network configuration analysis
* AI-guided network optimization
* Human-in-the-loop physical verification
* Automated network configuration retrieval
* Post-change network verification
* Cost-conscious network assurance

---

## Project Status

**Research & Development — In Progress**

---

## Keywords

`Network Automation` · `Network Assurance` · `Network Analysis` · `Network Optimization` · `Network Topology` · `Physical Connectivity` · `AI-Assisted Networking` · `SNMP` · `CDP` · `LLDP` · `Netmiko` · `NAPALM` · `TextFSM` · `EVE-NG` · `GNS3`
