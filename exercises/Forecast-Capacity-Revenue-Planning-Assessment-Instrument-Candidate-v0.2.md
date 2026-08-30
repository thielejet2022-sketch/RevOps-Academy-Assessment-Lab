# Forecast, Capacity & Revenue Planning Assessment Instrument

**Status:** Candidate v0.2  
**Date:** 2026-08-30  
**Canonical:** No  
**Assessment family:** A2 — Forecast, Capacity & Revenue Planning  
**Parent framework:** RevOps Competency Model Candidate v0.4  
**Parent methodology:** Assessment Methodology Candidate v0.2  
**Coverage architecture:** Role Profile Assessment Coverage Matrix Candidate v0.1  
**Dataset:** `RP-001-v0.1` — Revenue Planning Dataset Candidate v0.1  
**Supersedes:** A2 Candidate v0.1 for continued Candidate testing

## Purpose
Test whether a participant can construct, challenge, and operationalize a forward-looking revenue plan rather than merely diagnose historical performance.

The instrument tests whether the participant can connect revenue targets to funnel yield, pipeline requirements, seller productivity, hiring/ramp assumptions, timing, economics, risk, and operating decisions.

## Architecture Correction in v0.2
Candidate v0.1 embedded the planning facts inside the exercise. v0.2 removes that ownership.

> **The exercise defines the assessment interaction. The dataset defines the operating reality.**

All scenario facts, evidence packets, baseline values, and the default Planning Shock are now sourced from `RP-001-v0.1` in `/datasets`.

If the dataset changes materially, create a new dataset version and record that version in every assessment run. Do not silently alter this instrument's historical evidence environment.

---

# Core Distinction from A1

A1 asks:
> **Something is going wrong. Can you diagnose it and decide what to do?**

A2 asks:
> **The company wants a future result. Can you determine what must be true for the plan to work, challenge unsupported assumptions, and recommend a credible path?**

Historical diagnosis alone is not strong Forecasting & Revenue Planning evidence.

---

# Participant Opening

Present the **Stage 0 Participant Baseline** from `RP-001-v0.1`, then ask:

> **How would you determine whether the $15M New ARR target is credible, what would you want to understand before approving the hiring and marketing plans, and what would you do first?**

The participant may request additional information. There is no required question sequence and no hidden-answer checklist.

---

# Evaluator Operating Protocol

Use the evidence packets in `RP-001-v0.1`.

Rules:
- reveal only information responsive to the participant's request;
- provide the smallest fair evidence set needed to answer the question;
- do not hint that other packets exist;
- do not coach during the scored segment;
- allow revisions;
- record reasoning trajectory, not packet count;
- distinguish calculations from planning judgment;
- do not reward reproducing management's target;
- do not penalize evidence-based challenge to the target.

---

# Required Planning Decision Gate

Once enough evidence exists for a bounded planning recommendation, ask:

> **You are presenting the operating plan to the CEO, CRO, CMO, and CFO tomorrow. What revenue plan would you recommend now? State what you believe is supportable, the assumptions you would use, what resources you would authorize or stage, what you would not assume yet, and how you would manage the plan if actual performance differs from the assumptions.**

There is no single correct revenue target. A strong response may support $15M, recommend a lower commitment with upside, or stage a path toward $15M. Score the evidence and planning logic, not agreement with management.

---

# Planning Shock

After the participant commits to a plan, introduce the **Default Planning Shock** from `RP-001-v0.1` unless the scored variant explicitly specifies another versioned shock.

Observe whether the participant:
- updates the model rather than defending the original plan;
- distinguishes capacity from demand constraint;
- avoids treating one favorable metric as proof the whole plan is healthy;
- considers timing, reversibility, economics, and leading indicators;
- establishes a decision rule or gate rather than intuition alone.

---

# Intended Competency Observation

## Primary

### Forecasting & Revenue Planning
Observe decomposition of target into drivers; assumption challenge; target vs forecast vs capacity vs commitment; ramp/timing; attrition; seasonality; productivity distribution; scenarios/sensitivities; plan updates; planning gates/governance.

### Data & Analytics
Observe denominator/time-period discipline; distribution vs averages; evidence vs assumptions; unsupported extrapolation; sensitivity testing; avoidance of false precision.

### Commercial & Business Judgment
Observe economics/resource allocation; opportunity cost; reversibility; staged investment; ambition vs evidence; value of learning; ability to decide under uncertainty.

