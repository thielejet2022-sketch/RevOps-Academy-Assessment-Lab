# Human Pilot & Evaluator Protocol Candidate v0.1

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Purpose:** Define a small, low-risk external-participant pilot for the RevOps Academy & Assessment Lab after synthetic full-battery discrimination and pseudo-independent evaluator calibration.

## Critical Boundary
This protocol prepares a pilot. It does **not** authorize recruitment, launch a participant assessment, create a certification, validate a hiring instrument, or authorize publication of participant-specific results.

A real participant should not be assessed until JET explicitly decides to launch the pilot after reviewing the participant-facing disclosure and interaction design.

---

# 1. Pilot Objective

The first human pilot is a **developmental research exercise** designed to answer:

1. Can a real RevOps practitioner navigate the assessment naturally without being coached toward the framework?
2. Does the assessment elicit observable evidence across the intended competencies?
3. Do evaluators interpret messy human evidence consistently enough to support useful developmental feedback?
4. Where do real participants expose confusing prompts, leading questions, hidden assumptions, missing evidence paths, or unfair scoring behavior?
5. Can the system produce a useful debrief without overstating what has been validated?

The pilot is primarily a test of the **assessment system**, not a test of the participant.

---

# 2. External Participant Principle

External participants must not be dropped into the internal development workspace.

The participant experience and evaluator/development environment are separate.

Preferred flow:

**Participant Disclosure → Participant Assessment Interaction → Preserved Evidence Record → Independent Evaluation → Evaluator Reconciliation → Participant Debrief → Internal Methodology Review**

The participant does not need access to:
- synthetic PP-001/PP-002/PP-003 profiles;
- hidden evidence maps;
- evaluator calibration artifacts;
- answer-pattern development notes;
- internal scoring debates;
- unreleased Candidate methodology documents;
- JET/EVA design discussion;
- other participants' evidence or results.

This separation protects both participant experience and assessment integrity.

---

# 3. Staged Reveal Model

## Stage A — Before Participation: Required Disclosure

Before beginning, the participant should receive a concise participant-facing explanation covering:
- this is an experimental RevOps developmental assessment pilot;
- the system is still being designed and validated;
- participation is voluntary;
- it is not a certification;
- it is not an employment decision;
- no employer is receiving a hiring recommendation from this pilot;
- they will interact with an AI-supported assessment facilitator;
- their responses will be reviewed for developmental and methodology-testing purposes;
- what information will be retained and where;
- who will have access to participant-specific evidence;
- whether their de-identified evidence may be used to improve the methodology;
- they may stop participation;
- they will receive a developmental debrief after completion.

The participant must affirm that they understand the disclosure before assessment begins.

This Candidate does not prescribe a legal consent form. If the pilot later becomes consequential, commercial, research-regulated, or employment-selection related, appropriate legal/privacy review may be required.

## Stage B — During Participation: Limited Reveal

During assessment, the participant sees:
- scenario context;
- questions;
- evidence legitimately revealed through their inquiry;
- neutral facilitator responses;
- task transitions and practical instructions.

During assessment, the participant should **not** see:
- running competency scores;
- L1–L5 scoring anchors;
- hidden evidence packet inventory;
- “correct” evidence path;
- expected Role Fit;
- evaluator commentary;
- synthetic benchmark participants;
- hints that a particular phrase or governance construct produces L4;
- coaching on how to improve an answer before the evidence record is closed.

The facilitator may clarify task mechanics or ambiguous wording. It must not coach capability.

## Stage C — After Evidence Closure: Developmental Reveal

After the participant's evidence record is closed and evaluation is complete, the debrief may reveal:
- competencies materially observed;
- demonstrated strengths;
- developmental opportunities;
- provisional proficiency judgments where evidence supports them;
- Confidence;
- areas with insufficient evidence;
- examples of decisive observed behavior;
- how the framework distinguishes proficiency from Confidence;
- a plain-language explanation of the relevant L3/L4 seam when useful;
- an Overall Role Fit judgment only if the pilot design explicitly included a frozen Role Profile and evidence coverage is sufficient.

