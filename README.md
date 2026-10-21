# Online Retail Transaction Analysis | Excel Portfolio Project
link to workbook - https://github.com/deDara77/online-retail-analysis/releases/tag/v1.0
## Project overview

This project analyses a transactional dataset from an online retail business to understand merchandise value, cancellation related transactions, customer purchasing patterns, geographic concentration, and product performance.

The objective was to turn raw transaction records into a structured, reconcilable analysis that supports better business interpretation and decision making.

## Business questions

- What is the recorded merchandise value after accounting for credit notes and reversals?
- How much recorded value comes from postage, carriage, fees, commissions, and manual adjustments?
- How concentrated is merchandise value across countries, customers, and products?
- What does the distribution of invoice basket sizes reveal about purchasing activity?
- How can the underlying transaction data be reconciled to a single recorded-value measure?

## Tools and methods

**Tool:** Microsoft Excel / WPS Office

The analysis involved transaction-data preparation, formula-based classification, invoice level aggregation, KPI calculations, summary tables, charting, and reconciliation checks.

The workbook separates merchandise transactions from other recorded line types so that charges and adjustments are not automatically interpreted as product sales.

## Selected findings

- **Net merchandise value:** £9,771,234.83
- **Net recorded line value:** £9,726,006.95
- **Reconciliation difference:** £0.00
- **UK share of net merchandise value:** approximately 84.8%
- **Qualifying merchandise invoices in the basket-size analysis:** 19,773
- **Product concentration:** approximately 21.8% of products account for 80% of net merchandise value under the project's Pareto calculation.

These results describe recorded transaction values, not audited financial performance.

## Deliverables

- An Excel workbook with a dashboard and supporting analysis sheets
- KPI measures and reconciliation checks
- Monthly, country, customer, basket size, and product-concentration analyses
- A README documenting the workbook, definitions, scope, and interpretation limits

## Limitations

The dataset records transactions; it does not independently establish cash collected, profitability, or audited financial results. Negative quantities and credit notes affect net merchandise value. Customer identifiers may be missing, and December 2011 is a partial month, so monthly comparisons require care.

## Next steps

Future stages may reproduce selected calculations in SQL and Python, then develop an interactive reporting layer in Power BI. Those extensions are separate from this completed Excel deliverable.
