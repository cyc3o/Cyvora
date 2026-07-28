<p align="center">
  <img src="https://img.shields.io/badge/PYTHON-3.9%2B-blue" />
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-success" />
  <img src="https://img.shields.io/badge/LICENSE-MIT-blue" />
  <img src="https://img.shields.io/badge/TYPE-SOC%20TOOLKIT-orange" />
  <img src="https://img.shields.io/badge/PLATFORM-CLI-lightgrey" />
  <img src="https://img.shields.io/badge/PURPOSE-EDUCATIONAL-yellow" />
</p>

<h1 align="center">Log Processing Threat Correlation Platform</h1>
<p align="center"><b>SOC-Grade Log Analysis, Detection & Reporting Engine (Python)</b></p>

---

## Overview


Elite SOC Analyzer is a SOC-style log analysis and alerting engine built in Python, made for educational, research, and portfolio use. It shows how SOC tools work under the hood — log ingestion, detection logic, alert generation, risk scoring, MITRE ATT&CK mapping, IOC extraction, and reporting. Not a replacement for enterprise SIEM platforms like Splunk, QRadar, Sentinel, or ELK.

## Key Objective

Learn real-world SOC analyst and blue team workflows. Practice building security tooling in Python. Understand alert pipelines and SOC reporting logic. End up with a realistic, portfolio-ready cybersecurity project.

## Core Features

Log file analysis for auth, system, and generic logs. Rule-based detection logic. Behavioral and anomaly detection concepts. Alert generation with severity levels. MITRE ATT&CK technique mapping. Risk and severity scoring. IOC extraction for IPs, users, and Tor indicators. JSON and CSV report generation. Persistent master CSV for historical alerts. IOC feed export in JSON. Analyst-friendly CLI interface. Modular, clean Python architecture.

## Installation

**Requirements:** Python 3.x, lightweight commonly-available Python libraries, no enterprise/cloud/paid dependencies.

```bash
git clone https://github.com/cyc3o/ELITE-SOC-ANALYZER.git
cd ELITE-SOC-ANALYZER
python main.py
```
