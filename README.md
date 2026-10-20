# SOC Home Lab & SIEM Integration Project

## 📌 Overview
This project demonstrates a practical Security Operations Center (SOC) home laboratory setup designed for enterprise security monitoring, log aggregation, and threat detection. It integrates **IBM QRadar SIEM** with endpoint monitoring solutions to simulate real-world cyber attack scenarios and analyze associated telemetry.

---

## 🛠️ Tech Stack & Infrastructure
* **SIEM Platform:** IBM QRadar SIEM
* **Log Collection Agents:** WinCollect (Physical Host Integrations)
* **Endpoint Telemetry:** Sysmon (System Monitor), Process Hacker
* **Operating Systems:** Windows 10 (Virtual Machine), Physical Host Machine, Kali Linux
* **Attack Emulation Tools:** Nmap, Hydra, Kali Linux Utilities

---

## 🏗️ Architecture & Network Setup
1. **Endpoint Monitoring:** Integrated Sysmon and WinCollect on the physical host to capture granular system telemetry (Process Creation, Network Connections, Service Installs).
2. **SIEM Integration:** Configured log sources within IBM QRadar SIEM to ingest events seamlessly via WinCollect over Windows Event Forwarding protocols.
3. **Attack Emulation & Detection:** Simulated various attack vectors (e.g., Port Scans, Brute-Force Authentication attempts) originating from Kali Linux against target endpoints to validate SIEM parsing and alert triggering.

---

## 🔍 Key Responsibilities & Capabilities Demonstrated
* **Log Ingestion & Parsing:** Successfully ingested and parsed Windows Security, Sysmon, and WinCollect event logs inside QRadar.
* **Offense Analysis:** Created and tuned custom correlation rules to detect suspicious behavior and investigate generated SIEM offenses.
* **Threat Detection:** Analyzed execution chains, process creation trees, and malicious network traffic patterns.

---

## 🎯 Key Takeaways & Learned Skills
* Hands-on experience with SIEM configuration, WinCollect deployment, and Sysmon telemetry tuning.
* Deeper understanding of attack lifecycle mapping against the MITRE ATT&CK framework.
* Practical incident response workflow: Telemetry Collection ➡️ Rule Triggering ➡️ Offense Triage ➡️ Investigation.

## 📸 Project Screenshots & Proof of Concept

### QRadar SIEM Offenses & Alerts
![SIEM Alert](Screenshot%20\(13\).png)

### Telemetry & Log Analysis
![Log Analysis](Screenshot%20\(14\).png)
