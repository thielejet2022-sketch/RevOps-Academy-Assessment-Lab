# Dynamic Funnel Diagnosis — Interactive Assessment Prototype

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Target use:** Academy Mode and Assessment Lab prototype  
**Primary target profiles:** Manager, Director / Head of RevOps, VP of Revenue Operations

## Purpose
Prototype a dynamic RevOps assessment in which the participant begins with incomplete operating information, chooses what evidence to request, updates hypotheses as information is revealed, and ultimately makes a decision.

The exercise is designed to evaluate the **path of inquiry**, not merely the final answer.

## Participant Brief — Stage 0
You have joined the weekly executive revenue review for a B2B SaaS company. Leadership is concerned because growth investments are not producing the expected pipeline output.

Year over year:

- MQL volume: +29%
- SQL volume: +5%
- Sales headcount: +25% through 7 additional AEs
- Opportunities created: -7%
- Average sales cycle: increased to 82 days

The CEO asks:

> "We spent more on growth and added sellers. Why are opportunities down, and what should we do next?"

You do **not** have enough information to establish causation from these facts alone.

### Participant task
Explain what you believe the initial signals suggest, identify the most important question or evidence you want next, and explain why it matters.

The evaluator reveals additional information based on the participant's inquiry.

---

# Evaluator-Only Evidence Map

The following information is hidden from the participant at Stage 0.

## Evidence Packet A — Marketing Source / Mix
Reveal when the participant asks about lead source, channel mix, campaign mix, acquisition source, paid-vs-organic composition, or equivalent.

- Paid social MQLs: +88% YoY
- Paid social MQL-to-SQL conversion: 11% → 4%
- Organic MQLs: +6%
- Organic MQL-to-SQL conversion: 24% → 23%
- Partner/referral MQLs: +3%
- Partner/referral MQL-to-SQL conversion: 31% → 30%
- Paid social represented 18% of MQLs last year and 34% this year

### Interpretation guardrail
This is strong evidence that mix and/or paid-social quality contributes to MQL-to-SQL deterioration. It does not prove that paid social explains the entire opportunity decline or longer sales cycle.

## Evidence Packet B — Qualification / SDR
Reveal when the participant asks about qualification definitions, SDR performance, acceptance criteria, SQL definitions, response time, routing, or equivalent.

- Formal MQL and SQL definitions have not changed
- SDR headcount is flat
- Median lead-response time increased from 14 minutes to 47 minutes
- SDR accepted-lead volume increased 22%
- SDR-to-AE handoff SLA compliance fell from 91% to 72%
- Two of six SDRs account for most SLA misses

### Interpretation guardrail
Qualification operations are under strain. This may contribute to conversion loss, but definitions being unchanged does not establish that application of those definitions is consistent.

## Evidence Packet C — AE Ramp / Capacity
Reveal when the participant asks about ramp, tenure, rep productivity, quota capacity, new-vs-tenured AEs, or equivalent.

- 7 AEs were added over the prior 9 months
- 2 are fully ramped
- 3 are in months 4–6
- 2 are in months 1–3
- Tenured AE opportunity-to-close conversion is approximately flat YoY
- Newer AEs create 18% fewer qualified opportunities per assigned SQL than tenured AEs
- Sales enablement capacity did not increase with headcount

### Interpretation guardrail
Headline headcount growth materially overstates productive capacity. Ramp and enablement appear relevant, but this does not eliminate upstream demand/qualification issues.

## Evidence Packet D — SQL-to-Opportunity / Segment
Reveal when the participant asks where SQL-to-opportunity conversion is changing, segmentation, customer segment, ACV band, product, geography, or equivalent.

- Enterprise SQL-to-opportunity conversion: 37% → 35%
- Mid-market: 34% → 31%
- SMB: 29% → 18%
- SMB now represents 41% of SQL volume versus 30% last year
- Paid social contributes disproportionately to SMB volume

### Interpretation guardrail
The opportunity decline is concentrated substantially in SMB and interacts with the channel-mix change.

## Evidence Packet E — Sales Cycle / Stage Aging
Reveal when the participant asks about stage duration, cycle by segment, aging, where deals stall, procurement, competition, or equivalent.

- Enterprise sales cycle: 101 → 108 days
- Mid-market: 69 → 72 days
- SMB: 41 → 61 days
- Largest increase occurs between discovery and qualified evaluation
- No material change in late-stage legal/procurement duration

### Interpretation guardrail
The aggregate 82-day cycle is partly mix-sensitive, but SMB has also deteriorated materially on its own. The issue appears earlier in the selling process rather than primarily in procurement.

## Evidence Packet F — Loss / Disqualification Reasons
Reveal when the participant asks why leads, SQLs, or opportunities are rejected/lost, or asks about customer fit or competition.

- "No active project / researching" increased materially among SMB paid-social leads
- "Budget not established" increased moderately
- Competitive loss rate on qualified late-stage opportunities is approximately flat
- No major pricing change occurred during the period

### Interpretation guardrail
The evidence strengthens a quality/intent hypothesis for part of the funnel but does not justify labeling all paid social ineffective.

## Evidence Packet G — Economics / Spend
Reveal when the participant asks about marketing spend, CAC, cost per lead/opportunity, sales cost, revenue productivity, budget, or investment efficiency.

- Marketing spend: +34% YoY
- Paid-social spend: +96%
- Blended cost per MQL: +4%
- Blended cost per SQL: +27%
- Blended cost per created opportunity: +44%
- Sales compensation and payroll expense: +21%
- New ARR: +3%

### Interpretation guardrail
Growth investment is producing significantly weaker opportunity economics. CAC is not supplied because a defensible CAC calculation requires additional definitions and cost allocation; participants should not invent it.

