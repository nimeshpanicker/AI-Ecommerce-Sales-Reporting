# E-commerce Sales Performance Report

## 1. Executive Summary

The dataset contains **9,994 e-commerce transaction records** covering the period from **January 2011 to December 2014**. The analysis covers sales, profit, quantity, orders, customers, products, categories, regions, and monthly performance.

The business generated total revenue of **2,297,200.86** and total profit of **286,397.02**, resulting in an overall **12.47% profit margin**. The dataset contains **5,009 distinct orders** from **793 customers**, with an average order value of **458.61**.

No currency is specified in the dataset, so monetary values are presented without a currency symbol.

Key observations include:

- **Category:** Technology generated the highest revenue and profit, while Technology and Office Supplies had similar margins of 17.40% and 17.04%. Furniture generated 741,999.80 in revenue but only an 2.49% profit margin.
- **Region:** West generated the highest revenue, profit, quantity and regional profit margin. Central had the lowest regional margin at 7.92%.
- **Products:** Several high-revenue products generated zero or negative profit, demonstrating that revenue alone does not indicate profitability.
- **Time:** September, November and December were consistently among the strongest revenue months across the four years.
- **Annual performance:** Revenue increased from 484,247.50 in 2011 to 733,947.02 in 2014.
- **Monthly performance:** November 2014 generated the highest monthly revenue at 112,326.47, while December 2013 generated the highest monthly profit at 17,902.73.
- **Profitability:** October 2013 recorded the highest monthly profit margin at 27.92%, while January 2012 recorded the lowest at -18.05%.
- **Data quality:** No missing values or exact duplicate records were identified in the uploaded dataset.

---

## 2. KPI Summary

| **KPI** | **Value** |
|---|---:|
| Total Revenue | 2,297,200.86 |
| Total Profit | 286,397.02 |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Average Order Value | 458.61 |
| Total Quantity | 37,873 |
| Total Records | 9,994 |
| Order Date Range | January 2011 – December 2014 |

---

## 3. Product Performance

The following table presents the top 10 products by total revenue, identified using Product ID.

| **Rank** | **Product ID** | **Revenue** | **Profit** | **Profit Margin** | **Quantity** |
|---:|---|---:|---:|---:|---:|
| 1 | TEC-CO-10004722 | 61,599.82 | 25,199.93 | 40.91% | 20 |
| 2 | OFF-BI-10003527 | 27,453.38 | 7,753.04 | 28.24% | 31 |
| 3 | TEC-MA-10002412 | 22,638.48 | -1,811.08 | -8.00% | 6 |
| 4 | FUR-CH-10002024 | 21,870.58 | 0.00 | 0.00% | 39 |
| 5 | OFF-BI-10001359 | 19,823.48 | 2,233.51 | 11.27% | 37 |
| 6 | OFF-BI-10000545 | 19,024.50 | 760.98 | 4.00% | 48 |
| 7 | TEC-CO-10001449 | 18,839.69 | 6,983.88 | 37.07% | 38 |
| 8 | TEC-MA-10001127 | 18,374.90 | 4,094.98 | 22.29% | 12 |
| 9 | OFF-BI-10004995 | 17,965.07 | -1,878.17 | -10.45% | 27 |
| 10 | OFF-SU-10000151 | 17,030.31 | -262.00 | -1.54% | 11 |

### Product Observations

- **TEC-CO-10004722** generated the highest revenue at **61,599.82**, more than twice the revenue of the second-ranked product.
- TEC-CO-10004722 also generated the highest profit in the top-10 group at **25,199.93** and a **40.91% margin**.
- Four top-10 products generated margins above the overall company margin of 12.47%:
  - TEC-CO-10004722 — 40.91%
  - OFF-BI-10003527 — 28.24%
  - TEC-CO-10001449 — 37.07%
  - TEC-MA-10001127 — 22.29%
- Three top-10 products generated negative profit:
  - TEC-MA-10002412 — -1,811.08
  - OFF-BI-10004995 — -1,878.17
  - OFF-SU-10000151 — -262.00
