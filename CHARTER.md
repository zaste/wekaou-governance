# WEKAOU Charter

> **The Constitution of the WEKAOU Ecosystem**

**Version**: 1.0  
**Adopted**: [PENDING - First ACA Assembly]  
**Last Amended**: N/A  
**Status**: DRAFT  

---

## Preamble

The WEKAOU® standard represents a collective effort to establish open, interoperable specifications for Cognitive Governance Systems. This Charter defines the governance structure, principles, and processes that ensure the standard evolves transparently, equitably, and in service of the broader community.

---

## Article I: Purpose and Scope

### 1.1 Mission

The Alliance for Coherent AI (ACA) exists to:

1. **Steward the WEKAOU® standard** through transparent, evidence-based governance
2. **Foster a vibrant ecosystem** of compatible implementations and innovations
3. **Ensure accessibility** of the standard for all legitimate uses
4. **Maintain quality and coherence** across the specification lifecycle
5. **Enable community participation** in standard evolution

### 1.2 Core Values

- **Radical Transparency**: All decisions, debates, and rationale are public
- **Meritocracy**: Ideas are evaluated on evidence, not authority
- **Interoperability**: No vendor lock-in; multiple implementations welcome
- **Dogfooding**: We apply WEKAOU principles to govern WEKAOU itself
- **Inclusion**: Diverse perspectives strengthen the standard

---

## Article II: Organizational Structure

### 2.1 The Alliance for Coherent AI (ACA)

**Legal Form**: [TODO: Non-profit foundation / Open-source consortium]  
**Jurisdiction**: [TODO: To be determined by Steering Committee]  
**Members**: Contributors who meet participation criteria (defined in `aca/statutes.md`)

### 2.2 Governance Bodies

```
┌─────────────────────────────────────┐
│   ACA Steering Committee            │  ← Administrative oversight
│   (Elected by membership)           │
└────────────┬────────────────────────┘
             │
             ├─► Technical Steering Committee (TSC)  ← Technical decisions
             │   └─► Working Groups                  ← Domain expertise
             │
             └─► Community Moderators               ← Social infrastructure
```

#### 2.2.1 Steering Committee
- **Size**: 5-7 members
- **Term**: 2 years, staggered
- **Responsibilities**: Legal, financial, strategic oversight
- **Powers**: Appoint TSC, approve budgets, amend Charter

#### 2.2.2 Technical Steering Committee (TSC)
- **Size**: 5-9 members
- **Term**: 1 year, renewable
- **Responsibilities**: Technical direction, RFC approval, specification releases
- **Powers**: Merge authority on `wekaou-specification`, establish Working Groups

#### 2.2.3 Working Groups (WG)
- **Formation**: Proposed by community, approved by TSC
- **Scope**: Specific domains (e.g., WG-Domains, WG-Compliance, WG-Education)
- **Deliverables**: Recommendations to TSC, documentation, tooling

---

## Article III: The RFC Process

### 3.1 Standard Change Proposals (SCP)

All changes to `wekaou-specification` MUST go through the RFC process:

1. **Proposal**: Submit issue in `wekaou-rfc` using SCP template
2. **Discussion**: Community debates merits (minimum 14 days)
3. **Voting**: TSC votes (simple majority required)
4. **Implementation**: If accepted, PR to `specification` is authorized
5. **Archival**: Accepted RFCs are filed in `rfc/accepted/`

### 3.2 RFC States

- `proposed`: Initial submission
- `under-discussion`: Active debate period
- `voting`: TSC voting in progress
- `accepted`: Approved for implementation
- `rejected`: Not accepted (with rationale)
- `withdrawn`: Author withdrew proposal

### 3.3 Voting Rules

- **Quorum**: 60% of TSC members must participate
- **Approval**: Simple majority of votes cast
- **Veto**: None (no single member can block)
- **Tie-breaker**: TSC Chair casts deciding vote

---

## Article IV: Intellectual Property

### 4.1 Specification License

The WEKAOU® specification is licensed under **CC BY-SA 4.0** (Creative Commons Attribution-ShareAlike).

**Rationale**: Copyleft ensures derivative standards remain open while allowing commercial use.

### 4.2 Contributor License Agreement (CLA)

Contributors grant the ACA:
- Perpetual, worldwide, non-exclusive license to their contributions
- Right to relicense under compatible terms (with community approval)

**Process**: Automated CLA signing via CLA Assistant (see `CONTRIBUTING.md`)

### 4.3 Trademark

"WEKAOU®" is a registered trademark of the ACA.

**Usage Policy**:
- Conformant implementations may use "WEKAOU-compatible"
- Commercial use requires certification (via `compliance-suite`)
- Misrepresentation of conformance is prohibited

---

## Article V: Specification Versioning

### 5.1 Semantic Versioning

WEKAOU follows semver: `MAJOR.MINOR.PATCH`

- **MAJOR**: Breaking changes (e.g., 1.0 → 2.0)
- **MINOR**: New features, backward-compatible (e.g., 2.1 → 2.2)
- **PATCH**: Bug fixes, clarifications (e.g., 2.2.0 → 2.2.1)

### 5.2 Stability Tiers

- **Core (META-2.5)**: Immutable primitives, requires MAJOR version for changes
- **Stable (Tier 1-2)**: Mature, consensus-driven, MINOR/MAJOR changes
- **Experimental (Tier 3)**: Sandbox, rapid iteration, no version constraints

### 5.3 Deprecation Policy

Features may be deprecated but MUST:
1. Be marked in spec with deprecation notice (minimum 1 MINOR version)
2. Have migration path documented
3. Not be removed until next MAJOR version

---

## Article VI: Conflict Resolution

### 6.1 Technical Disputes

1. **First resort**: Discussion in `wekaou-rfc` or `wekaou-community`
2. **Escalation**: Working Group review (if applicable)
3. **Final decision**: TSC vote (simple majority)

### 6.2 Conduct Violations

See `CODE_OF_CONDUCT.md` for enforcement process.

### 6.3 Appeals

Decisions may be appealed to the ACA Steering Committee within 30 days.

---

## Article VII: Amendments

### 7.1 Charter Amendments

This Charter may be amended by:
1. Proposal submitted as RFC (special label: `charter-amendment`)
2. Community comment period (minimum 30 days)
3. TSC recommendation
4. ACA Steering Committee approval (2/3 majority)

### 7.2 Effective Date

Amendments take effect 7 days after approval unless otherwise specified.

---

## Article VIII: Dissolution

Should the ACA dissolve:
1. All specification assets transfer to [TODO: Specify successor organization or public domain]
2. Repositories become archived (read-only) on GitHub
3. Trademark enters public domain or transfers to successor

---

## Signatures

**Adopted by**: [PENDING - Inaugural ACA Assembly]  
**Date**: [PENDING]  

---

## Appendices

- **Appendix A**: ACA Statutes (see `aca/statutes.md`)
- **Appendix B**: TSC Mandate (see `tsc/mandate.md`)
- **Appendix C**: Working Group Charter Template (see `working-groups/`)

---

## Revision History

| Version | Date       | Changes                          | Approved By |
|---------|------------|----------------------------------|-------------|
| 1.0     | [PENDING]  | Initial Charter                  | [PENDING]   |

---

**Questions?** Open a discussion in [wekaou-community](https://github.com/zaste/wekaou-community) or contact the Steering Committee.
