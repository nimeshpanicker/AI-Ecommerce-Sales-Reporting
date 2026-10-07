# AI-Powered E-commerce Sales Analysis & Automated Reporting

An end-to-end **data analytics + AI automation portfolio project** built around an e-commerce transaction dataset and an n8n reporting workflow.

The project separates **deterministic analytics** from **AI interpretation**:

**Google Sheets → JavaScript KPI Analysis → Claude AI → GitHub → Gmail**

> The public repository is intentionally designed without customer-level records or other personally identifiable information.

## Project Overview

This project automates repetitive sales reporting. The workflow reads transaction data, calculates business KPIs and breakdowns in JavaScript, sends only aggregated results to Claude for narrative analysis, publishes a Markdown report to GitHub, and emails the same report to stakeholders.

The supplied project report describes two pipelines:

1. **Conversational Analyst** — users ask questions through an n8n chat interface and receive answers from a computed analytical summary.
2. **Automated Weekly Report** — a scheduled pipeline generates a structured Markdown report, commits it to GitHub, and sends it by email.

The workflow design and guardrails are documented in the accompanying project report. fileciteturn0file0L31-L65

## Key Results

| KPI | Value |
|---|---:|
| Records | 9,994 |
| Columns | 22 |
| Total Revenue | 2,297,200.86 |
| Total Profit | 286,397.02 |
| Profit Margin | 12.47% |
| Distinct Orders | 5,009 |
| Distinct Customers | 793 |
| Total Quantity | 37,873 |
| Average Order Value | 458.61 |
| Order Date Range | 2011-01-04 to 2014-12-31 |

### Business Highlights

- **Technology** is the strongest category by revenue and profit.
- **Furniture** generates substantial revenue but has the weakest category margin.
- **West** is the strongest region by revenue and profit.
- **Central** has the lowest regional margin.
- Some high-revenue products are not necessarily profitable, demonstrating why revenue alone is not enough for performance evaluation.

The portfolio report documents the same headline findings and recommends strengthening validation, shared analytics logic, date parsing, failure handling, and report-number validation. fileciteturn0file0L292-L365

## Architecture

```text
                         ┌─────────────────────┐
                         │   Google Sheets     │
                         │   E-commerce Data   │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │  JavaScript / n8n   │
                         │  KPI + Aggregation  │
                         └──────────┬──────────┘
                                    │
                       Compact JSON Summary
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │     Claude AI       │
                         │ Insights + Report   │
                         └──────────┬──────────┘
                                    │
                         ┌──────────┴──────────┐
                         ▼                     ▼
                ┌─────────────────┐    ┌─────────────────┐
                │     GitHub      │    │      Gmail      │
                │ Versioned .md   │    │ Stakeholder     │
                │ Reports         │    │ Delivery        │
                └─────────────────┘    └─────────────────┘
```

The source project report describes this two-pipeline architecture and the n8n node inventory. fileciteturn0file0L82-L107

## Repository Structure

```text
AI-Ecommerce-Sales-Reporting/
├── README.md
├── LICENSE
├── .gitignore
├── reports/
│   ├── ecommerce_sales_report_2026-10-07.md
│   ├── category_performance.csv
│   ├── regional_performance.csv
│   └── annual_performance.csv
├── workflow/
│   └── README.md
├── screenshots/
│   └── README.md
├── data/
│   └── README.md
└── docs/
    └── data_dictionary.md
```

The original project report proposes a layout containing `/workflow`, `/screenshots`, `/reports`, and `README.md`. fileciteturn0file0L235-L240

## Analytics Performed

The analytical layer calculates:

- Total revenue, profit and quantity
- Distinct orders and customers
- Average order value
- Profit margin
- Product performance
- Category performance
- Regional performance
- Annual/monthly trends
- Data-quality checks
- Duplicate-row count
- Missing-value counts

The documented workflow uses alias-based column detection, aggregation, margin calculations and monthly trend analysis. fileciteturn0file0L167-L191

## AI Guardrails

Claude is **not** given the raw transaction table. The workflow sends a compact analytical summary instead.

Guardrails include:

- Analyse only supplied summary values.
- Never invent, estimate or alter calculated values.
- Do not assign a currency unless the source specifies one.
- Treat unavailable metrics as unavailable rather than guessing.
- Separate observed results, interpretation and recommendations.
- Exclude PII and raw transaction records from public artifacts.

This aggregate-only design is explicitly described in the project report. fileciteturn0file0L203-L216

## Workflow

The scheduled reporting pipeline is designed to:

1. Run every Monday at 09:00.
2. Read the e-commerce data.
3. Collapse the transaction rows into one analytical summary.
4. Ask Claude to produce a structured report.
5. Commit the report to GitHub.
6. Email the report through Gmail.

The report-generation structure covers executive summary, KPI summary, product/category/region performance, monthly performance, profitability, data quality, insights, recommendations and conclusion. fileciteturn0file0L136-L160

## Data Privacy

The original workbook contains customer-level fields such as Customer ID, Customer Name, City, State and Postal Code. **Do not upload the raw workbook to a public GitHub repository.**

This repository therefore stores only aggregated portfolio-safe outputs. The source project specifically requires public artifacts to exclude customer names, emails, phone numbers, personal data and raw transaction records. fileciteturn0file0L157-L160

## Suggested n8n Setup

Credentials required:

- Google Sheets OAuth2
- Anthropic API / Claude
- GitHub OAuth2
- Gmail OAuth2

The workflow's documented technology stack uses n8n, Google Sheets, JavaScript Code nodes, Claude, GitHub and Gmail. fileciteturn0file0L72-L81

## Production Improvements

Recommended next steps:

1. Use priority-based column mapping.
2. Move shared analytics logic into one reusable sub-workflow.
3. Parse dates using an explicit format.
4. Add failure alerts.
5. Validate generated report numbers against the computed summary before publishing.
6. Add access control to the public chat.
7. Make email recipients configurable.
8. Add charts/PDF output for stakeholder delivery.
9. Add week-over-week comparisons.
10. Add threshold alerts for low category/region margins.

These improvements are based on the design review in the supplied portfolio report. fileciteturn0file0L308-L365

## Skills Demonstrated

- Data analysis
- Business intelligence
- JavaScript data processing
- n8n workflow automation
- Prompt engineering
- AI agents
- Google Sheets integration
- GitHub automation
- Gmail automation
- Data governance
- Automated reporting
- Portfolio documentation

The source report maps these skills directly to the project's workflow, analytics engine, AI guardrails and integrations. fileciteturn0file0L369-L380

## Portfolio Positioning

**Project title:** AI-Powered E-commerce Sales Analysis & Automated Reporting

**One-line resume description:**

> Built an n8n-powered AI reporting pipeline that calculates e-commerce KPIs with JavaScript, generates grounded business insights with Claude, versions automated reports in GitHub, and delivers stakeholder updates through Gmail.

## Author

**Panicker Nimesh Mahendran**  
Data Analyst (Fresher)

Repository target referenced in the project report:

`github.com/nimeshpanicker/AI-Ecommerce-Sales-Reporting`
