# Tata Motors FY25 Relative Valuation – README

## Overview

This repository presents a comprehensive, segment-linked **relative valuation model** for Tata Motors, integrating both Indian and global automotive OEM benchmarks. Built on FY25 projections and professional comps methodologies, it provides both whole-company and SOTP (Sum of the Parts) valuations, ensuring segment-level transparency. Key outlier adjustments and the latest peer data (including Hyundai’s India listing) deliver a rigorous, defendable equity valuation framework ideal for equity research, job applications, or investing.

## Key Features

- **Peer Selection**
  - **Indian Peers:** Maruti Suzuki (MARUTI), M&M (M&M), Force Motors (FORCEMOT), Ashok Leyland (ASHOKLEY), Hyundai (HYUNDAI)
  - **Exclusions**: Two-wheeler specialists Bajaj Auto and Eicher Motors for sector comparability
  - **Global Peers:** Mercedes, Volkswagen, Toyota, BMW, Volvo, GM, Hyundai (global), Ford (all based on FY24 results & translated to INR)
  - **Note:** Hyundai now bridges Indian/global groups with its BSE/NSE listing since Oct 2024

- **Multiples Used:**
  - EV/Revenue, EV/EBITDA, P/E—extracted for each peer group
  - Blended means and medians calculated by 60:40 Indian:global for overall fair value

- **Segment-Level (SOTP) Valuation:**
  - JLR: Valued with global peer multiples (captures international luxury positioning)
  - CV and PV segments: Indian peer multiples (reflect domestic operations)
  - Others: Uses a conservative/blended multiple
  - Net debt subtracted at the firm level

- **Implied Share Prices & Upside:**
  - Full implied price table for each method ([see Summary sheet]):
    - Indian Only: ₹2,508 (mean)
    - Global Only: ₹943 (mean)
    - Blended: ₹1,901 (mean)
    - **SOTP Integrated Price:** ₹1,643.04 (segment-weighted)
  - **CMP as of June 30, 2025:** ₹688
  - Upside from CMP: 139%–176% depending on method

- **Sensitivity & Transparency:**
  - Mean and median (and full range) shown for each multiple set
  - SOTP and whole-company outputs side by side
  - Outlier handling and major assumptions fully disclosed

## Usage

- **For Investors:** Spot Tata Motors’ valuation gap versus listed benchmarks ~ dynamically.
- **For Recruiters/Interviewers:** Review full analyst workflow, outlier screens, scenario/sensitivity logic, and professional summary.
- **For Analysts/Students:** Adapt framework for any diversified major (with SOTP or comps focus).

## Files

- **Tata-Motors-Relative-Valuation-2.xlsx**
  - `Summary`: Peer sets, multiples, implied price tables & SOTP output
  - `Indian Comps` / `Global Comps`: Raw trading multiples and calculated, outlier-adjusted group averages
  - `SOTP (Integrated)`: Segment-wise calculations (JLR, CV, PV, Others), peer-multiple mapping, EV, equity value, and per-share outputs

- **Data Sheets**
  - Full P&L, BS, and segment splits for all covered peers (Indian and global)

## Key Calculation Formulas

- **Implied EV (EV/EBITDA):**
   - EV = FY25E EBITDA × Peer Multiple
- **Implied Share Price:**
   - Implied Price = (EV - Net Debt) / Shares Outstanding
- **SOTP Segment Value Example:**
   - EV (JLR) = JLR EBITDA × Global Mean EV/EBITDA
(Repeat for each segment; SOTP price is sum after net debt)

## Tickers Used

| Company           | Exchange / Country            | Ticker Symbol          |
|-------------------|------------------------------|------------------------|
| **Indian Peers**  |                              |                        |
| Tata Motors       | NSE / BSE (India)            | TATAMOTORS / 500570    |
| Maruti Suzuki     | NSE / BSE (India)            | MARUTI / 532500        |
| M&M               | NSE / BSE (India)            | M&M / 500520           |
| Force Motors      | NSE / BSE (India)            | FORCEMOT / 500033      |
| Ashok Leyland     | NSE / BSE (India)            | ASHOKLEY / 500477      |
| Hyundai India     | NSE / BSE (India)            | HYUNDAI / 544274       |
| **Global Peers**   |                              |                        |
| Mercedes-Benz     | Xetra / Germany               | MBG / DAIMLER AG       |
| Volkswagen Group  | Xetra / Germany               | VOW3                   |
| Toyota Motor Corp | Tokyo Stock Exchange / Japan | 7203                   |
| BMW               | Xetra / Germany               | BMW                    |
| Volvo Cars        | Nasdaq Stockholm / Sweden     | VOLCAR-B               |
| General Motors    | NYSE / USA                   | GM                     |
| Hyundai Motor Co. | Korea Exchange / South Korea | 005380                 |
| Ford Motor Co.    | NYSE / USA                   | F                      |


## Assumptions/Disclosures

- **Peer multiples:** Calculated as of July 2025 based on latest FY24 (global) or FY25E (Indian).
- **Shares outstanding:** 368.25 crore (Tata Motors, FY25E)
- **Net debt:** Estimated at ₹30,706 Cr (from BS projections)
- **Multiples weighting:** Blended 60:40 for realism
- **Exclusions:** Two-wheeler specialists omitted from averages for fair comparability
- **Hyundai:** Treated as Indian for peer linkage
- **Segment splits:** Approximated based on last reported TCL segmental disclosure

## How to Update

- Drop new peer data into the `Indian Comps` or `Global Comps` tab.
- Update Tata Motors’ FY estimate and segment splits in `Summary`.
- All implied prices and SOTP outcomes update automatically.

## License

Open for academic, non-commercial use. Please reference or attribute if reusing major logic or visuals.

**Contact:**  
For questions, feedback, or model customization, DM the repo owner or connect on LinkedIn.  
*Made for deep-dive equity research and professional transparency.*

*(Last updated: July 31, 2025)*


