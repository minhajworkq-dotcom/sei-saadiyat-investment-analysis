# sei-saadiyat-investment-analysis
# Sei Saadiyat: Off-Plan Real Estate Investment Analysis

An Excel-based investment analysis of **Sei Saadiyat** (Aldar Properties, Saadiyat Cultural District, Abu Dhabi). It covers unit-level extraction, pricing benchmarks, rental yield, payment-plan cash flow, appreciation scenarios to 2040, weighted scoring and risk assessment, ending in a single investment verdict.

**File:** [`Sei_Saadiyat_Investment_Analysis.xlsx`](Sei_Saadiyat_Investment_Analysis.xlsx)
**Analysis date:** 15 September 2026
**Tools:** Excel (formula-driven dashboards, scenario inputs, charts)

## What's inside

| Layer | Sheets | Purpose |
|---|---|---|
| Data | `RAW_DATA` (778 rows), `source_data` (513 units), `SOURCE_DATA_01` | Extraction from developer documents, cleaned unit table, benchmark inputs |
| Inputs | `PRICE_INPUTS`, `RENTAL_INPUTS`, `PAYMENT_INPUTS`, `APPRECIATION_INPUTS`, `INVESTMENT_INPUTS`, `ADVANTAGE_INPUTS`, `RISK_INPUTS` | Live calculation sheets and scenario assumptions that drive the dashboards |
| Dashboards | `PROJECT_OVERVIEW`, `PAYMENT_ANALYSIS`, `PRICE_ANALYSIS`, `RENTAL_ANALYSIS`, `APPRECIATION_ANALYSIS`, `ADVANTAGE_ANALYSIS`, `RISK_ANALYSIS`, `INVESTMENT_ANALYSIS`, `CONCLUSION` | 42 charts across 9 dashboards, from KPIs to the final recommendation |
| Documentation | `START_HERE`, `README_SOURCES` | Navigation, methodology, source register, assumptions and limitations |

Change an assumption on any `*_INPUTS` sheet and the dashboards recalculate.

## Approach

1. **Extract** unit numbers, types, sizes and payment terms from the developer's floor plans and factsheet.
2. **Benchmark** price per sq ft against comparable Saadiyat listings (Mamsha Gardens, The Row Saadiyat, Louvre Residences).
3. **Model** gross rental yield, the 5/45/50 payment plan, and 2030 and 2040 value scenarios. Rent starts only after the Q4 2030 handover.
4. **Score** each unit type on a weighted model: capital appreciation 25%, rental return 20%, pricing 15%, location 15%, market fundamentals 10%, developer strength 10%, payment plan.
5. **Stress-test** the case with a probability-impact risk matrix and mitigations.

## Headline outputs

- Overall investment score: **86.2 / 100**, verdict *Recommended, long-term investment*
- Entry price from **AED 2.95M**; average price about **AED 4,016 / sq ft**
- Gross yield range **2.5% to 3.2%**; modeled appreciation **21.6% by 2030** and **98.0% by 2040**
- Best-fit product: **2BR** (highest modeled yield, risk-adjusted score of 83.3 / 100)
- Key risks: no income before handover, 50% of price due at handover, results depend on scenario assumptions

## Data notes and limitations

- The developer factsheet gives two different unit counts (**513** and **778**). Both are retained and flagged; unit-mix calculations use the 513 extracted units.
- Comparable prices are **asking prices** from a 15 Sep 2026 snapshot, not transaction prices.
- Forecasts are analytical scenarios, not official projections.
- Prepared for research and portfolio purposes only. Not financial or investment advice.
- Project data comes from developer marketing documents. This repo contains the analysis and extracted fields, not the original brochures.

## Author

**Minhaj KP**, Dubai, UAE · [GitHub](https://github.com/minhajworkq-dotcom)
