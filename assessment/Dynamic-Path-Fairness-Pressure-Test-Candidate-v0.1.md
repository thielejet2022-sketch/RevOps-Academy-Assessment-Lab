# Dynamic Inquiry Path Fairness Pressure Test

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Dataset:** `FD-001-v0.2`  
**Related scoring architecture:** `assessment/Scoring-Architecture-Candidate-v0.1.md`

## Purpose
Pressure-test whether a dynamic RevOps assessment can score materially different but competent inquiry paths fairly.

The central question is not whether participants uncover the same evidence. It is whether the assessment can distinguish the **quality of reasoning** when strong operators enter the problem through different doors.

## Fairness Principle
A participant should not be rewarded for matching the designer's preferred packet sequence.

A strong path should be judged by whether the participant:
- selects evidence that is consequential to a decision;
- updates hypotheses when evidence changes;
- distinguishes facts from assumptions;
- connects operating evidence to economics and tradeoffs;
- reaches a proportional decision without requiring perfect information;
- demonstrates role-appropriate scope and accountability.

The assessment should therefore score the **reasoning trajectory**, not hidden-map coverage.

---

# Path A — Funnel-First Operator

## Inquiry sequence
1. Ask where MQL-to-SQL conversion deteriorated by channel.
2. Ask whether the conversion problem is concentrated by segment.
3. Ask why SMB leads/opportunities are being rejected or lost.
4. Ask what the economics look like by funnel stage or segment.
5. Ask who owns end-to-end funnel performance and how investment decisions are reviewed.

## Likely evidence encountered
- A — Marketing Source / Mix
- D — SQL-to-Opportunity / Segment
- F — Loss / Disqualification Reasons
- G or M — Economics / CAC
- I — Governance / Ownership

## Defensible diagnosis
Paid-social expansion increased low-intent SMB volume, SMB qualification and SQL-to-opportunity conversion deteriorated, opportunity economics worsened, and siloed ownership allowed functional activity metrics to remain locally successful while system-level yield weakened.

## Strong decision behavior
A strong participant might hold or reduce **incremental** paid-social expansion, protect productive channels, isolate SMB paid-social cohorts, tighten qualification/feedback loops, and require an end-to-end funnel economics review before further growth investment.

They should not need to prove paid social is the sole cause before making a reversible resource-allocation decision.

## What this path may not observe
The participant may not discover AE ramp details, planning assumptions, or sales-enablement constraints.

That absence should not automatically lower the score if the final decision is well-supported by the evidence actually gathered and the participant does not make unsupported claims about sales capacity.

---

# Path B — Economics and Capacity-First Operator

## Inquiry sequence
1. Ask whether New ARR is meeting plan and whether growth economics improved or deteriorated.
2. Ask for revenue productivity by AE cohort rather than aggregate headcount.
3. Ask what assumptions justified the seven incremental AEs.
4. Ask where funnel conversion actually deteriorated by source or segment.
5. Ask who owns the integrated growth model and investment governance.

## Likely evidence encountered
- J — Revenue vs Plan
- L — AE Revenue Productivity
- H — Planning Assumptions
- A or D — Channel / Segment
- I — Governance / Ownership

## Defensible diagnosis
The business is materially below its New ARR growth plan despite increased Marketing and Sales investment. Headline AE growth overstates productive capacity, two additional AEs were approved using MQL volume despite deteriorating yield, and the planning/governance model treated activity growth as productive demand without enough end-to-end economic validation.

## Strong decision behavior
A strong participant might pause additional capacity expansion, reforecast using productive AE cohorts and observed conversion, hold incremental demand-generation investment pending source/segment yield review, and change approval criteria for future headcount and Marketing spend.

## What this path may not observe
The participant may not discover SDR response-time degradation, loss reasons, or the exact stage where SMB cycle lengthened.

That absence should not automatically lower the score if they avoid asserting those mechanisms as known causes.

---

# Path C — Plausible Hypothesis, Then Disconfirmation

## Inquiry sequence
1. Notice SMB cycle expansion and hypothesize that discovery/demo support is constrained.
2. Ask where the cycle has lengthened.
3. Ask whether solutions-consulting/demo capacity kept pace.
4. Receive mixed Evidence N showing support delay increased, but post-demo conversion did not materially deteriorate.
5. Pivot to lead quality/segment economics rather than defending the original hypothesis.

## Likely evidence encountered
- E — Sales Cycle / Stage Aging
- N — Discovery Support / Enablement Capacity
- A or D — Channel / Segment
- F or M — Loss / CAC
- possibly I — Governance / Ownership

## Defensible diagnosis
Discovery support capacity contributes to elapsed time but is not sufficient to explain the conversion failure. The participant updates toward a broader SMB demand-quality and funnel-economics diagnosis rather than preserving the original enablement explanation.

## Strong decision behavior
The participant may take a limited operational step to reduce support delay while explicitly refusing to treat added solutions-consulting headcount as the primary fix until the larger SMB quality/conversion problem is addressed.

## Why this path matters
This path directly tests whether **changing one's mind** is rewarded as competence rather than treated as evidence that the initial hypothesis was wrong.

---

