# Credit Card Customer & Transaction Analytics

An interactive Power BI portfolio project analysing credit card revenue, transaction activity, and customer segments.

## Project Overview

This project explores credit card performance through two interactive report pages:

- **CC Customer Report** — explores revenue across customer demographics and segments.
- **CC Transaction Report** — explores revenue and transaction activity across time, card categories, expenditure types, and transaction channels.

The objective is to turn raw data into useful business information and help stakeholders identify patterns that deserve further investigation.

## Business Questions

1. Which card category contributes the most revenue?
2. How do revenue and transaction volumes vary by quarter and week?
3. Which age groups and occupation segments contribute most to revenue?
4. Which expenditure types generate the highest revenue?
5. How does revenue vary across transaction channels?
6. How can customer segments be compared beyond total revenue alone?

## Tools & Skills

- Microsoft Power BI Desktop
- Power Query for data preparation (where used)
- DAX for measures and calculations (where used)
- Data visualisation and business analysis

## Dashboard Pages

### 1. Customer Analysis

![Customer Dashboard](Screenshots/customer_dashboard.png)

The customer page includes headline metrics and analysis by age group, gender, occupation, marital status, income group, state, card category, and weekly revenue.

### 2. Transaction Analysis

![Transaction Dashboard](Screenshots/transaction_dashboard.png)

The transaction page includes headline metrics and analysis by quarter, card category, expenditure type, education, occupation, and transaction channel.

## Headline Metrics

The supplied dashboard screenshots show approximately:

| Metric | Displayed value |
|---|---:|
| Revenue | 56.5M–57M |
| Total Interest | 8.0M |
| Income | 587.6M–588M |
| Transaction Count | 667K |
| Customer Satisfaction Score (CSS) | 3.19 |

These are screenshot readings, not independently audited figures. Confirm the exact values, units, currency, definitions, and default filter state in Power BI before publishing.

## Key Findings

See [Key Insights](Documentation/Key_Insights.md) for observations and validation notes.

## Business Recommendations

See [Business Recommendations](Documentation/Business_Recommendations.md) for suggested actions and follow-up analysis.

## Repository Structure

```text
Credit-Card-Customer-Transaction-Analytics/
├── README.md
├── Dashboard/
│   └── CreditCardReport.pbix
├── Dataset/
│   └── README.md
├── Screenshots/
│   ├── customer_dashboard.png
│   └── transaction_dashboard.png
└── Documentation/
    ├── Key_Insights.md
    └── Business_Recommendations.md
```

## How to Use

1. Download the PBIX file from the `Dashboard` folder.
2. Open it in Microsoft Power BI Desktop.
3. Refresh the data if you have the authorised source files and need to update the report.
4. Use the slicers and chart selections to explore the report.

## Data & Responsible Use

Add the dataset source, licence, access date, date range, table descriptions, and refresh instructions before publishing. Do not upload confidential, personally identifiable, or restricted customer data. Only include source CSV files if redistribution is permitted.

## Limitations

- Dashboard values may change when slicers are applied.
- Total revenue does not necessarily equal profit.
- Descriptive comparisons do not prove causation.
- Confirm the definitions of Revenue, Income, Interest, Transaction Count, and CSS before drawing business conclusions.

## Author

**[Your Name]**  
Aspiring Data Analyst  