The debrief must also repeat that the pilot is developmental and experimental and that the framework has not established predictive hiring or certification validity.

---

# 4. Participant Identity and Privacy Boundary

## Default data-minimization rule
Collect only what is necessary to run and evaluate the pilot.

Do not request:
- date of birth;
- home address;
- government identifiers;
- compensation history;
- protected-class information;
- medical information;
- unrelated personal information;
- confidential employer/customer data that is unnecessary to the exercise.

## Participant ID
Assign a neutral participant identifier such as:
- HP-001;
- HP-002.

Internal methodology artifacts should prefer the participant ID over the participant's name.

## Work-history evidence
For A5-style historical evidence, participants should be instructed not to disclose confidential employer information, customer names, proprietary datasets, trade secrets, credentials, passwords, or restricted internal materials.

They may generalize company/customer details where necessary while preserving the operating behavior being evaluated.

## Public repository boundary
**No identifiable participant evidence, raw transcript, private work history, contact information, or participant-specific assessment result belongs in the public GitHub repository.**

Public GitHub may contain:
- de-identified methodology findings;
- revised exercise design;
- aggregate or synthetic examples;
- Candidate framework changes that cannot reasonably identify a participant.

Participant-specific records require a private/controlled location appropriate to the eventual workflow. This protocol does not yet designate a final participant system of record.

---

# 5. Pilot Roles

## Participant
Provides responses and makes decisions naturally. Is not expected to know the competency model.

## Assessment Facilitator
Runs the participant-facing interaction.

Facilitator responsibilities:
- present scenarios consistently;
- reveal evidence only when justified by participant inquiry or instrument rules;
- ask pre-authorized probes neutrally;
- avoid coaching;
- avoid praise that signals score quality;
- avoid revealing hidden framework mechanics;
- preserve the participant's actual reasoning path.

## Evaluator
Reviews the closed evidence record after the participant-facing interaction.

Evaluator responsibilities:
- score observable evidence rather than presumed capability;
- distinguish Proficiency, Confidence, Profile Coverage, and Role Fit;
- preserve contradictions;
- cite decisive evidence;
- resist title/scale/polish/tool/outcome halo;
- use Insufficient Evidence when appropriate;
- avoid averaging.

## Pilot Owner
JET retains authority over whether the pilot proceeds, who participates, what participant-facing disclosure is used, and whether any participant-specific result is shared externally.

---

# 6. Interaction Isolation

A participant should interact in a **clean participant-facing chat/session**, not the internal RevOps Academy development chat.

The participant-facing environment should not expose internal Candidate artifacts or prior synthetic participants.

Internal evaluator work should occur separately after evidence closure.

## Preferred principle
**Assessment first. Evaluation second. Coaching third.**

Do not blend these phases in a way that changes the evidence being evaluated.

## Session continuity
If the assessment spans multiple sessions:
- preserve only necessary participant state;
- do not provide retrospective coaching between scored sections unless the protocol explicitly changes from assessment to Academy mode;
- clearly mark when scored evidence collection ends.

---

# 7. Facilitator Neutrality Rules

The facilitator may:
- clarify scenario facts already available;
- explain task mechanics;
- answer participant questions with evidence allowed by the instrument;
- ask neutral probes needed for evidence sufficiency;
- ask the participant to make a recommendation when they remain indefinitely analytical after sufficient evidence exists.

The facilitator must not:
- say “that's an L4 answer”;
- tell the participant which competency is being tested during the scored interaction unless the instrument intentionally requires it;
- reward use of framework vocabulary;
- suggest a missing economic, governance, leadership, or systems concept merely because the evaluator wants evidence for it;
- lead the participant toward the hidden evidence map;
- repair a weak answer before evidence closure;
- reveal another participant's response;
- imply that title, years, certifications, or tool experience determine proficiency.

## Neutral probe test
Before asking a probe, ask:
> **Would this question still be appropriate if I did not know what answer would score better?**

If no, do not ask it during scored evidence collection.

---

# 8. Pilot Assessment Scope

## First-human-pilot recommendation
Do **not** begin with the entire A1→A5 battery.

