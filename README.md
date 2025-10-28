

# 🔍 HTTPS PCAP Analysis

A beginner-friendly HTTPS-focused packet capture analysis.  
This repository demonstrates how to extract, filter, and analyze encrypted web traffic (HTTPS) using **Wireshark** — an essential skill for **SOC analysts** and **digital forensics** professionals.

---

## 📁 Files Included
- `https_traffic.pcap` – Original HTTPS packet capture file.  
- `analysis/https_pcap_analysis_notes.md` – Step-by-step analysis with answers and filters.  
- `filters.txt` – Wireshark filters used during investigation.

---

## 🔧 Tools Used
- **Wireshark** – For network packet inspection.  


---

## 🧪 Analysis Performed
- Identified and inspected encrypted HTTPS sessions.  
- Traced web interactions with the domain `web01.fruitinc.xyz`.  
- Located file access and photo retrieval within Slack web traffic.  
- Extracted router credentials from local HTTP management pages.  
- Verified certificate status via OCSP responses.  
- Found user email related to password reset activity.  
- Mapped a service assignment to a network interface (`lan:ntp`).

---

## 🧠 Key Learnings
- How to analyze **HTTPS traffic metadata** (SNI, OCSP, Certificates).  
- How to use **Wireshark filters** effectively for encrypted sessions.  
- How to reconstruct events using **Follow Stream**.  
- Importance of **context-based analysis** in SOC and DFIR workflows.  
- Recognizing patterns of **user activity** and **network device communication**.

---

## 📌 Use Case
This repository is designed for:
- Students learning **cyber forensics** or **SOC Level 1** operations.  
- Beginners practicing **Wireshark HTTPS analysis**.  
- Analysts exploring **metadata-based triage** in encrypted traffic.  
- Anyone documenting PCAP-based case studies for portfolio building.

---

## 📬 Contact
If you’re also learning cybersecurity or want to collaborate on forensics projects:

📧 **Email:** nitinnsharma48@gmail.com  
🐦 **Twitter:** [@cyberNSharma](https://twitter.com/cyberNSharma)  
🔗 **LinkedIn:** [www.linkedin.com/in/cybernsharma](https://www.linkedin.com/in/cybernsharma)

---

## ⭐ Give a Star!
If this project helped you learn packet analysis, please **⭐ star** the repo to support more beginner-friendly **cybersecurity and SOC-focused** projects!

---

**Author:** Nitin Sharma  
**Category:** Cyber Forensics / Blue Team  
**Topic:** HTTPS PCAP Analysis  
**Tool:** Wireshark
