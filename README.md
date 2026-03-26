# ⚠️ WORK IN PROCESS ⚠️ YETI Holdings — 3-Statement Financial Model & DCF Valuation w/ AI Tooling Usage

## Overview
A fully integrated 3-statement financial model built in Excel for YETI Holdings, Inc. (NYSE: YETI), covering 5 years of historical data (2021–2025) and a 5-year forecast (2026–2030) with a discounted cash flow valuation. Built independently using YETI's public 10-K filings, with AI tooling (Claude by Anthropic) used throughout to audit formula logic, catch errors, and pressure-test assumptions across all 590 formulas and four linked sheets, and (ChatGPT by OpenAI) for troubleshooting issues, QA, & refining knowledge as I built it.

---

## What's Included
- **Income Statement** — Revenue, gross profit, EBIT, and net income driven by margin assumptions
- **Balance Sheet** — Fully linked and balanced across all 10 years; working capital modeled via DSO, DIO, and DPO
- **Cash Flow Statement** — Built from scratch and tied to both the Income Statement and Balance Sheet
- **Assumptions Tab** — All forecast drivers (growth rates, margins, capex %, D&A %) consolidated into a single place
- **DCF & Valuation** — Unlevered FCF build, Gordon Growth terminal value, EV/EBITDA cross-check, and sensitivity analysis

---

## Valuation Output

| Metric | Value |
|---|---|
| WACC | 9.0% |
| Terminal Growth Rate | 2.5% |
| Implied Share Price (Gordon Growth) | $41.12 |
| Implied Share Price (EV/EBITDA) | $46.88 |
| Current Price (as of model date) | $33.50 |
| Implied Upside | ~22.7% |

---

## How I Used AI
Rather than using AI to build the model for me, I used it as an auditing and learning tool:

- **Formula auditing** — used AI to verify logic across all 590 formulas, checking cross-sheet links, and that the balance sheet balanced every year
- **Error identification** — caught a sign error in the EV/EBITDA implied share price (double-negative on net debt) and a stale hardcoded value in the trailing EV/EBITDA reference cell
- **Conceptual Q&A** — used it to deepen understanding of NOPAT, unlevered FCF, and why terminal value dominates DCF output (~75% of EV in this model)
- **Assumption pressure-testing** — stress-tested forecast drivers like DSO, DIO, DPO, and margin assumptions against YETI's historical trends

---

## Skills Demonstrated
- 3-statement model construction and cross-sheet formula linking
- Working capital modeling (DSO / DIO / DPO)
- DCF valuation methodology (NOPAT, UFCF, terminal value)
- Sensitivity analysis across WACC and terminal growth rate
- Reading and interpreting 10-K filings (YETI's public 10-K Data)

---

## Methodology
Developed using YETI's public 10-K filings as the primary data source. Built with guidance from financial modeling tutorials and AI tools (Claude by Anthropic, & ChatGPT by OpenAI) for auditing and troubleshooting. All forecast assumptions, investment drivers, and conclusions are my own.

---

## Tools
Microsoft Excel · YETI Official (10-K filings) · Claude by Anthropic (audit & QA) · ChatGPT by OpenAI (troubleshooting & QA)

---
