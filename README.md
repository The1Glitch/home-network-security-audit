# 🛡️ Home Network Security Audit

A practical cybersecurity audit of a live home network, showcasing my ability to identify vulnerabilities, analyze traffic, and recommend improvements using industry-standard tools. This project simulates the kind of work performed by entry-level security analysts and technical support engineers.

---

## 🎯 Objectives

- Map all connected devices and services
- Evaluate router and Wi-Fi security configurations
- Capture and analyze network traffic for anomalies
- Document findings and propose actionable security enhancements

---

## 🧪 Methodology

| Phase | Description |
|------|-------------|
| 🔍 **Reconnaissance** | Used Nmap to scan the network and identify active hosts, open ports, and service versions |
| 🔐 **Configuration Review** | Audited router settings including encryption, remote access, firmware version, and DHCP leases |
| 🕵️ **Traffic Analysis** | Captured packets with Wireshark to inspect DNS queries, HTTP requests, and suspicious traffic |
| 📄 **Reporting** | Compiled findings into a structured report with prioritized recommendations |

---

## 🧰 Tools & Technologies

- **Nmap** – Host discovery and port scanning  
- **Wireshark** – Deep packet inspection  
- **Router Admin Panel** – Configuration and firmware audit  
- **Markdown & GitHub** – Documentation and version control

---

## 📂 Repository Structure

---

## 🔍 Sample Findings

| Category | Issue | Severity | Recommendation |
|---------|-------|----------|----------------|
| Device Discovery | Unknown device detected | ⚠️ Medium | Investigate MAC address and isolate if unrecognized |
| Router Config | UPnP enabled | ⚠️ Medium | Disable to prevent external access vulnerabilities |
| Traffic | DNS queries to tracking domains | ⚠️ Low | Use DNS filtering or Pi-hole to block trackers |
| Protocols | SMB signing not enforced | ⚠️ Medium | Enforce signing to prevent man-in-the-middle attacks |

---

## ✅ Key Outcomes

- Improved router security posture
- Identified and documented potential risks
- Demonstrated ability to conduct a full audit cycle
- Created a reusable framework for future network assessments

---

## 👩🏽‍💻 About the Author

**Bonolo Mashabela**  
Cybersecurity Enthusiast | Backend Developer | IT Support Specialist  
📍 Pretoria, South Africa  
🎓 Certified in Full Stack Development, Digital Marketing, and Networking Basics

