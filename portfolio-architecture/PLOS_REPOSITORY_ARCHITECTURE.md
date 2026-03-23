![Status](https://img.shields.io/badge/Status-Canonical-blue.svg)
![Type](https://img.shields.io/badge/Type-Repository%20Architecture-purple.svg)
![Scope](https://img.shields.io/badge/Scope-Portfolio%20Level-black.svg)
![Portfolio](https://img.shields.io/badge/Portfolio-Product%20Leadership%20Operating%20System-black.svg)

# PLOS Repository Architecture

The **PLOS Repository Architecture** defines the canonical repository structure, artifact placement rules, control-layer hierarchy, and portfolio-level content organization for the **Product Leadership Operating System (PLOS)** repository.

Where the operating system architecture defines how the product organization functions conceptually, this artifact defines how the repository itself is structured so that the portfolio can be maintained with clarity, consistency, and architectural discipline.

It exists to ensure that the repository reflects the architecture it documents.

---

## Purpose

The purpose of repository architecture is to preserve a clean relationship between:
- portfolio-level control artifacts
- canonical pillar definitions
- supporting architecture models
- rendered diagrams
- README summaries
- cross-pillar governance artifacts
- shared supporting documentation

A strong repository architecture prevents confusion about what is canonical, where artifacts belong, how readers should interpret them, and which documents have the authority to govern others.

---

## Repository Design Principles

The repository must be organized according to the following principles:

1. **Control before summary**  
   Governing artifacts must exist above explanatory summaries.

2. **Canonical before supporting**  
   Core system definitions must be distinguishable from supporting models, examples, and visuals.

3. **Portfolio before pillar-local interpretation**  
   Portfolio rules must govern pillar representations, not the reverse.

4. **Architecture before presentation**  
   Diagrams and README files explain architecture but do not define it.

5. **Consistency before convenience**  
   Artifact placement and naming must preserve structural clarity even when alternative layouts might appear easier locally.

---

## Canonical Top-Level Structure

The portfolio repository should maintain the following top-level structure:

```text
product-leadership-operating-system/
├── README.md
├── LICENSE
├── pillars/
├── cross-pillar/
├── portfolio-architecture/
├── portfolio-architecture/diagrams/
├── assets/
├── assets/branding/
├── assets/diagrams/
└── docs/

---

## Artifact Precedence

The following artifact precedence is mandatory across the repository:

1. portfolio control artifacts  
2. canonical pillar definitions  
3. supporting models  
4. playbooks / labs artifacts  
5. diagrams  
6. README summaries  

Portfolio-control artifacts are the authoritative source of architectural truth across the repository.

This means:
- lower-precedence artifacts must align upward
- summaries may not override definitions
- diagrams may not redefine system behavior
- playbooks may not create canonical architecture
- labs artifacts may not become governing artifacts
- portfolio-control artifacts remain the highest repository-level authority
