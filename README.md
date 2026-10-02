# E-commerce Sales Analysis Report

## Executive Summary

This report presents a comprehensive analysis of 9,994 e-commerce sales records covering 5,009 distinct orders, 793 customers, 1,862 product IDs, 3 product categories, and 4 geographic regions. The dataset contains 22 analytical columns covering orders, customers, products, sales, quantity, discounts, and profit.

Key observations from the data include:

* The dataset generated total sales revenue of **2,297,200.86** and total profit of **286,397.02**, resulting in an overall profit margin of **12.47%**.
* The dataset contains **37,873 units** sold across **5,009 orders** and **793 customers**.
* The average order value is **458.61** based on total revenue divided by distinct orders.
* **Technology** generated the highest category revenue at **836,154.03** and the highest category profit at **145,454.95**.
* **West** generated the highest regional revenue at **725,457.82** and the highest regional profit at **108,418.45**.
* **Furniture** generated substantial revenue of **741,999.80**, but its profit margin was only **2.49%**, considerably lower than Technology and Office Supplies.
* The highest-revenue product was **Canon imageCLASS 2200 Advanced Copier**, generating **61,599.82** in revenue and **25,199.93** in profit.
* The highest monthly revenue occurred in **November 2014**, with **112,326.47** in revenue.
* The highest monthly profit occurred in **December 2013**, with **17,902.73** in profit.
* The highest monthly profit margin was **27.92% in October 2013**, while the lowest was **-18.05% in January 2012**.
* The dataset contains no missing values, no exact duplicate rows, and all analyzed order and shipping dates are valid.

## Overall Sales Statistics

| Metric | Value |
|---|---:|
| Total records retrieved | 9,994 |
| Number of columns | 22 |
| Distinct orders | 5,009 |
| Distinct customers | 793 |
| Distinct product IDs | 1,862 |
| Distinct product names | 1,841 |
| Total revenue | 2,297,200.86 |
| Total profit | 286,397.02 |
| Overall profit margin | 12.47% |
| Total quantity sold | 37,873 |
| Average order value | 458.61 |
| Minimum transaction sales | 0.44 |
| Maximum transaction sales | 22,638.48 |
| Minimum transaction profit | -6,599.98 |
| Maximum transaction profit | 8,399.98 |
| Order date range | 2011-01-04 to 2014-12-31 |
| Distinct categories | 3 |
| Distinct sub-categories | 17 |
| Distinct regions | 4 |
| Distinct states | 49 |
| Distinct cities | 531 |
| Distinct customer segments | 3 |

## Category-Level Analysis

The dataset contains three product categories: Technology, Furniture, and Office Supplies.

Technology generated the highest revenue and profit, while Furniture showed a substantially lower profit margin despite generating more than 741,000 in revenue.

| Rank | Category | Revenue | Profit | Profit Margin | Quantity | Orders |
|---:|---|---:|---:|---:|---:|---:|
| 1 | Technology | 836,154.03 | 145,454.95 | 17.40% | 6,935 | 1,710 |
| 2 | Furniture | 741,999.80 | 18,451.27 | 2.49% | 8,028 | 1,868 |
| 3 | Office Supplies | 719,047.03 | 122,490.80 | 17.04% | 22,910 | 4,308 |

### Category Observations

* Technology generated the highest revenue at **836,154.03**.
* Technology also generated the highest profit at **145,454.95**.
* Office Supplies generated **719,047.03** in revenue and **122,490.80** in profit.
* Furniture generated **741,999.80** in revenue but only **18,451.27** in profit.
* Furniture's **2.49% profit margin** is substantially lower than Technology's **17.40%** and Office Supplies' **17.04%**.

## Regional Analysis

The dataset covers four regions: West, East, Central, and South.

West generated the highest revenue and profit, while Central generated the lowest revenue and had the lowest regional profit margin.

| Rank | Region | Revenue | Profit | Profit Margin | Quantity | Orders |
|---:|---|---:|---:|---:|---:|---:|
| 1 | West | 725,457.82 | 108,418.45 | 14.94% | 12,266 | 1,611 |
| 2 | East | 678,781.24 | 91,522.78 | 13.48% | 10,618 | 1,401 |
| 3 | Central | 501,239.89 | 39,706.36 | 7.92% | 8,780 | 1,175 |
| 4 | South | 391,721.91 | 46,749.43 | 11.93% | 6,209 | 822 |

### Regional Observations

* West generated the highest revenue of **725,457.82**.
* West also generated the highest profit of **108,418.45**.
* East generated **678,781.24** in revenue and **91,522.78** in profit.
* Central generated **501,239.89** in revenue but only **39,706.36** in profit.
* Central recorded the lowest regional profit margin at **7.92%**.
* South generated the lowest regional revenue at **391,721.91**, but its profit of **46,749.43** exceeded Central's profit.

