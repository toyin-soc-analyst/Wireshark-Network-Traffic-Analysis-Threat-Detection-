# 🛡️ SOC-Level Network Traffic Analysis & Threat Detection Using Wireshark

## 🎯 Objective
To analyze network traffic using Wireshark and identify anomalies, suspicious behavior, and potential security threats across TCP, DNS, and ICMP protocols, simulating real-world SOC analysis.

---

## 📌 Project Overview
This project demonstrates hands-on experience analyzing real-world PCAP data using Wireshark to detect abnormal traffic patterns, investigate suspicious connections, and identify potential security threats.

---

## 🛠️ Tools & Technologies
- Wireshark
- TCP/IP Protocol Suite
- DNS Analysis
- Network Traffic Filtering
- Packet Inspection

---

## 🔍 Key Findings

- Identified high-volume traffic from internal IP **10.10.57.178**, indicating potential anomaly or abnormal behavior  
- Detected multiple TCP SYN packets targeting uncommon ports (e.g., **8888, 9999, 4444, 6666**), suggesting possible **port scanning activity**  
- Analyzed DNS query and response patterns to identify normal vs suspicious behavior  
- Detected packets with **invalid TCP checksum**, indicating possible malformed traffic or packet anomalies  
- Observed repeated connection attempts to external IPs, consistent with reconnaissance behavior  

---

## 📊 Sample Analysis

**Example Investigation:**
- Source IP: 192.168.1.100  
- Destination IP: 101.201.172.235  
- Protocol: TCP  
- Activity: SYN packets to multiple ports  
- Interpretation: Potential reconnaissance or port scanning attempt  

---

## 🧠 Skills Demonstrated
- Network Traffic Analysis  
- Threat Detection & Investigation  
- Packet Inspection (Wireshark)  
- Anomaly Identification  
- Cybersecurity Analysis  

---

## 📷 Screenshots

### Suspicious TCP Activity
(Add your screenshot here)

### DNS Traffic Analysis
(Add your screenshot here)

---

## 🚀 Key Takeaway
This project highlights the ability to analyze real-world network traffic, detect anomalies, and interpret potential security threats using industry-standard tools and methodologies aligned with SOC operations.
