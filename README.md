# Author: Steven Estill Jr
# Date: Mar 21 2026
# SOC_Project

# 🔐 Home Lab SOC (Wazuh + Attack Simulation)

> Hands-on Security Operations Center (SOC) lab simulating attacks and monitoring with Wazuh.

---

## 🧱 Lab Architecture
- **Ubuntu Server (Wazuh Manager)** – Central SIEM for log collection and alerting  
- **Windows Server 2022 (Victim)** – Wazuh agent installed, endpoint monitoring  
- **Kali Linux (Attacker)** – Used for offensive testing and attack simulation  

---

## ⚙️ Key Implementations
- Deployed Wazuh SIEM on Ubuntu and integrated Windows agent  
- Simulated attacks from Kali Linux and monitored Wazuh alerts  
- Collected logs, analyzed events, and investigated alerts  

---

## 🎯 Objectives
- Gain practical SOC experience  
- Understand attack detection and log analysis  
- Practice incident investigation in a controlled lab environment  

---

## 🛠️ Skills Demonstrated
- SIEM Configuration & Management (Wazuh)  
- Threat Detection & Log Analysis  
- Offensive Security Testing (Kali Linux)  
- Virtualization & Lab Setup  

---

## 📸 Visuals

### Wazuh Dashboard
![Wazuh Dashboard](screenshots/wazuh-dashboard.png)

### Example Attack Alert
![Attack Alert](screenshots/attack-alert.png)

### Lab Topology Diagram
![Lab Diagram](screenshots/lab-diagram.png)

> *Tip: Replace the above images with your actual screenshots in the `screenshots` folder.*

---

## 🔗 Optional Folders
- **`attacks/`** – Show example attack commands, logs, and alerts  
- **`diagrams/`** – Network diagram, lab layout, or architecture visuals  

---

> This repo demonstrates a fully functional SOC lab, simulating real-world attack scenarios and providing visibility into endpoint and network events.
