# Attack-Surface-Tracker-with-Amass-Asset-DB
# 🛡️ OpenAssetMap – External Attack Surface Modeling

![License](https://img.shields.io/badge/license-apache%202-blue)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)

OpenAssetMap is a cybersecurity project built on top of the [OWASP Open Asset Model](https://github.com/owasp-amass/open-asset-model), designed to map and model the full spectrum of external digital assets — including IP addresses, domains, netblocks, and organizational entities. The tool emphasizes visualizing and understanding the complex relationships that form an organization's attack surface.

---

## 🔍 Overview

Traditional asset discovery focuses only on IP addresses and domain names. This project leverages the OWASP Open Asset Model to create a **rich taxonomy of cyber assets**, capturing their **relationships**, **interconnections**, and **evolution over time**.

The goal is to help organizations and security professionals:
- Model their digital footprint beyond just infrastructure.
- Detect hidden or interconnected attack vectors.
- Share asset data internally and externally with standardized formats.

---

## 🚀 Features

- 🔗 Graph-based asset relationship mapping
- 🌐 Support for FQDNs, IPs, Autonomous Systems, Netblocks, and more
- 📊 Visual asset taxonomy viewer (optional UI)
- 🧠 Structured storage for asset intelligence and change tracking
- 🧱 Built on Go (Golang) and compliant with OWASP Amass standards

---

## 📦 Tech Stack

- **Golang** – Primary language for data modeling and logic
- **OWASP Open Asset Model** – Base specification and data structure
- **Graph DB (Optional)** – For storing and querying relationships
- **JSON/YAML Support** – For data import/export and sharing
- **CLI Tools** – For asset input, modeling, and export

---

## 🛠️ Installation

> ⚙️ Requires Go 1.20+ installed

```bash
git clone https://github.com/yourusername/openassetmap.git
cd openassetmap
go build -o openassetmap main.go
./openassetmap --help
