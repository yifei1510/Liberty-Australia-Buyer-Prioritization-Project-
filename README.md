# 📊 Liberty Australia Buyer Prioritisation Project

> A Tableau project that transformed a buyer research workbook into a decision-ready dashboard for Liberty's Australian CEO visit.

<img width="827" height="585" alt="Buyer Prioritisation Dashboard" src="https://github.com/user-attachments/assets/324edd3c-6c49-4c90-a50d-3ce0619d0681" />


## 📘 Project Background

Liberty needed a practical way to identify which Australian buyers should receive the greatest attention before a CEO visit. The source workbook contained potential buyers across all Australian states and territories, with information about location, business type, product fit, expected order potential, public verification evidence and contact readiness.

The final output needed to be accurate enough for operational planning and simple enough for senior stakeholders to interpret quickly.

## 📈 Executive Summary

- The database contains **100 unique buyers** across all eight Australian states and territories.
- **35 buyers are Tier 1**, representing the highest strategic priority, while **65 are Tier 2** and suited to follow-up and pipeline development.
- **NSW has 25 buyers**, followed by **VIC with 22** and **QLD with 18**. Together, these three states represent 65% of the database.
- NSW and VIC account for **18 of the Top 20 priority buyers**.
- **22 buyers match all four product categories**.
- Fruits and Vegetables each match **79 buyers**; Cereals match 40 and Spices match 39.
- Public email or phone details are available for 24 buyers, making direct-contact research an important next step before outreach.

## 🏆 Top 20 Priority Buyers

<img width="239" height="416" alt="Top 20 Priority Buyers" src="https://github.com/user-attachments/assets/f99e8c16-5079-4a70-b5ef-7f2715139f0f" />


This ranked view gives Liberty a focused CEO meeting shortlist. The bar length and colour intensity represent the Priority Score, while the rank and company name make the output immediately usable for visit planning.

## 🗺️ Buyer Coverage by State

<img width="685" height="213" alt="Buyer Tier Distribution by State" src="https://github.com/user-attachments/assets/35cfd8d5-9ae9-415c-ac59-9eba983d889b" />



The filled map shows the geographic concentration of buyers across Australia. Darker states contain more buyers, making NSW, VIC and QLD visible as the strongest areas of coverage while also highlighting lower-coverage territories.

## 🧩 Buyer Tier Distribution by State


<img width="685" height="237" alt="Product Category Coverage" src="https://github.com/user-attachments/assets/88a891fd-48f5-4aa8-a803-81b38b46be89" />


The stacked bars compare total buyer volume and tier composition at the same time. Tier 1 represents buyers with high order potential and priority for CEO meetings; Tier 2 represents medium-potential buyers suited to structured follow-up.

## 📦 Product Category Coverage

<img width="685" height="237" alt="Product Category Coverage" src="https://github.com/user-attachments/assets/6adf839a-cb34-4bbf-a86a-09f23881c77a" />


This chart shows the number of unique buyers matched to each product category. Fruits and Vegetables provide the widest market coverage, while Cereals and Spices represent narrower segments that may require more targeted outreach.

## 🎨 Dashboard Design Choices

The dashboard follows a summary-to-detail structure. KPI cards provide the first read, the Top 20 table supports meeting planning, and the map and bar charts explain the geographic and product patterns behind the totals.

Horizontal bars were used for company and category comparisons because the labels are long. The state chart uses stacked bars so users can compare both total buyer volume and tier composition. The filled map provides geographic context without requiring the reader to interpret coordinates.

## 🛠️ Tools Used

- **Microsoft Excel** for source review and structured outputs
- **Tableau Prep** for repeatable data transformation
- **Tableau Desktop** for calculated fields, analysis, filters and dashboard design
- **Data-quality checks** for field types, table grain, completeness, duplicates and count reconciliation

## 💼 Skills Demonstrated

I handled the project end to end, from source review to the final dashboard. The work demonstrates:

- maintaining clear table grain and metric definitions
- checking data quality, completeness and integrity before reporting
- working independently to identify patterns and gaps
- turning analysis into concise information for non-technical stakeholders
- building Tableau reports that support operational decisions
- documenting assumptions, data limitations and follow-up requirements

Although this project focuses on commercial buyer planning, the same analytical approach applies to community-service and program data: define what each record represents, verify data quality, document the measures, identify useful patterns and communicate the findings responsibly.

## ⚠️ Limitations and Next Steps

This dashboard is a verified snapshot rather than a time-series performance report. It shows prospect potential, not completed meetings, orders or revenue.

Recommended next steps:

- add meeting status, owner and follow-up date
- record outreach attempts and outcomes
- track conversion from priority buyer to qualified opportunity
- review the Priority Score with Liberty stakeholders as new evidence becomes available
- refresh public contact details before the CEO visit
- add data refresh and validation dates to the published dashboard

## 🔒 Data and Privacy

The public repository contains dashboard images and project documentation only. The buyer-level source data is not included because it contains business-targeting information and public contact references. Any public version of the Tableau workbook should use an approved, de-identified extract.