- FUR-CH-10002024 generated **21,870.58** in revenue but approximately **0.00** profit.
- Revenue rank does not consistently correspond to profitability. Several products with substantial revenue generated low or negative margins.

---

## 4. Category Performance

The dataset contains three product categories: Technology, Furniture and Office Supplies.

| **Category** | **Revenue** | **Profit** | **Quantity** | **Profit Margin** |
|---|---:|---:|---:|---:|
| Technology | 836,154.03 | 145,454.95 | 6,939 | 17.40% |
| Furniture | 741,999.80 | 18,451.27 | 8,028 | 2.49% |
| Office Supplies | 719,047.03 | 122,490.80 | 22,906 | 17.04% |

### Category Observations

- Technology ranks first in revenue at **836,154.03**.
- Technology also generated the highest category profit at **145,454.95**.
- Technology's profit margin was **17.40%**.
- Office Supplies generated **719,047.03** in revenue and **122,490.80** in profit.
- Office Supplies had the highest quantity at **22,906 units**.
- Furniture generated **741,999.80** in revenue but only **18,451.27** in profit.
- Furniture's **2.49% margin** is substantially below the overall business margin of 12.47%.
- The category results demonstrate that higher revenue does not necessarily produce proportionally higher profit.

---

## 5. Regional Performance

The dataset contains four geographic regions: West, East, Central and South.

| **Region** | **Revenue** | **Profit** | **Quantity** | **Profit Margin** |
|---|---:|---:|---:|---:|
| West | 725,457.82 | 108,418.45 | 12,266 | 14.94% |
| East | 678,781.24 | 91,522.78 | 10,618 | 13.48% |
| Central | 501,239.89 | 39,706.36 | 8,780 | 7.92% |
| South | 391,721.91 | 46,749.43 | 6,209 | 11.93% |

### Regional Observations

- West generated the highest revenue at **725,457.82**.
- West also generated the highest profit at **108,418.45**.
- West recorded the highest regional profit margin at **14.94%**.
- East ranked second in revenue, profit, quantity and margin.
- Central generated **501,239.89** in revenue but only **39,706.36** in profit.
- Central's profit margin of **7.92%** was the lowest among the four regions.
- South generated the lowest revenue at **391,721.91**, but its profit of **46,749.43** exceeded Central's **39,706.36** despite having lower revenue.
- West and East were above the overall business margin of 12.47%, while Central and South were below it.

---

## 6. Annual Performance

The dataset covers four complete calendar years.

| **Year** | **Revenue** | **Profit** | **Profit Margin** | **Quantity** | **Orders** |
|---:|---:|---:|---:|---:|---:|
| 2011 | 484,247.50 | 49,543.97 | 10.23% | 7,581 | 969 |
| 2012 | 470,532.51 | 61,618.60 | 13.10% | 7,979 | 1,038 |
| 2013 | 608,473.83 | 81,726.93 | 13.43% | 9,810 | 1,310 |
| 2014 | 733,947.02 | 93,507.51 | 12.74% | 12,503 | 1,692 |

### Annual Observations

- 2014 generated the highest annual revenue at **733,947.02**.
- 2014 also generated the highest annual profit at **93,507.51**.
- 2013 recorded the highest annual profit margin at **13.43%**.
- Revenue increased from **484,247.50 in 2011** to **733,947.02 in 2014**.
- Distinct orders increased from **969 in 2011** to **1,692 in 2014**.
- Quantity increased from **7,581 units in 2011** to **12,503 units in 2014**.
- 2012 generated slightly lower revenue than 2011 but produced substantially higher profit and a higher margin.

---

## 7. Monthly Performance

The dataset contains **48 monthly periods** from January 2011 through December 2014.

