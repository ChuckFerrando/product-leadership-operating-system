# Architecture Decision Records (ADR) Index
Product Leadership Systems Architecture (PLSA)

![Architecture](https://img.shields.io/badge/Architecture-Decision%20Records-black.svg)
![Type](https://img.shields.io/badge/Type-Architecture-purple.svg)
![Status](https://img.shields.io/badge/Status-Active-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

# Purpose

Architecture Decision Records (ADRs) document the key architectural decisions that shape the **Product Leadership Systems Architecture (PLSA)**.

While architecture artifacts describe **what the architecture is and how it works**, ADRs explain **why specific architectural choices were made**.

They provide a traceable history of architectural reasoning and ensure that future changes remain aligned with the original design intent.

---

# Decision Log

The following Architecture Decision Records define the foundational decisions of the PLSA framework.

| ADR | Title | Status | Summary |
|----|------|------|------|
| [ADR-001](ADR-001-PLSA_SYSTEM_MODEL.md) | Product Leadership Systems Architecture System Model | Accepted | Establishes PLSA as a structured leadership operating architecture. |
| [ADR-002](ADR-002-FIVE_SYSTEM_ARCHITECTURE.md) | Five-System Product Leadership Architecture | Accepted | Defines the canonical five-system model of the architecture. |
| [ADR-003](ADR-003-DECISION_INTELLIGENCE_LAYER.md) | Decision Intelligence as a Cross-Cutting System | Accepted | Establishes decision intelligence as a system supporting all leadership layers. |
| [ADR-004](ADR-004-ARCHITECTURE_GOVERNANCE_MODEL.md) | Architecture Governance Model | Accepted | Introduces governance rules protecting the architecture model and repository structure. |

---

# How Architecture Decisions Work

Architecture Decision Records follow a consistent structure:

- **Context** — the architectural problem being addressed  
- **Decision** — the architecture choice that was made  
- **Rationale** — why the decision was chosen  
- **Consequences** — implications of the decision  

This format ensures architectural reasoning is transparent and traceable.

---

# Relationship to the Architecture

ADRs complement the core architecture artifacts by documenting the reasoning behind them.

| Artifact Type | Purpose |
|---|---|
Architecture Artifacts | Define the structure of the architecture |
Architecture Governance | Protects architecture integrity |
Architecture Metamodel | Defines the structural concept model |
Architecture Decision Records | Explain why architectural choices were made |

Together these components form a complete architecture framework.

---

# Adding New Architecture Decisions

New Architecture Decision Records should be added when:

- introducing significant architecture changes
- defining new system boundaries
- modifying governance rules
- introducing major frameworks or operating models

New ADR files should be placed in:

architecture/decisions/

and added to the **Decision Log** table in this document.

---

# Why This Matters

Architecture Decision Records transform the repository from static documentation into a **traceable architecture system**.

They enable:

- transparency in architecture design
- consistent architectural evolution
- historical understanding of design decisions
- better governance of architecture changes

This approach mirrors the practices used in mature architecture teams and enterprise architecture programs.

---

# Summary

The Architecture Decision Record index provides a centralized log of the key architectural decisions that define the **Product Leadership Systems Architecture**.

It complements the architecture artifacts by documenting the reasoning behind the framework and preserving architectural intent as the repository evolves.

---

# License

This architecture documentation is licensed under the MIT License.

See the repository LICENSE file for full details.
