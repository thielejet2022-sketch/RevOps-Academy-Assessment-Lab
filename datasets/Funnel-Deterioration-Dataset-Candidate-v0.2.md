# Funnel Deterioration Dataset

**Status:** Candidate v0.2  
**Date:** 2026-08-30  
**Canonical:** No  
**Dataset ID:** FD-001-v0.2  
**Supersedes for testing:** FD-001-v0.1  
**Intended use:** RevOps Academy and Assessment Lab exercises

## Revision Purpose
Extend FD-001-v0.1 using findings from the first live VP-altitude validation run. This version adds economic and productivity evidence that a commercially capable participant reasonably requested but v0.1 could not answer.

The additions are designed to create diagnostic branches rather than reveal a single obvious answer.

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

Interpretation boundary: mix and/or paid-social quality contributes to MQL-to-SQL deterioration, but this does not explain the entire system by itself.

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

Interpretation boundary: nominal headcount materially overstates productive capacity; ramp and enablement matter without eliminating upstream issues.

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

Interpretation boundary: aggregate cycle is mix-sensitive, but SMB also deteriorated materially on its own; the issue appears earlier in the selling process.

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
- New ARR: +3% YoY

Interpretation boundary: growth investment is producing weaker opportunity economics.

## Evidence H — Planning Assumptions
Annual plan assumed:
- MQL volume +20%
- MQL-to-SQL conversion roughly flat
- 5 incremental AEs
- 5-month average ramp to full productivity
- Opportunity creation +18%
- Sales cycle roughly flat
- New ARR growth +15%

Two additional AEs were approved midyear after MQL growth exceeded plan. Approval used MQL volume as a leading capacity signal without adjusting for declining MQL-to-SQL conversion.

Interpretation boundary: additional capacity was approved using an activity metric whose economic yield had deteriorated.

## Evidence I — Governance / Ownership
- Marketing owns MQL volume and cost-per-MQL targets
- SDR leadership owns SQL volume
- Sales owns opportunity and bookings targets
- Finance approves incremental headcount
- No executive owner accountable for end-to-end funnel economics
- Weekly revenue review focuses primarily on totals versus plan by function
- Channel quality, conversion by cohort, and productive sales capacity are not reviewed together

Interpretation boundary: functional goals may be locally rational while the end-to-end system performs poorly; this is governance evidence, not proof of individual leadership failure.

## Evidence J — Revenue vs Plan
- Annual plan expected New ARR growth of +15% YoY at this point in the year
- Actual New ARR growth: +3% YoY
- Enterprise New ARR is approximately on plan
- Mid-market New ARR is modestly below plan
- SMB New ARR is materially below plan
- The company is therefore below the aggregate New ARR plan despite positive YoY growth

Interpretation boundary: positive revenue growth does not mean the growth investment is performing to plan. Segment performance matters, and the evidence does not by itself establish why SMB is below plan.

## Evidence K — ASP / ACV
Average new-logo ACV:
- Enterprise: +4% YoY
- Mid-market: +2% YoY
- SMB: -3% YoY
- Blended new-logo ACV: approximately flat YoY because segment mix shifted toward SMB
- No major list-price reduction occurred

Interpretation boundary: ASP/ACV compression is not the primary explanation for the large deterioration in opportunity economics, but mix and modest SMB ACV pressure contribute.

## Evidence L — AE Revenue Productivity
Use cohort-aware productivity rather than dividing total revenue by nominal headcount.

- Fully ramped tenured AEs: New ARR per fully productive AE is approximately flat YoY
- 2 newly added AEs now fully ramped: currently produce about 92% of the tenured-AE New ARR run rate
- 3 AEs in months 4–6: about 63% of tenured-AE New ARR run rate
- 2 AEs in months 1–3: about 28% of tenured-AE New ARR run rate
- Aggregate New ARR per employed AE is down approximately 17% YoY because the denominator includes a larger partially ramped cohort

Interpretation boundary: a simple revenue-per-head metric can make a normal ramp cohort look like broad rep failure. The newer cohort is not yet fully productive, but the evidence also does not prove that the hiring profile is sound.

## Evidence M — CAC Definition and Direction
For this synthetic dataset, Finance defines New Logo CAC as:

> acquisition-related Marketing expense + SDR compensation + new-logo AE compensation attributable to the period, divided by new logos won in the same measurement framework.

Under that consistent internal definition:
- Blended New Logo CAC: +31% YoY
- Enterprise CAC: +8%
- Mid-market CAC: +17%
- SMB CAC: +49%
- CAC payback period has lengthened materially in SMB

The dataset does not provide a fully loaded corporate CAC including unrelated G&A, Customer Success, or implementation expense.

Interpretation boundary: CAC deterioration is real under the stated definition and concentrated in SMB. Participants should challenge the definition when relevant rather than assuming all companies calculate CAC identically.

## Evidence N — Discovery Support / Enablement Capacity
Added to test a hypothesis surfaced during live validation rather than reward it automatically.

- Demo request volume from SMB increased 38% YoY
- Solutions-consulting headcount unchanged
- Median time from discovery to scheduled technical/demo support increased 2.5 → 4.5 business days for SMB
- However, opportunities receiving technical/demo support do not show a material decline in post-demo conversion versus last year
- Sales-content engagement among SMB opportunities is approximately flat

Interpretation boundary: support capacity is strained and may contribute to elapsed time, but available evidence does not support treating demo or enablement capacity as the primary cause of conversion deterioration.

## Cross-Evidence Tensions Deliberately Preserved
This dataset should not collapse into one villain:
- Paid social clearly deteriorated, but qualification operations also weakened.
- SMB is the largest problem area, but sales capacity is partially ramped rather than simply poor.
- Revenue is growing, but far below plan and at worse economics.
- ACV is not collapsing enough to explain the problem.
- Demo/support capacity is strained, but the conversion evidence does not establish it as the principal cause.
- CAC is worsening, but its definition must be understood.
- Governance and planning choices help explain why investment continued despite deteriorating yield.

## Dataset Validation Goals for v0.2
Future live runs should test whether participants:
1. distinguish positive YoY revenue growth from performance versus plan;
2. avoid misreading aggregate revenue per AE without cohort/ramp context;
3. use CAC only after understanding its definition;
4. distinguish ACV/mix effects from conversion effects;
5. update or reject a plausible enablement-capacity hypothesis when evidence is mixed;
6. make a reversible resource-allocation decision before every uncertainty is resolved;
7. identify the planning/governance failure at VP altitude.

## Versioning Rule
Historical exercises and assessment records must retain the dataset version used. Material changes to economics, GTM structure, funnel behavior, or conclusions require a new dataset version rather than silently rewriting historical evidence.

## Public-Data Guardrail
This is a synthetic learning dataset. Do not add participant records, proprietary employer data, real candidate assessments, or confidential company datasets.
