## Awesome Chocolates — Independent Sales Analysis
## Power BI | Star Schema | DAX

## Project Overview
An end-to-end Power BI report analyzing sales performance 
across 6 geographies, multiple products, and sales teams.
Built entirely independently — star schema, DAX measures, 
and business insights developed without tutorial guidance. 
No dataset was provided — data model and business questions 
were self-defined from scratch.h.

## Business Questions Answered
1. Which geography generates the highest revenue?
2. Where should we invest marketing budget?
3. What are the monthly revenue trends by geography?
4. Which products and categories drive the most sales?
5. How is sales performance distributed across regions?

## Key Insights
- Revenue is nearly equal across all 6 geographies 
  (less than 5% variance) — suggesting balanced market presence
- UK shows declining trend post Q4 2021 — ROI analysis 
  needed before budget decision
- Australia shows upward momentum in recent months
- India represents largest untapped market relative 
  to population size

## Data Model
Built a star schema independently with 4 tables:
- Sales (fact table)
- Products (dimension)
- Locations (dimension)
- People (dimension)

## Technical Skills Used
- Power BI Desktop
- Power Query — data cleaning, conditional columns
- Star Schema data modeling
- Filter context understanding

## DAX Measures Written

Total Amount = SUM(sales[Amount])

Total Boxes = SUM(sales[Boxes])

Amount per Box = DIVIDE([Total Amount], [Total Boxes])

Variance % = DIVIDE([Total Amount] - [Total Target], [Total Target])

## Report Pages
* Page 1: Salesperson Performance & Geography Revenue
* Page 2: Category Sales Distribution
* Page 3: Product Profitability & Shipment Analysis
* Page 4: Geography Trends & Marketing Investment Analysis
* Page 5: UK Market Decline Analysis

## Screenshots

## Highest Sales per Box By Salesperson
![Page 1](https://github.com/DeepakKhati/Sales-Analysis-Power-BI/blob/main/screenshots/01_Highest_Per_Box.png)

## Category with Highest % of Total Sales 
![Page 2](https://github.com/DeepakKhati/Sales-Analysis-Power-BI/blob/main/screenshots/02_Category_with_highest_percent.png)

## Lowest Per Box 
![Page 3](https://github.com/DeepakKhati/Sales-Analysis-Power-BI/blob/main/screenshots/03_Lowest_Per_Box.png)

## Geography Trends 
![Page 4](https://github.com/DeepakKhati/Sales-Analysis-Power-BI/blob/main/screenshots/04_Geography_Trends.png)

## Toolkit 
![Page 5](https://github.com/DeepakKhati/Sales-Analysis-Power-BI/blob/main/screenshots/05_Toolkit_country.png)


## Known Limitations
- Dataset does not include marketing spend data 
  — ROI analysis recommended as next step
- Data covers 2021-2022 only — trends may not 
  reflect current market conditions
- No cost data available — profitability analysis 
  limited to revenue metrics only

## Tools
Power BI Desktop | Power Query | DAX
