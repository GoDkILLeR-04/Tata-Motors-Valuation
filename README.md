# Tata Motors Stock Valuation 

This repository provides a suite of stock valuation models **Discounted Cash Flow (DCF)**, **Relative Valuation**, and **Sum of the Parts (SOTP)** to help you estimate the intrinsic and relative value of a publicly traded company. Whether you want to analyze a single-segment business or a diversified conglomerate, this toolkit offers practical, customizable templates for your analysis.

---

## Overview of Valuation Methods

### 1. Discounted Cash Flow (DCF)

DCF valuation estimates a company's intrinsic value by projecting its future free cash flows and discounting them to the present using an appropriate discount rate (typically the Weighted Average Cost of Capital, or WACC).  
- **Best for:** Companies with predictable cash flows.
- **Key Inputs:** Revenue growth, margins, capital expenditures, working capital changes, discount rate, terminal growth rate.

### 2. Relative Valuation

Relative valuation compares the target company’s valuation multiples (such as P/E, EV/EBITDA, P/B) to those of similar companies in its peer group. This method assesses whether a stock is undervalued or overvalued relative to comparable businesses.  
- **Best for:** Benchmarking against industry peers.
- **Key Inputs:** Peer group selection, financial metrics, multiples.

### 3. Sum of the Parts (SOTP)

SOTP valuation is used for diversified firms or conglomerates. Each business segment or subsidiary is valued independently (using DCF, relative, or asset-based methods) and then aggregated, with corporate-level adjustments (like cash, debt, and minority interests) to determine total equity value.  
- **Best for:** Multi-segment companies with distinct businesses.
- **Key Inputs:** Segment data, choice of valuation method per segment, corporate adjustments.

---

## Directory Structure

```
/Tata Motors-valuation
│
├── README.md                    # This file
│
├── DCF Model/
│   ├── DCF_Model.xlsx
│   └── README.md
│
├── Relative Valuation Model/
│   ├── Relative_Valuation_Model.xlsx
│   └── README.md
│
├── Sum of the Parts(STOP) Model/
│   ├── SOTP_Valuation_Model.xlsx
│   └── README.md
│
└── src/
    ├── dcf_model.py
    ├── relative_valuation.py
    └── sotp_valuation.py
```

---

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel)  
 
### How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/stock-valuation-models.git
    ```

2. **Select a Model:**
    - For **DCF analysis**, go to `/dcf/DCF_Model.xlsx`.
    - For **Relative Valuation**, go to `/relative/Relative_Valuation_Model.xlsx`.
    - For **SOTP Valuation**, go to `/sotp/SOTP_Valuation_Model.xlsx`.

3. **Input Data:**
    - Fill in the required financial and market data for the target company.
    - For SOTP, provide segment-specific inputs and any holding-level adjustments.

4. **Review Outputs:**
    - Each model provides implied valuation outputs and summary tables.
    - Use built-in sensitivity analysis features to test different scenarios.

---

## Example Scenarios

- **DCF Example:** Project free cash flows for five years, apply a terminal growth rate, and discount at WACC to get intrinsic value.
- **Relative Example:** Compare your target’s EV/EBITDA to peers, then apply the median multiple to your target’s EBITDA.
- **SOTP Example:** Value each segment using the most appropriate method, sum the parts, and adjust for cash and debt to get total equity value.

---

## When to Use Each Model

| Model                | Best For                                      |
|----------------------|-----------------------------------------------|
| **DCF**              | Companies with stable, predictable cash flows |
| **Relative**         | Peer benchmarking and market positioning      |
| **SOTP**             | Diversified firms or conglomerates            |

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

