![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Type](https://img.shields.io/badge/Type-Standard-blue.svg)
![Pillar](https://img.shields.io/badge/Pillar-7%20Product%20Leadership%20Playbooks-black.svg)
![Standard](https://img.shields.io/badge/Standard-Operating%20Rules-orange.svg)

# Playbook Operating Rules

This document defines the canonical **operating rules** for how playbooks are used, maintained, reviewed, and applied within **Pillar 7 — Product Leadership Playbooks** of the **Product Leadership Operating System (PLOS)**.

Where the:

- **Playbook Template** defines required structure  
- **Playbook Boundary Guardrails** define non-negotiable constraints  
- **Playbook Review Checklist** defines audit criteria  

The **Playbook Operating Rules** define how playbooks function as living execution artifacts within the operating system.

---

# Purpose

The purpose of these rules is to ensure that playbooks:

- are used consistently  
- remain within architectural boundaries  
- scale without drift  
- support execution without absorbing system responsibilities  
- remain maintainable as the operating system evolves  

These rules operate in conjunction with the Playbook Boundary Guardrails, which define the non-negotiable constraints. This document defines how playbooks operate within those constraints.
---

# Core Rule

> **Playbooks must standardize execution without redefining ownership**

Playbooks exist to make execution more consistent.

They do not exist to make new decisions, reinterpret evidence, or redefine how other pillars operate.

---

# 1. Playbooks Must Be Scenario-Based

Every playbook must correspond to a **clear recurring execution scenario**.

A playbook must not be created for:

- vague topics  
- generic principles  
- broad system descriptions already covered elsewhere  
- responsibilities owned by another pillar  

A valid playbook addresses a repeatable operating situation such as:

- preparing for a portfolio review  
- coordinating release readiness  
- managing execution across an initiative lifecycle  

---

# 2. Playbooks Must Follow the Canonical Template

All playbooks must:

- use the required template structure  
- preserve section ordering  
- define system interactions explicitly  
- include guardrails and failure modes  
- include signals of execution health without interpreting them  

No local variations should replace the canonical structure.

---

# 3. Playbooks Must Remain Execution-Only

Playbooks may:

- structure action  
- coordinate activity  
- sequence repeatable execution steps  
- create execution artifacts  
- establish shared visibility and operating consistency  

Playbooks must not:

- make decisions  
- interpret metrics or signals  
- evaluate outcomes  
- assign value  
- generate learning  
- create cross-system authority  

---

# 4. Playbooks Must Respect System Ownership

Each system retains ownership of its responsibilities.

## Strategy owns:
- direction  
- strategic framing  
- strategic refinement informed by learning  

## Governance owns:
- prioritization  
- sequencing  
- portfolio decisions  
- rebalance  

## Delivery owns:
- execution flow  
- delivery readiness  
- delivery coordination authority  

## Customer Outcomes System owns:
- interpretation  
- value qualification  
- outcome evaluation  
- learning generation  

## Decision Intelligence System owns:
- signals  
- dashboards  
- metrics  
- analytics  
- visibility  

## Playbooks own:
- execution patterns only  

---

# 5. Playbooks Must Preserve the Operating Loop

Playbooks must align to the canonical PLOS loop:

> **Strategy → Governance → Delivery → Outcomes → Learning → Strategy**

A playbook may support activity at one or more points in this loop.

It must not:

- short-circuit the loop  
- create alternate flows  
- bypass outcome mediation  
- collapse multiple ownership layers into one operating pattern  

---

# 6. Playbooks Must Preserve the Mediation Path

The canonical mediation rule always applies:

> **Decision Intelligence → Customer Outcomes → Strategy / Governance**

This means:

- playbooks may reference DI outputs as uninterpreted inputs  
- playbooks may consume Customer Outcomes insights as interpreted inputs  
- playbooks may support execution after governance decisions are made  

It does not mean:

- playbooks may route raw data directly into decision-making  
- playbooks may infer or recommend decisions from metrics  
- playbooks may substitute for Customer Outcomes interpretation  

---

# 7. Playbooks Must Produce Execution Outputs

Each playbook must produce outputs appropriate to an execution pattern.

Examples include:

- aligned execution plans  
- readiness artifacts  
- coordination packages  
- review preparation materials  
- communication artifacts  
- shared operating visibility  

Outputs must remain execution-oriented.

They must not become:

- governance decisions  
- strategic conclusions  
- outcome judgments  
- analytic interpretations  

---

# 8. Playbooks Must Be Reusable

A playbook must be reusable across repeated occurrences of the same operating scenario.

A playbook should not be written as:

- a one-time project document  
- a team-specific workaround  
- a temporary exception  
- a scenario that only applies to one moment in time  

If an artifact is not reusable, it is not a canonical playbook.

---

# 9. Playbooks Must Be Reviewable

All playbooks must be reviewed using the canonical review process.

At minimum, each playbook must be tested for:

- template compliance  
- boundary integrity  
- system ownership preservation  
- cross-pillar consistency  
- clarity of execution logic  
- absence of interpretation, evaluation, and decision logic  

Playbooks that violate guardrails must be blocked.

---

# 10. Playbooks Must Be Maintained as Controlled Artifacts

Playbooks are not informal notes.

They are controlled architectural artifacts.

This means they must be:

- named consistently  
- stored in the correct operating category  
- updated deliberately  
- reviewed when materially changed  
- aligned to the latest approved architecture state  

Playbooks should not evolve independently of the pillar’s standards and guardrails.

---

# 11. Playbooks Must Not Become a Meta-System

The Playbooks pillar must never evolve into a system that:

- redefines governance  
- interprets outcomes  
- absorbs delivery authority  
- acts as a decision support layer  
- acts as an analytics layer  

Playbooks must remain a **supporting execution layer**, not an overarching control layer.

---

# 12. Operating Rule for Cross-System Playbooks

Cross-system playbooks require additional discipline.

They may coordinate execution across multiple systems, but they must not:

- merge system ownership  
- create hybrid interfaces  
- combine evidence, meaning, and decisions  
- route raw signals directly into strategic or governance action  

Cross-system playbooks are valid only when they preserve the boundaries of every participating system.

---

# Relationship to Other Playbook Standards

These operating rules work together with the other pillar control artifacts:

- `PLAYBOOK_TEMPLATE.md` defines required structure  
- `PLAYBOOK_BOUNDARY_GUARDRAILS.md` defines hard constraints  
- `PLAYBOOK_REVIEW_CHECKLIST.md` defines audit criteria  
- `PLAYBOOK_COMPOSITION_MODEL.md` defines how multiple playbooks may work together  
- `PLAYBOOK_NAMING_STANDARD.md` defines naming consistency  

Together, these artifacts make Pillar 7 governable and scalable.

---

# Why This Matters

Without operating rules:

- playbooks drift into informal documentation  
- structure and guardrails are applied inconsistently  
- ownership boundaries erode over time  
- cross-system playbooks become risky  
- the pillar stops functioning as a controlled architectural layer  

These rules ensure that playbooks remain usable, repeatable, and aligned to the PLOS architecture as the repository grows.

---

# Summary

The **Playbook Operating Rules** define how playbooks function as controlled execution artifacts within the **Product Leadership Operating System**.

They ensure that playbooks:

- remain scenario-based  
- preserve system ownership  
- align to the PLOS loop  
- respect the mediation path  
- produce execution-oriented outputs  
- scale without architectural drift  

They are the operational discipline layer of Pillar 7.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
