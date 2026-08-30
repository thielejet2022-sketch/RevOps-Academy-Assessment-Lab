# Revenue Planning Dataset

**Status:** Candidate v0.1  
**Dataset ID:** RP-001-v0.1  
**Date:** 2026-08-30  
**Canonical:** No  
**Primary use:** Forecast, Capacity & Revenue Planning assessments  
**Origin:** Extracted from Forecast, Capacity & Revenue Planning Assessment Instrument Candidate v0.1 after first synthetic validation.

## Purpose
Provide a reusable, versioned operating environment for forward-looking RevOps planning exercises.

Exercises may reference this dataset but should not own or silently modify its underlying facts. Historical assessments retain the dataset version used at the time of evaluation.

## Stage 0 — Participant Baseline
- Current New ARR: **$12.0M**
- Preliminary next-year New ARR target: **$15.0M** (+25%)
- Current quota-carrying AEs: **24**
- Current fully ramped AEs: **20**
- Current average New ARR per fully ramped AE: **$600K**
- Current average sales cycle: **72 days**
- Current win rate from qualified opportunity: **22%**
- Current average new-logo ACV: **$30K**
- Current qualified pipeline created: **$54.5M**
- Marketing proposes **+30% demand-generation spend**
- Sales proposes adding **8 AEs** during Q1
- Finance's preliminary planning model assumes the eight AEs become fully productive after **four months**

## Packet A — Historical Growth and Attainment
- Prior-year New ARR: $10.4M
- Current-year New ARR: $12.0M
- Current-year plan: $13.0M
- Current-year attainment: 92%
- Current-year YoY New ARR growth: approximately 15%
- Preliminary next-year target assumes acceleration from approximately 15% actual growth to 25% growth.

## Packet B — Pipeline Coverage and Creation
- Current qualified pipeline created: $54.5M
- Current New ARR: $12.0M
- Effective qualified-pipeline-to-New-ARR yield is approximately 22%.
- To produce $15.0M at the same yield requires approximately $68.2M of qualified pipeline.
- That represents approximately 25% more qualified pipeline than current production.
- Pipeline coverage is uneven by quarter; Q1 enters the year with materially less mature pipeline than Q3/Q4 historically.

## Packet C — AE Productivity Distribution
- 20 fully ramped AEs average $600K New ARR each.
- Median fully ramped productivity is $560K.
- Top quartile averages $780K.
- Bottom quartile averages $390K.
- Four current AEs are still ramping and are not included in the $600K fully ramped average.
- Management's preliminary model uses $650K productivity for all fully ramped AEs next year.

## Packet D — Ramp Evidence
Historical cohorts hired during the last two years show:
- Month 1–2: approximately 10% of mature monthly productivity
- Month 3–4: approximately 35%
- Month 5–6: approximately 65%
- Month 7–8: approximately 85%
- Month 9+: approximately 100%
- Median time to sustained full productivity: approximately 8–9 months
- Finance's four-month full-productivity assumption is not supported by historical cohort performance.

## Packet E — Hiring Timing and Capacity
- Recruiting expects the proposed eight AEs could not all start January 1.
- Most realistic hiring schedule: 2 in January, 3 in March, 3 in May.
- Historical annual voluntary/involuntary AE attrition: 14%.
- Preliminary plan contains no explicit attrition backfill assumption.
- Sales management capacity is currently 8 AEs per frontline manager.
- No additional frontline manager is included in the proposed hiring plan.

## Packet F — Marketing / Demand Assumptions
- Marketing proposes +30% demand-generation spend.
- The plan assumes qualified pipeline rises proportionally by 30%.
- Historical relationship between incremental marketing spend and qualified pipeline has not been linear.
- Last year's +22% demand spend produced +13% qualified pipeline.
- Paid channels show declining marginal efficiency at current spend levels.
- Partner-sourced and expansion-adjacent referral programs have unused capacity but longer activation lead times.