| **Month** | **Revenue** | **Profit** | **Profit Margin** | **Quantity** | **Orders** |
|---|---:|---:|---:|---:|---:|
| Jan 2011 | 13,946.23 | 2,446.77 | 17.54% | 282 | 31 |
| Feb 2011 | 4,810.56 | 865.73 | 18.00% | 161 | 29 |
| Mar 2011 | 55,691.01 | 498.73 | 0.90% | 585 | 71 |
| Apr 2011 | 28,295.35 | 3,488.84 | 12.33% | 536 | 66 |
| May 2011 | 23,648.29 | 2,738.71 | 11.58% | 466 | 69 |
| Jun 2011 | 34,595.13 | 4,976.52 | 14.39% | 521 | 66 |
| Jul 2011 | 33,946.39 | -841.48 | -2.48% | 550 | 65 |
| Aug 2011 | 27,909.47 | 5,318.10 | 19.05% | 609 | 72 |
| Sep 2011 | 81,777.35 | 8,328.10 | 10.18% | 1,000 | 130 |
| Oct 2011 | 31,453.39 | 3,448.26 | 10.96% | 573 | 78 |
| Nov 2011 | 78,628.72 | 9,292.13 | 11.82% | 1,219 | 151 |
| Dec 2011 | 69,545.62 | 8,983.57 | 12.92% | 1,079 | 141 |
| Jan 2012 | 18,174.08 | -3,281.01 | -18.05% | 236 | 29 |
| Feb 2012 | 12,210.87 | 2,821.28 | 23.10% | 248 | 38 |
| Mar 2012 | 38,466.80 | 9,724.67 | 25.28% | 506 | 77 |
| Apr 2012 | 34,195.21 | 4,187.50 | 12.25% | 543 | 72 |
| May 2012 | 30,131.69 | 4,667.87 | 15.49% | 575 | 74 |
| Jun 2012 | 24,797.29 | 3,335.56 | 13.45% | 486 | 68 |
| Jul 2012 | 28,765.33 | 3,288.65 | 11.43% | 557 | 66 |
| Aug 2012 | 36,898.33 | 5,355.81 | 14.52% | 598 | 68 |
| Sep 2012 | 64,595.92 | 8,209.16 | 12.71% | 1,086 | 140 |
| Oct 2012 | 31,404.92 | 2,817.37 | 8.97% | 631 | 87 |
| Nov 2012 | 75,972.56 | 12,474.79 | 16.42% | 1,310 | 158 |
| Dec 2012 | 74,919.52 | 8,016.97 | 10.70% | 1,203 | 161 |
| Jan 2013 | 18,542.49 | 2,824.82 | 15.23% | 358 | 48 |
| Feb 2013 | 22,867.71 | 4,996.25 | 21.85% | 299 | 44 |
| Mar 2013 | 51,186.22 | 3,625.27 | 7.08% | 575 | 85 |
| Apr 2013 | 39,248.59 | 2,957.84 | 7.54% | 634 | 88 |
| May 2013 | 56,691.08 | 8,627.48 | 15.22% | 854 | 109 |
| Jun 2013 | 39,430.44 | 4,499.58 | 11.41% | 746 | 97 |
| Jul 2013 | 38,440.75 | 4,464.66 | 11.61% | 756 | 96 |
| Aug 2013 | 33,265.56 | 2,328.35 | 7.00% | 710 | 91 |
| Sep 2013 | 72,908.11 | 9,360.49 | 12.84% | 1,311 | 191 |
| Oct 2013 | 56,463.13 | 15,763.38 | 27.92% | 740 | 102 |
| Nov 2013 | 82,192.32 | 4,376.07 | 5.32% | 1,423 | 186 |
| Dec 2013 | 97,237.42 | 17,902.73 | 18.41% | 1,404 | 173 |
| Jan 2014 | 44,703.14 | 7,208.68 | 16.13% | 624 | 74 |
| Feb 2014 | 20,283.51 | 1,605.65 | 7.92% | 360 | 52 |
| Mar 2014 | 53,908.96 | 12,957.90 | 24.04% | 825 | 111 |
| Apr 2014 | 40,112.42 | 2,803.63 | 6.99% | 728 | 112 |
| May 2014 | 45,651.24 | 6,274.46 | 13.74% | 955 | 130 |
| Jun 2014 | 48,259.75 | 8,087.67 | 16.76% | 891 | 125 |
| Jul 2014 | 48,428.36 | 6,623.56 | 13.68% | 842 | 112 |
| Aug 2014 | 61,516.09 | 8,894.45 | 14.46% | 879 | 110 |
| Sep 2014 | 90,488.72 | 11,395.44 | 12.59% | 1,676 | 229 |
| Oct 2014 | 77,793.76 | 9,440.66 | 12.14% | 1,151 | 150 |
| Nov 2014 | 112,326.47 | 9,682.55 | 8.62% | 1,789 | 252 |
| Dec 2014 | 90,474.60 | 8,532.87 | 9.43% | 1,783 | 235 |

