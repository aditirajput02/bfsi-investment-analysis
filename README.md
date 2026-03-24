# BFSI Investment Product Dashboard

## Problem Statement
Financial firms lack visibility into which investment
products (SIP, MF, Insurance, FD) are preferred by
which customer segments — leading to poorly targeted
sales pitches and lost revenue.

## Dataset
- 1,000 customer records with 10 fields
- Fields: Age Band, Income Band, Risk Profile,
  Product, City, Channel, Investment Amount,
  Tenure, Satisfaction
- Source: Synthetic dataset modelled on patterns
  observed during AIM India exposure

## Dashboard Features
- 4 KPI cards: Avg Ticket, Customer Count,
  Satisfaction Rate, Total AUM (₹)
- Bar chart: Product preference by age group
- Donut chart: Risk profile distribution
- Scatter plot: Age vs Investment by risk profile
- Matrix: Avg investment by income band x product
- 3 interactive slicers: Age Band, City, Channel

## Key Business Insights

**Insight 1 — Product targeting**
SIP is preferred by 28% of 18-35 customers vs only
5% among 56+ customers. Sales teams should focus
digital SIP onboarding on young earners via App
and Online channels.

**Insight 2 — High value cross-sell**
Customers earning 12L+ invest 4x more in ULIPs
than the dataset average. Trigger ULIP cross-sell
campaigns for high-income FD holders.

**Insight 3 — Senior segment gap**
56+ customers hold 35% of all Fixed Deposits but
have very low health insurance uptake (13%).
Bundling health insurance into FD renewal
touchpoints is a high-margin opportunity.

## Business Impact

- Enables targeted product marketing by segment
- Identifies high-value customers for cross-selling
- Helps improve conversion rates through data-driven sales strategy

## Tools Used
- Microsoft Excel — data cleaning, derived columns
- Power BI Desktop — dashboard, DAX measures

## DAX Measures Written
- Customer Count = COUNTROWS(Cleaned_Data)
- Total AUM = SUM(Cleaned_Data[Investment_Amount_INR])
- Avg Ticket = AVERAGE(Cleaned_Data[Investment_Amount_INR])
- Satisfaction Rate = DIVIDE(satisfied count, total)

## Files in This Repository
- BFSI Customer Investment Behavior Analysis Power BI Dashboard.pbix
- BFSI Investment Dashboard Data.xlsx
- BFSI Customer Investment Behavior Analysis Power BI Dashboard.pdf
- /screenshots — 3 dashboard screenshots

## Why This Project
This project was inspired by real customer interaction patterns observed during my internship at AIM India,
where understanding investor behavior was critical for product positioning and sales strategy.

## Author
Aditi Rajput | MBA Student | Data Analytics
