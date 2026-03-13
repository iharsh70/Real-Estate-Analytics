Real Estate Market Analysis
Project Overview

This project performs a comprehensive analysis of 3,000 real estate listings across 5 major cities and 5 states, representing approximately $2.43 billion in total market value.

The analysis includes:

Exploratory Data Analysis (EDA)

Statistical insights

Professional data visualizations

Business intelligence insights

Strategic recommendations

The project is designed for data analytics portfolios, job interviews, and business presentations.

Dataset Summary
Metric	Value
Total Properties	3,000
Cities	Los Angeles, Sacramento, San Francisco, San Diego, Fresno
States	CA, IL, TX, NY, FL
Total Market Value	~$2.43 Billion
Average Price	$810,859
Price Range	$100,283 – $1,499,473
Data Quality	100% (No missing values, no duplicates)
Project Deliverables
Data Files
df_clean.csv

Cleaned dataset with numeric conversions.

Contains

Original dataset fields

Numeric conversions for:

Price

Bedrooms

Bathrooms

Area

Lot Size

Shape

3000 rows × 21 columns

Purpose

Foundation dataset used for all analysis.

df_with_features.csv

Enhanced dataset with engineered features.

Additional Features

Price_per_Sqft

Decade

Price_Segment

Shape

3000 rows × 23 columns

Purpose

Supports segmentation analysis and advanced insights.

Visualizations
Real Estate Dashboard

File: 01_Real_Estate_Dashboard.png

Resolution: 20 × 14 inches (200 DPI)

Includes 12 visualizations

Property Status Distribution (Pie Chart)

Property Type Distribution (Bar Chart)

Average Price by City

Price Distribution Histogram

Days on Market by Status (Box Plot)

Average Price by Property Type

Market Segmentation by Price

Price vs Area Scatter Plot

Days on Market by City

Sell-Through Rate by Segment

Feature Correlation Heatmap

Listings by State

Use Case

Executive presentations and stakeholder dashboards.

Detailed Market Analysis

File: 02_Detailed_Market_Analysis.png

Resolution: 16 × 12 inches (200 DPI)

Includes 4 deep-dive visualizations

City Market Overview (Price vs Days on Market)

Property Type Bubble Chart

Bedroom Price Analysis

Property Status Comparison

Use Case

Market research and competitive analysis.

Price Segmentation Analysis

File: 03_Price_Segmentation_Analysis.png

Resolution: 16 × 12 inches (200 DPI)

Includes 4 segmentation visualizations

Segment Volume vs Sales

Price Distribution by Segment

Segment Characteristics Comparison

Segment Performance Metrics

Use Case

Investor presentations and market strategy analysis.

Professional Report

File: Real_Estate_Analysis_Report.docx

A 15+ page business report containing:

Executive Summary

Data Quality & Methodology

Market Overview

Geographic Analysis

Property Feature Analysis

Market Segmentation Insights

Business Insights

Power BI Dashboard Architecture

Strategic Recommendations

Conclusion

Use Case

Client deliverables and professional reports.

Key Business Insights

The analysis generated 16 major insights.

Market Insights

Real estate market shows balanced demand.

Fresno has the highest average pricing.

San Francisco properties sell fastest.

Property type demand is evenly distributed.

Pricing is primarily driven by location.

Sales Insights

Luxury segment has the highest conversion rate.

Budget segment maintains steady demand.

Sold properties show a slight price premium.

Price distribution is symmetric.

Property Insights

Homes built in the 1970s show premium pricing.

Condos provide lower-cost entry points.

Lot size has an inverse relation with price.

Mid-range segment has fastest growth.

Market Structure Insights

City listing distribution is balanced.

Price per square foot varies widely.

Average selling cycle is predictable.

Statistical Metrics
Price Statistics
Metric	Value
Mean	$810,859
Median	$815,630
Standard Deviation	$399,732
Price Range	$100,283 – $1,499,473
Skewness	-0.0193
Kurtosis	-1.17
Gini Coefficient	0.2845
Sales Activity
Metric	Value
Sell Through Rate	34.8%
Pending Rate	33.3%
For Sale	31.9%
Avg Days on Market	61.2 days
Median DOM	62 days

Fastest Market: San Francisco (59.5 days)
Slowest Market: San Diego (62.5 days)

Feature Correlation with Price
Feature	Correlation
Bathrooms	+0.0095
Bedrooms	-0.0215
Area	-0.0321
Lot Size	-0.0436
Days on Market	+0.0037

Conclusion:

Location influences price far more than property features.

Market Segmentation
Segment	Price Range	Listings	Conversion
Budget	< $470K	750	33.3%
Mid-Range	$470K – $816K	750	35.7%
Upper-Mid	$816K – $1.16M	750	33.1%
Luxury	> $1.16M	750	37.2%

Highest demand segment: Luxury

Power BI Dashboard Design

The project includes a recommended 5-page Power BI dashboard.

Page 1 – Market Overview

KPI Cards

Status Distribution

Property Type Mix

Listings by City

Page 2 – Pricing Analysis

Price Distribution

Price by Property Type

Price vs Area

Correlation Heatmap

Page 3 – Sales Performance

Days on Market by City

Sell Through Rate by Segment

City Performance Matrix

Page 4 – Property Characteristics

Price vs Bedrooms

Price vs Bathrooms

Year Built vs Price

Page 5 – Segment Deep Dive

Segment Sales Performance

Segment Composition

Segment KPI Cards

Stakeholder Insights
For Real Estate Investors

Invest in mid-range segment ($470K–$816K)

Best liquidity and return balance

San Francisco offers fastest exits

Fresno offers highest price potential

For Real Estate Companies

Focus pricing models on location

Allocate marketing budget to luxury segment

Maintain diversified property portfolios

For Mortgage Service Providers

Location-based risk modeling

Develop premium mortgage products

Market shows stable liquidity

For Real Estate Appraisers

Location dominates valuation models

Price-per-square-foot shows high variance

Luxury homes sell faster than expected

Technical Details
Category	Tools
Language	Python 3.12
Libraries	Pandas, NumPy, SciPy
Visualization	Matplotlib, Seaborn
ML Tools	Scikit-learn
File Format	CSV
Visualization Format	PNG (200 DPI)
Project Statistics
Metric	Value
Records Analyzed	3,000
Columns	15 original / 23 processed
Analytical Dimensions	10
Visualizations	20
Insights Generated	16
Dashboard Pages	5
Report Length	15+ pages



Author

Harsh Chandrakant Immadi
harshimmadi18@gmail.com



