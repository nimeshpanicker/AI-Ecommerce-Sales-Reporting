# Part A: Stakeholder Report

# E-commerce Sales Performance Report

## 1. Executive Summary

The dataset covers 9,994 rows, with monthly data from January 2011 to December 2014. It shows total revenue of **2,297,200.86** and total profit of **286,397.02**, a **12.47%** profit margin. The business handled **5,009 orders** from **793 customers**, with an average order value of **458.61**. No currency is specified in the dataset, so values are shown without a currency symbol.

- **Category:** Technology and Office Supplies earn similar margins (17.40% and 17.04%). Furniture is a clear outlier at 2.49% despite 741,999.80 in revenue.
- **Region:** West leads on revenue and profit. Central has the lowest margin (7.92%).
- **Products:** Several top-10 revenue products have zero or negative profit.
- **Seasonality:** September, November and December are consistently the strongest revenue months in every year.

---

## 2. KPI Summary

| KPI | Value |
|---|---|
| Total Revenue | 2,297,200.86 |
| Total Profit | 286,397.02 |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Average Order Value | 458.61 |
| Total Quantity | 37,873 |

---

## 3. Product Performance

*Top 10 products by revenue. The summary identifies products by Product ID.*

| Rank | Product ID | Revenue | Profit | Profit Margin | Quantity |
|---|---|---|---|---|---|
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

**Observations**
- **TEC-CO-10004722** is the top product by revenue (61,599.82), more than double the second-ranked product. It also has the highest margin in the group (40.91%) and the highest profit (25,199.93).
- Four top-10 products exceed the overall 12.47% margin: TEC-CO-10004722, OFF-BI-10003527, TEC-CO-10001449 and TEC-MA-10001127.
- Three top-10 products are loss-making: TEC-MA-10002412 (-1,811.08), OFF-BI-10004995 (-1,878.17) and OFF-SU-10000151 (-262.00).
- FUR-CH-10002024 generated 21,870.58 in revenue with exactly 0.00 profit.
- Margins vary widely among the four OFF-BI products, from 28.24% to -10.45%, so revenue rank does not predict profitability.

---

## 4. Category Performance

| Category | Revenue | Profit | Quantity | Profit Margin |
|---|---|---|---|---|
| Technology | 836,154.03 | 145,454.95 | 6,939 | 17.40% |
| Furniture | 741,999.80 | 18,451.27 | 8,028 | 2.49% |
| Office Supplies | 719,047.03 | 122,490.80 | 22,906 | 17.04% |

**Observations**
- Technology ranks first in revenue, profit and margin.
- Office Supplies has the highest quantity (22,906), roughly 2.9 times Furniture's volume, and a 17.04% margin.
- Furniture ranks second in revenue but has by far the lowest profit (18,451.27) and a 2.49% margin, well below the 12.47% company average.

---

## 5. Regional Performance

| Region | Revenue | Profit | Quantity | Profit Margin |
|---|---|---|---|---|
| West | 725,457.82 | 108,418.45 | 12,266 | 14.94% |
| East | 678,781.24 | 91,522.78 | 10,618 | 13.48% |
| Central | 501,239.89 | 39,706.36 | 8,780 | 7.92% |
| South | 391,721.91 | 46,749.43 | 6,209 | 11.93% |

**Observations**
- West leads on revenue, profit, quantity and margin. East ranks second on all four.
- **Central vs. South:** Central has higher revenue (501,239.89 vs. 391,721.91) and quantity but lower profit (39,706.36 vs. 46,749.43). Its 7.92% margin is the lowest of the four regions.
- West and East are above the overall 12.47% margin. Central and South are below it.

---

## 6. Monthly Performance

The summary contains 48 months. Selected months illustrating the main patterns: