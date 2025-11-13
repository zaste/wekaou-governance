# WEKAOU Governance

> 🏛️ **Public records of the Alliance for Coherent AI (ACA)**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The constitutional framework, statutes, and public records of the governance system for the WEKAOU® ecosystem.

---

## 📋 Purpose

This repository contains the official governance documents that define how the WEKAOU community operates, makes decisions, and evolves the standard.

**This is "The Constitution"** — the meta-governance layer above all other repositories.

---

## 📁 Repository Structure

```
governance/
├── CHARTER.md              # The fundamental constitution
├── LICENSE                 # CC BY 4.0
├── README.md              # This file
│
├── /aca/                  # Alliance for Coherent AI
│   ├── statutes.md        # Legal framework (membership, elections, finances)
│   └── members.md         # Public member registry
│
├── /tsc/                  # Technical Steering Committee
│   ├── mandate.md         # Powers, responsibilities, decision-making
│   └── meetings/          # Public meeting notes
│
└── /working-groups/       # Specialized domain teams
    ├── README.md          # WG lifecycle and guidelines
    └── wg-domains/        # Domain-specific profiles working group
        └── README.md
```

---

## 🎯 Key Documents

### CHARTER.md
**The Constitution** — Defines:
- Core principles and values
- Governance structure (ACA, TSC, Working Groups)
- Amendment process
- Relationship between repositories

**Status**: DRAFT (awaiting inaugural ratification)

### aca/statutes.md
**The Legal Framework** — Specifies:
- Membership categories (Individual, Organizational)
- Election procedures (TSC, Steering Committee)
- Financial governance
- Amendment procedures

### tsc/mandate.md
**Technical Authority** — Establishes:
- TSC composition and selection
- RFC approval process
- Decision-making quorum and voting
- Powers and limitations

---

## 🏛️ Governance Architecture

```
                    ┌──────────────────┐
                    │  ACA Membership  │
                    │   (The People)   │
                    └────────┬─────────┘
                             │ Elects
                    ┌────────▼─────────┐
                    │       TSC        │
                    │ (The Parliament) │
                    └────────┬─────────┘
                             │ Approves
                    ┌────────▼─────────┐
                    │   RFCs (Bills)   │
                    └────────┬─────────┘
                             │ Updates
                    ┌────────▼──────────┐
                    │  Specification    │
                    │    (The Law)      │
                    └───────────────────┘
```

### Three Branches of Power

1. **Legislative**: RFC process (community proposes, TSC approves)
2. **Executive**: TSC (implements decisions, manages ecosystem)
3. **Judicial**: Code of Conduct enforcement + Charter interpretation

---

## 🗳️ How Decisions Are Made

### For Specification Changes
**MUST** go through RFC process:
1. Propose in [wekaou-rfc](https://github.com/zaste/wekaou-rfc)
2. Community discussion (2-4 weeks)
3. TSC vote (requires 2/3 majority)
4. If accepted → merged to specification

### For Governance Changes
**MUST** follow Charter amendment process:
1. Propose via RFC with `governance-amendment` label
2. TSC review and recommendation
3. Steering Committee approval (2/3)
4. Membership ratification (simple majority)

### For Working Group Creation
1. Submit RFC with scope and objectives
2. TSC charters with 2/3 vote
3. Lead appointed
4. Group operates autonomously within charter

---

## 🏅 Membership

### Individual Members
**Eligibility**: 
- 3+ accepted contributions to WEKAOU repos, OR
- 5+ RFC discussion participations, OR
- Nominated by member + TSC approval

**Rights**: Vote, propose RFCs, join Working Groups

### Organizational Members
**Tiers**: Platinum ($50k+), Gold ($25k+), Silver ($10k+), Bronze ($5k+)

**Benefits**: Voting rights, TSC nomination slots, certification priority

**Apply**: See [aca/members.md](./aca/members.md)

---

## 🔨 Technical Steering Committee (TSC)

### Current Composition
[PENDING - First election to be held]

### Responsibilities
- Approve/reject RFCs
- Manage specification releases
- Charter Working Groups
- Certify implementations via compliance-suite
- Resolve technical disputes

### Meetings
**Frequency**: Monthly (first Thursday)  
**Format**: Public video call (recorded)  
**Notes**: Published in `tsc/meetings/`

---

## 👥 Working Groups

### Active
- **WG-Domains**: Domain-specific profiles (healthcare, finance, etc.)
  - Status: PROPOSED (pending TSC charter approval)
  - Charter: [working-groups/wg-domains/README.md](./working-groups/wg-domains/README.md)

### Propose a New WG
Submit RFC describing scope, objectives, and deliverables. See [working-groups/README.md](./working-groups/README.md) for lifecycle details.

---

## 📜 Principles

The WEKAOU governance system is built on:

1. **Transparency**: All decisions, votes, and discussions are public
2. **Meritocracy**: Influence earned through contribution quality
3. **Consensus-Seeking**: Prefer agreement over voting when possible
4. **Separation of Powers**: No single entity controls the standard
5. **Openness**: Anyone can contribute, regardless of affiliation
6. **Stability**: High bar for breaking changes to specification

---

## 🔄 Amendment Process

### Minor Changes (typos, clarifications)
- Direct PR to this repository
- TSC member approval sufficient

### Major Changes (process, structure, powers)
- Follow governance amendment RFC process
- Requires Steering Committee + membership vote

---

## 🚀 Getting Involved

### As a Contributor
1. Read [CONTRIBUTING.md](https://github.com/zaste/wekaou-.github/blob/main/CONTRIBUTING.md)
2. Start participating in [RFC discussions](https://github.com/zaste/wekaou-rfc)
3. Make contributions to WEKAOU repositories

### As a Member
1. Meet eligibility criteria (see `aca/statutes.md`)
2. Open issue: "Membership Application: [Your Name]"
3. Include GitHub username and 3+ contribution links
4. TSC reviews quarterly

### As an Organization
1. Review membership tiers in `aca/statutes.md`
2. Contact Steering Committee via issue
3. Describe use case and intended tier

---

## 📚 Related Repositories

- [wekaou-specification](https://github.com/zaste/wekaou-specification) - The canonical standard
- [wekaou-rfc](https://github.com/zaste/wekaou-rfc) - Proposal and voting process
- [wekaou-community](https://github.com/zaste/wekaou-community) - Discussions and questions
- [wekaou-.github](https://github.com/zaste/wekaou-.github) - Organization-wide policies

---

## 📄 License

All governance documents are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**
- Adapt these governance structures for your projects
- Share and reference these documents

**With attribution to**: Alliance for Coherent AI (ACA) / WEKAOU Project

---

## ❓ Questions?

- **General**: Ask in [wekaou-community discussions](https://github.com/zaste/wekaou-community/discussions)
- **Membership**: Open an issue in this repository
- **Process clarifications**: Tag TSC members in relevant issues

---

<div align="center">

**Government of the people, by the people, for the people.**

[View Charter](./CHARTER.md) • [See Statutes](./aca/statutes.md) • [TSC Mandate](./tsc/mandate.md)

</div>
