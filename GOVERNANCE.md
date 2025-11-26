# Governance – Terra Protocol

This document defines how decisions are made in the Terra Protocol project.  
Governance ensures transparency, accountability, and long-term sustainability of the protocol and its ecosystem.

Terra Protocol uses a **three-layer governance system**:

1. **Project Governance (GitHub-based)**  
2. **Protocol Governance (TerraDAO)**  
3. **Ecosystem Governance (Polkadot OpenGov)**  

Each layer has a distinct role and authority.

---

# 🧩 1. Project Governance (GitHub)

This governs the **open-source development process**.

### Maintainer Responsibilities
- Review and merge pull requests  
- Maintain code quality  
- Approve releases  
- Manage repository structure  
- Ensure security and documentation standards  

### Decision Making
- Minor decisions → Maintainers  
- Major architectural decisions → Maintainers + community discussion  
- Breaking changes → Maintainers + advisory contributors  

### Voting  
At this stage, project governance uses **rough consensus**, meaning:

> “The maintainers, with community input, determine the best technical direction.”

Formal voting begins once TerraDAO is live.

---

# 🌐 2. Protocol Governance (TerraDAO)

Once live, Terra Protocol will be governed by **TerraDAO**, using:

- **TERRA** → economic rights token  
- **GOVT** → governance voting token  
- **WORK** → internal economy token (non-governance)  

### 2.1 Governance Authority

TerraDAO governs:

- Budget allocations  
- Worker compensation parameters  
- Rights-token metadata and rules  
- Revenue router configuration  
- Treasury allocations (DAO treasury, not Polkadot Treasury)  
- Economic parameters (e.g., bonding curve settings)  
- Pilot project approvals  
- Distribution of ecosystem incentives  

### 2.2 Token Governance Model

Terra uses a **dual-governance model**:

#### **GOVT Token (Voting Power)**
- Earned through contribution & participation  
- Not tied to economic rights  
- Used for:  
  - parameter changes  
  - budget approvals  
  - rights issuance rules  
  - project onboarding  

#### **TERRA Token (Economic Rights)**
- Does *not* provide direct governance power  
- Used for:  
  - revenue share  
  - ownership of economic privileges  
  - economic participation  

This separation avoids plutocracy and aligns with regulatory safety.

### 2.3 Voting Process

Standard flow:

1. Proposal submitted  
2. Discussion phase (off-chain or on-chain)  
3. Formal vote using GOVT token  
4. Execution via governance module  

Votes require:

- Minimum participation threshold  
- Majority approval  
- Optional conviction multiplier (similar to Polkadot)  

---

# 🏛 3. Ecosystem Governance (Polkadot OpenGov)

For cross-chain decisions, Terra aligns with **Polkadot OpenGov**.

Examples of decisions requiring OpenGov:

- Treasury funding  
- Polkadot-level integrations  
- XCM parameter changes affecting network-wide behavior  
- Ecosystem-wide economic standards  

Terra Protocol commits to:

- Full transparency with OpenGov  
- Submitting proposals when appropriate  
- Participating in governance discussions  
- Returning value to the Polkadot Treasury (Phase 2+)  

---

# 🔄 4. Governance Lifecycle

### Stage 1 — Proposal  
A request for change (RFC) is created.

Types:
- Feature  
- Parameter update  
- Budget request  
- Rights issuance rule  
- Treasury allocation  

### Stage 2 — Discussion  
Occurs via:

- GitHub Issues  
- TerraDAO channels (once live)  
- Polkadot OpenGov (if required)

### Stage 3 — Voting  
- GOVT token → Internal governance  
- OpenGov → Polkadot-level governance  

### Stage 4 — Execution  
After a proposal passes:

- Code changes are implemented  
- Economic settings updated  
- Contracts/modules deployed  
- Documentation updated  

---

# 🧱 5. Governance Hierarchy (Simplified)

```text
┌──────────────────────────────────────────────────────┐
│                    Polkadot OpenGov                  │
│      (Treasury, cross-chain, ecosystem-wide rules)   │
└───────────────▲───────────────────────────────▲──────┘
                │                               │
                │ XCM / Funding / Interop        │
                │                               │
┌───────────────┴───────────────────────────────┴──────┐
│                       TerraDAO                        │
│     (protocol rules, economic params, budget, RWA)    │
└───────────────▲───────────────────────────────▲──────┘
                │                               │
                │ Contribution / Code changes    │
                │                               │
┌───────────────┴───────────────────────────────┴──────┐
│                 Project Maintainers (GitHub)           │
│           (development, updates, releases)             │
└────────────────────────────────────────────────────────┘
---

# 📅 6. Governance Roadmap

### Phase 1 (Current)
- Maintainer-led governance  
- Community input via GitHub  
- GOVT token not launched yet  
- Voting simulated off-chain  

### Phase 2
- TerraDAO launch  
- GOVT token activated  
- On-chain proposals enabled  
- Worker incentives + rights rules live  

### Phase 3
- Multi-community governance  
- XCM-level governance interactions  
- Optional OpenGov integration for major decisions  

---

# 📬 7. Contact

For governance-related questions:

- GitHub Issues  
- TerraDAO channels (coming soon)  
- Polkadot community forums  

---

# 🤝 8. Commitment

Terra Protocol is committed to:

- transparent decision-making  
- responsible governance  
- community-driven development  
- alignment with Polkadot’s public-good philosophy

We believe governance should be open, inclusive, and accountable — ensuring Terra becomes a foundational layer for real-world economic systems.
---
