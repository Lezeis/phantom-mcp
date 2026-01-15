<div align="center">
  <img src="assets/img/logo.png" alt="Phantom Logo" width="450" />

  # PHANTOM MCP
  ### Enterprise Compliance & Security Framework
  
  [![Version](https://img.shields.io/badge/version-2.1.0-FF4444?style=for-the-badge&logo=shield)](https://github.com/mokhalifa83/phantom-mcp)
  [![License](https://img.shields.io/badge/license-MIT%20Enterprise-blue?style=for-the-badge)](LICENSE)
  [![Security](https://img.shields.io/badge/security-AUTHORIZED-green?style=for-the-badge&logo=lock)](docs/professional_audit_guide.md)
  
  <p align="center">
    <b>Authorized Security Auditing for the Modern Enterprise</b>
    <br />
    <br />
    <a href="https://mokhalifa.site"><strong>Explore the Docs »</strong></a>
    ·
    <a href="https://mokhalifa.site">View Demo</a>
    ·
    <a href="https://github.com/mokhalifa83/phantom-mcp/issues">Report Bug</a>
  </p>
</div>

---

## 🏛️ Project Overview

**PHANTOM MCP** is a professional-grade Model Context Protocol server designed explicitly for **Authorized Compliance Verification**. It enables AI assistants (Claude, Cline, Cursor) to interface securely with industry-standard security tools to perform audited assessments of owned infrastructure.

### 👤 Author & Maintainer

*   **Lead Architect:** [Mohamed Khalifa](https://mokhalifa.site)
*   **Portfolio:** [mokhalifa.site](https://mokhalifa.site)

---

## ⚡ Key Capabilities

| Compliance Module | Industry Standard | Capabilities |
| :--- | :--- | :--- |
| **Network Assurance** | **NIST 800-115** | Deep infrastructure analysis, port verification. |
| **AppSec Verification** | **OWASP ASVS** | Web vulnerability assessment, XSS/SQLi validation. |
| **Access Control** | **ISO 27001** | Authentication strength testing, password policy checks. |
| **Patch Management** | **CIS Controls** | CVE verification, exploit resistance testing. |

---

## 🔌 Universal Client Integration

PHANTOM runs on **Any** MCP-compatible client.

### 1. Claude Desktop (Native)
Seamless integration with Anthropic's native desktop app.
> *See: `docs/universal_setup.md` for JSON config.*

### 2. Cline / VS Code
Full support for the Cline extension, including auto-approved context.
> *See: `docs/cline_setup.md` for extension settings.*

### 3. Docker (Containerized)
Run as an isolated, secure container service.
```bash
docker-compose up -d
```

---

## 🛠️ Quick Start

1.  **Clone**
    ```bash
    git clone https://github.com/mokhalifa83/phantom-mcp.git
    cd phantom-mcp
    ```

2.  **Install**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run**
    ```bash
    python -m phantom.server
    ```

---

## 🔐 Disclaimer

**FOR AUTHORIZED USE ONLY.**
This software is provided for educational and professional compliance purposes. Usage of this tool for attacking targets without prior mutual consent is illegal.

<div align="center">
  <small>&copy; 2026 Mohamed Khalifa. All Rights Reserved.</small>
</div>
