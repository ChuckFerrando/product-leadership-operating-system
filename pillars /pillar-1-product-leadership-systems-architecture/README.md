![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-blue.svg)
![Type](https://img.shields.io/badge/Type-Architecture-purple.svg)
![Pillar](https://img.shields.io/badge/Pillar-1%20Product%20Leadership%20Systems%20Architecture-black.svg)
![Product Leadership OS](https://img.shields.io/badge/Product%20Leadership-Operating%20System-black.svg)

# Product Leadership Systems Architecture

## Purpose

This repository documents **Pillar 1** of the **Product Leadership Operating System (PLOS)** and defines the canonical five-system architecture through which product organizations translate strategy into governed investment, coordinated delivery, evaluated outcomes, and continuous learning.

---

## System Role in PLOS

The **Product Leadership Systems Architecture (PLSA)** is the canonical architecture layer of PLOS.

It defines the five-system structure that governs how the operating system functions:

- Strategy Execution System
- Portfolio Governance System
- Product Delivery System
- Customer Outcomes System
- Decision Intelligence System

It is the architectural reference point for all other pillars.

---

## What This Pillar Contains

This pillar contains:

- the canonical five-system architecture
- system relationship definitions
- architectural design principles
- operating loop definitions
- structural interaction models
- architecture governance artifacts

---

## Boundary Rules

Pillar 1 defines the architecture. It does not replace the execution responsibilities of the other pillars.

It must preserve:

- exact system boundaries
- exact canonical loop:
  **Strategy → Governance → Delivery → Outcomes → Learning → Strategy**
- separation between evidence, meaning, and decision-making
- the mandatory mediation path:
  **Decision Intelligence → Customer Outcomes → Strategy / Governance**

It must not:

- collapse system responsibilities
- redefine decision ownership outside Strategy and Governance
- permit Decision Intelligence to interpret, evaluate, recommend, or decide

---

## Relationship to Other Pillars

- **Pillar 2** operationalizes the leadership model that runs the architecture
- **Pillar 3** defines governance decision structures
- **Pillar 4** defines coordinated execution
- **Pillar 5** defines outcome interpretation, evaluation, and learning
- **Pillar 6** defines evidence production, metrics, dashboards, and descriptive analytics
- **Pillar 7** defines execution playbooks
- **Pillar 8** defines controlled experimentation

---

## Repository Structure

- `/architecture` → canonical architecture definitions and system-level models
- `/artifacts` → architectural control artifacts and responsibility mappings
- `/frameworks` → supporting operating views and interpretive frameworks
- `/diagrams` → Mermaid source diagrams and structural visualizations
- `/playbooks` → implementation support where applicable

---

## Key Artifacts

- `architecture/UNIFIED_PRODUCT_LEADERSHIP_SYSTEMS_ARCHITECTURE.md`
- `artifacts/SYSTEM_RESPONSIBILITIES_MATRIX.md`
- `frameworks/PRODUCT_LEADERSHIP_OPERATING_SYSTEM_OVERVIEW.md`
- `architecture/decisions/ADR_INDEX.md`

---

## License

This project is licensed under the MIT License.

See the [LICENSE](../../LICENSE) file for details.

See the full license text in the repository:

[MIT License](LICENSE)
