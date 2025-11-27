# Terra Protocol – Grant Whitepaper (Technical Version)

**Version:** 1.0  
**Author:** Robin Schaarschmidt  
**Status:** Grant Submission Draft  
**License:** MIT / Apache-2.0 (to be finalized)

---

# 1. Overview

Terra Protocol is a governance-first coordination layer designed for real-world communities, sustainable ecosystems, and regenerative economic networks.  
While the long-term vision includes physical communities and land-based pilot zones, the scope of this grant focuses exclusively on:

- core governance logic  
- rights-based token architecture  
- revenue routing mechanism  
- worker participation logic  
- Substrate-based prototype  

This document provides the technical foundation required for Web3 Foundation review.

---

# 2. Motivation

Modern decentralized governance lacks:

- persistent, non-inflationary rights representation  
- contribution-based governance  
- multi-layer, values-aligned onboarding  
- transparent revenue distribution mechanisms  
- regenerative, purpose-oriented economic models  

Terra introduces a novel 3-token, governance-first structure:

- **TERRA** – non-inflationary sovereign rights token  
- **GOVT** – contribution-based governance token  
- **CREDIT** – elastic revenue rights layer  
- **IMAP** – Initial Member Admission Protocol  
- **CDC** – Consensus Delegation Council  

Together, these components create a modular governance engine suitable for:

- digital communities  
- sustainability projects  
- public goods networks  
- real-world coordination systems  

---

# 3. System Architecture (Technical Summary)

Terra consists of 6 core Substrate pallets and 3 off-chain services.

### 3.1 On-Chain Modules (Pallets)

#### **1. terra_pallet — sovereign rights**
- fixed supply  
- genesis allocation  
- address-level caps  
- non-inflationary rights  
- governance weight: strategic or sovereign proposals

#### **2. govt_pallet — governance participation**
- minting tied to contribution events  
- non-transferable (or restricted)  
- used for daily & strategic voting  
- maintains governance reputation history

#### **3. credit_pallet — elastic revenue rights**
- abstract accounting layer  
- dynamic weighting: αTERRA + (1−α)GOVT  
- input for revenue router  
- not a tradable store-of-value token

#### **4. revenue_router_pallet**
- receives incoming revenue  
- distributes across:  
  - treasury  
  - workers  
  - ecosystem pools  
- integrates with CREDIT/ TERRA/ GOVT shares  
- Phase 2: XCM-compatible

#### **5. worker_engine_pallet**
- contribution tracking  
- task registration  
- GOVT issuance logic  
- optional CREDIT eligibility rules

#### **6. governance_engine_pallet**
- implements Governance 2.0  
- integrates TERRA + GOVT multi-layer voting  
- proposal lifecycle  
- decision class routing  

---

### 3.2 Off-Chain Components

#### **Indexer**
Aggregates:  
- events  
- revenue cycles  
- governance decisions  
- historical issuance

#### **Governance Simulator**
Before applying settings on-chain, community can simulate outcomes.

#### **Dashboard (Phase 2+)**
Visual interface for:  
- balances  
- proposals  
- CDC state  
- revenue distribution  

---

# 4. Governance 2.0 (Technical Summary)

### Three decision layers:

1. **Daily Governance** – GOVT-weighted  
2. **Strategic Governance** – mixed TERRA + GOVT  
3. **Sovereign Governance** – TERRA-weighted  

### IMAP  
- founding members must approve new members unanimously (Phase 0–1)  
- stores hashed metadata on-chain  

### CDC  
- founder delegates part of TERRA to a council  
- delegation activates only if the entire council votes YES  
- deactivates automatically once community TERRA > threshold  
- ensures early-stage decentralization and safety  

---

# 5. Token Model (Grant Version)

### **TERRA (fixed rights token)**  
- fixed supply  
- non-inflationary  
- not tied to speculative value  
- represents sovereign economic & governance rights  

### **GOVT (earned governance token)**  
- inflationary through work  
- non-transferable  
- represents contribution and participation  

### **CREDIT (elastic revenue share)**  
- dynamic accounting unit  
- reflects actual participation  
- enables transparent revenue cycles  

---

# 6. Deliverables (Grant-Focused)

Phase 0 (this proposal):
- Governance 2.0 spec  
- IMAP + CDC specs  
- Technical architecture document  
- Module designs (TERRA, GOVT, CREDIT, Router)

Phase 1:
- pallet prototypes  
- local testnet  
- documentation  
- minimal SDK draft  

---

# 7. Target Deployment

- Substrate-based chain (solo or parachain candidate)  
- optional hosting on existing parachain in later phases  

---

# 8. Licensing

Open source: MIT or Apache-2.0 (final decision pending).

---

# 9. Conclusion

Terra provides a novel governance structure combining real-world coordination with modular, transparent, Substrate-based architecture.

This grant request focuses solely on the technical foundation required to launch the Terra governance engine prototype.
