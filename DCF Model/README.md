# Tata Motors FY25 Discounted Cash Flow (DCF) Model – README

## Overview

This repository contains a robust Discounted Cash Flow (DCF) valuation model for Tata Motors, constructed to investment banking and equity research standards. The model incorporates four independent revenue forecasting approaches, scenario analysis, segment-level insights, and sensitivity tables, offering a transparent and flexible toolkit for understanding Tata Motors’ intrinsic value as of FY25.

## Key Features

- **Multi-Method Revenue Forecasting**:
  - Segment-based (JLR, CV, PV, Others; bottom-up build)
  - Scenario-based (Best/Base/Worst; custom growth rates)
  - Historical CAGR-based projection
  - Linear Regression trend modeling
- **Assumptions Fully Disclosed**:
  - WACC, terminal growth, EBIT margin, D&A, CapEx, and NWC are clearly outlined and editable
- **Professional DCF Structure**:
  - Forecast period: FY25–FY29, with separate DCF sheets for each scenario
  - Full build: EBIT, taxes, D&A, CapEx, NWC, FCF, terminal value, PV calculations
  - Equity value, EV, and per-share valuations for each method
- **Sensitivity Analysis**:
  - Dynamic tables showing implied share price ranges for variations in WACC and terminal growth
- **Scenario Comparison Table**:
  - Instantly compare Best/Base/Worst, CAGR, and regression outcomes side by side

## Model Outputs

- **Implied Share Prices (All Methods):**
  - Segment-Based: ₹1,371
  - Scenario – Best: ₹1,527
  - Scenario – Base: ₹1,273
  - Scenario – Worst: ₹899
  - CAGR-Based: ₹1,273
  - Linear Regression: ₹1,492
- **Market Price Benchmark**:
  - CMP as of July 2025: ₹687
  - Upside/downside metrics shown for each method

## File Structure

- **Tata-Motors-DCF.xlsx**
  - `Summary`: Top-down review, major assumptions, key outputs, and sensitivity heatmaps
  - `DCF-Segment`, `DCF-Best`, `DCF-Base`, `DCF-Worst`, `DCF-CAGR`, `DCF-LINEAR REGRESSION`: Full valuation logic, FCF and terminal value breakdowns, share price outputs
  - `Segment`: Revenue breakdown by JLR, CV, PV, Others (with forecast details)
  - `WACC`, `CapEx & NWC Forecast`, `IS`, `BS`, `CFS`: Model underpinnings, historicals, and critical assumptions

## Key Calculation Formulas

- **DCF Enterprise Value:**
   - EV = Σ (FCF_t / (1+WACC)^t) + (Terminal Value / (1+WACC)^n)
- **Equity Value:**
   - Equity Value = Enterprise Value + Cash – Debt
- **Implied Share Price:**
   - Implied Share Price = Equity Value / Shares Outstanding

## Assumptions/Notes

- **No actuals from FY25** are used: all projections were made using the latest available financial data up to FY24, maintaining pure forward-looking logic.
- All scenario rates, margin estimates, and working capital/capex ratios are editable on the relevant sheets.
- Market price and number of shares as per data available July 2025.
- Shares outstanding: ~383.25 crore (FY25E)
- WACC default: ~11.2%; Terminal growth default: 4%
- All currency values in ₹ crore unless otherwise stated.

## How to Update

- Edit revenue/EBIT margin forecasts in the relevant sheet of each approach.
- Adjust major assumptions directly in the `Summary` or `Assumptions` sheets.
- Update market price and share count in the `Summary` sheet for current upside stats.
- All calculated outputs, sensitivity tables, and scenario results will update automatically.

## License

Open for academic, non-commercial use. If you adapt for publication or commercial purposes, please attribute the structure and formulas.

**Contact:**  
For feedback, questions, or custom model requests, reach out via LinkedIn or GitHub issues.

*(Last updated: July 31, 2025)*

