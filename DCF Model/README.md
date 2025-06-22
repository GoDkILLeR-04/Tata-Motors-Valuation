# Discounted Cash Flow (DCF) Model

This repository contains a Discounted Cash Flow (DCF) model for valuing businesses, projects, or assets. The DCF approach estimates the value of an investment based on its expected future cash flows, which are discounted to the present value using a chosen discount rate.

## Features

- **Multiple Projection Methods:** Supports three distinct approaches for forecasting future cash flows.
- **Forecast of Free Cash Flows (FCF):** Input historical and projected financials to estimate future FCFs.
- **Discounting to Present Value:** Apply a discount rate (typically WACC) to bring future FCFs to present value.
- **Terminal Value Calculation:** Estimate the value beyond the explicit forecast period.
- **Sensitivity Analysis:** Assess how changes in key assumptions (growth rates, WACC, etc.) impact valuation.
- **User-Friendly Interface:** Easy-to-use spreadsheet or script for quick scenario analysis.

## Projection Methods

This DCF model allows you to choose from three projection methods for estimating future cash flows:

1. **CAGR_Model Projection:**  
   Uses management’s most likely scenario based on current trends and assumptions.

2. **CAGR_Model Projection:**  
   Assumes optimistic growth and margin improvements, reflecting a best-case scenario.

3. **Segment_Model Projection:**  
   Incorporates conservative estimates, considering potential risks and downturns.

4. **Scenario_Inputs Projection:**  
   Incorporates conservative estimates, considering potential risks and downturns.

You can input assumptions for each scenario to see how the valuation changes under different outlooks.

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel)

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/dcf-model.git
    ```
2. **Open the model:**
    - For the spreadsheet: Open `DCF_Model.xlsx`

3. **Input Assumptions:**
    - Revenue, EBIT, CAPEX, NWC changes, etc.
    - Discount rate (WACC)
    - Terminal growth rate
    - Choose and fill out assumptions for each projection method

4. **Review Outputs:**
    - Present value of forecasted cash flows for all scenarios
    - Terminal value and present value
    - Implied enterprise and equity value

5. **Adjust Assumptions:** Use built-in sensitivity tables or sliders to test different scenarios.

## Example

Here’s a simplified DCF formula for reference:

```
DCF = FCF1/(1+r)^1 + FCF2/(1+r)^2 + ... + FCFn/(1+r)^n + TV/(1+r)^n
```
Where:
- `FCF` = Free Cash Flow in each forecast period
- `r` = Discount rate (WACC)
- `TV` = Terminal Value

## Files issue or submit a pull request for impr

- `DCF_Model.xlsx` – Main spreadsheet model
- `README.md` – This file

## Contributing

Contributions are welcome! Please open anovements.
