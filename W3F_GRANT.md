# Terra Protocol – Open Grant Proposal

## 1. Project Overview
Terra is a governance-first coordination protocol built on Substrate.  
It introduces a modular rights-system (TERRA, GOVT, CREDIT), a revenue router, and a multi-layer governance engine suitable for real-world communities and public-good ecosystems.

This proposal covers Phase 0: governance specification, architecture, and pallet design.

**Repository:** https://github.com/Terra-Protocol/terra  
**Whitepaper (Technical):** https://github.com/Terra-Protocol/terra/blob/main/WHITEPAPER_GRANT.md  
**License:** MIT / Apache-2.0 (to be finalized)

---

## 2. Motivation
Current governance frameworks lack non-inflationary rights mechanisms, contribution-based governance, and programmable revenue sharing.

Terra introduces:
- TERRA (sovereign rights)
- GOVT (earned governance)
- CREDIT (elastic revenue rights)
- IMAP + CDC (safe early-stage onboarding governance)

This grant will produce the specifications and architecture required to implement these modules in Substrate.

---

## 3. Deliverables

### Milestone 1 – Governance Spec & Architecture  
Duration: 4–6 weeks  
Payment: $20,000

Deliverables:  
- Governance 2.0 spec  
- IMAP specification  
- CDC specification  
- WHITEPAPER_GRANT.md  
- ARCHITECTURE.md v2  
- Design notes for TERRA / GOVT / CREDIT

### Milestone 2 – Token Modules Design & Prototype  
Duration: 6–8 weeks  
Payment: $50,000

Deliverables:  
- pallet skeletons (TERRA, GOVT, CREDIT)  
- interfaces & data models  
- unit-test stubs  
- developer documentation in `/docs/specs`  
- local dev-chain configuration

### Milestone 3 – Revenue Router & Worker Engine  
Duration: 6–8 weeks  
Payment: $50,000

Deliverables:  
- revenue_router_pallet prototype  
- worker_engine logic  
- integrated minimal testnet  
- documentation + usage examples

---

## 4. Team

### Founder – Robin Schaarschmidt  
I am the conceptual architect and creator of the Terra governance model.  
My role is system design, governance logic, and coordination.  
A dedicated Substrate engineering team will be assembled in Phase 1 from the Polkadot ecosystem.

### Planned team hiring  
2–4 Substrate/Rust engineers  
hired through Polkadot community channels.

---

## 5. License
MIT or Apache-2.0

---

## 6. Future Plans
After completing this grant, Terra will propose:

- Phase 1: full prototype  
- Phase 2: on-chain governance engine + XCM Router  
- Phase 3: real-world pilot with Treasury support
