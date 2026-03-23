![Status](https://img.shields.io/badge/Status-Canonical-blue.svg)
![Type](https://img.shields.io/badge/Type-Terminology%20Control-purple.svg)
![Scope](https://img.shields.io/badge/Scope-Portfolio%20Level-black.svg)
![Portfolio](https://img.shields.io/badge/Portfolio-Product%20Leadership%20Operating%20System-black.svg)

# PLOS Canonical Terminology

The **PLOS Canonical Terminology** artifact defines the official language, naming discipline, and controlled vocabulary used across the **Product Leadership Operating System (PLOS)** portfolio.

Where individual repositories, diagrams, READMEs, and supporting models may explain parts of the operating system in different levels of detail, this artifact establishes the **single canonical terminology layer** that all portfolio artifacts must follow.

It exists to prevent ambiguity, synonym drift, local renaming, boundary confusion, and silent architectural erosion caused by inconsistent language.

---

## Purpose

The purpose of canonical terminology is to ensure that all portfolio artifacts describe the same architecture using the same language.

This artifact preserves:
- naming consistency
- architectural clarity
- system identity
- cross-pillar coherence
- repository discipline
- diagram consistency
- review consistency

In PLOS, terminology is not cosmetic. Terminology is part of architectural control.

---

## Core Naming Principle

The portfolio must use **one canonical set of names** for:
- the operating system
- the canonical architecture
- the pillars
- the system layers
- the operating loop
- cross-pillar relationships
- artifact types
- governance pathways

No artifact may introduce alternate names for canonical entities if those alternate names create ambiguity, overlap, or interpretive drift.

---

## Canonical Portfolio Terms

### Product Leadership Operating System
**Canonical term:** **Product Leadership Operating System**  
**Approved abbreviation:** **PLOS**

Definition:  
The full portfolio-level operating system that explains how product organizations translate:

> **Strategy → Governance → Delivery → Outcomes → Learning → Strategy**

PLOS is the overall operating system and portfolio, not a single pillar.

### Product Leadership Systems Architecture
**Canonical term:** **Product Leadership Systems Architecture**  
**Approved abbreviation:** **PLSA**

Definition:  
The canonical five-system architecture defined within **Pillar 1** of PLOS.

PLSA is a component of PLOS, not a synonym for PLOS.

---

## Mandatory PLOS / PLSA Distinction

The distinction between **PLOS** and **PLSA** must remain exact.

### Correct usage
- **PLOS** = the full operating system and multi-pillar portfolio
- **PLSA** = the canonical five-system architecture inside Pillar 1

### Incorrect usage
- using PLOS and PLSA interchangeably
- referring to PLSA as the entire portfolio
- referring to PLOS as only the five-system architecture
- collapsing Pillar 1 into the full operating system

Any artifact that blurs this distinction introduces architecture confusion and must be corrected.

---

## Canonical Operating Loop

The canonical operating loop must always appear exactly as:

> **Strategy → Governance → Delivery → Outcomes → Learning → Strategy**

This wording and ordering are mandatory.

### Rules
- do not rename stages
- do not reorder stages
- do not collapse stages
- do not replace arrows with alternative implied logic
- do not substitute synonyms that weaken meaning
- do not remove Learning from the loop

### Incorrect alternatives
The following are not acceptable replacements:
- Strategy → Delivery → Outcomes
- Strategy → Execution → Results
- Strategy → Governed Investment → Coordinated Delivery → Measurable Outcomes → Learning
- Plan → Build → Measure → Learn

Those may be explanatory phrases in limited context, but they are not the canonical loop.

---

## Canonical Pillar Names

The 8 pillars must be named exactly as follows:

1. **Systems Architecture**  
2. **Operating Model**  
3. **Portfolio Governance**  
4. **Product Delivery**  
5. **Customer Outcomes**  
6. **Decision Intelligence**  
7. **Playbooks**  
8. **Labs**

These are the canonical portfolio pillar names.

### Rules
- do not rename pillars casually
- do not add alternate pillar titles as if they are equivalent canonical names
- do not create hybrid pillar labels
- do not merge pillar identities in diagrams or summaries
- do not expand pillar names differently across artifacts unless explicitly required by artifact context and still clearly anchored to the canonical name

---

## Canonical Five-System Architecture Terms

Within the canonical architecture, the five systems are:

1. **Strategy System**
2. **Portfolio Governance System**
3. **Product Delivery System**
4. **Customer Outcomes System**
5. **Decision Intelligence System**

These five systems belong to the **Product Leadership Systems Architecture (PLSA)** inside **Pillar 1**.

### Rules
- retain exact system names
- do not rename “Portfolio Governance System” to “Governance Engine,” “Investment System,” or similar substitutes
- do not rename “Customer Outcomes System” to “Insights System,” “Value System,” or “Measurement System”
- do not rename “Decision Intelligence System” to “Analytics System,” “Intelligence Layer,” or “BI Layer” as canonical replacements
- do not add systems
- do not split systems
- do not collapse systems into hybrid constructs

---

## Canonical Ownership Terms

The following ownership statements are canonical and should remain stable:

- **Strategy** → direction and refinement
- **Governance** → prioritization, tradeoffs, decisions
- **Delivery** → execution
- **Customer Outcomes** → interpretation, evaluation, value qualification, learning
- **Decision Intelligence** → signals, metrics, dashboards, descriptive analytics only
- **Playbooks** → execution patterns only
- **Labs** → controlled experimentation only

These ownership statements should be used consistently across architecture artifacts and reviews.

---

## Canonical Separation Terms

The following separation rule is canonical:

> **Never collapse evidence, meaning, and decision-making into the same layer.**

The associated canonical mapping is:

- **Evidence** = Decision Intelligence
- **Meaning** = Customer Outcomes
- **Decisions** = Strategy / Governance

These terms are not interchangeable.

### Rules
- do not describe Decision Intelligence as owning meaning
- do not describe Customer Outcomes as merely collecting evidence
- do not describe Strategy or Governance as raw evidence-processing layers
- do not collapse interpretation and decision into one stage

---

## Canonical Mediation Terms

The required mediation path must be expressed as:

> **Decision Intelligence → Customer Outcomes → Strategy / Governance**

This is the canonical influence path for evidence-based decision input.

### Approved supporting phrasing
- Customer Outcomes is the mandatory mediation layer between evidence and decision action.
- Strategy must not refine itself from raw dashboards.
- Governance must not act directly on raw signals.

### Prohibited phrasing
- analytics drives strategy directly
- dashboards determine governance decisions
- telemetry informs prioritization directly
- outcomes are just metrics
- analytics evaluates value

Those phrases collapse boundaries and must not be used as architecture language.

---

## Canonical Pillar 6 Terminology

For **Decision Intelligence**, the canonical layered sequence is:

> **Instrumentation → Signals → Metrics → Analytics → interpreted exclusively by Customer Outcomes**

### Approved Decision Intelligence terms
- instrumentation
- telemetry
- signals
- metrics
- dashboards
- descriptive analytics
- measurement visibility
- evidence surfaces
- analytics and visibility
- measurement integrity

### Prohibited Decision Intelligence substitutions when they imply expanded authority
- interpretation engine
- decision engine
- recommendation layer
- value evaluator
- strategic optimizer
- autonomous governance input

Decision Intelligence may describe evidence. It may not own meaning or decision.

---

## Canonical Pillar 5 Terminology

For **Customer Outcomes**, the following terms are canonical and approved:

- outcome evaluation
- value qualification
- value realization
- learning generation
- customer impact
- business impact
- outcome interpretation
- outcome judgment
- meaning assignment

### Rules
- Customer Outcomes owns interpretation and evaluation
- Customer Outcomes must not be reduced to reporting or dashboards
- Customer Outcomes must not be renamed into a generic analytics function
- Customer Outcomes is not synonymous with performance measurement alone

---

## Canonical Pillar 7 Terminology

For **Playbooks**, approved terminology includes:

- playbooks
- execution patterns
- operating guidance
- applied practices
- repeatable methods
- practical routines

### Rules
Playbooks must be described as **how work is executed**, not as decision authority, interpretive authority, or system-governing architecture.

### Prohibited terminology when used as canonical authority language
- operating system controller
- decision playbook authority
- strategic evaluation layer
- experimentation authority
- architecture override mechanism

---

## Canonical Pillar 8 Terminology

For **Labs**, approved terminology includes:

- labs
- controlled experimentation
- experimental environment
- exploratory trial
- innovation testing
- promotion pathway

The canonical promotion path is:

> **Labs → Outcomes → Governance**

### Rules
- Labs must not be described as production authority
- Labs must not be described as a shortcut to canon
- Labs must not be described as interpreting evidence canonically
- Labs must not be described as replacing Governance or Customer Outcomes

---

## Canonical Artifact Terms

The following artifact terms should be used consistently:

- **portfolio control artifacts**
- **canonical pillar definitions**
- **supporting models**
- **playbooks / labs artifacts**
- **diagrams**
- **README summaries**

These align to the canonical artifact precedence order and should not be casually renamed into ambiguous categories.

### Approved artifact-related terminology
- canonical
- supporting
- summary
- control artifact
- rendered diagram
- portfolio-level artifact
- pillar-level artifact
- cross-pillar artifact

### Terms to avoid when they obscure authority
- source of truth, unless explicitly clarified
- master doc, unless formally defined
- working canon
- semi-canonical
- soft authority artifact

Authority should be described through artifact precedence, not vague labels.

---

## Canonical Review Terms

All signoff reviews should use the following labels exactly:

### Status
- **Approved**
- **Approved with Cleanup**
- **Blocked**

### Review sections
- **Architecture Assessment**
- **Blocking Issues**
- **Non-Blocking Cleanup**
- **Copy-Paste Fix Set**

These review terms help preserve a stable review protocol across sessions and repositories.

---

## Naming Discipline Rules

The following rules are mandatory across the portfolio:

1. **Use exact canonical names for core systems and pillars**  
2. **Do not introduce synonyms as replacements for canonical names**  
3. **Do not let diagram labels drift from repository terminology**  
4. **Do not use local shorthand that obscures formal ownership**  
5. **Do not mix explanatory phrasing with canonical naming in a way that creates ambiguity**  
6. **Do not allow README simplifications to become architecture drift**  
7. **Do not use new names for existing concepts without explicit architectural justification**

Terminology consistency is required across:
- repositories
- READMEs
- diagrams
- supporting models
- cross-pillar artifacts
- reviews
- generated content

---

## Allowed Explanatory Flexibility

Explanatory language is allowed when it helps readability, but only if it does not replace canonical terminology.

For example:
- “execution” may be used to explain **Product Delivery**
- “measured signals” may be used to explain **Decision Intelligence**
- “value judgment” may be used to explain **Customer Outcomes**

However, the canonical term must remain primary and structurally clear.

Explanatory language must support the architecture, not mutate it.

---

## Terminology Conflict Resolution

If terminology conflicts appear across artifacts, resolve them using the following priority:

1. portfolio control artifacts  
2. canonical pillar definitions  
3. supporting models  
4. playbooks / labs artifacts  
5. diagrams  
6. README summaries  

Lower-precedence artifacts must be corrected to align with higher-precedence terminology.

No README, diagram, or local supporting artifact may redefine a canonical term.

---

## Review Standard

Any terminology review should assess:
- correctness of PLOS / PLSA distinction
- exact preservation of the canonical loop
- exact preservation of canonical pillar names
- exact preservation of canonical system names
- consistency of ownership language
- consistency of mediation language
- absence of synonym drift
- absence of boundary-blurring terminology
- alignment across diagrams, READMEs, and control artifacts

Any artifact that introduces naming drift in a way that weakens architecture should be corrected before signoff.

---

## Summary

The **PLOS Canonical Terminology** artifact defines the official language of the portfolio so that all repositories and artifacts describe the same architecture with the same meanings.

Its purpose is to ensure that:
- PLOS remains distinct from PLSA
- the canonical loop remains exact
- pillars and systems retain stable names
- ownership boundaries remain linguistically clear
- evidence, meaning, and decision are not collapsed through language
- diagrams and READMEs stay aligned to architecture
- terminology drift does not become architecture drift

In PLOS, language is part of system control. Protecting terminology is part of protecting the architecture.

---

## License

This repository is licensed under the MIT License. See the root `LICENSE` file for details.
