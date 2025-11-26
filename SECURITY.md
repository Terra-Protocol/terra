# Security Policy – Terra Protocol

Security is a core priority of Terra Protocol.  
We follow industry standards for responsible disclosure and aim to protect users, contributors, and the broader Polkadot ecosystem.

This document explains how to report vulnerabilities, how we review them, and our commitments to security.

---

# 🔐 1. Supported Versions

During Phase 1, Terra Protocol is in active development and does not yet maintain formal stable releases.  
The following branches are considered “supported” for security reports:

- `main` — active development  
- any tagged testnet release (when available)

Once stable releases exist, we will support the latest **two minor versions**.

---

# 📣 2. Reporting a Vulnerability

**Do NOT open a public GitHub issue.**  
Security vulnerabilities must be reported responsibly and privately.

### Please email:

👉 **terra-protocol-security@protonmail.com**  
*(placeholder — update with your preferred address)*

Your report should include:

- Description of the vulnerability  
- Steps to reproduce  
- Potential impact  
- Code or contract locations affected  
- Any relevant logs, screenshots, or PoC  

We will acknowledge receipt within **72 hours**.

---

# 🛠 3. Our Security Commitments

When you report a vulnerability, we promise:

- Acknowledgement within **72 hours**  
- Initial assessment within **7 days**  
- A fix or mitigation plan within **14 days** (depending on severity)  
- Coordination with you on public disclosure  
- Credit in release notes (if desired)

We aim to follow best practices from:

- Web3 Foundation  
- Substrate security guidelines  
- Responsible Disclosure standards  

---

# 🧪 4. Security Practices

Terra Protocol uses several security measures:

### ✔ Code Review  
All pull requests are reviewed by maintainers before merging.

### ✔ Least-privilege governance  
Economic and governance parameters go through OpenGov-compatible procedures.

### ✔ Internal Testing  
Unit tests, integration tests, and simulation tests are required for major modules.

### ✔ Avoidance of high-risk patterns  
We avoid:
- unbounded loops  
- unnecessary external calls  
- unsafe Rust blocks  
- direct property tokenization (regulatory risk)  
- global mutable state  

### ✔ Audits  
Internal reviews will be conducted during Phase 1.  
Formal third-party audits may follow in Phase 2.

---

# 📦 5. Scope

The following components are considered part of the Terra Protocol security boundary:

- Rights-Based Tokenization Engine  
- XCM Payment Router  
- Governance Integration Layer  
- Revenue Router  
- Terra SDK (Rust + TypeScript)  
- Smart contracts deployed on Moonbeam  
- Any code under the `Terra-Protocol/` GitHub organization  

---

# 🚫 6. Out-of-Scope

The following are *not* covered by this security policy:

- Social engineering attacks  
- Lost private keys / user wallet security  
- Phishing on external platforms  
- Issues caused by modified or unofficial forks  
- Third-party dependencies (unless integrated directly into core modules)

---

# 🔁 7. Public Disclosure Policy

After a fix is implemented and validated:

1. A security advisory is published in the repository  
2. Release notes include credit (optional)  
3. Relevant documentation is updated  
4. Deprecated or unsafe patterns are removed  

Severe vulnerabilities affecting Polkadot components (XCM, OpenGov, etc.) will be coordinated with relevant ecosystem teams.

---

# 🙏 8. Responsible Disclosure

We deeply appreciate responsible security research.  
By following this policy, you help ensure that Terra Protocol remains safe for:

- builders  
- contributors  
- communities  
- the Polkadot ecosystem  

Thank you for helping make Terra Protocol secure.
