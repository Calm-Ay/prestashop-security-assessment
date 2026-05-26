# PrestaShop Security Assessment Report

![Security](https://img.shields.io/badge/Type-Web%20App%20Security-orange?style=for-the-badge&logo=shield)
![Platform](https://img.shields.io/badge/Platform-PrestaShop-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-Rasaq%20Ayomide-blue?style=for-the-badge)

> A detailed security assessment of a PrestaShop e-commerce deployment, identifying vulnerabilities, misconfigurations, and attack vectors with full remediation guidance.

---

## Overview

This report documents a thorough security assessment performed against a PrestaShop e-commerce application. The assessment covers the full attack surface including authentication, authorization, input handling, session management, and server-side configurations.

---

## Contents

| File | Description |
|------|-------------|
| `PrestaShop_Security_Assessment_Report.docx` | Full security assessment report with vulnerability details, proof-of-concept, and fixes |

---

## Key Areas Covered

- **Authentication & Authorization Testing** — Brute force, privilege escalation, broken access control
- **Input Validation** — SQL Injection, XSS, Command Injection, File Upload vulnerabilities
- **Session Management** — Cookie security, session fixation, token analysis
- **API & Admin Panel Security** — Exposed endpoints, weak credentials, misconfigured permissions
- **Server & Configuration Review** — SSL/TLS, HTTP headers, directory listing, error disclosure
- **Third-Party Plugins** — Vulnerability assessment of installed PrestaShop modules

---

## Vulnerability Summary

| Severity | Count |
|----------|-------|
| 🔴 Critical | — |
| 🟠 High | — |
| 🟡 Medium | — |
| 🟢 Low | — |

> *Full details are in the report document.*

---

## Methodology

- **OWASP Top 10** — Web application vulnerability classification
- **OWASP WSTG** — Web Security Testing Guide
- **Manual Testing + Automated Scanning** — Burp Suite, Nikto, WPScan-equivalent tools

---

## Disclaimer

> This security assessment was conducted in an authorized, controlled lab environment for educational purposes only. All findings are reported responsibly. Do not attempt to replicate these techniques on systems you do not own or have explicit written permission to test.

---

## Author

**Rasaq Ayomide**
Security Researcher | Web Application Penetration Tester
- GitHub: [@Calm-Ay](https://github.com/Calm-Ay)
- Email: 210804102@live.unilag.edu.ng
