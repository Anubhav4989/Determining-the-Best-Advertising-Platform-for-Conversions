# Determining the Best Advertising Platform for Conversions

## Overview
This project analyzes the performance of two distinct advertising campaigns conducted on Facebook and Google AdWords in 2019. By comparing metrics such as clicks, conversions, and cost-effectiveness, the project aims to identify the more effective platform to optimize resource allocation and improve advertising strategies.

## Business Problem
As a marketing agency, the goal is to maximize ROI for clients' advertising campaigns. This study evaluates which platform performs better, enabling the agency to make data-driven decisions for future campaigns.

## Dataset Description
The dataset comprises 365 records, each corresponding to a day in 2019, with detailed metrics for Facebook and AdWords campaigns.

### Key Features
#### Facebook Ad Campaign Data:
- **Ad Campaign Name**: Identifier for the Facebook campaign.
- **Ad Views**: Total ad views.
- **Ad Clicks**: Total clicks.
- **Ad Conversions**: Successful conversions (e.g., purchases).
- **Cost per Ad**: Daily ad expenditure.
- **Click-Through Rate (CTR)**: `(Clicks / Views) * 100`
- **Conversion Rate (CVR)**: `(Conversions / Clicks) * 100`
- **Cost per Click (CPC)**: `(Ad Cost / Clicks)`

#### AdWords Campaign Data:
- **Ad Campaign Name**: Identifier for the AdWords campaign.
- **Ad Views**: Total ad views.
- **Ad Clicks**: Total clicks.
- **Ad Conversions**: Successful conversions.
- **Cost per Ad**: Daily ad expenditure.
- **Click-Through Rate (CTR)**: `(Clicks / Views) * 100`
- **Conversion Rate (CVR)**: `(Conversions / Clicks) * 100`
- **Cost per Click (CPC)**: `(Ad Cost / Clicks)`

## Research Questions
- Which platform achieves more conversions and clicks?
- Which platform is more cost-effective?
- Do more clicks lead to more conversions?

## Libraries Used
- **Core Libraries**: `numpy`, `pandas`
- **Visualization**: `matplotlib`, `seaborn`
- **Statistical Analysis**: `scipy.stats`, `statsmodels`
- **Machine Learning**: `sklearn`
- **Warnings Handling**: `warnings`

## Steps in the Analysis
1. **Data Loading and Cleaning**
   - Converted the `Date` column to datetime format.
   - Verified data types and summary statistics.

2. **Performance Comparison**
   - Analyzed distribution of clicks and conversions.
   - Categorized daily conversions into defined ranges.
   - Visualized the frequency of high versus low conversion days.

3. **Click-to-Conversion Analysis**
   - Evaluated the relationship between clicks and conversions for both platforms using scatter plots.

## Insights
- Facebook had more high-conversion days compared to AdWords.
- AdWords struggled with days having higher conversion counts (>10).
- The relationship between clicks and conversions highlighted that more clicks generally led to more conversions but varied by platform.

## Visualizations
The project includes:
- Histograms for clicks and conversions.
- Bar charts for frequency of conversion categories.
- Scatter plots showing clicks vs. conversions.

## Conclusion
Based on the analysis:
- Facebook outperformed AdWords in terms of conversions and high-conversion days.
- AdWords requires strategic adjustments to increase its effectiveness.

## Author
Anubhav Kumar Tiwary

For inquiries, please contact:
- Email: anubhavkumartiwary0109@gmail.com
- GitHub: [Anubhav Kumar Tiwary](https://github.com/Anubhav4989)
