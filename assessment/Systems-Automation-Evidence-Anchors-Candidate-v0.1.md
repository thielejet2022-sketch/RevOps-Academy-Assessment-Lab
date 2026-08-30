# Systems & Automation — Evidence Anchors

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Parent framework:** RevOps Competency Model Candidate v0.2  
**Purpose:** Test whether the emerging L1–L5 proficiency architecture transfers from Commercial & Business Judgment to a materially different competency.

## Competency Definition
Ability to use, design, govern, and architect CRM, GTM tooling, integrations, automation, and system environments appropriate to the participant's level of responsibility.

Higher proficiency emphasizes architecture, governance, reliability, business fit, and complexity management rather than merely greater personal configuration skill.

## Critical Construct Separation
This competency must not collapse **technical skill** and **systems leadership** into one ladder.

A participant may be exceptionally strong at Salesforce, HubSpot, SQL, workflow configuration, APIs, or automation and still not demonstrate L4/L5 systems architecture. Conversely, a strategic RevOps leader may demonstrate L4 systems judgment without personally being the strongest administrator or developer on the team.

Score what the participant demonstrates in the work being evaluated.

---

# L1 — Foundational

## Core signal
**Understands core system concepts and performs defined configuration/data tasks with guidance.**

## Observable evidence
- navigates common CRM/GTM objects, fields, workflows, reports, or user processes;
- understands basic relationships among records and systems;
- performs defined configuration, data-maintenance, or automation tasks using established instructions;
- recognizes common data-quality, permissions, workflow, or integration problems;
- knows when to escalate a change beyond their authority or knowledge.

## Boundary test
**Can the participant execute a defined systems task correctly, but still needs guidance to choose or design the solution?**

If yes, L1 may be appropriate.

## Not enough for L2
Tool familiarity, certifications, or completing prescribed configuration steps do not by themselves demonstrate independent systems ownership.

---

# L2 — Practitioner

## Core signal
**Independently solves familiar systems problems within an established architecture.**

## Observable evidence
- configures routine fields, workflows, reports, permissions, routing, or automation independently;
- diagnoses common failures using logs, field history, workflow logic, test records, or equivalent evidence;
- understands upstream/downstream effects of routine changes;
- tests changes before release and verifies expected behavior;
- documents routine configuration and avoids unnecessary duplication;
- chooses a reasonable solution among familiar alternatives.

## Boundary from L1
The transition is **independent routine application**, not mastery of more product features.

## Boundary test
**Can the participant independently solve the familiar systems problem without needing someone else to structure the implementation?**

---

# L3 — Advanced

## Core signal
**Designs and improves cross-functional system solutions under ambiguity.**

## Observable evidence
- translates ambiguous business requirements into system/process design;
- reasons across objects, workflows, integrations, handoffs, permissions, reporting, and downstream consequences;
- identifies when a requested automation would encode a bad process rather than improve it;
- challenges requirements and simplifies architecture where appropriate;
- evaluates build-versus-buy or configuration-versus-customization tradeoffs at practical operating scale;
- designs testing, rollout, documentation, ownership, and recovery/exception handling;
- resolves conflicts among Marketing, Sales, CS, Finance, or other stakeholders about system behavior;
- connects technical choices to adoption, data quality, reporting integrity, and operating outcomes.

## Boundary from L2
L2 works independently **within** an established architecture. L3 can design and improve solutions when the business problem, requirements, or cross-functional implications are ambiguous.

## Boundary test
**Did the participant merely implement the requested solution, or did they determine what the solution should be and how it should work across functions?**

---

# L4 — Strategic

## Core signal
**Shapes GTM systems architecture, standards, investment decisions, and governance across functions.**

## Observable evidence
- defines architectural principles for CRM, data ownership, integrations, automation, reporting, identity/permissions, or GTM tooling;
- makes consequential platform, consolidation, integration, or technical-debt tradeoffs in business terms;
- establishes standards for what should be automated, customized, purchased, integrated, retired, or left manual;
- balances speed, maintainability, reliability, user experience, cost, security/privacy constraints, and future flexibility;
- defines ownership and change-control mechanisms appropriate to risk;
- prevents local functional optimization from degrading the shared revenue architecture;
- frames systems investments around business capability rather than tool enthusiasm;
- influences senior stakeholders when architecture requires changing process, ownership, budget, or operating behavior.

## Boundary from L3
L3 designs strong cross-functional solutions. L4 **shapes the architecture and governance within which many solutions and investment decisions are made**.

## Boundary test
**Did the participant solve a complex systems problem, or did they change how the organization makes and governs systems decisions?**

## Important rule
L4 does not require the participant to personally perform every advanced configuration task. The evaluator should look for sufficient technical fluency to make defensible architecture and governance decisions, plus evidence that those decisions improve the operating system.

---

# L5 — Enterprise / Architect

## Core signal
**Creates reusable systems architecture and governance that remains coherent across materially different GTM contexts, platforms, organizational structures, and change over time.**

## Observable evidence
- separates durable architecture principles from platform-specific implementation choices;
- designs reference architectures or decision frameworks that support materially different GTM motions without forcing false uniformity;
- establishes how local teams may vary workflows, tools, data models, or integrations while preserving shared semantic, governance, security/privacy, and reporting integrity;
- defines migration, interoperability, exception, lifecycle, and deprecation principles for complex environments;
- governs architectural evolution as products, acquisitions, geographies, regulations, business units, or portfolio companies change;
- reasons explicitly about centralization versus local autonomy;
- designs systems that preserve comparability and control while allowing justified variation;
- recognizes when standardization creates more risk or friction than value;
- creates reusable decision architecture that other systems leaders can apply without the original designer present.

