# Evidence Modality Architecture — Pressure Test

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Parent framework:** RevOps Competency Model Candidate v0.4  
**Trigger:** Cross-Functional Leadership Evidence Anchors Candidate v0.1 exposed that different competencies may require different evidence-collection methods.

## Question
Where should **evidence modality** live in the RevOps Academy & Assessment Lab architecture?

Candidate options:

1. add modality to the core Competency Model architecture;
2. place modality in Assessment Methodology;
3. leave modality entirely to individual Exercise design.

The goal is to preserve the approved core architecture:

> **Competency × Proficiency × Role Profile**

while ensuring assessments collect evidence appropriate to the capability being evaluated.

---

# Working Definition

**Evidence modality** is the method by which observable evidence of competency is elicited or collected.

Examples:
- analytical case;
- dynamic diagnostic case;
- technical/system-design case;
- stakeholder simulation;
- structured behavioral/work-history interview;
- artifact/work-product review;
- live task or demonstration;
- repeated longitudinal observation.

Modality is not a proficiency level, competency, participant characteristic, or score.

---

# Option 1 — Add Modality to the Core Competency Model

Possible architecture:

> Competency × Proficiency × Role Profile × Evidence Modality

## Advantages
- makes evidence method highly visible;
- discourages one-size-fits-all assessment design;
- could map each competency to preferred assessment types.

## Problems
- changes the meaning of the approved core architecture;
- modality does not describe the participant or target role;
- multiple modalities may assess the same competency/proficiency;
- one exercise may produce evidence for several competencies through different mechanisms;
- modality choices can evolve as assessment technology changes without changing the competency construct;
- risks making the Competency Model responsible for test administration details.

## Pressure-test verdict
**Reject as a core dimension.**

Evidence modality is structurally different from Competency, Proficiency, and Role Profile. Adding it to the multiplication would confuse the construct being assessed with the method used to observe it.

---

# Option 2 — Place Modality in Assessment Methodology

Possible architecture:

**Competency Model** defines:
- what capability exists;
- proficiency altitude;
- target Role Profile patterns.

**Assessment Methodology** defines:
- what constitutes sufficient evidence;
- which evidence modalities are appropriate;
- how modalities can be combined;
- confidence implications;
- evaluator rules;
- fairness and comparability expectations.

**Exercises** instantiate the methodology in specific scenarios.

## Advantages
- preserves the clean approved core architecture;
- separates construct definition from evidence collection;
- allows modality guidance to evolve without redefining competencies;
- supports multi-method assessment;
- provides a central place to govern validity, confidence, fairness, and evidence sufficiency;
- prevents individual exercise authors from inventing incompatible evidence rules.

## Problems
- requires a methodology layer with enough specificity to be useful without becoming bureaucratic;
- competency-specific modality guidance still needs to exist somewhere accessible;
- poor implementation could create duplicated modality rules across methodology and evidence-anchor files.

## Pressure-test verdict
**Preferred architecture.**

Modality belongs primarily in Assessment Methodology.

---

# Option 3 — Leave Modality Entirely to Exercise Design

Possible architecture:

Each exercise author independently decides whether to use a case, simulation, interview, artifact, or other method.

## Advantages
- maximum flexibility;
- minimal central governance;
- easy experimentation during early development.

## Problems
- assessment quality becomes exercise-author dependent;
- the same competency could be assessed with radically different evidentiary strength without that difference being visible;
- confidence ratings could become inconsistent;
- behavioral competencies are vulnerable to weak self-description being treated as observed capability;
- hiring use becomes especially risky because comparability across participants may collapse;
- lessons learned would remain trapped inside individual exercises.

## Pressure-test verdict
**Reject as the sole home.**

Exercises should choose and implement modalities, but they should do so within methodology-level rules.

---

# Recommended Layering

## Layer 1 — Competency Model
Answers:

> **What capability are we evaluating, at what proficiency altitude, relative to what Role Profile?**

Owns:
- competency definitions;
- shared L1–L5 spine;
- Role Profile framework;
- high-level evidence principles;
- competency-specific observable anchors by reference.

Does **not** own test-delivery mechanics.

## Layer 2 — Assessment Methodology
Answers:

> **What evidence would allow us to make a trustworthy judgment about that capability?**

