# Revenue Systems & Process Dataset

**Status:** Candidate v0.1  
**Dataset ID:** RSP-001-v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Primary use:** A3 Revenue Systems & Process Design assessments

## Purpose
Provide a reusable operating environment for assessing RevOps systems architecture and process design without turning the assessment into product-specific CRM trivia.

Exercises may reference this dataset but should not own or silently alter its facts.

## Stage 0 — Participant Baseline
A B2B SaaS company has grown from $18M to $42M ARR in three years. Its GTM stack includes a CRM, marketing automation platform, enrichment provider, scheduling tool, CPQ, customer-success platform, BI layer, and several point-to-point integrations.

The company has approximately:
- 75 quota-carrying sellers;
- 14 SDRs;
- 20 marketers;
- 10 customer-success managers;
- 38,000 active account records;
- 112,000 contact/lead records;
- 9,000 new inbound records per month.

Leadership says the CRM “works,” but teams increasingly distrust routing, stage data, attribution, ownership, and reports.

Current symptoms:
- 17% of inbound MQLs are not assigned within 30 minutes;
- duplicate account rate estimated at 11%;
- 8% of SQLs have no valid account owner when created;
- opportunity stage definitions vary by team;
- Sales frequently edits marketing-source fields manually;
- Finance's bookings report differs from Sales by 6–9% each month;
- customer-success handoff requires manual spreadsheet cleanup;
- CRM automation count has grown to 147 active workflows/rules with limited documentation.

The CRO wants the team to “clean up Salesforce.” The CMO wants attribution protected. Finance wants a trustworthy bookings number. Sales managers do not want additional rep administration.

The participant should not assume the named CRM is the root problem.

## Packet A — Lead Capture and Identity
- Forms create person records before reliable company matching is complete.
- Free-email domains account for 18% of inbound volume.
- Enrichment completes asynchronously, typically 2–8 minutes after creation.
- Routing currently fires immediately on record creation.
- Duplicate prevention uses email only; no durable person/account identity strategy exists.
- Some contacts are re-created when they re-enter via campaign forms.

## Packet B — Routing Logic
- Routing uses geography, employee count, named-account lists, and current account owner.
- Logic exists across three automation tools plus CRM assignment rules.
- Two tools can update owner after initial assignment.
- SDR territories were changed twice this year; old rules remain active in one automation layer.
- Exceptions are handled through Slack messages to Ops.
- No single routing decision log exists.

## Packet C — Lifecycle Definitions
- Marketing defines MQL as score threshold + fit.
- SDR leadership defines accepted SQL as “rep-confirmed active evaluation.”
- Sales creates opportunities at either discovery booked or discovery completed depending on team.
- Recycled leads may return to MQL automatically after 30 days even if disqualification reason remains unresolved.
- There is no canonical lifecycle-state model or mutually exclusive status design.

## Packet D — Opportunity Stage Governance
- Six stages exist in CRM.
- Teams use different exit criteria for stages 2–4.
- Required fields are based mainly on stage, but managers routinely request exceptions.
- Close date is automatically pushed 30 days when overdue.
- Some reps advance stage to satisfy forecast inspection, then move records backward later.
- Historical stage-change timestamps are incomplete because older automation overwrote fields.

## Packet E — Data Ownership
- Marketing owns source taxonomy in theory.
- Sales can edit original source and latest source.
- Finance maintains a spreadsheet adjustment table for booking corrections.
- Customer Success maintains its own implementation-start date.
- No data-owner matrix distinguishes business ownership from technical stewardship.
- Field creation requires no formal approval.

## Packet F — Reporting Reconciliation
- Sales bookings report uses opportunity Closed Won amount and close date.
- Finance uses executed contract value and contract effective date.
- Amendments, credits, and ramped contracts are handled differently.
- Neither report is necessarily “wrong”; the business has not defined which metric serves which management purpose.
- Executive dashboard labels both as “Bookings.”

## Packet G — Integration Architecture
- Marketing automation → CRM is bi-directional.
- Enrichment → CRM updates firmographics.
- CPQ → CRM updates product/amount fields.
- CRM → customer-success platform creates handoff records.
- BI ingests CRM and finance data nightly.
- Four integrations use shared admin credentials.
- Error monitoring is mostly email-based.
- Retry behavior is inconsistent.
- There is no integration inventory with system-of-record designation by object/field domain.

## Packet H — Automation Estate
- 147 active automations.
- 41 have no documented owner.
- 28 appear to overlap another rule/workflow.
- 19 were created for temporary campaigns or territory changes.
- Several trigger on each other's updates.
- Sandbox testing exists for major CRM releases but not consistently for automation changes.
- Rollback plans are uncommon.

## Packet I — Security and Access
- Sales reps can edit several fields used by Finance and Marketing reporting.
- Shared integration credentials are not tied to service accounts.
- Admin access is held by 11 users.
- No quarterly access review exists.
- This assessment is not a cybersecurity audit, but architecture should recognize control implications.

## Packet J — Change Constraints
- Quarter end is six weeks away.
- CRO refuses a “big bang” rebuild during quarter close.
- CMO has a major campaign launching in three weeks.
- Finance needs next month's board reporting to reconcile.
- Sales leadership will support changes if rep workflow does not materially slow down.
- RevOps team has one admin, one analyst, one ops manager, and access to a contractor for 15 hours/week.

## Packet K — Business Priorities
Leadership agrees on four desired outcomes:
1. no high-fit inbound lead should disappear or sit unowned;
2. lifecycle and opportunity data should support trustworthy conversion reporting;
3. bookings reporting should reconcile by definition and purpose;
4. system changes should become easier to govern and safer to deploy.

Leadership has not agreed on implementation sequence.

## Packet L — Existing Assets
Available artifacts:
- partial field dictionary last updated 10 months ago;
- outdated routing flowchart;
- CRM schema export;
- automation inventory with names but not owners/purpose;
- finance booking-adjustment spreadsheet;
- no current system-context diagram;
- no canonical lifecycle state diagram;
- no documented integration ownership matrix.

## Default Change Shock
After the participant proposes a design, reveal:

> Two weeks into implementation, the CMO announces a new product-led trial motion that will create thousands of self-service accounts each month. Some trial users will belong to existing enterprise accounts, others will be net new. Sales wants every enterprise-domain trial routed immediately to the named-account AE. Product wants the trial experience to remain self-service until a usage threshold is reached.

Observe whether the participant adapts the architecture rather than bolting on another one-off rule.

## Design Characteristics
The dataset deliberately includes:
- symptoms across process, data, systems, governance, and reporting;
- legitimate metric-definition conflicts rather than one “correct” report;
- asynchronous enrichment that complicates routing;
- multiple automation layers and exception handling;
- pressure for quick fixes during a constrained implementation window;
- a temptation to treat CRM cleanup as the entire problem;
- future-motion change that tests architectural extensibility.

## Versioning Rules
- Exercises reference `RSP-001-v0.1` explicitly.
- Do not silently alter values or facts used by historical assessment runs.
- Changes that materially affect architecture choices require a new dataset revision/version.
- Historical evidence records retain the dataset version used.

## Governance
This dataset is **Candidate only**. It does not claim to represent every SaaS architecture or a validated benchmark of RevOps systems proficiency.

Canonical promotion requires JET's explicit review and approval of a specific identifiable Candidate.
