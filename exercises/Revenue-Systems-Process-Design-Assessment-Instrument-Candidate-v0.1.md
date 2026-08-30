# Revenue Systems & Process Design Assessment Instrument

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Assessment family:** A3 — Revenue Systems & Process Design  
**Parent framework:** RevOps Competency Model Candidate v0.4  
**Parent methodology:** Assessment Methodology Candidate v0.2  
**Coverage architecture:** Role Profile Assessment Coverage Matrix Candidate v0.1  
**Dataset:** `RSP-001-v0.1` — Revenue Systems & Process Dataset Candidate v0.1  
**Primary target Role Profile for system testing:** VP Revenue Operations

## Purpose
Assess whether a participant can design or repair a revenue operating system across process, data, automation, ownership, integrations, reporting, and governance without reducing the problem to product-specific CRM administration.

This instrument is intentionally tool-neutral. The participant may discuss Salesforce, HubSpot, Dynamics, or other platforms if helpful, but proficiency is judged on architecture and reasoning rather than recall of product menus or configuration trivia.

## Core Question

> **Can this person turn a messy GTM system into a coherent operating architecture that is reliable, governable, extensible, and aligned to the business?**

---

# Stage 0
Use the participant baseline from `RSP-001-v0.1`.

## Opening Prompt

> **The CRO says, “We need to clean up Salesforce.” Based on the symptoms you see, how would you frame the problem, what would you investigate first, and what would you change now versus later?**

The participant may request additional information. There is no required packet sequence and no hidden answer checklist.

---

# Evaluator Operating Protocol

Use the evidence packets in `RSP-001-v0.1` responsively.

Rules:
- reveal the smallest fair evidence set that answers the participant's question;
- do not hint at unrequested packets;
- do not reward product-specific vocabulary unless it advances the architecture;
- allow diagrams, tables, pseudo-workflows, object models, or narrative designs;
- ask clarifying questions when the participant's architecture depends on an unstated assumption;
- distinguish quick fixes from durable architecture;
- record how the participant handles tradeoffs, sequencing, exceptions, ownership, observability, and change risk;
- do not force a single “correct” system design.

---

# Required Design Deliverable

Once sufficient evidence has been surfaced, ask the participant to produce a concise target-state design covering:

1. **Lifecycle architecture**  
   How person/account identity, MQL/SQL/opportunity/recycle states, stage criteria, and handoffs should work.

2. **Routing architecture**  
   When enrichment occurs, where routing logic lives, how ownership is determined, how exceptions are handled, and how routing decisions are traceable.

3. **Data ownership / system-of-record model**  
   Which business function owns definitions, which system owns authoritative values, who may edit critical fields, and how conflicting metrics are handled.

4. **Automation / integration architecture**  
   How automation should be consolidated, monitored, tested, documented, and changed safely.

5. **Reporting architecture**  
   How Sales and Finance can use different legitimate measures without labeling both ambiguously as the same metric.

6. **Implementation sequence**  
   What should be stabilized in the next six weeks, what can wait, what should not be changed during quarter close, and what rollback/measurement controls are needed.

7. **Governance**  
   How field creation, automation changes, system ownership, documentation, access, and exception management should work after the cleanup ends.

The deliverable may be written, diagrammed, or presented conversationally. Format quality should not overshadow architecture quality.

---

# Required Decision Gate

Ask:

> **You have limited RevOps capacity and quarter end is six weeks away. What are the three most important actions you would authorize now, what would you explicitly defer, and what risks are you accepting by that sequence?**

Observe prioritization and restraint. A participant who tries to rebuild everything at once should not automatically score higher for ambition.

---

# Change Shock

Use the Default Change Shock from `RSP-001-v0.1` involving the new product-led trial motion.

Then ask:

> **What changes in your architecture, and what stays stable?**

Strong evidence should show whether the design contains reusable principles rather than a collection of brittle point solutions.

---

# Intended Competency Observation

## 6. Systems & Automation — Primary
Observe whether the participant:
- identifies systems of record and integration boundaries;
- consolidates or rationalizes automation thoughtfully;
- designs for monitoring, failure handling, traceability, testability, and rollback;
- recognizes access/control implications without turning the case into a security audit;
- distinguishes business architecture from tool mechanics;
- avoids point-to-point sprawl and undocumented side effects;
- designs for future change rather than only current-state cleanup.

## 5. Process Design & Optimization — Primary
Observe whether the participant:
- maps the operating process before automating it;
- clarifies state transitions, decision rules, exception paths, ownership, and handoffs;
- removes ambiguity and unnecessary manual work;
- sequences improvements based on value, risk, and dependencies;
- distinguishes process defects from system defects;
- creates a process that can be measured and governed.

## 2. Funnel, Lead & Lifecycle Management — Primary
Observe whether the participant:
- designs coherent lifecycle states and qualification transitions;
- handles recycle/re-entry intentionally;
- aligns routing, ownership, stage criteria, and reporting;
- prevents mutually contradictory statuses;
- understands identity/account matching implications for lead flow.

