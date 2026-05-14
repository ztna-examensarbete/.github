# Zero Trust Network Access — Degree Project 2026

This organisation hosts the degree project of **Martin Karlsson** and **Elin Olsson**,
students of the **Network Security Specialist (SN24)** programme at
**Folkuniversitetet Gothenburg**.

The project explores how **Zero Trust Network Access (ZTNA)** principles can be
put into practice with open source software only — no commercial platforms,
no cloud services.

## Project

### [sn24-ztna](https://github.com/ztna-examensarbete/sn24-ztna)

A ZTNA gateway built and verified in a GNS3 lab environment:

- A Linux gateway acting as the **Policy Enforcement Point (PEP)**
- **OIDC authentication** via Dex and OAuth2-Proxy
- **Identity-based policy** in Nginx (L7) and **microsegmentation** with nftables (L3)
- Default deny, logging at every step, verified with reproducible test cases

The repository carries the design documentation, configuration guides, threat
model and test plan — how the environment was built and verified.
