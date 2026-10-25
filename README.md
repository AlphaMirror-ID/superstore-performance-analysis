# Showroom Sales Analysis

A data analytics portfolio project analyzing sales performance across 10 car showroom branches in 2025. The project summarizes sales KPIs, vehicle category performance, branch results, product contribution, monthly trends, payment methods, and transaction status using a Power BI dashboard.

## Project Overview

The goal of this project is to turn showroom transaction data into actionable insights that can support sales monitoring and business evaluation.

- **Dataset:** `showroom_mobil_10cabang_clean.csv`
- **Dashboard:** Microsoft Power BI (`Dashboard-Showroom.pbix`)
- **Report:** `showroom-sales-analysis-report.pdf`
- **Coverage:** 10,000 transactions across 10 branches during 2025

## Tools & Technologies

- **CSV** — cleaned transaction dataset
- **Microsoft Power BI** — dashboard and interactive filtering
- **Data analysis** — KPI calculation, category and branch comparisons, product ranking, and monthly trend analysis

## Repository Structure

```text
showroom-sales-analysis/
├── README.md
├── data/
│   └── showroom_mobil_10cabang_clean.csv
├── dashboard/
│   ├── dashboard-overview.png
│   └── Dashboard-Showroom.pbix
└── reports/
    └── showroom-sales-analysis-report.pdf
```

## Dataset

The dataset contains 10,000 transactions from 10 showroom branches during 2025. The analysis uses fields including sales value, order ID, quantity, vehicle category, branch, product, transaction date, payment type, trade-in status, and transaction status.

## Key Findings

- **Total sales:** Rp3,092,685,000,000 across **10,000 transactions** and **10,433 units**.
- **Completion rate:** 89.7%, representing **8,966 completed transactions**.
- **Top vehicle category:** SUVs generated Rp1,680,293,000,000, contributing **54.3%** of total sales. MPVs ranked second with Rp997,200,000,000.
- **Branch performance:** Malang recorded the highest total sales at **Rp324,667,000,000**. Karawang recorded the lowest at **Rp295,398,000,000**.
- **Top product:** Honda CR-V 1.5 Turbo RS ranked first by total sales.
- **Monthly trend:** August recorded the highest sales, while June recorded the lowest.
- **Transaction status:** 542 transactions were cancelled and 492 were refunded, totaling **1,034 transactions (10.3%)** that were not completed.
- **Payment method:** Credit was the most frequently used payment method.
- **Trade-in:** 3,523 transactions (35.2%) were marked as trade-in.

*Figures above are taken from the project's showroom analysis report. Sales value is not the same as profit or margin; profitability data would be needed to assess profit performance.*

## Business Recommendations

1. **Prioritize SUV demand planning.** SUVs account for 54.3% of total sales, so monitor SUV demand, stock availability, and sales performance regularly. Keep MPVs under close review as the second-largest category.
2. **Use Malang as a comparison point, not an automatic template.** Review Malang's sales approach and compare its category mix, transaction volume, and completion rate with other branches before applying practices elsewhere.
3. **Investigate cancelled and refunded transactions.** Track the 542 cancelled and 492 refunded orders by branch, product, month, and payment method to identify where further investigation is most useful. The current aggregate figures do not establish the causes.
4. **Review the monthly sales pattern.** Compare August's high sales with June's low sales and check whether the difference relates to vehicle category, branch performance, promotions, or transaction volume before planning future campaigns.
5. **Monitor transaction completion alongside sales.** Report completed, cancelled, and refunded transactions together with total sales so that the team can distinguish gross sales activity from completed orders.
6. **Review the credit payment journey.** Since credit is the most frequently used payment method, monitor its completion and cancellation rates to identify potential process improvements. The data alone does not prove that credit causes cancellations or refunds.
7. **Track trade-in activity.** Trade-in accounts for 35.2% of transactions. Compare its sales and completion metrics with non-trade-in transactions to evaluate its role in the sales process.

## Dashboard Preview

![Showroom Sales Dashboard](dashboard/dashboard-overview.png)

The screenshot provides a static preview of the Power BI dashboard. To explore the report interactively, download `Dashboard-Showroom.pbix` from the `dashboard/` directory and open it with Microsoft Power BI Desktop.

## Project Report

The full report is available here:

[`reports/showroom-sales-analysis-report.pdf`](https://github.com/AlphaMirror-ID/showroom-sales-analysis/blob/main/reports/showroom-sales-analysis-report.pdf)


## Author

**Aziyusman Maulana**

Data Analytics Portfolio Project