Start with a bounded subset that is long enough to test the interaction but short enough to respect the participant's time and allow close observation.

Recommended first pilot:
1. **A1 Dynamic GTM Diagnostic**;
2. **A4 Stakeholder Alignment & Change Simulation**;
3. short structured debrief after evidence closure.

Why A1 + A4:
- different modalities;
- analytical plus relational evidence;
- exposes hidden-evidence interaction behavior;
- tests facilitator neutrality;
- covers several Strategic Anchors;
- avoids asking an external volunteer to endure a five-part experimental battery before basic usability is proven.

A5 may be added in a later pilot after privacy/work-history handling is proven.

A2/A3/full battery can follow after the participant interaction itself is stable.

---

# 9. Role Profile Use in First Pilot

The first human pilot should primarily evaluate **competency evidence and participant experience**, not make a high-stakes full VP Role Fit claim.

If a VP Role Profile is used:
- freeze it before evidence begins;
- tell the participant that a developmental role-pattern comparison may be included;
- do not imply job qualification;
- use Overall Role Fit: Insufficient Evidence if the A1+A4 scope cannot support sufficient profile breadth.

A narrow pilot should not manufacture a full-profile conclusion.

---

# 10. Evidence Record

After the participant interaction ends, create a closed evidence record containing:
- participant ID;
- assessment version;
- dataset version;
- date;
- participant responses;
- evidence revealed;
- facilitator probes;
- participant recommendations/decisions;
- explicit contradictions or revisions;
- session notes required to understand the interaction.

Do not include evaluator scores in the evidence record supplied to an independent evaluator.

The evidence record should distinguish participant words/actions from facilitator statements.

---

# 11. Evaluator Independence

For the first pilot, the strongest available design is:

### Evaluator 1
EVA evaluation using the frozen Candidate methodology.

### Evaluator 2
A genuinely independent human evaluator if available and willing, using the same evaluator protocol and blinded evidence record.

JET may observe the process, but if JET knows the participant personally, JET's assessment should not be treated as an independent blinded evaluator score unless the design specifically controls for that relationship.

If only EVA evaluates the first pilot, call it a **single-evaluator usability/development pilot**, not an evaluator-reliability test.

---

# 12. Independent Scoring Protocol

Each evaluator records before reconciliation:
- competency evidence observed;
- proficiency judgment;
- Confidence;
- counterevidence/contradictions;
- Profile Coverage;
- Role Fit only if scope supports it;
- decisive evidence;
- unanswered questions that materially limit the judgment.

Evaluators must not see each other's scores before submitting their own first-pass evaluation.

---

# 13. Disagreement Taxonomy

When evaluators disagree, classify the disagreement before attempting reconciliation:

1. **Evidence disagreement** — they interpret what happened differently.
2. **Competency-attribution disagreement** — they agree on behavior but map it to different competencies.
3. **Proficiency-boundary disagreement** — same evidence/competency, different L-level.
4. **Confidence disagreement** — same proficiency, different sufficiency/reliability judgment.
5. **Coverage disagreement** — different judgment about whether enough of the profile was observed.
6. **Role Profile disagreement** — different interpretation of target-role expectations.
7. **Halo/bias disagreement** — title, scale, polish, familiarity, or outcome appears to influence one judgment.
8. **Instrument ambiguity** — assessment wording or evidence path itself caused the disagreement.

Do not average the evaluator scores to resolve disagreement.

Reconciliation should record why the disagreement occurred and whether the methodology, instrument, evaluator guidance, or no artifact needs revision.

---

# 14. Participant Debrief

The participant should receive something useful in exchange for their time.

Recommended debrief structure:

### What we observed
Behavioral evidence, not personality labels.

### Demonstrated strengths
Specific examples.

### Development opportunities
Specific next-level behaviors rather than generic advice.

### Evidence limits
What the pilot did not observe strongly enough.

### Developmental profile
Competency/proficiency/Confidence only where supported.

### What this does not mean
Not certification, not employment qualification, not prediction of job performance.

