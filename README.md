# SentinelEye---Network-Traffic-Analyzer-IDS-Python-
sentinel-eye/ ├── src/ │   ├── sniffer.py │   ├── detector.py │   ├── alert.py │   └── web_dashboard.py ├── config/ │   └── rules.yaml ├── tests/ ├── requirements.txt ├── README.md └── .gitignore
# SentinelEye - Network Traffic Analyzer & IDS

A lightweight, educational network monitoring tool that captures packets, detects suspicious activities, and generates security alerts in real-time.

![SentinelEye Dashboard](screenshot.png)

## ⚠️ Legal Disclaimer

This tool is for **educational purposes only**. Only use it on networks you own or have explicit permission to test. Unauthorized network monitoring may violate laws and regulations.

## Features

- 📡 Real-time packet capture and analysis
- 🚨 Threat detection (port scans, DDoS attempts, brute force)
- 📊 Protocol distribution visualization
- 🔍 Suspicious port monitoring
- 🕵️ Sensitive data exposure detection
- 📈 HTML report generation with graphs
- ⚙️ Customizable YAML rules
- 🖥️ Cross-platform (Linux, Windows, macOS)

## Prerequisites

- Python 3.8+
- Administrator/root privileges (for packet capture)
- Npcap (Windows) or libpcap (Linux)

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/sentinel-eye.git
cd sentinel-eye