### Monthly Observations

- **November 2014** generated the highest monthly revenue at **112,326.47**.
- **December 2013** generated the highest monthly profit at **17,902.73**.
- **October 2013** recorded the highest monthly profit margin at **27.92%**.
- **January 2012** recorded the lowest monthly profit margin at **-18.05%**.
- September, November and December were consistently among the strongest revenue months across the four years.
- November 2014 also recorded the highest monthly quantity at **1,789 units** and the highest number of orders at **252**.
- Some months generated strong revenue but relatively low margins. For example, November 2014 generated the highest revenue but only an **8.62% margin**.
- Monthly results demonstrate that revenue growth and profitability do not always move together.

---

## 8. Profitability Analysis

The overall dataset generated:

- **Revenue:** 2,297,200.86
- **Profit:** 286,397.02
- **Profit Margin:** 12.47%

### High-Revenue / High-Profit Areas

Technology was the strongest category by both revenue and profit:

- Revenue: **836,154.03**
- Profit: **145,454.95**
- Margin: **17.40%**

West was the strongest region:

- Revenue: **725,457.82**
- Profit: **108,418.45**
- Margin: **14.94%**

### High-Revenue / Lower-Profit Areas

Furniture generated:

- Revenue: **741,999.80**
- Profit: **18,451.27**
- Margin: **2.49%**

This represents a substantial difference between sales volume and profitability.

Several individual products also demonstrate the same pattern. For example:

| Product ID | Revenue | Profit | Margin |
|---|---:|---:|---:|
| TEC-MA-10002412 | 22,638.48 | -1,811.08 | -8.00% |
| FUR-CH-10002024 | 21,870.58 | 0.00 | 0.00% |
| OFF-BI-10004995 | 17,965.07 | -1,878.17 | -10.45% |
| OFF-SU-10000151 | 17,030.31 | -262.00 | -1.54% |

These results show why product-level profitability should be monitored alongside revenue.

---

## 9. Data Quality

The uploaded dataset contains 9,994 records and 22 columns.

| **Data Quality Check** | **Result** |
|---|---:|
| Total records | 9,994 |
| Total columns | 22 |
| Missing values | 0 |
| Exact duplicate rows | 0 |
| Distinct Order IDs | 5,009 |
| Distinct Customer IDs | 793 |
| Distinct Product IDs | 1,862 |
| Distinct Product Names | 1,841 |
| Distinct Categories | 3 |
| Distinct Sub-Categories | 17 |
| Distinct Regions | 4 |
| Distinct States | 49 |
| Distinct Cities | 531 |
| Distinct Customer Segments | 3 |
| Valid Order Dates | 9,994 |
| Valid Ship Dates | 9,994 |

### Data Quality Observations

- No missing values were identified across the uploaded dataset.
- No exact duplicate transaction rows were identified.
- Order Date values were successfully parsed across the four-year period.
- Ship Date values were successfully parsed.
- The dataset contains transaction-level customer, product, sales and profitability information.
- The analysis uses aggregated business metrics and does not expose individual customer information in the stakeholder report.

