# RevOps Assessment Scoring Architecture

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Related artifacts:** RevOps Competency Model Candidate v0.2; Commercial & Business Judgment Evidence Anchors Candidate v0.1; Commercial Judgment Adversarial Scoring Test Candidate v0.1

## Purpose
Define a reusable scoring architecture for evaluating demonstrated RevOps capability without collapsing competency, proficiency, role expectations, and evaluator confidence into one misleading number.

The architecture should support Academy feedback and Assessment Lab evaluation while remaining explainable to participants, hiring leaders, and evaluators.

## Core Principle
Assessment should answer four separate questions:

1. **Competency:** What capability was demonstrated?
2. **Proficiency:** At what level was that capability demonstrated?
3. **Role fit:** How does the demonstrated proficiency compare with the target Role Profile?
4. **Confidence:** How strong and repeatable is the evidence supporting the judgment?

These should remain distinct in the underlying assessment record even if a simplified summary is later presented.

## Evidence Chain
A strong assessment should examine the participant's reasoning across the following chain:

**Evidence → Interpretation → Economics → Tradeoff → Decision → Accountability**

Not every exercise must expose every element equally. The chain is a reasoning lens, not a requirement that participants use a prescribed response format.

## Candidate Evidence Dimensions
The following dimensions emerged from adversarial testing and may be used as evidence lenses within competencies.

### 1. Evidence Discipline
Does the participant use the facts actually available, distinguish observation from assumption, and request information because it changes a decision?

### 2. Causal Discipline
Does the participant distinguish correlation, hypothesis, and demonstrated causation? Do they resist unsupported certainty?

### 3. Economic Connection
Does the participant connect operating evidence to revenue, efficiency, productivity, unit economics, capital, opportunity cost, or other relevant business consequences?

### 4. Tradeoff Quality
Does the participant recognize competing uses of resources, constraints, second-order effects, reversibility, and opportunity cost?

### 5. Decision Quality
Does the participant identify what decision is actually required, what can be decided now, what should wait, and what evidence threshold is sufficient?

### 6. Uncertainty Handling
Does the participant identify what is unknown, avoid inventing missing facts, and choose a sensible way to reduce uncertainty without demanding perfect information?

### 7. Accountability & Implementation Logic
Does the participant connect recommendations to ownership, operating mechanisms, adoption, checkpoints, or measurable outcomes appropriate to the role?

## Relationship to Competencies
Evidence Dimensions are **not additional competencies**.

Competencies describe the capability being assessed. Evidence Dimensions describe qualities of reasoning that may appear across several competencies.

For example, Causal Discipline may influence evidence for Data & Analytics, Funnel & Lifecycle Management, and Commercial & Business Judgment. Creating Causal Discipline as a twelfth competency would therefore risk duplication.

## Proficiency Scoring
Each competency demonstrated in an exercise may receive a provisional proficiency judgment:

- **Level 1 — Foundational**
- **Level 2 — Practitioner**
- **Level 3 — Advanced**
- **Level 4 — Strategic**
- **Level 5 — Enterprise / Architect**

A score should be anchored in observable evidence specific to that competency.

### No averaging by default
Do not automatically average competency scores into a single overall proficiency number.

A participant with Level 5 Commercial Judgment and Level 2 Systems & Automation is not meaningfully represented by an arithmetic Level 3.5.

The competency profile itself is the primary result.

## Role Fit
A Role Profile establishes target proficiency expectations by competency.

Role fit should compare demonstrated evidence with those target expectations rather than changing the underlying proficiency score.

Candidate comparison labels:

- **Below target evidence**
- **Approaching target evidence**
- **Meets target evidence**
- **Exceeds target evidence**
- **Insufficient evidence**

These labels are intentionally evidence-focused. They should not be represented as a final hiring decision.

## Confidence
Each proficiency judgment should include an evidence-confidence label:

- **Low confidence:** isolated, ambiguous, or narrow evidence
- **Moderate confidence:** multiple consistent signals with limited breadth or repetition
- **High confidence:** repeated clear evidence across materially different situations

High confidence means confidence in the assessment judgment, not that the participant is highly proficient.

