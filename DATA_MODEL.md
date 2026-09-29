# Data Model

The Power BI model extract provided for this project contains the following tables.

| Table | Purpose |
|---|---|
| `clean_patient_payments` | Patient payment / collection analysis |
| `clean_insurance` | Insurance-related payments and reimbursements |
| `clean_government` | Government reimbursement analysis |
| `clean_cash_outflows` | Operational cash-outflow / expense analysis |
| `clean_outstanding` | Outstanding receivables and pending balances |
| `clean_monthly_financial` | Monthly financial summaries and trends |
| `Date_Dimension` | Time-based filtering and period analysis |

## Suggested Model Design

Use `Date_Dimension` as the central calendar table for monthly, quarterly, and yearly financial trend analysis.

The remaining tables represent the major financial areas used by the dashboard.