## 1. GTM Systems Thinking — Primary
Observe whether the participant connects Marketing, SDR, Sales, Finance, CS, Product, data, systems, incentives, definitions, and reporting rather than optimizing one tool in isolation.

## Secondary
May support evidence for:
- Data & Analytics
- Change Management & Adoption
- Commercial & Business Judgment
- Communication & Executive Readout

Do not force secondary scores when the behavior is merely incidental.

---

# Adjacent-Level Signals

## Systems & Automation
### L1 — Foundational
Can identify common CRM objects, fields, workflows, or automation concepts with guidance.

### L2 — Practitioner
Can independently configure or maintain familiar workflows and solve routine system problems within an established architecture.

### L3 — Advanced
Can design an integrated cross-functional system/process solution under ambiguity, including data flow, automation, ownership, exceptions, testing, and operational tradeoffs.

### L4 — Strategic
Additionally shapes durable architecture and governance: system-of-record principles, change standards, integration/automation governance, observability, design rules, and senior tradeoffs that materially improve how the revenue system operates over time.

### L5 — Enterprise / Architect
Requires triangulated evidence that the participant can create reusable systems architecture and governance across materially different contexts, complexity, scale, and change. Do not award from this case alone.

## Process Design & Optimization
### L1
Recognizes basic process steps and defects with guidance.

### L2
Can document and improve a familiar process independently.

### L3
Can redesign an ambiguous cross-functional process with clear states, ownership, decision rules, exception handling, controls, and measurement.

### L4
Additionally creates reusable operating standards/governance and reshapes how the organization designs, owns, and evolves critical processes.

### L5
Requires evidence of reusable process architecture across materially different operating environments.

---

# Known Assessment Traps

## CRM-trivia trap
Knowing exactly where a checkbox lives is not the target construct.

## Big-bang trap
A complete rebuild is not automatically superior to a staged repair.

## Automation-equals-progress trap
More workflows do not equal better architecture.

## Diagram beauty trap
A polished architecture diagram can conceal weak reasoning.

## Single-source absolutism trap
Not every legitimate business metric must collapse into one value. Different definitions may serve different purposes if clearly governed.

## Tool-preference trap
Do not reward or penalize the participant for preferring Salesforce, HubSpot, or another platform absent business evidence.

## Admin-to-architect inflation trap
Strong product administration is valuable but does not automatically demonstrate L4 systems leadership.

## Governance-theater trap
Naming a change board, RACI, or data council without defining decisions, ownership, triggers, or operating behavior is weak evidence.

## Overengineering trap
Do not reward architecture that creates unnecessary complexity for the company's scale and constraints.

---

# Evidence Record Requirements

Record:
- participant/anonymized ID;
- instrument/version;
- dataset/version;
- target Role Profile;
- evidence packets encountered;
- target-state architecture proposed;
- decisions and sequencing;
- explicit deferrals/restraint;
- assumptions;
- response to Change Shock;
- competencies materially observed;
- competency-level Proficiency;
- competency-level Confidence;
- Observed Role Fit;
- Overall Role Fit only when accumulated Profile Coverage supports it;
- Profile Coverage description;
- strengths and development edge;
- Insufficient Evidence areas;
- evaluator identity/version;
- unresolved disagreement.

---

# Participant-Facing Result Guardrails

Explain:
- what systems/process capability was demonstrated;
- evidence supporting the judgment;
- whether the participant distinguished architecture from administration;
- whether their design balanced reliability, simplicity, governance, and changeability;
- what cannot be concluded from the case;
- Confidence;
- Observed Role Fit only within the scope tested.

Do not imply this one instrument proves complete RevOps role readiness.

---

# System-Test Success Criteria

A3 should eventually show that it can:
1. distinguish tool knowledge from systems architecture;
2. distinguish routine administration (L2) from ambiguous cross-functional design (L3);
3. distinguish strong design (L3) from durable system/governance shaping (L4);
4. reward process clarity before automation;
5. reward sequencing and restraint under operational constraints;
6. expose brittle point-solution thinking through the Change Shock;
7. avoid platform bias;
8. produce meaningful Confidence and Insufficient Evidence judgments;
9. add new Profile Coverage rather than merely repeat A1/A2 evidence;
10. surface methodology defects if competency boundaries blur.

---

# Validation Status

This instrument has not yet been run through a controlled synthetic end-to-end validation.

No empirical inter-rater reliability, predictive validity, hiring validity, certification threshold, or minimum evidence standard is established.

---

# Governance

This document is a **Candidate only**.

It was created under JET's approved Candidate-development architecture for a small series of complementary assessments. That approval does not make this instrument, its dataset, evidence assignments, or level signals canonical.

Canonical promotion requires JET's explicit review and approval of a specific identifiable Candidate.
