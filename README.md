# Amazon Advertising Keyword Analysis

## Business Problem

Amazon sellers often run advertising campaigns targeting many keywords.

Without analysing performance data, it can be difficult to identify which keywords are profitable and which ones are wasting advertising budget.

This analysis aims to identify profitable keywords and recommend advertising strategy improvements.

## Overview

This project analyses Amazon advertising keyword performance using Python.

The goal is to identify profitable keywords and wasted advertising spend.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains advertising performance data for Amazon keywords including:

- Clicks
- Spend
- Orders
- Sales

## Sample Data

| Keyword | Clicks | Spend | Orders | Sales |
|--------|--------|-------|--------|-------|
| mini speaker | 2131 | 2229 | 240 | 13410 |
| wireless speaker | 1343 | 1396 | 161 | 8971 |
| cheap bluetooth speaker | 2134 | 2059 | 108 | 4326 |  

## Metrics Analysed

- CPC (Cost Per Click)
- Conversion Rate
- ACOS
- ROAS

## Key Findings

Best performing keywords:
- wireless speaker
- mini speaker
- waterproof speaker

Underperforming keyword:
- cheap bluetooth speaker

Recommendation:
Increase bids for high performing keywords and reduce spend on inefficient ones.

## Visualisations

### ROAS vs Ad Spend

This chart compares advertising spend against return on ad spend (ROAS) for each keyword.  
It helps identify keywords that generate strong returns relative to their advertising investment.

<p align="center">
<img src="roas_vs_spend.png" width="600">
</p>

Insight: Keywords such as "mini speaker" and "wireless speaker" generate strong ROAS while using relatively low advertising spend, suggesting potential opportunities for scaling.

### ACOS vs Conversion Rate

This chart compares advertising cost of sale (ACOS) against conversion rate.  
It helps identify inefficient keywords that require high advertising cost but generate relatively low conversions.

<p align="center">
<img src="acos_vs_conversion.png" width="600">
</p>

Insight: "cheap bluetooth speaker" shows high ACOS and low conversion rate, indicating inefficient ad spend.

## Business Recommendations

Based on the analysis:

• Increase bids on **mini speaker**, **wireless speaker**, and **waterproof speaker** keywords due to strong ROAS.

• Reduce or pause **cheap bluetooth speaker** due to low conversion rate and poor advertising efficiency.

• Review **bluetooth speaker** and **party speaker** campaigns to improve targeting or reduce CPC.

## Skills Demonstrated

• Data analysis using Python and Pandas  
• Marketing performance analysis  
• Advertising efficiency metrics (ACOS, ROAS, Conversion Rate)  
• Data visualisation using Matplotlib  
• Business insight generation  
• Marketing optimisation recommendations  
