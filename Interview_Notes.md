# Interview notes — Comparative Financial Analysis of Leading Indian Banks

## 45–60 second project explanation

“I completed a beginner-level comparative financial analysis of ICICI Bank, HDFC Bank, Axis Bank, and SBI using Microsoft Excel. I collected FY2024-25 and FY2025-26 figures from bank annual reports and investor disclosures, organized them in a raw-data sheet, linked them to a comparison sheet, calculated net-profit and NII growth, and created four charts. I compared profitability, asset quality, and operating efficiency using ROA, ROE, GNPA, NNPA, and cost-to-income. I also built a simple equal-weight rank-sum score. Under that method ICICI ranked first, closely followed by HDFC. The main lesson was that no single metric is enough: SBI led on profit scale and ROE, ICICI on NII growth and ROA, and HDFC on GNPA and cost-to-income. The model is descriptive and has limitations because bank-reported ratios and business mixes can differ.”

## Likely questions

### Why did you choose these four banks?
They are large, familiar Indian banks that make a useful peer group for a basic comparison. They provide a mix of private-sector banks and a large public-sector bank.

### Why these metrics?
They cover four dimensions: profitability, core interest income, asset quality, and operating efficiency. Together they provide a broader view than net profit alone.

### What is NII?
Net Interest Income is interest earned minus interest paid. It reflects income from the bank's core interest-based activities.

### What is the difference between GNPA and NNPA?
GNPA measures gross non-performing loans before relevant provisions. NNPA reflects non-performing loans after relevant provisions and adjustments, relative to net advances. The exact regulatory calculation is more detailed than simple subtraction.

### What are provisions?
Provisions are expenses recognized to account for expected losses, including losses that may arise from loans that are not fully recoverable. They reduce reported profit when recognized.

### Why is higher ROA generally better?
ROA measures profit relative to average assets. A higher value generally indicates that the bank generates more profit for each unit of assets, although context matters.

### Why can ROE be high while ROA is low?
ROE measures return relative to shareholders' equity, while ROA uses assets as the denominator. Leverage and capital structure can affect the relationship, so the two ratios should be considered together.

### How did you calculate growth?
Growth (%) = (FY26 value − FY25 value) / FY25 value × 100.

### How does your overall score work?
I ranked each bank from 1 to 4 on seven metrics, with the best value receiving rank 1. I added the ranks, so a lower score is better. Each metric has equal weight, which is a simple learning approach rather than a formal bank rating.

### What are the limitations?
The sample has four banks and two years. Bank size, business mix, differences in reported ratio definitions, liquidity, capital adequacy, provisions, and macroeconomic factors are not fully modelled. Equal weighting is arbitrary and can change the ranking if the selected metrics or weights change.

### What would you improve next?
I would document the exact report page for every figure, reconcile definitions more thoroughly, extend the time series, and add capital adequacy, liquidity, credit-cost, and segment information before drawing stronger conclusions.

## Resume bullets

**Comparative Financial Analysis of Leading Indian Banks | Microsoft Excel**

- Compared ICICI Bank, HDFC Bank, Axis Bank, and SBI across profitability, core interest income, asset quality, and operating-efficiency indicators using FY25–FY26 reported data.
- Calculated year-on-year net-profit and NII growth, developed an equal-weight rank-sum comparison, and presented results using Excel tables and charts.

Only include these bullets once you have checked the workbook and saved the final report and workbook together. Be prepared to explain every metric and formula.