## Boundary from L4
L4 strategically governs a complex GTM systems environment. L5 **creates transferable architecture for governing multiple materially different environments and their evolution**.

## Boundary test
**Did the participant establish excellent architecture for this organization, or did they demonstrate a reusable way to preserve integrity across different architectures, contexts, and future change?**

---

# Cross-Level Summary

| Level | Systems & Automation signal |
|---|---|
| **L1 Foundational** | Performs defined systems work with guidance |
| **L2 Practitioner** | Independently solves familiar problems within established architecture |
| **L3 Advanced** | Designs cross-functional solutions under ambiguity |
| **L4 Strategic** | Shapes architecture, standards, investments, and governance across functions |
| **L5 Enterprise / Architect** | Creates reusable architecture and complexity governance across materially different environments |

---

# Adversarial Calibration Cases

## Case A — Elite Administrator Trap
A participant can build complex Salesforce Flows, understands APIs, writes sophisticated queries, diagnoses integration failures quickly, and knows the platform deeply. However, when given ambiguous business requirements, they implement requested solutions without challenging process design, create local automations that conflict with shared data architecture, and do not establish change governance.

**Expected interpretation:** Potentially very strong technical execution, but this evidence alone should not produce L4/L5. Depending on the demonstrated cross-functional design behavior, Systems & Automation may be L2 or L3 despite exceptional platform depth.

## Case B — Non-Builder Strategic Leader Trap
A VP does not personally configure Salesforce. They can, however, explain the object/data implications of a proposed workflow, challenge unnecessary customization, define integration and ownership principles, make a defensible build/buy decision, establish change governance, and direct qualified administrators/developers toward an architecture that serves the business.

**Expected interpretation:** Lack of personal configuration should not automatically cap the participant below L4. The evidence must show genuine technical fluency and architecture judgment rather than delegation plus vocabulary.

## Case C — Tool Collector Trap
A participant recommends replacing CRM, adding an AI prospecting platform, buying a new attribution tool, implementing a data warehouse, and adding automation because each tool is “best in class.”

**Expected interpretation:** Tool breadth is not systems proficiency. Without architecture, business requirements, ownership, integration logic, economics, and governance, this may demonstrate weak Systems & Automation judgment.

## Case D — Standardization Trap
An enterprise leader mandates identical lifecycle stages, objects, fields, workflows, and tooling across several acquired businesses with materially different GTM motions solely to create consistency.

**Expected interpretation:** Enterprise scope does not equal L5. Failure to govern justified variation may be evidence against Enterprise/Architect proficiency.

---

# Cross-Cutting Scoring Rules

## Technical depth versus proficiency altitude
Technical depth is relevant evidence but not a direct proxy for level. Evaluate whether the participant's technical capability is appropriate to the decision they are making.

## Architecture without technical grounding
Do not award L4/L5 for abstract “architecture” language when the participant cannot reason about concrete consequences such as data ownership, workflow behavior, integration dependencies, reporting semantics, permissions, maintainability, failure modes, or migration risk.

## Business judgment interaction
Systems decisions often reveal Commercial & Business Judgment, Process Design, Change Management, or Data & Analytics. Score those separately when observed. Do not double-count the same evidence merely because one systems decision touches several competencies.

## Insufficient evidence
A strategic participant should not receive a low Systems & Automation score merely because the exercise never meaningfully tested systems judgment. Use **Insufficient evidence**.

## Confidence
Record confidence separately. A single architecture discussion may demonstrate high-quality evidence but does not prove durable capability across platforms or environments.

---

# Transfer-Test Result

The five-level proficiency architecture transfers conceptually from Commercial & Business Judgment to Systems & Automation **only if the competency-specific manifestation changes**.

The general altitude pattern remains useful:

1. guided recognition/execution;
2. independent familiar application;
3. ambiguous cross-functional design;
4. strategic operating architecture/governance;
5. reusable architecture and complexity governance across materially different contexts.

But the evidence cannot be copied mechanically from Commercial Judgment. Systems & Automation requires explicit protection against two opposite biases:
- equating advanced hands-on technical skill with strategic/enterprise proficiency;
- awarding strategic/enterprise proficiency to senior leaders who lack enough technical grounding to make defensible systems decisions.

This supports a shared **proficiency architecture with competency-specific evidence anchors**.

---

# Implication for the Competency Model

The transfer test increases confidence that L1–L5 can function as a common proficiency spine across different competencies while preserving domain-specific manifestations.

It does **not** yet justify mass-producing all remaining competency anchors. Two competencies now support the architecture, but additional tests should focus on domains that stress different constructs, especially:
- Cross-Functional Leadership or Change Management & Adoption, where evidence is behavioral and relational rather than primarily analytical/technical;
- Communication & Executive Readout, where polished language can create a strong false-positive risk.

## Recommended Next Step
Before building another evidence-anchor document, pause artifact creation and decide whether the two successful vertical slices provide enough confidence to draft a **Competency Model Candidate v0.3** that incorporates the now-tested proficiency definitions at the model level.

That would be a consolidation decision, not automatic promotion. Candidate v0.2 would remain intact, and v0.3 would remain non-canonical until explicitly reviewed and approved.

## Governance
This is a Candidate only. It does not modify the canonical competency model, scoring architecture, role profiles, or assessment standard. Promotion requires JET's explicit approval of a specific identifiable Candidate.
