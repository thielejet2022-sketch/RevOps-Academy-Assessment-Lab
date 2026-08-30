# Stakeholder Alignment & Change Dataset

**Status:** Candidate v0.1  
**Dataset ID:** SC-001-v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Primary use:** A4 Stakeholder Alignment & Change Simulation

## Purpose
Provide a reusable operating environment for observing Cross-Functional Leadership and Change Management & Adoption through actual stakeholder tension rather than analytical discussion about stakeholder management.

Exercises may reference this dataset but should not own or silently alter its facts.

---

# Scenario Context

A $90M ARR B2B SaaS company has approved a new opportunity qualification and forecasting process after two quarters of forecast misses and inconsistent pipeline quality.

The executive team previously agreed to three changes:
1. an opportunity may not enter the committed pipeline without documented business problem, buying process, next step, and target decision date;
2. Sales managers must inspect these fields during weekly pipeline review;
3. Marketing and SDR teams will use a revised SQL acceptance definition so Sales receives fewer low-intent handoffs.

The process was designed jointly by RevOps, Sales Operations, Marketing Operations, and Finance and was announced three weeks ago.

The rollout is now in trouble.

---

# Stage 0 — Participant Baseline

- Forecast accuracy has averaged ±22% over the last two quarters.
- Executive target is ±8% within two quarters.
- Approximately 38% of open opportunities currently lack one or more newly required qualification elements.
- Two of four Regional VPs are enforcing the new process.
- Two are not.
- Sales managers report that the new requirements add administrative burden.
- Marketing believes the revised SQL definition is causing Sales to reject leads too aggressively.
- SDR leadership believes acceptance criteria are changing by region.
- Finance supports the new controls and wants enforcement immediately.
- CRO publicly supported the redesign but privately told one Regional VP, “Do what you need to do to hit the number.”
- The next board forecast review is in five weeks.

The participant is acting as the senior RevOps leader responsible for getting the operating change adopted without pretending that RevOps has unilateral authority over Sales, Marketing, or Finance.

---

# Stakeholder Profiles

## Stakeholder A — CRO, Maya Chen
Public position: Supports forecast discipline and the new process.

Private incentives/concerns:
- Board pressure after two misses.
- Fears tighter qualification will make pipeline coverage look worse immediately.
- Does not want a process rollout to become an excuse for missing the quarter.
- Values decisive operators and dislikes bureaucratic language.
- Has unintentionally weakened the rollout by allowing informal exceptions.

Behavior in simulation:
- initially asks participant to “get everyone aligned” without confronting the exception issue;
- may become defensive if accused of hypocrisy;
- responds positively to clear business consequences, bounded choices, and explicit decisions needed from her.

## Stakeholder B — Regional VP Sales East, Marcus Reed
Position: Resists the new requirements.

Concerns:
- Team is at 84% of quarterly target.
- Believes reps should sell, not complete CRM fields.
- Thinks experienced managers can judge deal quality without standardized criteria.
- Says the process was “designed by people who don't carry quota.”
- Has instructed managers not to remove deals from commit solely because fields are incomplete.

Behavior:
- challenges RevOps credibility;
- asks for proof the new process improves revenue rather than data cleanliness;
- will accept a limited pilot or simplified requirement if it clearly protects selling time and improves decisions.

## Stakeholder C — Regional VP Sales West, Elena Alvarez
Position: Supports the change.

Evidence:
- West adopted the process earliest.
- Qualification completeness improved from 61% to 91%.
- Forecast variance improved from 19% to 11% in the first month.
- Reps complain about some duplicate entry.
- Elena believes manager inspection, not required fields alone, is driving the improvement.

Behavior:
- can provide practical implementation evidence;
- warns against turning the process into CRM compliance theater.

## Stakeholder D — CMO, Priya Shah
Position: Supports better qualification but believes Sales is using the new SQL definition to reject legitimate demand.

Evidence/concerns:
- SQL acceptance fell from 71% to 54% after rollout.
- Rejection reasons are inconsistently captured.
- Paid demand budget is under scrutiny.
- Marketing fears the new process will make its funnel appear weaker without proving downstream quality improved.

Behavior:
- asks for consistent acceptance rules and feedback data;
- resists unilateral Sales control over SQL definitions;
- responds to shared metrics and closed-loop learning.

## Stakeholder E — SDR VP, Jordan Blake
Position: Frustrated and increasingly cynical.

Concerns:
- SDRs are being coached to one definition while regions apply different acceptance standards.
- Reps are gaming rejection reasons.
- SDR morale is falling because teams believe goals remain unchanged while acceptance gets harder.

Behavior:
- wants explicit rules and escalation path;
- may overstate Sales bad faith if not challenged.

## Stakeholder F — CFO, Daniel Foster
Position: Wants immediate enforcement.

