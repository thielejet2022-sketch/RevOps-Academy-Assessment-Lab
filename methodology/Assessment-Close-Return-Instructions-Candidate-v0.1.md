# Assessment Close & Return Instructions Candidate v0.1

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Delivery method:** D1-Pilot  
**Pilot:** HP-001  
**Purpose:** Define how the participant closes the scored assessment, preserves the original reasoning path, and returns the completed participant-owned ChatGPT conversation for evaluation.

## Critical Boundary
This Candidate does not launch HP-001 and does not claim that a specific ChatGPT sharing/export path has already been verified for the pilot.

The exact return mechanism must be confirmed during DR-001 before external launch. If ChatGPT's current sharing behavior differs from these instructions, revise this artifact rather than improvising with the external participant.

---

# 1. Trigger

Use these instructions only after the facilitator has completed A1 and A4 and has said:

> **ASSESSMENT EVIDENCE CLOSED**

From this point forward:
- the scored evidence record is closed;
- the participant should not revise prior assessment answers for scoring purposes;
- no scoring, coaching, competency profile, or Role Fit judgment should be provided inside the participant assessment conversation before independent evaluation;
- post-assessment logistics and participant-experience feedback may continue without changing the scored evidence.

---

# 2. Participant-Facing Close Message

Present the following:

## Assessment complete

**ASSESSMENT EVIDENCE CLOSED**

Thank you. You've completed the scored portion of the RevOps Assessment Pilot.

Please leave your earlier assessment responses as they are. Your original reasoning path, including questions, changes of mind, uncertainty, and decisions, is part of the evidence the pilot is designed to observe.

You have **not** received a score or developmental evaluation yet. That happens separately after the completed conversation is returned and reviewed.

### What happens next

Your next step is to return this completed assessment conversation to JET so it can be reviewed as the pilot evidence record.

Please follow the return instructions below.

---

# 3. Preferred D1 Return Method — Subject to DR-001 Verification

## Method A — Share the completed conversation

If your ChatGPT interface provides a **Share** option for this conversation:

1. Use ChatGPT's Share control for this completed conversation.
2. Review the sharing screen before creating the link.
3. Create/copy the conversation share link only if you are comfortable sharing the conversation with JET for the purposes described in the pilot disclosure.
4. Send that link directly to JET using the communication method you used for the pilot invitation.
5. Do not post the link publicly.

When you send it, include:

> **RevOps Pilot complete — assessment conversation attached/shared for evaluation.**

JET should confirm receipt before the pilot evidence handoff is considered complete.

## Important

The shared conversation should contain only the pilot assessment interaction. If you accidentally used a conversation containing unrelated personal or confidential material, **do not share it**. Tell JET and use an alternate return method instead.

---

# 4. Fallback Return Method — Subject to DR-001 Verification

If the Share control is unavailable, fails, or would expose unrelated material, do not improvise by posting the assessment publicly.

Instead:

1. Tell JET that the normal share method is unavailable.
2. Preserve the conversation in your ChatGPT history if possible.
3. Wait for the approved fallback instruction.

During DR-001, JET and EVA will determine whether a practical fallback should be:
- copied transcript text;
- a participant-generated document/PDF containing the complete conversation;
- another verified private transfer method.

No fallback is declared canonical in this Candidate until tested.

---

# 5. Participant Experience Feedback

After the scored evidence has been closed, the facilitator may ask the participant for **assessment-experience feedback**. This feedback is not added retroactively to scored competency evidence.

Suggested prompt:

> Before you leave, we'd also value your feedback on the assessment itself. This will not change your scored evidence.
>
> In a few sentences, please tell us:
> - What felt realistic?
> - What felt confusing or artificial?
> - Did the facilitator ever seem to lead you toward an answer?
> - Did you feel able to ask for the information you needed?
> - Was there an important RevOps capability you felt you could not demonstrate?
> - Roughly how long did the experience take you?
>
> You can answer here or send the feedback to JET separately.

If experience feedback is included in the returned conversation, label it clearly as **post-assessment participant feedback**, not scored evidence.

---

# 6. JET Receipt Procedure — Operator Instructions

When JET receives the returned conversation:

