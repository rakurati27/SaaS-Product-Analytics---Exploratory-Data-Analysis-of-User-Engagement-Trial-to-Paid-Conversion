# SaaS Product Analytics: Exploratory Data Analysis of User Engagement & Trial-to-Paid Conversion”

## Executive Summary
This project analyzes trial-to-paid conversion behavior in a SaaS platform to identify early engagement signals associated with higher conversion likelihood.
Using SQL-driven metrics, exploratory analysis, and behavioral segmentation on a representative sample dataset, the analysis focuses on how user engagement patterns differ between converting and non-converting users and translates those findings into actionable product and growth recommendations aimed at improving conversion efficiency and reducing Customer Acquisition Cost (CAC)

## Data Source
The dataset used in this project was sourced from Kaggle and consists of a sample SaaS user engagement dataset (~1,000 records) designed to simulate trial-to-paid conversion behavior.

The dataset is clean and well-structured, with no missing or malformed values. As a result, the emphasis of this project is on analytical reasoning, metric definition, and insight generation, rather than extensive data cleaning.

## Business Problem
SaaS companies often experience low trial-to-paid conversion rates, increasing CAC and limiting revenue growth. While many users sign up for trials, only a subset demonstrate behaviors that indicate strong purchase intent.

### Key Questions Addressed
- Which user engagement behaviors during the trial period are most strongly associated with conversion?
- How do engagement levels differ between converting and non-converting users?
- Do device type and referral source influence engagement depth and conversion likelihood?
- Where can product and growth teams intervene to improve conversion efficiency?

## Workflow
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/cb5a53ec-8cea-4cc9-ade7-bcb6dcd167f3" />

## Methodology
# Data Review & Validation
- Reviewed dataset structure and column definitions
- Verified dataset completeness and consistency
- Confirmed absence of missing or malformed values
- Validated conversion labels and engagement metrics
Since the dataset was pre-cleaned, the analysis prioritizes metric ownership and behavioral interpretation, reflecting how analysts often work with analytics-ready data in real business environments.

# Metric Definitions (Metric Ownership)
- Trial-to-Paid Conversion Rate
  Paid users ÷ total trial users
- Activation Metric
  Users completing ≥ X meaningful actions within the trial period
- Engagement Intensity
  Combination of session duration and number of user actions
- Time-to-Conversion
  Time elapsed between trial signup and first payment
These metrics were designed to capture early user intent, not just surface-level activity.

# Exploratory & Segmented Analysis
- Univariate analysis of engagement and usage metrics
- Bivariate analysis of engagement metrics vs conversion outcomes
- Segmentation by:
  Device type
  Referral source
  Engagement intensity bands
- SQL-based aggregation of conversion KPIs across user segments

# Visualization & Storytelling
- Side-by-side comparisons of converters vs non-converters
- Segment-level engagement and conversion trends
- Visual identification of behavioral patterns associated with higher conversion likelihood

## Key Insights
- Users exhibiting higher engagement intensity during the trial period demonstrated a substantially higher likelihood of conversion, suggesting early activation as a leading indicator of purchase intent.
- Referral sources varied not only in signup volume but also in down-funnel engagement quality, with certain channels producing more engaged trial users.
- Desktop users showed longer sessions and higher engagement depth compared to mobile users, indicating potential onboarding or usability friction on mobile devices.
- Engagement patterns revealed distinct behavioral groupings, separating casual evaluators from high-intent trial users even within a limited sample dataset.

## Recommendations
- Prioritize acquisition channels that consistently generate high-engagement trial users, even if total signup volume is lower, to improve CAC efficiency.
- Optimize onboarding flows to guide users toward high-impact activation actions early in the trial lifecycle.
- Investigate and reduce early-stage mobile friction to improve engagement depth and activation.
- Use engagement thresholds to trigger contextual nudges or upgrade prompts during the trial period.

## Skills Demonstrated
| Technology           | Purpose                                    |
| -------------------- | ------------------------------------------ |
| Python               | Data manipulation and exploratory analysis |
| Pandas               | Data preprocessing and transformation      |
| NumPy                | Numerical computations                     |
| Matplotlib / Seaborn | Visualization and insight communication    |
| SQL                  | Aggregations, filtering, KPI computation   |
| GitHub               | Version control and documentation          |

## Limitations
- The analysis is based on a sample dataset (~1,000 users) and may not capture all behaviors present in large-scale production environments.
- Insights are directional, intended to inform hypotheses rather than provide statistically conclusive results.
- Real-world implementation would require validation using larger datasets and controlled experimentation.

## Next Steps
- Scale the analysis using production-level data to validate engagement-conversion relationships.
- Extend analysis to downstream metrics such as retention and Lifetime Value (LTV).
- Develop a conversion propensity model using early engagement features.
- Operationalize insights through dashboards and A/B testing frameworks.
