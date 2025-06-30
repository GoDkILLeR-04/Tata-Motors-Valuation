# Relative Valuation Model for Stocks

This repository provides a **Relative Valuation Model** for stocks, allowing users to estimate the fair value of a company by comparing it to similar companies using key financial multiples.

## What is Relative Valuation?

Relative valuation, also known as **comparable company analysis (CCA)** or **peer group analysis**, is a method of valuing a company by comparing its valuation ratios to those of similar publicly traded companies. This approach is widely used by analysts and investors to assess whether a stock is undervalued or overvalued relative to its peers.

## Key Features

- **Selection of Peer Companies:** Input or select a group of comparable companies within the same industry or sector.
- **Valuation Multiples:** Analyze and compare valuation metrics such as:
  - Price/Earnings (P/E)
  - Price/Sales (P/S)
  - EV/EBITDA
  - And others as needed
- **Customizable Data Input:** Enter financial data manually or link to data sources (e.g. Yahoo Finance, Bloomberg, APIs).
- **Summary Output:** Calculates implied valuation ranges for the target company based on peer multiples.
- **Sensitivity Analysis:** Test the impact of using different peer groups or adjusting multiples.

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel),

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/relative-valuation-model.git
    ```
2. **Open the model:**
    - For the spreadsheet: Open `Relative_Valuation_Model.xlsx` (or the Google Sheets link if provided).
    - For the Python script: Navigate to `/src` and run `python relative_valuation.py`.

3. **Input Data:**
    - Enter the financial metrics for your target company and selected peers (revenue, EBITDA, net income, etc.).
    - Fill in the current market prices, enterprise values, and shares outstanding as needed.

4. **Choose Multiples:**
    - Select which valuation multiples to use for comparison.
    - The model will calculate the average, median, or custom percentile for each multiple across the peer group.

5. **Review Output:**
    - The model will output an implied valuation range for your target stock based on each multiple.
    - Sensitivity tables help you see how results change with different peer selections or adjustments.

## Example

Suppose your target company has $100M in EBITDA, and the median EV/EBITDA multiple for the peer group is 10x:

```
Implied Enterprise Value = 10 x $100M = $1,000M
```
Similar calculations are performed for other multiples to triangulate a reasonable value range.

## Files

- `Relative_Valuation_Model.xlsx` – Main spreadsheet model
- `/src/relative_valuation.py` – Optional Python implementation
- `README.md` – This file

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

