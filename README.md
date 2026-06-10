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
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/23944253-7044-4515-a413-1b2ceba6ad7b" />


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

- **West region leads** with 31.4% of total revenue.
- **Revenue grew 50.5%** over four years despite a 2016 dip of 4.3%.
- **Technology dominates revenue** despite having the fewest 
  transactions — Phones alone generate 14.5% of total revenue.
- **High volume ≠ high revenue** — Binders lead transaction count 
  (1,492 orders) but generate only 8.8% of revenue.
- **Top 5 states generate 51.9%** of revenue — California alone 
  exceeds all bottom 5 states combined.
- **Sales peak every November** and drop every January — a 
  consistent four-year structural pattern.
- **Consumer segment drives 50.8%** of revenue; Home Office has 
  the highest average order value at $243.

## Regional Performance

<img width="504" height="253" alt="image" src="https://github.com/user-attachments/assets/7d36a4da-fb09-4c31-81d7-fed24921a182" />

  
The West region leads all four regions with **$710.2K in revenue 
(31.4% share)**, followed closely by East at $669.5K (29.6%). 
Central contributes 21.8% and South trails at 17.2%.

The gap between West (31.4%) and South (17.2%) represents a 
**14.2 percentage point difference** — indicating uneven geographic 
revenue distribution across the business.

## Revenue Trends 2015–2018

<img width="623" height="265" alt="image" src="https://github.com/user-attachments/assets/03cebc96-994c-4ace-9901-3a3a93a9dbb6" />


Revenue grew **50.5% across the full four-year period**, from 
$479.9K in 2015 to $722.1K in 2018. 
The journey was not linear: Overall revenue followed a consistent  upward trajectory across all four years.

- Q4 peaks every year — the highest quarter in each year is always Q4 without exception.

- A recurring Q1 dip visible across all four years.

- 2016 shows the flattest period — peaks and troughs remained at similar levels to 2015.

- Growth visibly accelerated from 2017 — both peaks and troughs rose sharply through 2017 and 2018.

- Highest single quarter: 2018 Q4 at $278.4K.

>At the quarterly level, **Q4 consistently outperforms all other quarters every year without exception**. The highest single quarter was 2018 Q4 at $278.4K.



## Category Performance

<img width="512" height="392" alt="image" src="https://github.com/user-attachments/assets/4b09fd36-663e-4f9d-8509-c938348fbafd" />


**Transaction count and revenue tell completely different stories** 
about the same sub-categories — a critical finding for resource 
allocation decisions.

- **Technology** leads revenue despite the fewest transactions.
- **Phones** generate 14.5% of total revenue ($327.8K) with 
  moderate order volume.
- **Binders** lead transaction count at 1,492 orders but generate 
  only 8.8% of revenue ($200K).
- **Fasteners** represent the weakest performer — low count and 
  just $3K in revenue.
- **Copiers** show the highest revenue per transaction — only 66 
  orders but $146K revenue.

> High order volume does not guarantee high revenue. Transaction 
> count alone is a misleading measure of sub-category value.

## Geographic Performance

<img width="627" height="380" alt="image" src="https://github.com/user-attachments/assets/86eba694-b5aa-4d73-9a79-a81518da02c2" />


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

<img width="545" height="380" alt="image" src="https://github.com/user-attachments/assets/e2a0fbfe-09bb-470a-98e6-b99d645872e1" />


Monthly revenue analysis across all four years reveals a 
**consistent and predictable seasonal pattern**:

- **November** is the strongest month every year ($21.9K average).
- **September** produces a notable mid-year peak ($18.8K average).
- **January** is the weakest month every year ($5.9K average).
- **February** consistently follows as the second weakest ($3.7K).

This pattern repeats without exception across 2015, 2016, 2017 
and 2018 — confirming it is a **structural business characteristic**, 
not random variation. The business should align inventory, 
staffing and marketing spend with this known cycle.


## Customer Segments

<img width="529" height="265" alt="image" src="https://github.com/user-attachments/assets/010db45c-17ae-425c-b113-ab6315756f22" />


| Segment  | Revenue | AOV |
|---|---|---|
| Cunsumer | $1.1M | $225.07 |
| Corporate | $688.5K | $233.15 |
| Home Office | $425.0k | $243.40 |

**Consumer** generates the highest revenue but has the lowest average order value (AOV), indicating strong performance driven by order volume. 

**Home Office** shows the opposite pattern—lower overall revenue but the highest AOV, reflecting fewer yet higher-value purchases.


## Business Recommendations

1. **Defend West region leadership** — invest in retention and 
   expansion marketing in the dominant region.
2. **Grow the South region** — 17.2% share indicates underdevelopment 
   relative to population and market size.
3. **Build Q1 recovery strategies** — January consistently underperforms; 
   targeted promotions could lift the annual weakest month.
4. **Prioritise Technology category** — highest revenue per transaction 
   across all sub-categories.
5. **Target Home Office segment expansion** — highest AOV, lowest 
   customer count, largest untapped growth opportunity.
6. **Focus geographic expansion on proven markets** — California, 
   New York and Texas demonstrate established buying behaviour.


## Tools Used

**Technical Skills:**
- Microsoft Excel (Pivot Tables, Power Query, GETPIVOTDATA).
- Dynamic KPI cards with GETPIVOTDATA formulas.
- Slicer-driven filtering with Report Connections.
- VBA macro for filter clearing.
- Combo charts, line charts, horizontal bar charts.

**Analytical Skills:**
- Business question formulation.
- Volume vs value analysis.
- Seasonal pattern identification.
- Geographic performance analysis.
- Customer segmentation analysis.
- Dashboard design principles.


[View Interactive Dashboard](https://github.com/Princess-Okere/Superstore-Sales-Dashboard/blob/ae4c4aaee695fc6771819d1df9661d87926dd1ee/train%20analysis%20%26%20dashboard.xlsm)

*Dataset: US Superstore Sales | Source: Kaggle | 
Tool: Microsoft Excel | Period: 2015–2018*



  