Owns:
- evidence modalities;
- evidence sufficiency;
- modality strengths/limitations;
- triangulation rules;
- Confidence implications;
- evaluator consistency rules;
- dynamic evidence principles;
- fairness/comparability rules;
- observed behavior versus self-reported behavior distinctions.

## Layer 3 — Exercise / Assessment Instrument
Answers:

> **How will this particular participant be given an opportunity to demonstrate the capability?**

Owns:
- scenario;
- dataset/version;
- prompts;
- stakeholder roles;
- evidence-release mechanics;
- task sequence;
- time/interaction constraints where applicable;
- selected modality or combination of modalities;
- scoring targets and evaluator instructions by reference.

## Layer 4 — Evidence Record / Evaluation
Answers:

> **What did the participant actually demonstrate, and how confident are we?**

Owns:
- observed evidence;
- competency-specific interpretation;
- proficiency judgment;
- Confidence;
- Role Fit comparison where applicable;
- Insufficient evidence flags;
- evaluator notes.

This layer does not change the competency or methodology.

---

# Key Architectural Distinction

> **The Competency Model defines the construct. Assessment Methodology defines trustworthy observation. Exercises create the opportunity. Evaluation records the evidence and judgment.**

This separation keeps the core model stable while allowing assessment methods to evolve.

---

# Modality Is Many-to-Many

A major reason modality should not become a core dimension is that the relationship is many-to-many.

One competency may require several modalities for high confidence.

Example: **Cross-Functional Leadership**
- stakeholder simulation may reveal behavior under resistance;
- structured work-history evidence may reveal sustained influence over time;
- longitudinal observation may reveal whether governance survives after intervention.

One modality may also test several competencies.

Example: **dynamic funnel case**
- Funnel, Lead & Lifecycle Management;
- Data & Analytics;
- Commercial & Business Judgment;
- GTM Systems Thinking;
- Communication & Executive Readout.

Therefore modality should be treated as an evidence-collection design choice governed by methodology, not a fourth axis of participant capability.

---

# Candidate Modality Taxonomy

This is a working taxonomy, not a required final list.

## 1. Analytical Case
Participant interprets a defined evidence set and produces analysis/recommendation.

Strong for:
- Data & Analytics;
- Forecasting & Revenue Planning;
- Commercial & Business Judgment.

Limitation: can over-reward polished written reasoning and under-observe interactive behavior.

## 2. Dynamic Diagnostic Case
Participant requests evidence, revises hypotheses, and decides as information is revealed.

Strong for:
- Funnel, Lead & Lifecycle Management;
- GTM Systems Thinking;
- Commercial & Business Judgment;
- Data & Analytics.

Limitation: quality depends heavily on hidden-evidence design and evaluator consistency.

## 3. Technical / System-Design Case
Participant diagnoses or designs CRM, automation, data, integration, or architecture decisions.

Strong for:
- Systems & Automation;
- Process Design & Optimization;
- Data & Analytics.

Limitation: can confuse technical implementation depth with strategic systems leadership unless anchors explicitly prevent it.

## 4. Stakeholder Simulation
Participant interacts with simulated stakeholders whose positions, incentives, authority, and resistance respond to the participant's choices.

Strong for:
- Cross-Functional Leadership;
- Communication & Executive Readout;
- Change Management & Adoption.

Limitation: simulation quality and consistency can materially affect the evidence produced.

## 5. Structured Behavioral / Work-History Evidence
Participant describes prior situations using a structured evidence protocol focused on context, behavior, resistance, decisions, outcomes, and durability.

Strong for:
- Cross-Functional Leadership;
- Change Management & Adoption;
- Operating Cadence & Execution;
- higher-altitude evidence that unfolds over time.

Limitation: self-reported evidence is weaker than directly observed behavior and may require corroboration or careful Confidence limits.

## 6. Artifact / Work-Product Review
Evaluator reviews participant-created operating artifacts such as forecasts, process maps, dashboards, governance documents, system designs, lifecycle definitions, or executive readouts.

Strong for:
- Process Design & Optimization;
- Systems & Automation;
- Forecasting & Revenue Planning;
- Communication & Executive Readout.

Limitation: authorship, context, constraints, and actual organizational impact may be uncertain.

## 7. Live Task / Demonstration
Participant performs a bounded task directly.