Concerns:
- Board confidence in forecast is damaged.
- Does not want another quarter of subjective exceptions.
- Prefers hard controls and measurable compliance.

Behavior:
- pushes for mandatory fields and system-enforced stage gates;
- may underweight seller workflow and adoption risk;
- responds to evidence that behavioral adoption and manager inspection matter more than field completion alone.

---

# Evidence Packets

## Packet A — Adoption by Region
East:
- qualification completeness: 52%
- manager inspection adherence: 41%
- forecast variance: 24%

West:
- qualification completeness: 91%
- manager inspection adherence: 88%
- forecast variance: 11%

Central:
- qualification completeness: 76%
- manager inspection adherence: 69%
- forecast variance: 16%

International:
- qualification completeness: 63%
- manager inspection adherence: 58%
- forecast variance: 20%

The sample is early and does not prove causality.

## Packet B — Seller Workflow
- Reps enter some qualification data in CRM and some in call notes.
- Two required fields duplicate information already captured in call-recording summaries.
- Average opportunity update time increased by approximately 4 minutes.
- High-performing West managers use the qualification questions conversationally during deal review rather than treating them as form completion.

## Packet C — SQL Acceptance
- Acceptance fell 71% → 54% overall.
- West acceptance fell 70% → 62% while opportunity conversion improved modestly.
- East acceptance fell 72% → 46% with no measurable opportunity-conversion improvement yet.
- Rejection reason “not qualified” increased sharply but is poorly defined.
- Approximately 27% of rejected SQLs lack a usable rejection reason.

## Packet D — Governance Gap
The approved rollout document defines the new process but does not specify:
- who can approve regional exceptions;
- who owns changes to SQL acceptance criteria;
- how conflicting interpretations are resolved;
- when the process will be reviewed;
- which measures determine whether the change is working.

## Packet E — Manager Behavior
- Teams with high manager inspection adherence show better field completeness.
- Reps report that manager behavior matters more than rollout emails.
- Some managers tell reps to “fill enough to pass the check.”
- No manager coaching guide was included in the rollout.

## Packet F — Incentives
- SDR variable compensation still rewards accepted SQL volume.
- Marketing quarterly goals include MQL and SQL volume.
- Sales managers are paid on bookings and have no explicit forecast-quality component.
- No compensation change is currently approved.

## Packet G — Executive Messaging
- CRO launch email called the process “mandatory.”
- In two regional calls afterward, the CRO emphasized local judgment and avoiding unnecessary admin.
- Regional leaders interpreted this differently.
- No follow-up clarification has been issued.

## Packet H — Customer/Revenue Risk
- Three large East deals are currently in commit despite weak qualification evidence.
- Removing all three would reduce reported commit coverage materially.
- One may be real but underdocumented; two show no confirmed decision process.
- Board review is five weeks away.

---

# Default Simulation Escalations

## Escalation 1 — Sales resistance
Marcus says:
> “You're asking my team to spend more time feeding the CRM while we're behind quota. Show me why I should enforce this instead of letting my managers manage.”

## Escalation 2 — Marketing conflict
Priya says:
> “Sales is weaponizing your new definition to reject leads they don't want. I'm not accepting a 54% acceptance rate as proof Marketing suddenly got worse.”

## Escalation 3 — Executive inconsistency
If participant proposes uniform enforcement, CRO Maya says privately:
> “I support the process, but don't force Marcus to pull those three deals out of commit five weeks before the board meeting. We need room for judgment.”

## Escalation 4 — Adoption shock
Two weeks into the participant's intervention:
- field completeness rises to 82%;
- manager inspection rises only to 61%;
- forecast quality improves slightly;
- reps report growing “check-the-box” behavior;
- SQL acceptance remains inconsistent by region.

The participant must decide whether the rollout is working and what to change.

---

# Design Characteristics

This dataset deliberately creates:
- legitimate stakeholder incentives rather than cartoon villains;
- executive inconsistency;
- tension between control and seller productivity;
- ambiguity between compliance and adoption;
- functional metrics that can conflict;
- early evidence that is suggestive but not causal proof;
- incentives misaligned with the desired behavior;
- a need for leadership without unilateral authority;
- a change that may itself need refinement rather than blind enforcement.

There is no single required resolution.

---

# Versioning Rules

- Exercises reference this dataset by ID/version.
- Historical assessment records retain the dataset version used.
- Changes that materially alter stakeholder incentives, evidence, likely decisions, or difficulty require a dataset revision.
- New stakeholder structures or materially different change environments should normally become a new dataset rather than silently modifying SC-001.

---

# Governance

This dataset is **Candidate only**.

It does not validate any competency level, hiring inference, or change-management methodology.

Canonical promotion requires JET's explicit review and approval of a specific identifiable Candidate.