# Path D — Executive-Language Shortcut

## Inquiry sequence
1. Ask for no additional evidence or request broad undirected dashboards.
2. Declare a GTM transformation necessary.
3. Recommend reallocating budget, redesigning the funnel, adding AI, restructuring ownership, or changing the tech stack without identifying the binding constraint.

## Expected scoring behavior
This path should score materially below Paths A-C even if the final language sounds strategic.

The participant has not demonstrated evidence discipline, causal discipline, proportional decision-making, or uncertainty handling.

This is a control path for executive-language inflation.

---

# Cross-Path Scoring Test

## Principle 1 — Do not score packet count
Discovering seven packets is not inherently better than discovering four.

A participant who requests more evidence than needed may demonstrate weaker prioritization than one who reaches a sound reversible decision earlier.

## Principle 2 — Score only claims supported by encountered evidence
A participant cannot receive credit for identifying a mechanism they never investigated unless it is already supported by Stage 0 facts.

They also should not be penalized for failing to mention hidden facts they never had a reason to request.

## Principle 3 — Missing evidence can constrain scope, not automatically proficiency
If a path does not expose enough evidence to observe a competency, mark that competency **Insufficient evidence** rather than infer a lower level.

Example: Path A may strongly demonstrate Funnel & Lifecycle Management and Commercial Judgment but provide insufficient evidence for Forecasting & Revenue Planning.

## Principle 4 — Role altitude changes what must eventually happen
A Manager can demonstrate strong performance by isolating operating constraints, setting owners, and creating a corrective cadence.

A Director should connect multiple functional mechanisms and operating consequences.

A VP should eventually convert the evidence into a resource-allocation decision and identify a durable planning/governance issue when the encountered evidence supports one.

A VP should not be required to uncover Evidence I specifically if another path provides sufficient evidence of the operating-model flaw.

## Principle 5 — Disconfirmation is positive evidence
If new evidence weakens the participant's hypothesis and they revise it appropriately, that should increase Evidence Discipline, Causal Discipline, and Uncertainty Handling judgments.

The assessment must not reward stubborn consistency.

## Principle 6 — Decision timing matters
There is a difference between:
- healthy refusal to make an irreversible decision with insufficient evidence; and
- indefinite analysis after enough evidence exists for a reversible, bounded action.

The evaluator should record the point at which a reasonable provisional decision became supportable.

---

# Expected Role-Fit Equivalence

For a VP-targeted run, Paths A and B can both plausibly demonstrate **Approaching to Meets target evidence** depending on final decision quality and governance reasoning, despite discovering different packets.

Path C can also reach the same range if the participant visibly updates the hypothesis, connects the revised diagnosis to economics, and makes a proportional executive decision.

The assessment should not force all three paths into identical competency profiles. Fairness means equivalent reasoning quality can receive equivalent role-fit treatment while producing different observed-competency evidence.

Example:

- Path A may show stronger Funnel & Lifecycle Management.
- Path B may show stronger Forecasting & Revenue Planning.
- Path C may show especially strong Causal Discipline and Uncertainty Handling.

Those are **different evidence profiles**, not necessarily different overall quality.

---

# Evaluator Calibration Questions

Before this dynamic assessment can be considered validated, test whether two independent evaluators can answer consistently:

1. At what point did each path have enough evidence for a reversible decision?
2. Which competencies were actually observable versus merely plausible?
3. Did either evaluator penalize a participant for not uncovering hidden packets?
4. Did either evaluator reward executive vocabulary unsupported by reasoning?
5. Did a hypothesis revision receive positive evidence credit?
6. Would Paths A and B with equally strong reasoning receive comparable role-fit judgments?
7. Could an evaluator explain the score without referencing a secret preferred evidence sequence?

---

# Findings from This Pressure Test

## Finding 1 — Dynamic assessment can support multiple valid paths
The architecture is viable only if the hidden evidence map is treated as a responsive environment, not an answer key.

## Finding 2 — Competency coverage and performance quality must remain separate
Different paths naturally expose different competencies. The assessment record therefore needs an explicit **Insufficient evidence** state rather than forcing every competency to a proficiency level.

## Finding 3 — Decision threshold should become an evaluator observation
The point at which sufficient evidence exists for a bounded decision is itself meaningful. This should be recorded, but not reduced to a simple request-count rule.

## Finding 4 — Hypothesis revision should be explicitly positive
The current scoring architecture already recognizes updating recommendations. Dynamic exercises should operationalize this more visibly because it is one of their strongest advantages over static assessments.

## Finding 5 — Five requests is useful for prototyping, not yet a fairness rule
A hard five-request limit can force prioritization, but some inquiry paths may need more or fewer turns depending on how evidence packets are structured. Do not canonize the number yet.

## Finding 6 — Evaluator consistency is now the largest validation risk
The next major test should compare two evaluators scoring the same participant transcript. Dynamic evidence improves realism but increases evaluator discretion.

## Governance
This is a Candidate pressure-test artifact only. It does not change the canonical competency model, dataset rules, scoring architecture, or exercise standard. Any promotion or material scoring-rule change requires JET's explicit approval of a specific identifiable Candidate.