Strong for:
- technical execution;
- analytical execution;
- communication tasks;
- some process-design work.

Limitation: short tasks may over-test speed and under-test sustained judgment.

## 8. Longitudinal Observation
Evidence is collected across repeated work or assessment interactions over time.

Strong for:
- leadership;
- change/adoption;
- operating cadence;
- L5 durability/transferability claims.

Limitation: expensive and slow; unsuitable as a universal requirement.

---

# Confidence Implications

Evidence modality should influence **Confidence**, not directly determine proficiency.

Example:
- a brilliant written stakeholder answer may support L4 reasoning but only Low/Moderate confidence in actual Cross-Functional Leadership behavior;
- repeated successful stakeholder simulations plus structured work-history evidence may support the same L4 proficiency judgment with higher confidence;
- a live technical demonstration may produce strong evidence of implementation skill but still insufficient evidence of L4 systems governance.

Therefore:

> **Do not award a higher proficiency level merely because a stronger modality was used. Use stronger/multiple modalities to increase confidence in the proficiency judgment.**

---

# Triangulation Principle

No universal rule should require multiple modalities for every competency.

Instead, triangulation should increase as:
- stakes increase;
- proficiency claim increases;
- the competency is difficult to observe in a single interaction;
- self-report forms a large portion of evidence;
- the decision has significant hiring, certification, or development consequences.

Candidate principle:

> **Evidence burden should rise with the consequence and breadth of the claim, not merely with the participant's title.**

A low-stakes Academy exercise may reasonably produce a provisional L3/Moderate judgment. A high-stakes claim that someone is consistently L5 in Cross-Functional Leadership should require materially broader evidence.

---

# Pressure-Test Scenarios

## Scenario A — Same competency, different modality
Two participants receive Cross-Functional Leadership assessments.

Participant 1 writes an excellent essay describing how to resolve Sales/Marketing conflict.

Participant 2 navigates a stakeholder simulation, revises approach after resistance, clarifies decision rights, and creates durable accountability.

Both may demonstrate sophisticated reasoning, but the second produces stronger directly observed behavioral evidence.

**Conclusion:** modality affects Confidence/evidence quality, not the definition of L4.

## Scenario B — Same modality, different competencies
A dynamic funnel case reveals excellent Funnel/Lifecycle reasoning and Commercial Judgment but contains no meaningful stakeholder resistance.

**Conclusion:** do not score Cross-Functional Leadership merely because the participant mentions stakeholders.

## Scenario C — High-quality artifact, unknown impact
A participant presents an excellent lifecycle governance framework from prior work, but authorship and adoption cannot be established.

**Conclusion:** the artifact may support architecture reasoning, but Confidence in demonstrated organizational leadership should remain constrained.

## Scenario D — Multiple weak modalities
A participant provides a polished interview answer, a generic slide deck, and a rehearsed stakeholder script.

**Conclusion:** three weak sources do not automatically equal strong triangulation. Evidence quality matters more than evidence count.

---

# Pressure-Test Result

The cleanest architecture is:

> **Competency Model → Assessment Methodology → Exercise / Assessment Instrument → Evidence Record / Evaluation**

with Dataset as a reusable operating-reality asset referenced by exercises where applicable.

Evidence modality belongs primarily in **Assessment Methodology** and is selected/implemented by individual exercises.

It should **not** become a fourth dimension of the approved Competency × Proficiency × Role Profile architecture.

This finding also clarifies that the repository's existing `methodology/` layer has a substantive purpose rather than serving as a miscellaneous folder.

---

# Recommended Next Step

Do not modify Competency Model Candidate v0.4 solely to add modality.

Instead, use this finding to draft a compact **Assessment Methodology Candidate v0.1** that consolidates the already-tested principles for:
- evidence modality;
- evidence sufficiency;
- Confidence;
- dynamic evidence;
- triangulation;
- evaluator consistency;
- Insufficient evidence;
- separation of proficiency from Role Fit.

That would begin turning the existing scoring and assessment Candidates into a coherent methodology layer without disturbing the approved core model architecture.

## Governance
This document is a Candidate only. It does not change the parent Competency Model Candidate v0.4 or establish canonical assessment methodology. Any consolidation into a methodology Candidate remains non-canonical until reviewed and explicitly approved for promotion.
