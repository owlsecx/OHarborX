# 🦉 OHarborX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OHarborX** — Harbor Container Registry Server Config Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OHarborX — Harbor Container Registry Server Config Auditor. It provides stdlib YAML-lite / env / nginx.conf / JSON parsers. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib YAML-lite / env / nginx.conf / JSON parsers
- harbor.yml & harbor.yml.tmpl — admin / DB / Redis secrets, external_url, HTTPS, internal TLS, logging, Trivy policy, jobservice, notification, metrics, proxy, storage_service, version end-of-life
- common/config — core / jobservice / registry / registryctl / nginx / portal / trivy-adapter
- docker-compose.yml for the Harbor stack — exposed internal ports, privileged, docker.sock, secrets
- Auth — db_auth, LDAP / OIDC / UAA verify_cert, self-registration, project creation restriction
- JSON exports — projects, members, robot accounts, registry endpoints / proxy-cache upstreams

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OHarborX                                     # interactive menu
./OHarborX --scan -r /path/to/root
./OHarborX --demo
./OHarborX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