### Participant feedback to the Lab
Ask:
- What felt unclear?
- What felt artificial?
- Did any question feel leading?
- Did you feel you had enough information to reason?
- Did the facilitator accidentally signal preferred answers?
- Did the debrief feel recognizable and useful?
- What important RevOps capability did the interaction fail to let you demonstrate?

Participant feedback is evidence about the **instrument**, not merely satisfaction data.

---

# 15. Reveal After Debrief

After scored evidence is closed, the participant may be shown more of the methodology if JET chooses.

Recommended default:
- explain the competency model at a high level;
- explain Proficiency vs Confidence;
- explain why hidden evidence exists;
- explain that the system is designed to reward disciplined uncertainty and evidence-seeking rather than guessing the answer;
- explain relevant developmental seams.

Do **not** automatically disclose the complete hidden evidence map or reusable answer key after the first pilot if the same instrument will be used with later participants.

Protecting future assessment integrity is legitimate so long as participants were not misled about the nature of the exercise.

---

# 16. Participant-Specific Publication Rule

Participant-specific results are private by default.

Do not publish or share identifiable results outside the agreed pilot participants/evaluators without the participant's explicit permission and JET's explicit approval.

Even with permission, consider whether publication could affect employment reputation or future assessment integrity.

De-identified methodology findings may be candidates for the public repository only after reasonable re-identification risk review.

---

# 17. Stop Conditions

Pause the pilot interaction if:
- participant wants to stop;
- participant begins disclosing unnecessary sensitive/confidential information;
- facilitator realizes hidden scoring logic was accidentally revealed in a way that materially contaminates the assessment;
- the instrument fails technically such that the evidence path is no longer comparable;
- a serious ambiguity makes continued scoring unfair.

A stopped pilot may still provide methodology-learning evidence, but should not receive an overconfident proficiency/Role Fit judgment.

---

# 18. Pilot Success Criteria

The first human pilot succeeds if it teaches us whether:
- participant can navigate the interaction naturally;
- facilitator can remain neutral;
- evidence retrieval feels responsive rather than game-like;
- at least several intended competencies produce observable evidence;
- evaluator can cite evidence for judgments;
- Confidence and Insufficient Evidence work with messy human responses;
- participant debrief is useful and recognizable;
- participant feedback exposes concrete instrument improvements;
- no unsupported certification/hiring claim is made;
- privacy/public-repository boundaries are preserved.

The participant does **not** need to score well for the pilot to succeed.

---

# 19. Evidence Required Before Expanding Pilot

Before moving from one friendly participant to a broader pilot, review:
- participant feedback;
- facilitator contamination/leading incidents;
- evidence gaps;
- evaluator disagreement;
- time burden;
- privacy/record handling;
- whether A1+A4 produced useful developmental evidence;
- whether any prompt or hidden evidence path requires revision.

Only then decide whether to:
- repeat A1+A4;
- add A5;
- run A1→A5;
- introduce a second independent evaluator;
- revise methodology/instruments;
- stop the pilot.

---

# 20. Pre-Launch Checklist

Before HP-001 begins, JET and EVA should explicitly confirm:
- participant-facing disclosure text is approved;
- participant interaction environment is isolated from internal development materials;
- participant ID assigned;
- assessment/instrument versions frozen;
- dataset versions frozen;
- pilot scope frozen;
- facilitator instructions loaded;
- participant-specific evidence storage location decided;
- no participant-specific evidence will enter public GitHub;
- debrief format prepared;
- evaluator plan identified;
- participant has affirmed the disclosure.

**Pilot launch requires a separate explicit JET decision.**

---

# 21. Recommended Next Artifact

Create a short, human-readable **Participant Invitation & Disclosure Candidate v0.1** plus a **Participant Session Start Prompt Candidate v0.1**.

These should be written for the external participant, not for framework designers.

They should reveal enough for informed participation without exposing scoring anchors or hidden evidence mechanics.

After those are pressure-tested, JET can decide whether to launch HP-001.

---

# Governance

Candidate only.

Creating this protocol does not recruit a participant, launch a pilot, authorize participant-specific publication, establish a system of record, certify anyone, validate the assessment for employment selection, or make any methodology canonical.