1. Confirm receipt to the participant.
2. Do not provide an immediate score or improvised assessment.
3. Confirm that the returned artifact appears to contain the full participant interaction from session start through **ASSESSMENT EVIDENCE CLOSED**.
4. Assign/confirm the neutral participant ID, e.g. `HP-001`.
5. Keep participant identity separate from any public methodology artifact.
6. Do not commit the participant transcript, identifiable excerpts, contact details, or participant-specific result to the public GitHub repository.
7. Preserve the returned evidence in the private/controlled operational location selected before HP-001 launch.
8. Create the evaluator evidence record separately.
9. Begin evaluation only after the evidence record is considered closed.

If the transcript appears incomplete, record that limitation rather than silently reconstructing missing participant evidence.

---

# 7. Evidence Integrity Rules

The returned conversation is treated as the source evidence record for D1-Pilot.

Do not:
- edit participant answers to make them clearer;
- remove weak or contradictory reasoning because a later answer is stronger;
- add evaluator interpretations into the participant transcript;
- infer missing questions/answers;
- convert post-assessment feedback into scored competency evidence;
- treat ChatGPT-generated facilitator text as participant evidence;
- use unrelated personal information from the participant's account or conversation.

If a participant corrects a typo after evidence closure without changing substantive meaning, preserve the original where possible and note the correction separately rather than silently replacing the evidence.

---

# 8. DR-001 Verification Checklist

Before HP-001 external launch, run DR-001 using JET's separate ChatGPT account. DR-001 is a delivery/usability dry run only and must not be treated as human validation evidence.

Verify:

## Entry
- shared starting conversation opens from the separate account;
- participant can continue the conversation;
- no internal development chat/history is exposed;
- no hidden evaluator/scoring material is visible.

## Assessment behavior
- READY launches the intended A1 experience;
- dynamic evidence behavior works;
- A1 decision gate occurs without obvious coaching;
- transition to A4 works;
- A4 stakeholder simulation behaves consistently;
- evidence closure occurs clearly;
- no visible scoring/debrief occurs prematurely.

## Return
- participant account exposes an appropriate Share mechanism, if available;
- the resulting shared artifact contains the complete continued assessment, not merely the original starting conversation;
- JET can open/read the returned conversation from the primary account/environment;
- the returned artifact does not expose unrelated account history or private content;
- link permissions/behavior are understandable enough to explain to an external participant;
- a workable fallback exists if sharing fails.

## Evidence usability
- evaluator can distinguish participant messages from facilitator messages;
- full reasoning trajectory is preserved;
- post-assessment feedback can be separated from scored evidence;
- transcript is usable without asking participant to reconstruct what happened.

Record DR-001 failures as delivery-method findings, not assessment-performance findings.

---

# 9. DR-001 Role Boundary

JET may play a participant persona during DR-001 to exercise the system, but because JET has helped design the framework and knows substantial internal architecture:

- DR-001 cannot validate competency scoring;
- DR-001 cannot validate proficiency discrimination;
- DR-001 cannot validate Role Fit;
- DR-001 cannot validate evaluator reliability;
- DR-001 cannot validate participant fairness;
- DR-001 cannot be counted as HP-001 or another human-pilot participant.

DR-001 may validate only delivery, usability, interaction integrity, hidden-material separation, evidence capture, and return mechanics.

---

# 10. Dry-Run Failure Rule

If DR-001 shows that the continued shared conversation does not preserve the intended assessment behavior or cannot return a usable evidence record without exposing hidden/private material, **do not launch HP-001 using D1-Pilot**.

Return to the delivery architecture decision and choose or design another mechanism.

This is a delivery checkpoint, not a reason to weaken the assessment methodology.

---

# 11. Pre-Launch Gate After DR-001

D1-Pilot may proceed to external launch review only when:
- entry works;
- hidden/internal material remains hidden;
- facilitator behavior is acceptably stable;
- assessment closure works;
- return mechanism works;
- evidence is readable and complete enough for evaluation;
- participant-specific storage location has been selected;
- participant-facing return instructions match the tested interface.

After these conditions are satisfied, stop at:

> **APPROVAL REQUIRED — Launch HP-001**

JET must explicitly approve external launch.

---

# Governance

Candidate only.

Creating this artifact does not launch DR-001 or HP-001. DR-001 is the next delivery validation activity after the complete delivery kit is assembled and pressure-tested.
