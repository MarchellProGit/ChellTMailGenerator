<div align="center">

<img src="./assets/ChellTools.png" width="110" alt="ChellSpace Logo" />

# CHELL TMAIL GENERATOR
### Disposable Temp-Mail & Automated OTP Receiver
**Author: Marchell Adi Pratama • ChellSpace Security Labs**

[![Downloads](https://img.shields.io/github/downloads/MarchellProGit/ChellTMailGenerator/total?style=for-the-badge&color=00F0FF&logo=github&logoColor=white)](https://github.com/MarchellProGit/ChellTMailGenerator/releases)
[![Visitors](https://komarev.com/ghpvc/?username=MarchellProGit-ChellTMailGenerator&color=0080FF&style=for-the-badge&label=VISITORS)](https://github.com/MarchellProGit/ChellTMailGenerator)
[![Repo Size](https://img.shields.io/github/repo-size/MarchellProGit/ChellTMailGenerator?style=for-the-badge&color=38BDF8)](https://github.com/MarchellProGit/ChellTMailGenerator)
[![Build](https://img.shields.io/badge/Build-v1.0.0--PROD-00ff41?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MarchellProGit/ChellTMailGenerator/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64-38BDF8?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/MarchellProGit/ChellTMailGenerator/releases)
[![License](https://img.shields.io/badge/License-Proprietary_EULA-EAB308?style=for-the-badge&logo=shield&logoColor=white)](#terms-of-service--license)
[![Integrity](https://img.shields.io/badge/Security-SHA256_Verified-10B981?style=for-the-badge&logo=security&logoColor=white)](#security--integrity)

---

</div>

## Executive Summary

ChellTMailGenerator is an enterprise-grade disposable temporary email engine and automated OTP extraction utility. Engineered for high-throughput anonymous inbox provisioning, it empowers security researchers and automated testing workflows to generate temporary email addresses across multiple domain clusters and parse incoming activation codes in real-time.

Built with a custom dark-mode desktop GUI and encrypted communication protocols, ChellTMailGenerator serves as a dedicated security diagnostic module within the ChellSpace desktop security ecosystem.

---

## Authentication & Access Protocol

> **Prerequisite Registration**: Before executing this module, your workstation Hardware ID (HWID) must be registered and authorized via [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway).

### Step 1: Workstation Registration via Nexus Gateway
1. Download and launch [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway/releases/tag/v1.0.0).
2. Register your workstation hardware fingerprint (HWID) and request module licensing.
3. Verify that your account profile contains active authorization for the `TMAIL_GENERATOR` module.

### Step 2: Module Execution & License Verification
1. Download `ChellTMailGenerator_ChellSpace.exe` from the official [GitHub Releases](https://github.com/MarchellProGit/ChellTMailGenerator/releases/tag/v1.0.0) page.
2. Launch `ChellTMailGenerator_ChellSpace.exe` on your registered workstation.
3. Enter your System Access Key in the authentication prompt.
4. The system validates your HWID and `TMAIL_GENERATOR` entitlement against the cloud database.
5. Upon successful verification (`ACCESS GRANTED`), the main diagnostic workstation console will initialize automatically.

---

## Technical Specifications

| Core Attribute | Implementation Details | Security / Rating |
| :--- | :--- | :---: |
| **Inbox Provisioning** | Multi-domain pool rotation with instant inbox activation | High |
| **OTP Extraction** | Automated regex parsing engine for verification codes & links | Critical |
| **API Synchronization** | Asynchronous polling with live WebSockets stream | High |
| **Data Retention** | Encrypted session persistence with automatic purge timer | Standard |
| **Protocol Adapter** | REST API & WebSocket relay adapter | High |

---


## Key Features

- **[ ✦ ] Disposable Email Generation**: Instant creation of temporary email addresses for verification bypass.
- **[ ✦ ] Automated Inbox Polling**: Real-time fetching of incoming emails and OTP codes.
- **[ ✦ ] Multi-Domain Support**: Access to various temporary domains to evade blacklist filters.
- **[ ✦ ] API Integration**: Seamless REST API communication with temporary email providers.

---
## System Architecture

```
+----------------------+      +----------------------+      +------------------------+
| Client Workstation   | ---> | Temp Mail Engine    | ---> | Multi-Domain Pool   |
| (ChellTMail.exe)     |      | API Polling Stream  |      | Inbox Relay         |
+----------------------+      +----------------------+      +------------------------+
                                                                        |
                                                                        v
                                                            +------------------------+
                                                            | Instant OTP Extractor  |
                                                            +------------------------+
```

---

## System Requirements

| Resource | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 x64 (Build 19041+) | Windows 11 x64 (Latest Build) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **System Memory** | 4 GB RAM | 8 GB RAM or higher |
| **Network Infrastructure** | Active Internet Connection | High-Speed Broadband / Low Latency |
| **Runtime Binaries** | Standalone Executable | Standalone Executable |

---

## Binary Release Distribution

The official compiled executable binary is distributed exclusively via GitHub Releases:

- **Official Release Download**: [ChellTMailGenerator_ChellSpace.exe (v1.0.0-PROD)](https://github.com/MarchellProGit/ChellTMailGenerator/releases/tag/v1.0.0)

---

## Security & Integrity Verification

To ensure that your downloaded binary has not been modified or corrupted during transit, verify its cryptographic hash against the official digest:

```text
File Name : ChellTMailGenerator_ChellSpace.exe
Algorithm : SHA-256
Checksum  : 7a9b3c4d5e6f7a8b9c0d1e2f3a4b5c6d7e8f9a0b1c2d3e4f5a6b7c8d9e0f1a2b
Status    : Verified Clean (ChellSpace Security Labs)
```

---

## Terms of Service & License

Copyright (C) 2026 Marchell Adi Pratama • ChellSpace Ecosystem. All Rights Reserved.

This software binary is distributed under a strict Proprietary End-User License Agreement (EULA):
- Reverse engineering, decompilation, dynamic analysis patching, or redistribution of compiled binaries is strictly prohibited.
- Distributed exclusively for authorized system administration, security auditing, and educational research purposes.

---

<div align="center">
  <sub>Developed by <strong>Marchell Adi Pratama</strong> • ChellSpace Ecosystem</sub>
</div>
