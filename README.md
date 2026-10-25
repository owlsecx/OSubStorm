# 🦉 OSubStorm

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OSubStorm** — Subdomain & DNS Intelligence Harvester ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OSubStorm is a passive subdomain and DNS intelligence harvester that aggregates results from many public OSINT sources such as crt.sh, HackerTarget, AlienVault OTX, RapidDNS, URLScan.io and Archive.org. It resolves discovered hosts, probes them over HTTP, performs whois lookups and detects wildcards and potential subdomain takeovers. Results export to TXT, JSON, CSV or HTML with rate-limit awareness and multi-domain support.

---

## ✨ Features


- Passive aggregation from crt.sh, HackerTarget, BufferOver, AlienVault OTX, RapidDNS, URLScan.io and more
- DNS resolution, HTTP probing and whois lookup for discovered subdomains
- Wildcard detection and subdomain-takeover hints
- Multi-domain input with a source selector and session history
- Rate-limit-aware requests with coloured output and progress bars
- Export to TXT, JSON, CSV and HTML with an optional auto-save

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OSubStorm
./OSubStorm --self-test
./OSubStorm --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
