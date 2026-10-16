# Comparative Financial Analysis of Leading Indian Banks (FY2024-25 to FY2025-26)

## Project overview

This beginner-level finance project compares four major Indian banks — ICICI Bank, HDFC Bank, Axis Bank, and State Bank of India (SBI) — using financial indicators for FY2024-25 (FY25) and FY2025-26 (FY26).

The project was built in Microsoft Excel. It organizes reported figures, calculates year-on-year growth, compares selected banking ratios, visualizes results, and uses a simple rank-sum method to summarize relative performance.

## Objective

Compare the four banks across four dimensions:

- **Profitability:** Net profit, Return on Assets (ROA), Return on Equity (ROE)
- **Core interest income:** Net Interest Income (NII) and NII growth
- **Asset quality:** Gross Non-Performing Assets (GNPA) and Net Non-Performing Assets (NNPA)
- **Operating efficiency:** Cost-to-income ratio

## Banks and period

- ICICI Bank
- HDFC Bank
- Axis Bank
- State Bank of India (SBI)
- Financial years ended 31 March 2025 and 31 March 2026

Figures are intended to use standalone bank data where available. Monetary values are in INR crore; ratios and growth rates are expressed as percentages.

## Metrics

| Metric | What it indicates | General interpretation |
|---|---|---|
| Net profit | Earnings after expenses, provisions, and tax | Higher is generally better; totals are affected by bank size |
| Net Interest Income (NII) | Interest earned minus interest paid | Growth can indicate stronger core interest income |
| ROA | Profit relative to average assets | Higher generally indicates stronger asset profitability |
| ROE | Profit relative to shareholders' equity | Higher generally indicates stronger accounting return on equity |
| GNPA | Gross non-performing loans relative to gross advances | Lower generally indicates better asset quality |
| NNPA | Net non-performing loans after relevant provisions/adjustments relative to net advances | Lower generally indicates lower residual problem-loan exposure |
| Cost-to-income ratio | Operating expenses relative to operating income, as reported | Lower generally indicates better operating efficiency |

## Methodology

1. Figures were recorded in an Excel `Raw Data` sheet with financial year, unit, and source information.
2. Values were linked to an `Analysis` sheet to reduce duplicate manual entry.
3. Net profit growth and NII growth were calculated using:

   `Growth (%) = (FY26 value - FY25 value) / FY25 value * 100`

4. Banks were ranked across seven measures: FY26 ROA, FY26 ROE, FY26 GNPA, FY26 NNPA, FY26 cost-to-income ratio, net profit growth, and NII growth.
5. Higher is better for ROA, ROE, and the two growth measures. Lower is better for GNPA, NNPA, and cost-to-income.
6. The seven ordinal ranks were added. A lower total score indicates a stronger result under this project's chosen method.
7. Four charts were prepared: net profit comparison, ROA vs ROE, GNPA vs NNPA, and overall score.

## Main observations from the project dataset

- SBI recorded the highest FY26 net profit and the highest net-profit growth in the group.
- ICICI Bank recorded the highest NII growth in the group.
- HDFC Bank had the lowest FY26 GNPA ratio and cost-to-income ratio in the dataset.
- ICICI Bank had the highest FY26 ROA and the lowest FY26 NNPA ratio in the dataset.
- SBI had the highest FY26 ROE, but the lowest ROA and the highest GNPA and NNPA ratios among the four banks.
- Axis Bank's net profit declined even though its NII increased; additional expense, provision, tax, and non-interest-income data would be needed to assess the reasons.
- Under the equal-weight rank-sum method, the overall scores were ICICI Bank: 13, HDFC Bank: 14, SBI: 21, and Axis Bank: 22.

These observations describe the selected dataset only. They are not a formal credit rating, investment recommendation, or definitive judgment of overall bank quality.

## Limitations

- The comparison covers four banks and two financial years only.
- Ratio definitions, averaging conventions, and reporting presentation can differ by institution.
- The overall score weights all seven metrics equally and does not account for capital adequacy, liquidity, risk-adjusted returns, bank business mix, macroeconomic conditions, or valuation.
- Absolute profit and NII are affected by bank size and business mix.
- Before public submission, retain the exact report/page or investor-disclosure reference for each figure in the workbook and reconcile any differences in restated comparative values.

## Files

The package currently contains:

- `Project_Report.docx` — editable six-page report
- `Project_Report.pdf` — PDF version of the report
- `README.md` — project overview and methodology
- `SOURCES.md` — official bank source pages
- `Interview_Notes.md` — short interview explanation and practice questions

**Add your own Excel workbook** to this folder before publishing the repository. Suggested filename: `Indian_Bank_Financial_Analysis.xlsx`. The workbook was not attached to this package, so it is not included here.

## Tools

- Microsoft Excel

No Python, SQL, Power BI, or machine learning was used in this project.

## Disclaimer

Prepared for educational purposes only. This is a descriptive comparison, not financial advice or a recommendation to buy or sell securities.