## Top 5 Products by Revenue

The five products with the highest total revenue are detailed below:

| Rank | Product | Revenue | Profit | Profit Margin | Quantity |
|---:|---|---:|---:|---:|---:|
| 1 | Canon imageCLASS 2200 Advanced Copier | 61,599.82 | 25,199.93 | 40.91% | 20 |
| 2 | Fellowes PB500 Electric Punch Plastic Comb Binding Machine with Manual Bind | 27,453.38 | 7,753.04 | 28.24% | 31 |
| 3 | Cisco TelePresence System EX90 Videoconferencing Unit | 22,638.48 | -1,811.08 | -8.00% | 6 |
| 4 | HON 5400 Series Task Chairs for Big and Tall | 21,870.58 | 0.00 | 0.00% | 39 |
| 5 | GBC DocuBind TL300 Electric Binding System | 19,823.48 | 2,233.51 | 11.27% | 37 |

## Lowest Profitability Among High-Revenue Products

Several products generated significant revenue while producing very low or negative profit.

| Product | Revenue | Profit | Profit Margin |
|---|---:|---:|---:|
| Cisco TelePresence System EX90 Videoconferencing Unit | 22,638.48 | -1,811.08 | -8.00% |
| GBC DocuBind P400 Electric Binding System | 17,965.07 | -1,878.17 | -10.45% |
| High Speed Automatic Electric Letter Opener | 17,030.31 | -262.00 | -1.54% |
| Lexmark MX611dhe Monochrome Laser Printer | 16,829.90 | -458.33 | -2.72% |
| Martin Yale Chadless Opener Electric Letter Opener | 16,656.20 | -1,530.48 | -9.19% |

These products demonstrate that high sales revenue does not necessarily translate into positive profitability.

## Annual Sales Performance

The dataset covers four years from 2011 through 2014.

| Rank | Year | Revenue | Profit | Profit Margin | Quantity | Orders |
|---:|---:|---:|---:|---:|---:|---:|
| 1 | 2014 | 733,947.02 | 93,507.51 | 12.74% | 12,503 | 1,692 |
| 2 | 2013 | 608,473.83 | 81,726.93 | 13.43% | 9,810 | 1,310 |
| 3 | 2011 | 484,247.50 | 49,543.97 | 10.23% | 7,581 | 969 |
| 4 | 2012 | 470,532.51 | 61,618.60 | 13.10% | 7,979 | 1,038 |

### Annual Observations

* **2014** generated the highest annual revenue at **733,947.02**.
* **2014** also generated the highest annual profit at **93,507.51**.
* **2013** recorded the highest annual profit margin at **13.43%**.
* Revenue increased from **470,532.51 in 2012** to **733,947.02 in 2014**.
* The number of distinct orders increased from **969 in 2011** to **1,692 in 2014**.

## Monthly Performance

The dataset contains monthly sales records from January 2011 through December 2014.

### Highest Revenue Months

| Rank | Month | Revenue | Profit | Profit Margin |
|---:|---|---:|---:|---:|
| 1 | November 2014 | 112,326.47 | 9,682.55 | 8.62% |
| 2 | December 2013 | 97,237.42 | 17,902.73 | 18.41% |
| 3 | September 2014 | 90,488.72 | 11,395.44 | 12.59% |
| 4 | December 2014 | 90,474.60 | 8,532.87 | 9.43% |
| 5 | November 2013 | 82,192.32 | 4,376.07 | 5.32% |

### Highest Profit Months

| Rank | Month | Revenue | Profit | Profit Margin |
|---:|---|---:|---:|---:|
| 1 | December 2013 | 97,237.42 | 17,902.73 | 18.41% |
| 2 | October 2013 | 56,463.13 | 15,763.38 | 27.92% |
| 3 | September 2014 | 90,488.72 | 11,395.44 | 12.59% |
| 4 | March 2014 | 53,908.96 | 12,957.90 | 24.04% |
| 5 | November 2014 | 112,326.47 | 9,682.55 | 8.62% |

### Profit Margin Extremes

* The highest monthly profit margin was **27.92% in October 2013**.
* The second-highest monthly profit margin was **25.28% in March 2012**.
* The lowest monthly profit margin was **-18.05% in January 2012**.
* January 2012 generated **18,174.08** in revenue but recorded a loss of **3,281.01**.

## Profitability Analysis

The overall business generated **286,397.02** in profit from **2,297,200.86** in revenue, producing an overall profit margin of **12.47%**.

The analysis demonstrates significant differences in profitability across categories, regions, products, and months.

### Key Profitability Observations