---

## 10. Key Business Insights

### 1. Technology Is the Strongest Profit Contributor

Technology generated **836,154.03** in revenue and **145,454.95** in profit, producing a **17.40% margin**.

### 2. Furniture Has a Significant Profitability Gap

Furniture generated **741,999.80** in revenue but only **18,451.27** in profit.

Its **2.49% margin** is substantially below the overall business margin of **12.47%**.

### 3. West Is the Strongest Region

West generated:

- **725,457.82** revenue
- **108,418.45** profit
- **14.94%** margin

It led all four regions across these measures.

### 4. Revenue Does Not Guarantee Profit

Several products among the top 10 by revenue generated negative profit.

The most significant example is:

**OFF-BI-10004995**

- Revenue: **17,965.07**
- Profit: **-1,878.17**
- Margin: **-10.45%**

### 5. 2014 Was the Highest-Revenue Year

2014 generated:

- **733,947.02** revenue
- **93,507.51** profit
- **12.74%** margin
- **1,692** distinct orders

### 6. Monthly Revenue Is Concentrated Toward the End of the Year

September, November and December repeatedly appear among the strongest revenue months across the four-year period.

### 7. High Revenue Can Coincide With Lower Margins

November 2014 produced the highest monthly revenue of **112,326.47**, but its profit margin was only **8.62%**.

This demonstrates that revenue growth should be evaluated together with profitability.

---

## 11. Business Recommendations

Based strictly on the observed data:

### 1. Investigate Furniture Profitability

Review Furniture pricing, discounts, product-level margins and cost structure because the category generated substantial revenue but only a **2.49% margin**.

### 2. Review Loss-Making High-Revenue Products

Products with significant revenue and negative profit should be investigated individually.

Particular attention should be given to products such as:

- TEC-MA-10002412
- OFF-BI-10004995
- OFF-SU-10000151

### 3. Monitor Regional Profitability

Central recorded the lowest regional margin at **7.92%**. Product mix, discounts and transaction profitability should be examined to understand the difference from West and East.

### 4. Track Revenue and Profit Together

Monthly reporting should include both revenue and profit because high-revenue months can still have relatively low margins.

### 5. Prioritize Sustainable Product Performance

Products should be evaluated using a combination of:

- Revenue
- Profit
- Profit Margin
- Quantity
- Order volume

rather than revenue alone.

### 6. Use Recurring Automated Reporting

The recurring reporting workflow can monitor changes in:

- Revenue
- Profit
- Profit Margin
- Product performance
- Category performance
- Regional performance
- Monthly trends

This allows stakeholders to identify changes without manually rebuilding the analysis.

---

## 12. Conclusion

This analysis of **9,994 e-commerce transaction records** covering **5,009 orders and 793 customers** generated total revenue of **2,297,200.86** and total profit of **286,397.02**, resulting in an overall profit margin of **12.47%**.

Technology was the strongest category by revenue and profit, while Furniture generated substantial revenue but comparatively low profitability.

West was the strongest region across revenue, profit, quantity and regional profit margin. Central recorded the lowest regional margin at **7.92%**.

At the product level, the analysis identified several high-revenue products with zero or negative profit, demonstrating the importance of analyzing profitability alongside revenue.

Annual performance improved in terms of revenue and order volume, with **2014** producing the highest revenue and profit. Monthly analysis showed that September, November and December were repeatedly among the strongest revenue periods.

The dataset contains **no missing values and no exact duplicate records**, providing a reliable foundation for the analytical and automated reporting workflow.

---

## 13. Technical Workflow

This report is part of an AI-powered automated data analysis and reporting workflow built using **n8n, Google Sheets, JavaScript, Claude AI, Gmail and GitHub**.

### Interactive Data Analyst

```text
Chat Trigger
      ↓
Google Sheets
      ↓
JavaScript Data Processing
      ↓
AI Agent
      ↓
Claude Sonnet 5.5
      ↓
Interactive Business Analysis
