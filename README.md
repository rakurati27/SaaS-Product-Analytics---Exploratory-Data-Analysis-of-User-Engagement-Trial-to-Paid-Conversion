# SaaS Product Analytics: Exploratory Data Analysis of User Engagement & Trial-to-Paid Conversion”

## Executive Summary
This project explores user behavior patterns in a SaaS product to identify key drivers of trial-to-paid conversion. Through exploratory data analysis (EDA), segmentation, and targeted visualization, we uncover engagement metrics and user characteristics that distinguish converting from non-converting users, providing insights to improve onboarding flows, acquisition channels, and monetization strategies.

## Business Problem
SaaS platforms often struggle with low conversion rates from trial users to paid customers, resulting in higher Customer Acquisition Costs (CAC) and lower revenue growth. This analysis aims to:

Identify engagement patterns and indicators associated with conversion
Assess the impact of device type, referral source, and engagement metrics
Support data-driven product decisions to increase conversion and retention

## Data Flow Diagram
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/15782862-64cc-4ea3-9da8-68752abbe8a8" />

## Methodology
Data Cleaning & Profiling
- Checked for missing values
- Standardized data types
- Cleaned inconsistent entries

Exploratory Data Analysis (EDA)
- Univariate analysis: distributions of key metrics
- Bivariate analysis: engagement vs conversion
- Segmentation by device type & referral source

SQL‐Driven Metrics
- Aggregated conversion rates
- Identified high-impact engagement activities
- Computed engagement KPIs (e.g., average session time)

Visualization & Storytelling
- Side-by-side comparison of converters vs non-converters
- Trends over time and across user segments

## Skills Demonstrated
| Technology           | Purpose                                 |
| -------------------- | --------------------------------------- |
| Python               | Data manipulation, statistical analysis |
| Pandas               | Data preprocessing                      |
| NumPy                | Numerical calculations                  |
| Matplotlib / Seaborn | Visualization                           |
| SQL                  | Aggregations, filtering, KPI queries    |
| GitHub               | Version control                         |

## Key Insights
Users who spent more time per session and completed more actions had higher conversion rates.
Referral sources varied in conversion effectiveness — some channels produced more engaged users.
Device type segmentation revealed different behavior patterns (e.g., desktop vs mobile).
Visualizing engagement metrics uncovered distinct clusters of user behavior associated with conversions.

These outcomes provide actionable guidance for optimizing onboarding flows and channel strategy to boost conversions.

## Recommendations
Focus on referral sources with higher conversion lift
Tailor onboarding messages by device type
Experiment with feature usage incentives in trial period
Use engagement thresholds (session length / actions) to trigger upsell prompts

## Next Steps
Build a predictive model for conversion likelihood
Integrate time-based retention analysis
Convert notebooks into modular scripts and create dashboards
