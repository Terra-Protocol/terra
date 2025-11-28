
# Terra Protocol – A Rights-Based Economic Layer for Real-World Communities
### Whitepaper v1.0 – Grant Edition (B)

---

## 1. Abstract

Terra Protocol introduces a modular, rights-based economic infrastructure for real-world communities built natively on Polkadot. Terra separates economic rights, revenue distribution, local economic activity, and governance into four interoperable tokens: **TERRA**, **CREDIT**, **WORK**, and **GOVT**.

Through XCM-enabled payment flows, programmable revenue distribution, and transparent governance, Terra provides an open, decentralized, and scalable framework for micro-economies, regenerative projects, and community-owned infrastructure.

---

## 2. Motivation

Communities, regenerative settlements, and real-world projects struggle with:

- opaque governance  
- unclear rights structures  
- inefficient value distribution  
- lack of economic transparency  
- isolated local currencies  
- poor integration with digital economies  

Terra solves this by introducing an **on-chain economic layer** that aligns contributors, workers, treasuries, and long-term participants.

---

## 3. Why Polkadot

Polkadot provides a unique foundation:

- **OpenGov:** the strongest governance system in Web3  
- **XCM:** secure cross-chain interoperability  
- **AssetHub:** native asset operations  
- **Moonbeam / Astar:** smart-contract execution  
- **HydraDX:** deep liquidity infrastructure  
- **Treasury:** public-goods aligned funding  

Terra extends Polkadot with a programmable economic system for real-world coordination.

---

## 4. System Overview

Terra Protocol introduces:

1. **Rights-Based Tokenization (TERRA)**  
2. **Revenue Claim Mechanism (CREDIT)**  
3. **Local Economy Token (WORK)**  
4. **Governance Layer (GOVT)**  
5. **Revenue Router**  
6. **XCM Payment Router**  
7. **Terra SDK** for developers

Each component is modular and can be deployed independently.

---

## 5. Token Model

### 5.1 TERRA – Rights & Participation Token
- Fixed supply  
- Represents long-term economic rights  
- Determines revenue share via **CREDIT minting**  
- Cannot be redeemed directly  
- Cannot be inflated

### 5.2 CREDIT – Revenue Claim Token
- Minted through the Revenue Router  
- Distributed proportionally to TERRA holders  
- Redeemable for DOT, WORK, or stablecoins  
- Burned on redemption  
- Bridges revenue to TERRA without making TERRA a payout token

### 5.3 WORK – Local Economy Token
- Used for wages, internal markets, housing, food, resources  
- Bonding curve mechanism for pricing  
- Convertible to DOT via liquidity pools  
- Not tied to governance or long-term rights

### 5.4 GOVT – Governance Token
- Inflationary, earnable  
- Pure governance  
- No revenue claim  
- Used for proposals, votes, and parameter adjustments

---

## 6. Revenue Flow

1. Real-world activity generates revenue (in WORK, DOT, stablecoins).  
2. Revenue Router collects revenue.  
3. Allocation rules executed (example 40/40/20).  
4. The portion allocated to TERRA holders is converted into **CREDIT**.  
5. CREDIT is redeemable through a Redemption Pool.  
6. Treasury receives its share in **CREDIT**, converts to **DOT**.  
7. Liquidity pools receive allocations to stabilize WORK/DOT.

### Summary
```
Revenue → Revenue Router → CREDIT → Redemption → DOT/WORK
```

---

## 7. Governance

### GOVT Token governs:
- protocol parameters  
- bonding curve settings  
- treasury allocations  
- onboarding of new communities  
- revenue ratios  
- smart contract upgrades  

Governance is fully OpenGov compatible.

---

## 8. XCM Architecture

The Terra XCM Payment Router:
- enables multi-chain payments  
- routes WORK ↔ DOT ↔ stablecoins  
- allows fee abstraction for workers  
- supports automated cross-chain payouts

---

## 9. Developer Architecture

Modules included:

- Rights Engine  
- Revenue Router  
- Payment Router  
- Governance Module  
- SDK (Rust + TypeScript)  
- Example Economy Implementation

Developers can integrate Terra with minimal boilerplate.

---

## 10. Use Cases

- regenerative villages  
- co-living communities  
- sustainable farming clusters  
- DAO-managed real-world projects  
- community-owned energy & resources  
- micro-economies in developing regions  
- service networks (cleaning, maintenance, repairs)

---

## 11. Treasury Model

Treasury receives **CREDIT** → redeems for **DOT** → funds:

- development  
- bounties  
- liquidity provisioning  
- grants for local communities  
- infra maintenance  

DOT is the primary reserve asset.

---

## 12. Token Distribution (Example)

- 55% Treasury  
- 20% Worker Vesting & Rewards  
- 20% Team (4-year vesting)  
- 5% Partnerships & Integrations  

---

## 13. Roadmap

### Phase 1 (3 months)
- Rights Engine  
- XCM Router Prototype  
- Governance Module  
- SDK Alpha  
- Testnet

### Phase 2 (6 months)
- Full XCM integration  
- Extended Revenue Engine  
- Treasury Management Module  
- WORK Bonding Curve  
- Audit  

---

## 14. Conclusion

Terra Protocol provides a transparent, modular, and scalable framework for building real-world economies on Polkadot. It enables communities to govern themselves, distribute value fairly, and operate cross-chain through XCM.
