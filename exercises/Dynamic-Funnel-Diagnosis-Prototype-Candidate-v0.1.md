# Dynamic Funnel Diagnosis — Interactive Assessment Prototype

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Target use:** Academy Mode and Assessment Lab prototype  
**Primary target profiles:** Manager, Director / Head of RevOps, VP of Revenue Operations  
**Dataset:** `FD-001-v0.1` — `datasets/Funnel-Deterioration-Dataset-Candidate-v0.1.md`

## Purpose
Prototype a dynamic RevOps assessment in which the participant begins with incomplete operating information, chooses what evidence to request, updates hypotheses as information is revealed, and ultimately makes a decision.

The exercise is designed to evaluate the **path of inquiry**, not merely the final answer.

## Dataset Boundary
This exercise does not own the underlying operating facts. All Stage 0 facts, hidden evidence, and interpretation boundaries are defined in dataset `FD-001-v0.1`.

Historical runs of this exercise must retain the dataset version used. A material dataset change requires explicit exercise review rather than silently changing prior assessment meaning.

## Participant Brief — Stage 0
Use the Stage 0 facts from `FD-001-v0.1`.

The CEO asks:

> “We spent more on growth and added sellers. Why are opportunities down, and what should we do next?”

The participant does **not** have enough information to establish causation from Stage 0 facts alone.

### Participant task
Explain what the initial signals suggest, identify the most important question or evidence wanted next, and explain why it matters.

The evaluator reveals additional information based on the participant's inquiry.

---

# Evaluator Evidence Routing

Use the evidence sections in `FD-001-v0.1`. Do not duplicate or alter their facts inside this exercise.

Map participant inquiries naturally:
- lead source/channel/campaign mix → Evidence A
- qualification/SDR/routing/response time → Evidence B
- AE ramp/tenure/productivity/capacity → Evidence C
- segment or SQL-to-opportunity conversion → Evidence D
- sales cycle/stage aging/stalls → Evidence E
- loss/disqualification/customer fit/competition → Evidence F
- spend/economics/revenue productivity → Evidence G
- plan/capacity assumptions/hiring justification → Evidence H
- ownership/governance/review cadence → Evidence I

Do not reveal the routing map during a scored or learning run until debrief.

## Interaction Rules
The participant may request evidence naturally rather than selecting from a menu. Do not reward keyword guessing. Reveal only the evidence reasonably responsive to the inquiry.

After each reveal ask:

> “What does this change in your working hypothesis, and what do you want to know or decide next?”

Use up to **five evidence requests** before requiring a decision recommendation. This is a prototype constraint, not a canonical assessment rule.

If a participant asks a commercially sensible question the dataset cannot answer, state that the evidence is unavailable rather than inventing a value. Record the missing evidence as a dataset-validation finding.

## Final Participant Task
Ask the participant to give the current diagnosis, distinguish facts from remaining hypotheses, state what they would do now, identify what they would not do yet, and explain the business rationale.

For Director and VP profiles, also ask what operating or governance change should persist after the immediate problem is addressed.

---

# Evaluator Observation Guide

Record the participant's **sequence**, not only the final answer.

Observe:
- what they noticed from Stage 0;
- their first evidence request and why;
- whether each reveal changed their hypothesis;
- whether they pursued confirming and disconfirming evidence;
- whether they prioritized economically consequential uncertainty;
- whether they jumped to causation;
- whether they recognized productive capacity versus nominal headcount;
- whether they connected functional metrics into an end-to-end system;
- whether they reached a decision before exhausting every possible question;
- whether their recommendation was proportional to the evidence.

## High-Value Inquiry Patterns
There is no single required sequence. Strong participants may enter through different doors.

Potentially high-value early questions include:
- Where exactly did conversion deteriorate?
- Did lead/channel mix change?
- Are the seven AEs actually ramped and productive?
- What assumptions justified incremental growth investment?
- Where did the sales cycle increase?
- What are the economics per SQL/opportunity?

Score the reasoning behind the inquiry, not similarity to a preferred script.

## Weak Inquiry Patterns
Potential negative evidence includes:
- requesting large undirected data dumps;
- repeatedly asking for descriptive metrics without narrowing a decision;
- asking only for evidence that confirms the initial hypothesis;
- ignoring contradictory evidence;
- inventing unavailable facts;
- making an irreversible recommendation before establishing the constraint.

---

# Role-Altitude Expectations

## Manager
Should isolate material operating constraints, organize the investigation, establish owners, and propose practical corrective actions.

## Director / Head of RevOps
Should integrate funnel, capacity, planning, economics, and cross-functional ownership into an operating correction plan.

## VP of Revenue Operations
Should additionally determine whether the evidence exposes a flaw in the growth operating model, frame executive resource-allocation decisions, and establish durable governance or decision architecture.

A VP-level response should not be rewarded for simply requesting more sophisticated data. Seniority is demonstrated through integration, judgment, consequence, and decision responsibility.

---

# Live Validation Finding — Run 1
The first VP-altitude live run demonstrated that healthy uncertainty should count as positive evidence, but an evaluator must distinguish it from indefinite analysis after sufficient evidence exists for a reversible decision.

The run also surfaced missing dataset evidence that commercially capable participants may reasonably request: revenue versus plan, revenue per AE/productive cohort, ASP/ACV movement, and a defensible CAC definition/calculation. These gaps are recorded in `FD-001-v0.1` and should not be filled ad hoc during administration.

# Prototype Validation Questions
After running the exercise, evaluate:
1. Did inquiry sequence reveal useful evidence beyond the final answer?
2. Were dataset evidence packets realistic and internally coherent?
3. Did the five-request constraint force useful prioritization or artificial behavior?
4. Could different strong inquiry paths still produce fair scores?
5. Did the evaluator have too much discretion mapping questions to evidence?
6. Did the exercise distinguish Manager, Director, and VP reasoning using the same dataset?
7. Which competencies were genuinely observable and which require another exercise?
8. Could another evaluator administer it consistently?

## Governance
This is a prototype Candidate only. The interaction rules, inquiry limit, role-altitude expectations, and validation findings are not canonical assessment standards. The exercise must be validated before formal hiring or certification use.
