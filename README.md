# 🛡️ Cybersecurity Intelligence Agent (Colab-Based Project)

A modular cybersecurity threat detection agent built entirely using **free tools** in **Google Colab**. This project showcases real-world cyber defense workflows — from threat feed ingestion and phishing detection to malware sandboxing and PCAP traffic analysis — all runnable without paid services or local setup.

---

## 🚀 Features

### 🔹 1. Threat Intelligence Feed Integration
- Pulls real-time IOCs from **AlienVault OTX**
- Parses indicators like IPs, domains, and hashes

### 🔹 2. Phishing Email Detection
- Uses **zero-shot NLP model** (`facebook/bart-large-mnli`) to classify email text
- Detects phishing, spam, or safe intent without training

### 🔹 3. IOC Log Correlation
- Scans server logs for malicious IPs, hashes, and suspicious commands
- Highlights **Indicators of Compromise** using regex patterns

### 🔹 4. Malware Sandboxing (Simulated)
- Parses real **sandbox JSON reports**
- Extracts dropped files, contacted IPs, queried domains

### 🔹 5. PCAP Network Analysis
- Uses **Scapy** to inspect `.pcap` files in Colab
- Extracts IP traffic, suspicious ports, DNS activity

---

## 📂 Folder Contents

| File | Description |
|------|-------------|
| `Cybersecurity_Intelligence_Agent.ipynb` | Main notebook (Colab-ready) |
| `requirements.txt` | Python dependencies |
| `sample_logs.txt` | IOC test logs |
| `malware_report.json` | Simulated sandbox output |
| `4SICS-GeekLounge-151021.pcap` | Public PCAP test file |

---

## 🧠 Tools & Libraries Used

- `transformers`, `torch` – NLP classification
- `requests` – API integration
- `scapy` – Packet inspection
- `json`, `re` – IOC parsing
- `pandas`, `nest_asyncio`, `pyshark` (optional)

---

## ▶️ Run in Colab

> Open this notebook in Google Colab to try it instantly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O7ySZzb2gf2cb24fuCxuI958X8sexBPo?usp=sharing)

---

Sure! Here's a customized version for you, Koushik, that presents a polished and professional image for recruiters:

---

## 👨‍💻 Author

**Koushik Kanneti**
🎓 MS in Business Analytics, University of Illinois Urbana-Champaign
📡 Background in Electronics & Communication Engineering
📊 Passionate about Data Science, AI Applications, and Tech-Driven Business Strategy
📫 [LinkedIn](https://www.linkedin.com/in/koushik-k-796900202/) • [Email](koushikkanneti123@gmail.com)

---



## 🏁 Note

This project demonstrates:
- Real-world cybersecurity engineering
- API integration, NLP, log forensics, malware analysis, packet inspection
- Ability to build an end-to-end system using **only free and open-source tools**

Feel free to connect or reach out!

