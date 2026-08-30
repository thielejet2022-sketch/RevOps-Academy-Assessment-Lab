# Revenue Systems & Process Design — End-to-End System Validation Run

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Instrument tested:** Revenue Systems & Process Design Assessment Instrument Candidate v0.1  
**Dataset:** RSP-001-v0.1  
**Target Role Profile:** VP Revenue Operations  
**Participant:** Controlled synthetic participant  
**Validation purpose:** Test whether A3 distinguishes strong CRM administration from integrated systems/process architecture and strategic governance.

## Important Limitation
This is a synthetic system test authored and evaluated within the same development environment. It is not independent evaluator evidence, inter-rater reliability evidence, predictive validity, or hiring validity.

---

# Synthetic Participant Design

The participant is deliberately modeled as a **very strong CRM / RevOps systems practitioner** who has substantial Salesforce administration and automation experience but has not consistently operated as an enterprise systems architect.

Intended behavior:
- technically fluent;
- rapidly identifies broken workflows and fields;
- proposes sensible automation cleanup;
- understands routing and lifecycle mechanics;
- tends to solve visible defects before fully defining business architecture;
- can produce strong L2/L3 work;
- may drift toward point solutions when requirements change;
- does not naturally establish durable system-of-record principles, observability standards, or cross-functional change governance.

The test is whether technical fluency is prevented from inflating into L4 systems leadership.

---

# Interaction Trace

## Stage 0
Participant receives the RSP-001-v0.1 baseline and the CRO request to “clean up Salesforce.”

### Synthetic participant opening
The participant immediately rejects “clean up Salesforce” as too narrow and says they first need to understand which failures are process, data-definition, ownership, integration, or configuration problems.

They ask for:
1. lifecycle definitions and where they conflict;
2. routing rules and ownership logic;
3. major automation/integration failures;
4. reporting-definition disagreements;
5. quarter-end constraints.

### Evidence released
Relevant dataset packets covering lifecycle ambiguity, routing, automation/integrations, reporting, and timing constraints.

### Observed reasoning
The participant identifies that the CRM contains symptoms of a broader operating-model problem:
- mutually inconsistent lifecycle states;
- routing logic distributed across multiple mechanisms;
- duplicate/identity problems affecting assignment and reporting;
- automations with unclear ownership and side effects;
- Finance and Sales using different definitions under ambiguous labels;
- quarter-end timing makes a broad rebuild risky.

They recommend documenting current-state lifecycle and routing before deleting workflows.

**Provisional evidence:** clear L3 Process Design and Systems & Automation. Technical skill is being used in service of architecture rather than trivia.

---

# Stage 1 — Lifecycle and Routing Design

The participant proposes:
- one explicit lifecycle-state model with mutually understandable definitions;
- separate concepts for lifecycle state, qualification status, opportunity stage, and ownership rather than overloading one field;
- a defined recycle/re-entry path;
- account/person matching before final ownership assignment where practical;
- one governed routing service or logic layer rather than rules scattered across forms, workflows, integrations, and rep-created automation;
- routing reason and timestamp retained for traceability;
- exception queue for records that cannot be confidently routed;
- explicit ownership for routing-rule changes.

They suggest fixing high-volume routing defects immediately while deferring lower-risk field cleanup.

### Evaluator observation
This exceeds routine CRM administration. The participant is designing coherent states, decision rules, exception handling, traceability, and ownership.

**Process Design:** L3 strong.  
**Systems & Automation:** L3 strong.

---

# Stage 2 — Automation and Integration Architecture

Participant learns there are 147 automations, overlapping triggers, undocumented integration dependencies, and manual downstream cleanup.

### Synthetic participant response
They propose inventorying automations by:
- business purpose;
- trigger;
- object/data touched;
- owner;
- downstream dependency;
- failure consequence;
- last meaningful use.

They would classify each as retain, consolidate, replace, or retire.

They propose a sandbox/test process for material changes and rollback plans for quarter-end-critical flows.

However, when asked how the organization should know that an automation or integration has silently failed, the participant initially answers with admin alerts and a weekly exception report rather than a broader observability architecture.

When probed, they add error logging and integration monitoring but do not clearly define service ownership, health thresholds, business-level controls, or escalation standards.

### Evaluator observation
The design is competent and materially above routine administration, but its reliability model remains somewhat operational/reactive.

**Systems & Automation:** L3, not yet L4.

---

# Stage 3 — Reporting and System-of-Record Problem

The participant learns that Sales and Finance both report “bookings,” but Sales means signed contract value while Finance means a finance-recognized measure. Different systems and timing rules produce legitimate but conflicting values.

### Synthetic participant response
They reject forcing one number to serve both purposes.

They propose:
- define distinct metrics with unambiguous names;
- document business purpose and calculation;
- assign definition ownership;
- identify authoritative source for each component;
- preserve reconciliation between operational and finance measures;
- prevent dashboards from labeling both simply “Bookings.”

They say CRM can display Finance's authoritative value if useful, but should not independently recreate Finance logic when Finance remains the authoritative source.

