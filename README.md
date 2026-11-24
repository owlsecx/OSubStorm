# 🦉 OSubStorm

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OSubStorm** — Subdomain & DNS Intelligence Harvester

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

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, bundled CPython version, and every bundled library with its exact
  version and license. Feed it to Grype, Trivy or Dependency-Track to audit
  our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

**No telemetry, no analytics, no licence check-in.** This tool does not phone
home. Verify that claim yourself:

```bash
sudo strace -f -e trace=network ./OSubStorm --help   # watch every network call
firejail --net=none ./OSubStorm --help               # deny the network entirely
```

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)
