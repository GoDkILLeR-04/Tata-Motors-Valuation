# Sum of the Parts (SOTP) Valuation Model for Stocks

This repository provides a **Sum of the Parts (SOTP) Valuation Model** for stocks, enabling users to value a diversified company or conglomerate by separately valuing each of its business segments and aggregating their values.

## What is SOTP Valuation?

Sum of the Parts (SOTP) valuation is a method used to value a company by assessing the value of each of its individual business units or subsidiaries, and then adding them together to arrive at the total enterprise value. This approach is particularly useful for conglomerates or companies with distinct divisions operating in different industries.

## Key Features

- **Segment-by-Segment Valuation:** Value each business segment using the most appropriate valuation method (DCF, relative valuation, precedent transactions, etc.).
- **Aggregation of Values:** Sum the individual segment values to estimate the company’s total enterprise value (EV).
- **Adjustments:** Account for corporate assets, liabilities, and other adjustments (e.g., cash, debt, minority interests, non-operating assets).
- **Sensitivity Analysis:** Analyze how changes in segment assumptions impact the total valuation.
- **User-Friendly Structure:** Easy-to-follow spreadsheet or script for customizing segment inputs and assumptions.

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel), [Google Sheets](https://sheets.google.com/),  
  _or_
- Python 3.x if using the script-based model (see `/src` directory)

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/sotp-valuation-model.git
    ```
2. **Open the model:**
    - For the spreadsheet: Open `SOTP_Valuation_Model.xlsx` (or the Google Sheets link if provided).
    - For the Python script: Navigate to `/src` and run `python sotp_valuation.py`.

3. **Input Segment Data:**
    - Enter financial and valuation data for each business segment.
    - Choose the valuation approach for each segment (e.g., apply different multiples, DCFs, or asset values as appropriate).
    - Enter corporate-level adjustments (cash, debt, investments, etc.).

4. **Review Output:**
    - The model will sum the values of all segments and apply adjustments to arrive at the implied equity value.
    - Sensitivity tables allow you to see how changes in segment values impact the overall valuation.

## Example

Suppose a company has two segments:
- **Segment A:** Valued at $1,200M (DCF)
- **Segment B:** Valued at $800M (Relative Valuation)

Corporate-level adjustments:
- **Cash:** $100M
- **Debt:** $400M

The SOTP equity value is:
```
Total Segment Value = $1,200M + $800M = $2,000M
Adjusted Equity Value = $2,000M + $100M (Cash) - $400M (Debt) = $1,700M
```

## Files

- `SOTP_Valuation_Model.xlsx` – Main spreadsheet model
- `/src/sotp_valuation.py` – Optional Python implementation
- `README.md` – This file

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

