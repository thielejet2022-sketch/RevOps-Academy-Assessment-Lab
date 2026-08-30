# Funnel Deterioration Dataset

**Status:** Candidate v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Dataset ID:** FD-001-v0.1  
**Intended use:** RevOps Academy and Assessment Lab exercises

## Purpose
Provide a reusable, versioned operating dataset for exercises involving funnel deterioration, growth investment, sales capacity, commercial judgment, and executive operating-model diagnosis.

Exercises should reference this dataset version rather than own or duplicate the underlying operating facts.

## Company Context
B2B SaaS company. Year-over-year growth investment has increased, but pipeline output and economic efficiency have deteriorated.

## Stage 0 Facts
- MQL volume: +29%
- SQL volume: +5%
- Sales headcount: +25% through 7 additional AEs
- Opportunities created: -7%
- Average sales cycle: 82 days

These facts are insufficient to establish causation.

## Evidence A — Marketing Source / Mix
- Paid social MQLs: +88% YoY
- Paid social MQL-to-SQL conversion: 11% → 4%
- Organic MQLs: +6%
- Organic MQL-to-SQL conversion: 24% → 23%
- Partner/referral MQLs: +3%
- Partner/referral MQL-to-SQL conversion: 31% → 30%
- Paid social represented 18% of MQLs last year and 34% this year

Interpretation boundary: strong evidence that mix and/or paid-social quality contributes to MQL-to-SQL deterioration, but not proof that paid social explains the entire opportunity decline or longer sales cycle.

## Evidence B — Qualification / SDR
- Formal MQL and SQL definitions unchanged
- SDR headcount flat
- Median lead-response time: 14 → 47 minutes
- SDR accepted-lead volume: +22%
- SDR-to-AE handoff SLA compliance: 91% → 72%
- Two of six SDRs account for most SLA misses

Interpretation boundary: qualification operations are under strain; unchanged definitions do not prove consistent application.

## Evidence C — AE Ramp / Capacity
- 7 AEs added over prior 9 months
- 2 fully ramped
- 3 in months 4–6
- 2 in months 1–3
- Tenured AE opportunity-to-close conversion approximately flat YoY
- Newer AEs create 18% fewer qualified opportunities per assigned SQL than tenured AEs
- Sales enablement capacity did not increase with headcount

Interpretation boundary: nominal headcount materially overstates productive capacity; ramp and enablement are relevant without eliminating upstream issues.

## Evidence D — SQL-to-Opportunity / Segment
- Enterprise SQL-to-opportunity: 37% → 35%
- Mid-market: 34% → 31%
- SMB: 29% → 18%
- SMB share of SQL volume: 30% → 41%
- Paid social contributes disproportionately to SMB volume

Interpretation boundary: opportunity deterioration is substantially concentrated in SMB and interacts with channel mix.

## Evidence E — Sales Cycle / Stage Aging
- Enterprise sales cycle: 101 → 108 days
- Mid-market: 69 → 72 days
- SMB: 41 → 61 days
- Largest increase occurs between discovery and qualified evaluation
- No material change in late-stage legal/procurement duration

Interpretation boundary: aggregate cycle is mix-sensitive, but SMB has also deteriorated materially on its own; the issue appears earlier in the selling process.

## Evidence F — Loss / Disqualification Reasons
- “No active project / researching” increased materially among SMB paid-social leads
- “Budget not established” increased moderately
- Competitive loss rate on qualified late-stage opportunities approximately flat
- No major pricing change during the period

Interpretation boundary: strengthens a quality/intent hypothesis for part of the funnel without proving all paid social is ineffective.

## Evidence G — Economics / Spend
- Marketing spend: +34% YoY
- Paid-social spend: +96%
- Blended cost per MQL: +4%
- Blended cost per SQL: +27%
- Blended cost per created opportunity: +44%
- Sales compensation and payroll expense: +21%
- New ARR: +3%

Interpretation boundary: growth investment is producing weaker opportunity economics. A defensible CAC is not supplied and must not be invented.

## Evidence H — Planning Assumptions
Annual plan assumed:
- MQL volume +20%
- MQL-to-SQL conversion roughly flat
- 5 incremental AEs
- 5-month average ramp to full productivity
- Opportunity creation +18%
- Sales cycle roughly flat

Two additional AEs were approved midyear after MQL growth exceeded plan. Approval used MQL volume as a leading capacity signal without adjusting for declining MQL-to-SQL conversion.

Interpretation boundary: evidence of a planning-model failure in which incremental capacity was approved using an activity metric whose economic yield had deteriorated.

## Evidence I — Governance / Ownership
- Marketing owns MQL volume and cost-per-MQL targets
- SDR leadership owns SQL volume
- Sales owns opportunity and bookings targets
- Finance approves incremental headcount
- No executive owner accountable for end-to-end funnel economics
- Weekly revenue review focuses primarily on totals versus plan by function
- Channel quality, conversion by cohort, and productive sales capacity are not reviewed together

Interpretation boundary: functional goals may be locally rational while the end-to-end system performs poorly; this is governance evidence, not proof of individual leadership failure.

## Missing Evidence Identified During Live Validation
The first live VP-altitude run surfaced commercially sensible questions that this version cannot fully answer:
- revenue versus plan
- revenue per AE / productive AE cohort
- ASP / ACV movement
- defensible CAC and its cost-allocation definition

These are intentionally marked as missing rather than invented. A future dataset revision should add them only after defining internally coherent assumptions and ensuring they do not make the diagnosis trivial.

## Versioning Rule
Historical exercises and assessment records must retain the dataset version used. Material changes to economics, GTM structure, funnel behavior, or conclusions should create a new dataset version rather than silently rewriting historical evidence.

## Public-Data Guardrail
This is a synthetic learning dataset. Do not add participant records, proprietary employer data, real candidate assessments, or confidential company datasets.