### Evaluator observation
Strong system-of-record reasoning and metric governance. This is one of the participant's strongest architecture moments.

**GTM Systems Thinking:** L3 strong.  
**Data & Analytics:** useful secondary evidence.  
**Systems & Automation:** near L4 boundary on this dimension.

---

# Required Design Deliverable

## Synthetic target-state architecture

### Lifecycle
Participant defines discrete lifecycle, qualification, opportunity, and ownership concepts with explicit transition criteria and recycle/re-entry logic.

### Routing
Participant centralizes routing logic, enriches/matches before final assignment where feasible, records routing reason, creates exception handling, and assigns ownership for rules.

### Data ownership
Participant defines authoritative systems/owners for critical values and separates business-definition ownership from technical implementation ownership.

### Automation/integration
Participant inventories and rationalizes automation, consolidates overlapping rules, uses testing and rollback for material changes, and adds operational monitoring.

### Reporting
Participant creates named, governed measures rather than forcing legitimate operational and finance definitions into one ambiguous metric.

### Implementation sequence
Participant proposes:
1. stabilize high-impact routing/lifecycle defects;
2. freeze nonessential automation changes through quarter end;
3. document/inventory critical automation and integrations;
4. establish target-state lifecycle/routing model;
5. migrate in controlled waves after quarter close;
6. retire redundant fields/workflows only after dependencies are confirmed.

### Governance
Participant proposes:
- named business owner for lifecycle/routing definitions;
- RevOps technical owner for implementation;
- documented change requests for material automation/field changes;
- quarterly cleanup review;
- restricted ability to create production automation.

### Evaluator observation
This is strong L3 architecture with several L4-like governance elements. The governance remains more a set of sensible controls than a fully articulated operating architecture with durable decision rights, observability standards, design principles, and cross-system change mechanisms.

---

# Required Decision Gate

Participant authorizes three immediate actions:

1. **Stabilize routing and lifecycle contradictions that are actively losing or misassigning demand.**
2. **Freeze and inventory quarter-end-critical automation before broad cleanup.**
3. **Define authoritative business definitions and system ownership for lifecycle and bookings before rebuilding reports.**

Explicitly deferred:
- wholesale object-model redesign;
- broad field deletion;
- mass workflow migration;
- platform replacement;
- cosmetic cleanup.

Accepted risk:
Some technical debt remains for another quarter, but customer/revenue-impacting defects are addressed while destructive change risk is contained.

### Evaluator observation
Strong sequencing and restraint. The participant resists the big-bang trap.

---

# Change Shock

The participant learns that Product will launch a self-serve trial motion next quarter. Trial users may belong to named enterprise accounts and should sometimes route to an AE rather than remain in a PLG nurture path.

## Synthetic participant response
The participant initially proposes adding a trial-specific routing branch to the centralized routing logic.

When asked what should remain stable, they say:
- identity/account matching remains upstream of ownership assignment;
- lifecycle state remains distinct from acquisition source;
- routing must remain traceable;
- exception handling remains required;
- named-account policy should remain a business-owned rule;
- the PLG motion should introduce a new source/engagement state, not create a parallel duplicate lifecycle.

They revise the design so trial behavior becomes another input into governed routing rather than a separate point solution.

### Evaluator observation
The initial instinct was a point-rule addition, but the participant recovered by applying stable architecture principles. This is positive evidence of adaptability and disconfirmation.

The shock exposes the intended seam:
- strong L3 can adapt an integrated architecture under change;
- L4 should more naturally begin from reusable design principles and governance that absorb new motions without requiring evaluator prompting.

---

# Competency Evaluation

## 6. Systems & Automation
**Proficiency:** L3 — Advanced, near L4 boundary  
**Confidence:** Moderate

Evidence:
- architecture rather than configuration trivia;
- automation rationalization;
- system-of-record boundaries;
- integration awareness;
- testing/rollback;
- traceability and exception handling;
- adaptable design under PLG shock.

Constraint on L4:
- observability, service ownership, durable design standards, and cross-system change governance required prompting or remained underdeveloped.

## 5. Process Design & Optimization
**Proficiency:** L3 — Advanced  
**Confidence:** Moderate

Evidence:
- explicit states/transitions;
- separation of process concepts;
- exception paths;
- ownership and handoffs;
- process-first sequencing;
- controlled migration and restraint.

Constraint on L4:
- limited evidence of reshaping how the organization repeatedly designs and governs critical processes beyond this case.

## 2. Funnel, Lead & Lifecycle Management
**Proficiency:** L3 — Advanced  
**Confidence:** Moderate

Evidence:
- coherent lifecycle architecture;
- recycle/re-entry;
- routing/ownership alignment;
- identity/account matching implications;
- PLG motion integrated without duplicating lifecycle.

## 1. GTM Systems Thinking
**Proficiency:** L3 — Advanced  
**Confidence:** Moderate

Evidence:
- integrated Marketing, SDR, Sales, Finance, Product, data, systems, definitions, and reporting;
- avoided optimizing Salesforce in isolation.

## 4. Data & Analytics
**Proficiency:** Narrowly observed, provisional L3  
**Confidence:** Low

