# E-commerce Sales Performance Report

## 1. Executive Summary

This analysis covers **9,994 transaction records** across **22 fields**. Total revenue is **2,297,200.86**, total profit is **286,397.02**, and overall profit margin is **12.47%**.

Technology is the strongest category by revenue and profit, while Furniture has the weakest margin. West leads regional revenue and profit, while Central has the lowest regional margin.

## 2. KPI Summary

| KPI | Value |
|---|---:|
| Records | 9,994 |
| Revenue | 2,297,200.86 |
| Profit | 286,397.02 |
| Profit Margin | 12.47% |
| Orders | 5,009 |
| Customers | 793 |
| Quantity | 37,873 |
| Average Order Value | 458.61 |
| Order Date Range | 2011-01-04 to 2014-12-31 |

## 3. Category Performance

| Category        |   Revenue |    Profit |   Quantity |   Orders |   Margin % |
|:----------------|----------:|----------:|-----------:|---------:|-----------:|
| Technology      | 836154.03 | 145454.95 |       6939 |     1544 |      17.40 |
| Furniture       | 741999.80 |  18451.27 |       8028 |     1764 |       2.49 |
| Office Supplies | 719047.03 | 122490.80 |      22906 |     3742 |      17.04 |

**Finding:** Technology leads revenue. Furniture has the lowest margin at 2.49%.

## 4. Regional Performance

| Region   |   Revenue |    Profit |   Quantity |   Orders |   Margin % |
|:---------|----------:|----------:|-----------:|---------:|-----------:|
| West     | 725457.82 | 108418.45 |      12266 |     1611 |      14.94 |
| East     | 678781.24 |  91522.78 |      10618 |     1401 |      13.48 |
| Central  | 501239.89 |  39706.36 |       8780 |     1175 |       7.92 |
| South    | 391721.91 |  46749.43 |       6209 |      822 |      11.93 |

**Finding:** West leads revenue and profit. Central has the lowest margin at 7.92%.

## 5. Top Products by Revenue

| Product Name                                                                |   Revenue |   Profit |   Quantity |   Margin % |
|:----------------------------------------------------------------------------|----------:|---------:|-----------:|-----------:|
| Canon imageCLASS 2200 Advanced Copier                                       |  61599.82 | 25199.93 |         20 |      40.91 |
| Fellowes PB500 Electric Punch Plastic Comb Binding Machine with Manual Bind |  27453.38 |  7753.04 |         31 |      28.24 |
| Cisco TelePresence System EX90 Videoconferencing Unit                       |  22638.48 | -1811.08 |          6 |      -8.00 |
| HON 5400 Series Task Chairs for Big and Tall                                |  21870.58 |     0.00 |         39 |       0.00 |
| GBC DocuBind TL300 Electric Binding System                                  |  19823.48 |  2233.51 |         37 |      11.27 |
| GBC Ibimaster 500 Manual ProClick Binding System                            |  19024.50 |   760.98 |         48 |       4.00 |
| Hewlett Packard LaserJet 3310 Copier                                        |  18839.69 |  6983.88 |         38 |      37.07 |
| HP Designjet T520 Inkjet Large Format Printer - 24" Color                   |  18374.90 |  4094.98 |         12 |      22.29 |
| GBC DocuBind P400 Electric Binding System                                   |  17965.07 | -1878.17 |         27 |     -10.45 |
| High Speed Automatic Electric Letter Opener                                 |  17030.31 |  -262.00 |         11 |      -1.54 |

## 6. Annual Performance

|    Year |   Revenue |   Profit |   Orders |   Margin % |
|--------:|----------:|---------:|---------:|-----------:|
| 2011.00 | 484247.50 | 49543.97 |   969.00 |      10.23 |
| 2012.00 | 470532.51 | 61618.60 |  1038.00 |      13.10 |
| 2013.00 | 608473.83 | 81726.93 |  1310.00 |      13.43 |
| 2014.00 | 733947.02 | 93507.51 |  1692.00 |      12.74 |

## 7. Data Quality

- Missing values: **0**
- Exact duplicate rows: **0**
- Rows with invalid/missing order or ship dates: **0**
- Source sheet used: **Data**
- Public repository recommendation: do not publish raw customer-level transaction records.

## 8. Key Insights

1. Technology is the strongest category by both revenue and profit.
2. Furniture requires profitability attention because its margin is materially below the other categories.
3. West is the leading region by revenue and profit.
4. Central has the weakest regional margin and should be investigated for discounting, product mix or cost drivers.
5. Revenue leadership does not automatically imply profit leadership; product-level margin should be monitored alongside sales.
6. Annual performance shows continued revenue growth toward 2014.

## 9. Recommendations

- Review low-margin Furniture products and discount levels.
- Investigate the drivers of Central's lower margin.
- Track product-level profitability rather than revenue alone.
- Add automated threshold alerts for margin deterioration.
- Add week-over-week and month-over-month comparisons.
- Validate generated AI report figures against the deterministic KPI summary before publishing.

## 10. Technical Workflow

**Google Sheets → JavaScript KPI Analysis → Claude AI → GitHub → Gmail**

The supplied project report describes the same architecture and emphasizes that deterministic calculations should remain in the code layer while Claude is used for interpretation. fileciteturn0file0L52-L55
