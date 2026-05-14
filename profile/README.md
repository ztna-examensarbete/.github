<h1 align="center">Zero Trust Network Access</h1>

<p align="center">
  <em>Degree project 2026 · Network Security Specialist (SN24)</em><br>
  <strong>Martin Karlsson &amp; Elin Olsson</strong> · Folkuniversitetet Gothenburg
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/Platform-GNS3-blue" alt="Platform">
  <img src="https://img.shields.io/badge/OS-Debian%2012-red" alt="OS">
  <img src="https://img.shields.io/badge/License-CC%20BY%204.0-blue" alt="License">
</p>

---

This organisation hosts a degree project exploring how **Zero Trust Network Access (ZTNA)**
principles can be put into practice with open source software only — no commercial
platforms, no cloud services.

## Project

### [sn24-ztna](https://github.com/ztna-examensarbete/sn24-ztna)

A ZTNA gateway built and verified in a GNS3 lab environment.

| Principle | Implementation |
| :--- | :--- |
| **Always verify** | OIDC authentication via Dex and OAuth2-Proxy |
| **Least privilege** | Identity-based policy in Nginx (L7) + nftables (L3) |
| **Assume breach** | Default deny, microsegmentation, logging at every step |

The repository carries the design documentation, configuration guides, threat model
and test plan — how the environment was built and verified.