Evidence:
- metric-definition governance and authoritative-source reasoning.

Insufficient breadth for stronger standalone judgment.

## 9. Change Management & Adoption
**Result:** Insufficient Evidence

The participant discussed sequencing and technical change control, but stakeholder adoption behavior was not directly observed. Do not convert implementation planning into Change Management proficiency.

## 7. Commercial & Business Judgment
**Result:** Narrowly observed  
**Confidence:** Low

Sequencing and risk decisions were sensible, but economic tradeoff evidence was limited.

## 11. Communication & Executive Readout
**Result:** Narrowly observed  
**Confidence:** Low

The participant communicated architecture clearly, but executive communication was not a major construct in this run.

## Other competencies
**Insufficient Evidence:**
- Forecasting & Revenue Planning
- Cross-Functional Leadership
- Operating Cadence & Execution as sustained behavior

---

# Role Fit Treatment

## Observed Role Fit — VP Revenue Operations
**Approaching target**

The participant demonstrates strong systems/process capability and several strategic instincts, but the observed behavior is predominantly L3 integrated design rather than consistent L4 architecture/governance shaping.

## Overall VP Role Fit
**Insufficient evidence**

A3 alone cannot support a complete VP judgment.

## Profile Coverage Added by A3
Materially observed:
- Systems & Automation
- Process Design & Optimization
- Funnel, Lead & Lifecycle Management
- GTM Systems Thinking

Narrowly observed:
- Data & Analytics
- Commercial & Business Judgment
- Communication & Executive Readout

Insufficient in this instrument:
- Forecasting & Revenue Planning
- Cross-Functional Leadership
- Change Management & Adoption
- sustained Operating Cadence & Execution

---

# System Audit

## 1. Tool knowledge vs systems architecture
**PASS provisionally.** Product fluency did not determine the score. The participant had to reason about lifecycle, data ownership, process, integration, reliability, and governance.

## 2. L2 administration vs L3 design
**PASS provisionally.** The participant crossed L3 by designing an ambiguous cross-functional operating architecture rather than merely configuring known requirements.

## 3. L3 vs L4
**PASS provisionally, with a useful refinement.** L4 systems evidence should not be awarded merely because governance artifacts are named. It requires durable architecture principles, decision rights, observability/reliability standards, and change mechanisms that shape how the system evolves.

## 4. Process before automation
**PASS.** The participant modeled lifecycle/routing before automation cleanup.

## 5. Sequencing and restraint
**PASS.** Quarter-end constraints produced staged repair rather than a big-bang rebuild.

## 6. Change Shock
**PASS.** The PLG shock exposed an initial point-solution instinct and then demonstrated adaptation toward reusable principles.

## 7. Platform bias
**PASS provisionally.** No Salesforce menu/configuration recall was required for strong evidence.

## 8. Confidence and Insufficient Evidence
**PASS.** The run did not manufacture Change Management or leadership scores from technical implementation behavior.

## 9. New Profile Coverage
**PASS.** A3 materially adds Systems & Automation and Process Design evidence that A1/A2 do not directly provide.

## 10. Methodology defects
**One important seam clarified:** technical change control is not the same construct as Change Management & Adoption. The framework should preserve that boundary.

---

# Calibration Findings

## Finding 1 — Technical fluency must remain subordinate to architecture
A highly skilled administrator can demonstrate L3 systems capability when they independently design integrated architecture under ambiguity. Product expertise alone remains insufficient for L4.

## Finding 2 — Governance theater applies strongly in systems work
A change board, documentation requirement, or automation inventory is not automatically strategic governance.

For L4 Systems & Automation, look for behavior such as:
- durable design principles;
- explicit system-of-record architecture;
- decision rights;
- observability/reliability standards;
- controlled change mechanisms;
- architecture that absorbs new GTM motions without proliferating exceptions;
- senior tradeoff framing around complexity, reliability, cost, and adaptability.

## Finding 3 — Change control ≠ Change Management
Testing, rollback, release controls, documentation, and technical sequencing belong primarily to systems/process capability.

Change Management & Adoption requires evidence involving human adoption, incentives, resistance, communication, behavior change, reinforcement, and sustained use.

This distinction protects Competency 9 from being accidentally scored whenever a participant proposes an implementation plan.

---

# Validation Status

A3 passes this first controlled synthetic system test for continued Candidate development.

It does **not** establish empirical inter-rater reliability, predictive validity, hiring validity, certification validity, or a validated VP Role Profile.

A contrasting synthetic L4 systems architect should eventually test whether the instrument positively elicits durable architecture/governance behavior rather than merely withholding L4 from a strong L3 participant.

---

# Recommended Next Design Action

Proceed to **A4 — Stakeholder Alignment & Change Simulation** before running the contrasting L4 A3 case.

Reason: A3 surfaced a clean boundary between technical change control and human Change Management. A4 is now the best place to test whether the competency framework can observe the missing human/relational construct without collapsing into generic “communication skills.”

---

# Governance

This document is a **Candidate only**.

No canonical framework, methodology, dataset, or competency model was changed by this synthetic validation run.
