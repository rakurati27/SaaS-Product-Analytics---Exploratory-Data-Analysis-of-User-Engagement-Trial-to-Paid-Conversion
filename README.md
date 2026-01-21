# SaaS Product Analytics: Exploratory Data Analysis of User Engagement & Trial-to-Paid Conversion”

## Executive Summary
This project explores user behavior patterns in a SaaS product to identify key drivers of trial-to-paid conversion. Through exploratory data analysis (EDA), segmentation, and targeted visualization, we uncover engagement metrics and user characteristics that distinguish converting from non-converting users, providing insights to improve onboarding flows, acquisition channels, and monetization strategies.

## Business Problem
SaaS platforms often struggle with low conversion rates from trial users to paid customers, resulting in higher Customer Acquisition Costs (CAC) and lower revenue growth. This analysis aims to:

Identify engagement patterns and indicators associated with conversion
Assess the impact of device type, referral source, and engagement metrics
Support data-driven product decisions to increase conversion and retention

## Data Flow Diagram
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/eda5ac61-1c13-49b3-9e74-13ef6531c22c" />

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
- Users who spent more time per session and completed more actions had higher conversion rates.
- Referral sources varied in conversion effectiveness — some channels produced more engaged users.
- Device type segmentation revealed different behavior patterns (e.g., desktop vs mobile).
- Visualizing engagement metrics uncovered distinct clusters of user behavior associated with conversions.

These outcomes provide actionable guidance for optimizing onboarding flows and channel strategy to boost conversions.

## Recommendations
- Focus on referral sources with higher conversion lift
- Tailor onboarding messages by device type
- Experiment with feature usage incentives in trial period
- Use engagement thresholds (session length / actions) to trigger upsell prompts

## Next Steps
- Translate engagement metrics into actionable conversion levers that product and growth teams can implement
- Use behavioral insights to optimize onboarding and activation, not just report metrics
- Link acquisition channels to down-funnel business impact (conversion, retention, LTV)
- Extend analysis toward predictive and proactive decision-making rather than retrospective reporting