## Evidence Packet H — Planning Assumptions
Reveal when the participant asks about the plan, budget assumptions, capacity model, hiring justification, expected conversion, ramp assumptions, or forecast logic.

The annual plan assumed:
- MQL volume +20%
- MQL-to-SQL conversion roughly flat
- 5 incremental AEs, not 7
- 5-month average ramp to full productivity
- opportunity creation +18%
- sales cycle roughly flat

Two additional AEs were approved midyear after MQL growth exceeded plan. The approval used MQL volume as a leading capacity signal without adjusting for the declining MQL-to-SQL conversion.

### Interpretation guardrail
This provides evidence of a planning-model failure: additional capacity was approved using an activity metric whose economic yield had deteriorated.

## Evidence Packet I — Governance / Ownership
Reveal when the participant asks who owns funnel health, who approved changes/investments, what operating cadence exists, or how Marketing/Sales/Finance coordinate.

- Marketing owns MQL volume and cost-per-MQL targets
- SDR leadership owns SQL volume
- Sales owns opportunity and bookings targets
- Finance approves incremental headcount
- No executive owner is accountable for end-to-end funnel economics
- Weekly revenue review focuses primarily on totals versus plan by function
- Channel quality, conversion by cohort, and productive sales capacity are not reviewed together

### Interpretation guardrail
Functional goals may be locally rational while the end-to-end system performs poorly. This is governance evidence, not proof of individual leadership failure.

---

# Dynamic Interaction Rules

## Participant inquiry
The participant may request evidence naturally rather than selecting from a menu.

The evaluator should map a reasonable inquiry to the closest evidence packet and reveal only the relevant information.

## Do not reward keyword guessing
The participant does not need to use the evaluator's exact terminology. A commercially sensible question should receive the corresponding evidence.

## Do not reveal the full map
Unless the exercise is being used for teaching after completion, do not list all available evidence packets.

## Follow-up depth
After each reveal, ask the participant:

> "What does this change in your working hypothesis, and what do you want to know or decide next?"

## Maximum inquiry rounds — prototype
Use up to **five evidence requests** before requiring a decision recommendation.

This is a prototype constraint, not yet a canonical assessment rule.

## Final participant task
After the inquiry rounds, ask:

> "You are back in the executive revenue review. Give your current diagnosis, distinguish facts from remaining hypotheses, state what you would do now, identify what you would not do yet, and explain the business rationale."

For Director and VP profiles, also ask:

> "What operating or governance change, if any, should persist after the immediate problem is addressed?"

---

# Evaluator Observation Guide

Record the participant's **sequence**, not only the final answer.

Observe:
- what they noticed from Stage 0;
- their first evidence request and why they chose it;
- whether each reveal changed their hypothesis;
- whether they pursued confirming and disconfirming evidence;
- whether they prioritized economically consequential uncertainty;
- whether they jumped to causation;
- whether they recognized productive capacity versus nominal headcount;
- whether they connected functional metrics into an end-to-end system;
- whether they reached a decision before exhausting every possible question;
- whether their recommendation was proportional to the evidence.

## High-value inquiry patterns
There is no single required sequence. Strong participants may enter through different doors.

Examples of potentially high-value early questions include:
- Where exactly did conversion deteriorate?
- Did lead/channel mix change?
- Are the seven AEs actually ramped and productive?
- What assumptions justified the incremental growth investment?
- Where did the sales cycle increase?
- What are the economics per SQL/opportunity?

The evaluator should score the reasoning behind the inquiry, not similarity to a preferred script.

## Weak inquiry patterns
Potential negative evidence includes:
- requesting large undirected data dumps;
- repeatedly asking for descriptive metrics without narrowing a decision;
- asking only for evidence that confirms the initial hypothesis;
- ignoring contradictory evidence;
- inventing unavailable facts;
- making an irreversible recommendation before establishing the constraint.

---

# Likely Integrated Diagnosis — Evaluator Reference Only

A defensible integrated interpretation is that several interacting issues are present:

1. Marketing mix shifted heavily toward paid social, which produced substantial MQL volume but much weaker qualification yield.
2. The mix shift disproportionately increased SMB volume, where SQL-to-opportunity conversion deteriorated.
3. SDR response/handoff performance weakened under increased volume.
4. Sales headcount growth overstated productive capacity because most new AEs were still ramping and enablement capacity did not scale.
5. SMB cycle time deteriorated materially, particularly early in the selling process.
6. Growth economics weakened while spend increased.
7. Two additional AEs were approved using MQL volume without adjusting for deteriorating conversion, exposing a planning-model weakness.
8. Functional ownership and review cadence optimize local metrics without clear accountability for end-to-end funnel economics.

No participant needs to discover all eight points to demonstrate competence. What matters depends on the target Role Profile and the quality of reasoning demonstrated within the available inquiry rounds.

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

# Prototype Validation Questions

After running the exercise, evaluate:

1. Did the participant's inquiry sequence reveal useful evidence about proficiency beyond the final answer?
2. Were the hidden packets sufficiently realistic and internally coherent?
3. Did the five-request constraint force useful prioritization or create artificial behavior?
4. Could different strong inquiry paths still produce fair scores?
5. Did the evaluator have too much discretion in mapping questions to packets?
6. Did the exercise distinguish Manager, Director, and VP reasoning without changing the underlying dataset?
7. Which competencies were genuinely observable and which would require another exercise?
8. Could the exercise be administered consistently by another evaluator?

## Governance
This is a prototype Candidate only. The hidden evidence, interaction rules, inquiry limit, expected diagnosis, and role-altitude expectations are not canonical assessment standards. The exercise must be validated before use as a formal hiring or certification instrument.