* Technology produced the highest category profit of **145,454.95**.
* Office Supplies produced **122,490.80** in profit.
* Furniture produced only **18,451.27** in profit despite generating **741,999.80** in revenue.
* West produced the highest regional profit at **108,418.45**.
* Central had the lowest regional profit margin at **7.92%**.
* Some high-revenue products generated negative profit, including the Cisco TelePresence System EX90 and GBC DocuBind P400.
* Monthly profitability varied substantially, with some months producing negative margins.

## Data Quality

The dataset exhibits high completeness and integrity across the analyzed fields.

| Check | Value |
|---|---:|
| Records retrieved | 9,994 |
| Columns analyzed | 22 |
| Missing values | 0 |
| Exact duplicate rows | 0 |
| Invalid Order Dates | 0 |
| Invalid Ship Dates | 0 |
| Distinct orders | 5,009 |
| Distinct customers | 793 |
| Distinct product IDs | 1,862 |
| Distinct categories | 3 |
| Distinct sub-categories | 17 |
| Distinct regions | 4 |
| Distinct states | 49 |
| Distinct cities | 531 |
| Distinct customer segments | 3 |

### Data Quality Observations

* All 9,994 records contain values across the analyzed columns.
* No exact duplicate records were detected.
* All Order Date values were successfully parsed.
* All Ship Date values were successfully parsed.
* No missing values were detected across the dataset.
* The dataset contains transaction-level sales and profit information suitable for aggregation by product, category, region, customer segment, and time.

## Key Insights

* **Strong Overall Revenue and Profit:** The dataset generated **2.30 million** in total revenue and **286,397.02** in profit, resulting in a **12.47% overall profit margin**.
* **Technology Leads Profitability:** Technology generated the highest revenue (**836,154.03**) and highest profit (**145,454.95**) among the three categories.
* **Furniture Has a Low Margin:** Furniture generated **741,999.80** in revenue but only **18,451.27** in profit, resulting in a **2.49% profit margin**.
* **West Leads Regional Performance:** West generated the highest revenue (**725,457.82**) and profit (**108,418.45**) among the four regions.
* **Central Shows Lower Profitability:** Central generated **501,239.89** in revenue but only **39,706.36** in profit, giving it the lowest regional profit margin of **7.92%**.
* **Revenue Does Not Always Equal Profit:** Several high-revenue products generated negative profit, demonstrating the importance of monitoring profitability alongside sales volume.
* **2014 Was the Strongest Revenue Year:** 2014 generated **733,947.02** in revenue and **93,507.51** in profit.
* **Monthly Performance Varies Significantly:** November 2014 generated the highest monthly revenue at **112,326.47**, while October 2013 recorded the highest monthly profit margin at **27.92%**.

### Interpretation

The analysis indicates that overall sales performance is driven by a combination of product category, geographic region, and time-based factors. Technology is a major contributor to both revenue and profitability, while Furniture requires closer profitability monitoring because of its relatively low margin.

The presence of high-revenue products with negative profit also demonstrates that revenue alone is not sufficient to evaluate product performance. Profit margin should be considered alongside revenue when identifying products that contribute positively to business performance.

Regional results also vary considerably. West combines the highest revenue with the highest profit, while Central has a lower profit margin despite generating more revenue than South.

## Business Recommendations

* Monitor Furniture products and sub-categories with low profit margins to identify opportunities for pricing, discount, or cost optimization.
* Investigate high-revenue products that generate negative profit and evaluate their pricing, discount levels, and fulfillment costs.
* Analyze the drivers behind West's strong revenue and profitability and determine whether similar practices can be applied to other regions.
* Review Central-region product and discount performance because of its comparatively low **7.92%** profit margin.
* Track monthly revenue and profit together rather than relying solely on sales volume.
* Prioritize products that demonstrate both strong revenue generation and sustainable profit margins.
* Use category, region, and product-level profitability metrics as part of recurring management reporting.

## Conclusion

This analysis of **9,994 e-commerce sales records** across **5,009 orders and 793 customers** reveals total revenue of **2,297,200.86** and total profit of **286,397.02**, resulting in an overall profit margin of **12.47%**.

Technology was the strongest category by both revenue and profit, while Furniture generated substantial revenue but comparatively low profitability. West was the highest-performing region by revenue and profit, while Central recorded the lowest regional profit margin.

The analysis also identified substantial differences in product-level profitability, including several high-revenue products that generated negative profit. Annual and monthly analysis further demonstrated significant variations in revenue, profit, and margin over time.

The dataset contains no missing values, no exact duplicate rows, and no invalid analyzed dates, providing a strong foundation for business intelligence and automated reporting.

---

*Generated from the complete ecommerce dataset (`ecommerce_postgres_final(1).csv`) containing 9,994 records and 22 analytical columns. Calculations are based on the uploaded transaction-level dataset. Report prepared for the AI-Powered E-commerce Sales Analysis & Automated Reporting project using n8n, JavaScript, Claude AI, Gmail, and GitHub.*
