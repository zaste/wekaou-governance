# WEKAOU Governance

> 🏛️ **Public records of the Alliance for Coherent AI (ACA)**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📋 Purpose

This repository contains the complete governance framework for the WEKAOU® open standard:

- **Charter**: The "constitution" defining organizational structure and processes
- **ACA Records**: Legal statutes, member registry, and financial transparency
- **TSC Operations**: Technical Steering Committee mandate and meeting archives
- **Working Groups**: Domain-specific initiatives and their charters

---

## 🗂️ Repository Structure

```
governance/
├── CHARTER.md                 # The Constitution
├── LICENSE                    # CC BY 4.0
│
├── /aca/                      # Alliance for Coherent AI
│   ├── statutes.md            # Legal framework and bylaws
│   └── members.md             # Public member registry
│
├── /tsc/                      # Technical Steering Committee
│   ├── mandate.md             # Responsibilities and powers
│   └── meetings/              # Meeting notes archive
│       └── README.md
│
└── /working-groups/           # Specialized working groups
    ├── README.md              # WG overview and formation process
    └── wg-domains/            # Domain-specific profiles
        ├── charter.md
        └── meetings/
```

---

## 📜 Key Documents

### [CHARTER.md](CHARTER.md) - The Constitution

The foundational document defining:
- Mission and core values
- Organizational structure (ACA, TSC, WGs)
- RFC process for specification changes
- Intellectual property and licensing
- Conflict resolution procedures
- Amendment process

**Status**: DRAFT - Pending inaugural ACA assembly

### [aca/statutes.md](aca/statutes.md) - Legal Framework

Detailed bylaws covering:
- Membership categories (Individual, Organizational)
- Election procedures
- Financial governance
- Amendment processes

**Current Version**: 0.1 (DRAFT)

### [aca/members.md](aca/members.md) - Member Registry

Public record of:
- Active individual members
- Organizational members (by tier)
- Emeritus contributors
- Membership statistics

**Status**: No members yet (pending inaugural assembly)

### [tsc/mandate.md](tsc/mandate.md) - Technical Authority

Defines the TSC's:
- Responsibilities (RFC approval, releases, tooling)
- Composition and election process
- Decision-making procedures
- Powers and limitations
- Accountability mechanisms

**Status**: DRAFT - Pending TSC formation

---

## 🎯 How to Participate

### Join as a Member

See eligibility criteria in [aca/statutes.md](aca/statutes.md#article-ii-membership).

**For Individuals**: Contribute to WEKAOU repositories, then apply via GitHub issue.

**For Organizations**: Contact the Steering Committee to discuss membership tiers.

### Propose Governance Changes

1. Open an issue in [wekaou-rfc](https://github.com/zaste/wekaou-rfc)
2. Use the `governance-amendment` label
3. Follow the RFC process outlined in [CHARTER.md](CHARTER.md#article-iii-the-rfc-process)

### Participate in Working Groups

See available WGs in [working-groups/](working-groups/) and express interest in their discussion threads.

---

## 🔍 Governance at a Glance

### Organizational Structure

```
┌─────────────────────────────────────────┐
│   ACA Steering Committee                │  ← Administrative oversight
│   (Elected by membership)               │
└──────────────┬──────────────────────────┘
               │
               ├──► Technical Steering Committee (TSC)  ← Technical decisions
               │   └──► Working Groups                  ← Domain expertise
               │
               └──► Community Moderators               ← Social infrastructure
```

### Decision Flow for Specification Changes

```
1. Proposal → RFC issue in wekaou-rfc
2. Discussion → Community debates (minimum 14 days)
3. Voting → TSC votes (simple majority)
4. Implementation → PR to wekaou-specification
5. Archival → Accepted RFCs filed in rfc/accepted/
```

---

## 📊 Current Status

| Body | Status | Next Milestone |
|------|--------|----------------|
| ACA Steering Committee | Not formed | Inaugural assembly |
| TSC | Not formed | First election (post-assembly) |
| WG-Domains | Charter draft | TSC approval |
| Member Registry | Empty | First members after assembly |

---

## 🔗 Related Repositories

- [wekaou-specification](https://github.com/zaste/wekaou-specification) - The canonical standard
- [wekaou-rfc](https://github.com/zaste/wekaou-rfc) - RFC process for governance
- [wekaou-community](https://github.com/zaste/wekaou-community) - Public discussions
- [wekaou-.github](https://github.com/zaste/wekaou-.github) - Organization-wide templates

---

## 💡 Philosophy

WEKAOU governance embodies **dogfooding**: we apply WEKAOU principles to govern WEKAOU itself.

**Core Values**:
- 🔍 **Radical Transparency**: All decisions, debates, and rationale are public
- ⚖️ **Meritocracy**: Ideas evaluated on evidence, not authority  
- 🔓 **Interoperability**: No vendor lock-in; multiple implementations welcome
- 🤝 **Inclusion**: Diverse perspectives strengthen the standard

---

## 📞 Contact

- **General Questions**: [wekaou-community discussions](https://github.com/zaste/wekaou-community/discussions)
- **Governance Proposals**: Open issue in this repository
- **Private Matters**: [Contact form on wekaou.org](https://wekaou.org/contact) [TODO]

---

## 📄 License

All governance documents are licensed under [CC BY 4.0](LICENSE).

You are free to:
- Share and adapt these documents
- Use them as templates for your own projects

With attribution to the WEKAOU project.

---

<div align="center">

**Transparent governance for a coherent ecosystem.**

[View Charter](CHARTER.md) • [Browse Repositories](https://github.com/zaste?q=wekaou) • [Join Community](https://github.com/zaste/wekaou-community)

</div>
