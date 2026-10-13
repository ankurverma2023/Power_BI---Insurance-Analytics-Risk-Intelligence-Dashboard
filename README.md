# Power_BI---Insurance-Analytics-Risk-Intelligence-Dashboard
A 4-page Power BI report analyzing policies, premiums, claims, and customer risk for a global insurance portfolio (2023–2026).

## 📌 Business Questions
- Which products, channels, and regions drive premium?
- How well are policies retained (renewed vs. lapsed vs. cancelled)?
- Where are claims, severity, and loss ratio concentrated?
- Which customers and policies are most profitable or risky?

## 📊 Report Pages
| Page | What it shows |
|------|---------------|
| Executive Overview | Portfolio KPIs, monthly premium trend, policy status, premium by line and region |
| Policy & Premium | Top 10 products, average premium, channel mix, new vs. renewal, premium vs. gross premium, status by business line |
| Claims & Risk | Claim amount by region, severity, premium vs. incurred, claims by line, claim types, risk score and category |
| Customer & Policy Details | Top 10 customers, customer table, profitability scatter, policy-level details |

## 🔢 Key Metrics
| Metric | Value |
|--------|-------|
| Total Policies | 200K |
| Total Customers | 47K |
| Total Premium | 394.91M |
| Gross Premium | 412.86M |
| Average Premium | 1.97K |
| Total Commission | 36.31M |
| Estimated Profit | 150.84M |
| Total Claims | 32K |
| Claim Amount | 330.48M |
| Total Paid | 200.11M |
| Total Incurred | 244.07M |
| Loss Ratio | 61.80% |
| Fraud Claims | 2K |

## 💡 Insights
- **Premium by line:** Health 91M, Motor 65M, Liability 58M, Marine 56M, Life 50M, Property 36M, Cyber 36M, Travel 2M.
- **Premium by region:** Europe 121M, North America 107M, Asia Pacific 107M, Middle East & Africa 40M, Latin America 19M.
- **Channels:** Broker (47M) > Agent Network (37M) > Online (34M) > Bancassurance (31M) > Direct (26M).
- **Products:** Marine Liability has the highest premium (22M) and highest average premium (10.7K).
- **Retention:** Renewed 40%, Lapsed 27.24%, Active 26.85%, Cancelled 5.92%.
- **Claims:** Health has 16.9K of 32K claims; Travel has 2.5K claims on only 2M premium.
- **Severity:** Medium 14K, High 11K, Low 5K, Catastrophic 3K.
- **Risk mix:** Medium 52.64%, Low 39.07%, High 8.3%; average risk scores are nearly uniform across lines (~54).

## 🎯 Outcomes
- Consolidated policy, premium, claims, and customer data into one report with consistent KPIs.
- Cross-filtering slicers: Year, Region, Business Line, Product, Channel, Policy Status, Risk Category, Claim Status, Claim Severity.
- Highlighted retention (lapse rate), channel, and claim-severity priorities for management.
- Added customer-to-policy drill-down for underwriting and account review.

## 🛠️ Tech Stack
Power BI Desktop · DAX · Power Query · Data Modeling · SQL Server · Advanced Excel

## 📁 Repository Structure
├── /dashboard      # .pbix file
├── /data           # synthetic / anonymized dataset
├── /screenshots    # page previews (Page1–Page4)
└── README.md

## ⚠️ Data Note
Dataset is synthetic / anonymized and for portfolio purposes only.

## 👤 Author
[Ankur verma], Data Analyst & BI Consultant · [https://www.linkedin.com/in/ankurvermaoberoi/] · [av9054516@gmail.com]