### GTM Systems Thinking
Observe integration of demand, funnel yield, capacity, ramp, management capacity, enablement, segment mix, timing, and economics.

## Secondary
- Operating Cadence & Execution
- Communication & Executive Readout
- Funnel, Lead & Lifecycle Management

Do not force secondary scores when evidence is incidental.

---

# Adjacent-Level Signals for Forecasting & Revenue Planning

**L1 — Foundational:** Identifies basic planning inputs with guidance but cannot independently construct a defensible plan.

**L2 — Practitioner:** Independently constructs/maintains a familiar revenue or capacity plan using supplied assumptions and identifies straightforward gaps.

**L3 — Advanced:** Challenges assumptions, integrates ramp/productivity/pipeline/timing, builds scenarios, identifies planning risk, and designs an effective operating response.

**L4 — Strategic:** Additionally shapes material resource decisions and planning governance through investment gates, assumption ownership, commitment/upside separation, decision rules, standards, or senior tradeoff mechanisms.

**L5 — Enterprise / Architect:** Requires evidence beyond this case of reusable planning architecture/governance across materially different contexts. Do not infer L5 from this instrument alone without extraordinary triangulated evidence.

---

# Known Assessment Traps

- **Target obedience:** agreement with CEO target is not proficiency.
- **Spreadsheet sophistication:** complex arithmetic is not automatically strategic planning.
- **Headcount arithmetic:** annualized capacity that ignores start dates/ramp/attrition/demand is weak evidence.
- **Average productivity:** averages should not silently become universal seller assumptions.
- **Linear demand:** spend increases do not automatically create proportional pipeline.
- **Optimism stacking:** several plausible improvements can collectively create an unsupported plan.
- **Conservatism:** uncertainty alone does not justify refusing reversible investment.
- **Vocabulary inflation:** terminology counts only when correctly connected to reasoning and decisions.

---

# Evidence Record Requirements

Record:
- participant/anonymized ID;
- instrument/version;
- dataset/version (`RP-001-v0.1` unless explicitly changed);
- target Role Profile;
- evidence packets encountered;
- material calculations/assumptions;
- plan revisions;
- Decision Gate response;
- Planning Shock response/version;
- materially observed competencies;
- competency-level Proficiency and Confidence;
- Observed Role Fit;
- Overall Role Fit only when accumulated Profile Coverage supports it;
- Profile Coverage description;
- strengths and development risks;
- Insufficient Evidence areas;
- evaluator identity/version;
- unresolved disagreement.

---

# Participant-Facing Result Guardrails

Explain what planning capability was demonstrated, the supporting evidence, strengths, development edge, limitations, Confidence, and Observed Role Fit only within tested scope.

Do not present A2 as a complete VP RevOps assessment.

---

# Validation Reference

The first controlled synthetic validation of Candidate v0.1 is recorded in:

`assessment/Forecast-Planning-End-to-End-System-Validation-Run-Candidate-v0.1.md`

That run remains historically tied to `RP-001-v0.1`. v0.2 changes the storage/reference architecture, not the facts used in that validation.

The run provisionally supported L2/L3 and L3/L4 discrimination and surfaced the calibration principle that consequential decision size alone does not establish L4. Strategic planning proficiency requires evidence of system-shaping planning mechanisms, standards, governance, architecture, or senior decision process.

---

# System-Test Success Criteria

Continue testing whether A2 can:
1. distinguish historical diagnosis from forward planning;
2. distinguish L2 model execution from L3 integrated planning;
3. distinguish L3 situational decisions from L4 planning governance/system shaping;
4. reward revision when assumptions change;
5. penalize unsupported optimism stacking;
6. avoid target-obedience bias;
7. separate planning sophistication from spreadsheet complexity;
8. produce meaningful Confidence and Insufficient Evidence judgments;
9. accumulate with A1 without double counting;
10. expose methodology defects rather than hide them.

---

# Validation Status

Candidate v0.2 has not yet been independently validated. The v0.1 synthetic run supports continued development only.

No empirical inter-rater reliability, predictive validity, hiring validity, certification threshold, or minimum evidence standard is established.

---

# Governance

This document is a **Candidate only**.

v0.2 corrects dataset ownership by referencing the separately versioned `RP-001-v0.1`. It does not canonicalize the instrument, dataset, scoring logic, or coverage architecture.

Canonical promotion requires JET's explicit review and approval of a specific identifiable Candidate.