A Level 2 judgment can have High confidence. A Level 5 judgment can have Low confidence.

## Penalties and Guardrails
Assessment should not simply award points for desirable concepts. Certain reasoning failures should constrain the proficiency that can be demonstrated in an exercise.

### Unsupported causal certainty
A participant who confidently asserts causation without sufficient evidence should not receive advanced credit merely because the proposed explanation is plausible.

### Fabricated facts
Inventing missing facts should be treated as an evidence-discipline failure.

### Vocabulary inflation
Sophisticated terminology without demonstrated reasoning should not increase proficiency.

### Unbounded analysis
Requesting every conceivable metric without prioritizing decision-relevant evidence should not be treated as analytical sophistication.

### Transformation bias
Proposing major structural change before establishing whether the problem is structural should not be rewarded as strategic thinking.

## Positive Signals Often Missed by Traditional Scoring
The architecture should explicitly recognize:

- identifying that available evidence is insufficient;
- asking a high-value follow-up question;
- narrowing an investigation intelligently;
- delaying an irreversible decision for a defensible reason;
- choosing a reversible experiment that increases learning speed;
- changing a recommendation when new evidence contradicts the original hypothesis;
- identifying that a familiar playbook does not fit the current context.

## Dynamic Evidence Model
Future exercises may reveal additional information in response to participant questions.

This creates an opportunity to assess not only the final answer but the **path of inquiry**.

A participant may therefore demonstrate competence by:
1. identifying the decision;
2. requesting a high-value piece of evidence;
3. updating the hypothesis based on what is revealed;
4. selecting an action proportional to the remaining uncertainty.

This structure should be explored before building static multiple-choice-style assessment mechanics.

## Assessment Record — Candidate Structure
A scored exercise could eventually record:

- exercise and dataset version;
- target Role Profile;
- competencies observed;
- evidence excerpts or evaluator notes;
- proficiency level by observed competency;
- evidence dimensions materially affecting the judgment;
- role-target comparison;
- confidence level;
- material reasoning strengths;
- material reasoning risks;
- unanswered or untested competencies.

## Academy vs Assessment Lab

### Academy Mode
Scoring should primarily support learning. Feedback may explain reasoning gaps, show stronger alternatives, and recommend practice.

### Assessment Lab Mode
Scoring should preserve evaluator discipline. The evaluator should distinguish observed evidence from interpretation and avoid coaching the participant during a scored segment unless the exercise intentionally tests response to feedback.

The same competency and evidence architecture may support both modes, but participant interaction rules differ.

## Hiring Guardrail
The framework may provide evidence relevant to hiring, but it should not present a competency score as a complete hiring decision.

Hiring decisions may legitimately include experience, domain context, leadership fit, values, compensation, references, role-specific requirements, and other evidence outside this framework.

## Validation Requirements Before Canonical Adoption
Before this scoring architecture is promoted, test whether:

1. two evaluators can reach reasonably consistent judgments from the same evidence;
2. adjacent proficiency levels can be distinguished without relying on title;
3. the Evidence Dimensions improve scoring rather than create hidden double-counting;
4. dynamic follow-up information improves validity without making exercises evaluator-dependent;
5. role-fit comparisons remain separate from demonstrated proficiency;
6. confidence labels are applied consistently;
7. the framework resists executive-language inflation and unsupported certainty;
8. scoring remains understandable to a participant or hiring leader who did not design the framework.

## Open Questions
- Should Evidence Dimensions eventually be rated explicitly, or remain evaluator lenses?
- What minimum evidence is necessary to score a competency rather than mark it Insufficient Evidence?
- Should some reasoning failures cap the maximum proficiency assignable in a specific exercise?
- How should evaluator disagreement be reconciled?
- When does a set of exercise-level judgments become sufficient to describe durable proficiency?
- What, if any, composite summary is useful without obscuring the competency profile?

## Governance
This document is a Candidate only. It does not establish a canonical scoring model, validated assessment instrument, certification standard, or hiring decision system. Promotion requires JET's explicit approval of this specific artifact or a later identifiable version.
