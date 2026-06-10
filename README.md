# US Superstore Sales Performance Dashboard (2015–2018)

An interactive sales performance dashboard analyzing 9,800 retail 
transactions from a US Superstore across four years (2015–2018). 
Built entirely in Microsoft Excel using Power Query, Pivot Tables, 
GETPIVOTDATA formulas, and dynamic slicer-driven filtering.

## Table of Contents
- [Dashboard Preview](#dashboard-preview)
- [Project Overview](#project-overview)
- [Business Questions](#business-questions)
- [Key Findings](#key-findings)
- [Regional Performance](#regional-performance)
- [Revenue Trends 2015–2018](#revenue-trends-20152018)
- [Category Performance](#category-performance)
- [Geographic Performance](#geographic-performance)
- [Seasonal Patterns](#seasonal-patterns)
- [Customer Segments](#customer-segments)
- [Business Recommendations](#business-recommendations)
- [Tools Used](#tools-used)

## Dashboard Preview
[View Full Dashboard Overview](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/969fbc02d0415b7cb91e2c8f04d7868cb7305cbc/Dashboard-Overview.png)

## Project Overview
---
| Detail | Information |
|---|---|
| Dataset | US Superstore Sales |
| Rows | 9,800 transactions |
| Period | 2015 – 2018 |
| Tool | Microsoft Excel |
| Features | Dynamic slicers, KPI cards, Pivot Tables, Power Query |
---

## Business Questions

This dashboard was built to answer seven business questions:

1. How does revenue compare across the four US regions, and what 
   is each region's percentage share of total sales?
2. How did revenue evolve quarter by quarter across 2015–2018, 
   and what does the quarterly breakdown reveal about growth 
   momentum and seasonal peaks?
3. Which product category produces the most revenue?
4. Does the sub-category with the highest transaction count also 
   generate the most revenue — or is there a gap between volume 
   and value?
 5. Which 5 states generate the highest revenue and which 5 
   generate the lowest — and what is the gap between them?
6. What seasonal patterns exist in monthly revenue across the 
   four-year period?
7. How do the three customer segments (Consumer, Corporate, 
   Home Office) compare by revenue and average order value?

## Key Findings

- **West region leads** with 31.4% of total revenue
- **Revenue grew 50.5%** over four years despite a 2016 dip of 4.3%
- **Technology dominates revenue** despite having the fewest 
  transactions — Phones alone generate 14.5% of total revenue
- **High volume ≠ high revenue** — Binders lead transaction count 
  (1,492 orders) but generate only 8.8% of revenue
- **Top 5 states generate 51.9%** of revenue — California alone 
  exceeds all bottom 5 states combined
- **Sales peak every November** and drop every January — a 
  consistent four-year structural pattern
- **Consumer segment drives 50.8%** of revenue; Home Office has 
  the highest average order value at $243

## Regional Performance

[View Regional performance Chart](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/591083688b0eb13222c1fe4c7034b56a493de82e/Chart_01%20Revenue%20trend%20by%20Region.png)
  
The West region leads all four regions with **$710.2K in revenue 
(31.4% share)**, followed closely by East at $669.5K (29.6%). 
Central contributes 21.8% and South trails at 17.2%.

The gap between West (31.4%) and South (17.2%) represents a 
**14.2 percentage point difference** — indicating uneven geographic 
revenue distribution across the business.

## Revenue Trends 2015–2018

[View Revenue Trend Chart](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/591083688b0eb13222c1fe4c7034b56a493de82e/Chart_02%20Revenue%20trend%20by%20Year(Qtr).png)

Revenue grew **50.5% across the full four-year period**, from 
$479.9K in 2015 to $722.1K in 2018. The journey was not linear:

- **2016**: Revenue declined 4.3% — the only down year in the dataset
- **2017**: Recovered strongly with 30.6% growth — the strongest 
  single-year growth recorded
- **2018**: Continued growth at 20.3%

At the quarterly level, **Q4 consistently outperforms all other 
quarters every year without exception**. The highest single quarter 
was 2018 Q4 at $278.4K.

## Category Performance

[View Category Chart](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/c216671039d14afad70b413614c29493ca384a01/Chart_04%20Revenue(%26%20product%20count)%20by%20Category%20and%20sub-category.png)

**Transaction count and revenue tell completely different stories** 
about the same sub-categories — a critical finding for resource 
allocation decisions.

- **Technology** leads revenue despite the fewest transactions
- **Phones** generate 14.5% of total revenue ($327.8K) with 
  moderate order volume
- **Binders** lead transaction count at 1,492 orders but generate 
  only 8.8% of revenue ($200K)
- **Fasteners** represent the weakest performer — low count and 
  just $3K in revenue
- **Copiers** show the highest revenue per transaction — only 66 
  orders but $146K revenue

> High order volume does not guarantee high revenue. Transaction 
> count alone is a misleading measure of sub-category value.

## Geographic Performance

[View States Performance Chart](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/8ae2a46ec0b835b158ad3d4a6908d8bb0cf11915/Chart_05%20Revenue%20across%20top%20%26%20bottom%205%20States.png)

Geographic revenue is heavily concentrated. The **top 5 states 
generate 51.9% of total revenue** while the **bottom 5 generate 
just 0.3%**.

**Top 5 States:**
| State | Revenue |
|---|---|
| California | $446.3K |
| New York | $306.4K |
| Texas | $168.6K |
| Washington | $135.2K |
| Pennsylvania | $116.3K |

**Bottom 5 States:**
| State |  Revenue |
|---|---|
| Wyoming | $1.6K |
| South Dakota | $1.3K |
| Maine |  $1.3K |
| West Virginia | $1.2K |
| North Dakota | $920 |

>**California alone ($446.3K) exceeds all five bottom states combined ($6K).**


## Seasonal Patterns

![Seasonal Patterns Chart](chart_06_seasonal_patterns.png)

Monthly revenue analysis across all four years reveals a 
**consistent and predictable seasonal pattern**:

- **November** is the strongest month every year ($21.9K average)
- **September** produces a notable mid-year peak ($18.8K average)
- **January** is the weakest month every year ($5.9K average)
- **February** consistently follows as the second weakest ($3.7K)

This pattern repeats without exception across 2015, 2016, 2017 
and 2018 — confirming it is a **structural business characteristic**, 
not random variation. The business should align inventory, 
staffing and marketing spend with this known cycle.





  