## Packet G — Funnel and ACV Assumptions
- Current win rate: 22%.
- Preliminary plan assumes 24% win rate.
- Current ACV: $30K.
- Preliminary plan assumes $32K ACV.
- No approved pricing change currently supports the ACV increase.
- Sales leadership believes improved enterprise mix could raise ACV, but the territory/segment model has not yet been redesigned.
- No specific initiative has yet been tied to the two-point win-rate improvement.

## Packet H — Seasonality and Timing
- Historical New ARR distribution: Q1 19%, Q2 23%, Q3 27%, Q4 31%.
- Q1 is constrained by pipeline entering the year and holiday-period demand creation.
- Proposed hiring creates most incremental capacity after Q1.
- Preliminary finance model spreads the $15M target evenly by quarter.

## Packet I — Economics
- Current blended new-logo CAC: $18K.
- Current new-logo ACV: $30K.
- Gross margin: 78%.
- CAC increased 17% this year while ACV increased 2%.
- Proposed marketing and sales headcount plan increases acquisition spending approximately 28% before considering additional management or enablement capacity.
- Finance has not yet modeled payback sensitivity under different productivity/ramp outcomes.

## Packet J — Enablement and Management Capacity
- Current sales enablement team: 2 people.
- The team supported 9 AE hires this year and reported onboarding capacity constraints.
- Time-to-first-qualified-opportunity worsened by approximately three weeks in the most recent cohort.
- Sales leadership believes onboarding can absorb eight more AEs without incremental resources but has not supplied a capacity model.

## Packet K — Customer / Market Context
- Core market growth estimate: 8–10%.
- Company believes share gains are possible.
- Competitive win/loss rates are broadly stable.
- No major new product launch is committed before Q3.
- Enterprise segment has stronger ACV but a materially longer sales cycle than SMB/MM.

## Packet L — Executive Constraints
- CEO views 25% growth as strategically important but has said the operating plan must be credible.
- Board has not yet approved the final annual plan.
- CFO is willing to fund growth but wants explicit productivity gates before releasing all proposed hiring/spend.
- CRO wants hiring authorization immediately because recruiting lead time is long.
- CMO needs Q1 budget commitments within three weeks.

## Packet M — Alternative Capacity Levers
Potential levers under discussion:
- improve productivity of current bottom/middle cohorts;
- improve ramp through enablement;
- increase qualified pipeline through non-paid channels;
- change segment mix;
- improve conversion;
- increase ACV through packaging/pricing or mix;
- add AEs;
- reduce attrition;
- redesign territories or books of business.

None is guaranteed. Each requires assumptions, timing, ownership, and evidence.

## Default Planning Shock
At the end of Q1:
- qualified pipeline creation is 12% below planning assumption;
- fully ramped AE productivity is 6% above plan;
- CRO wants to accelerate remaining AE hires because productivity looks strong;
- CFO wants to freeze hiring because pipeline is behind.

The shock may be replaced in future exercise variants, but any scored run must record the exact dataset and shock version used.

## Design Characteristics
This dataset deliberately contains:
- a strategic growth target that is not automatically an operating forecast;
- unsupported improvement assumptions across multiple drivers;
- ramp and hiring-timing friction;
- seasonality;
- attrition exposure;
- demand-efficiency uncertainty;
- management and enablement constraints;
- acquisition-economics pressure;
- legitimate executive disagreement;
- multiple potentially valid plans rather than one answer key.

## Versioning Rules
- Minor corrections that do not affect analytical conclusions may retain the version with documented correction history.
- Changes to values or facts that can alter participant reasoning require a dataset revision.
- Material changes to economics, GTM structure, planning challenge, or likely conclusions require a major dataset version.
- Historical assessment records must retain `RP-001-v0.1` when that was the environment used.
- Exercises reference this dataset by ID/version and must not silently override facts.

## Governance
This dataset is **Candidate only**.

Extraction from the A2 instrument corrects the working architecture so the dataset can evolve independently from the exercise. It does not make the dataset canonical or validate its realism, difficulty, scoring behavior, or hiring relevance.

Canonical promotion requires JET's explicit review and approval of a specific identifiable Candidate.
