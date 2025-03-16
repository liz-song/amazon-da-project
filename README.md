# Data Analysis of the Impact of Brand Name Queries on CTR, Conversion Rate, and Brand-Specific Funnel Performance

## Overview
This project analyzes the impact of brand names in search queries on Click-Through Rate (CTR) and Conversion Rate (CVR) using web log data. The primary objective is to test the hypothesis that search queries containing brand names exhibit a higher CTR compared to non-brand queries. The analysis employs exploratory data analysis (EDA) and statistical hypothesis testing to identify patterns in brand-related queries and their influence on key performance metrics. Additionally, brand-specific funnel performance is assessed to provide targeted optimization strategies.

## Data Source
- **Dataset:** Kaggle - Amazon Advertising Performance Metrics
- **Link:** Amazon Advertising Performance Metrics

## Requirements
To run the analysis, the following Python libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
- `statsmodels`
- `TfidfVectorizer`

**Warning:** Ensure that the dataset file is located in the same directory as the Jupyter notebook file. If the dataset path is incorrect, errors may occur during execution.

## Summary of Insights
### Analysis Objectives
- Examine the impact of brand names in search queries on CTR and CVR.
- Compare performance metrics (CTR, CVR) between brand and non-brand queries.
- Conduct statistical validation using **Mann-Whitney U Test** to assess significance.
- Perform brand-specific funnel performance analysis.

### Key Findings
- **Search queries containing brand names showed, on average, a 15% higher CTR than non-brand queries.**
- Brands exhibited different performance patterns across the conversion funnel:
  - **High CTR & High CVR (e.g., Bunmo):** Strong overall performance. 
    - *Strategy:* Maintain brand trust and expand product visibility through high-quality content and user engagement strategies.
  - **High CTR & Low CVR (e.g., Chewigem, Oombee):** High initial engagement but low conversion.
    - *Strategy:* Optimize landing pages and checkout processes to reduce drop-offs, introduce targeted promotions, and refine product positioning.
  - **Low CTR & Low CVR (e.g., Fidgetland, Tangle, Speks):** Weak engagement and conversion rates.
    - *Strategy:* Increase brand awareness through SEO improvements, influencer marketing, and paid search campaigns to drive qualified traffic.
- Brand-specific funnel weaknesses were identified, highlighting areas for improvement in conversion optimization.

## Recommendations & Future Work
- **Data Expansion:** Incorporate additional behavioral and demographic data to enhance analysis depth.
- **Addressing Skewness & Imbalance:** Improve parametric testing by resolving dataset imbalances.
- **Advanced Modeling:** Apply NLP techniques to further analyze user intent and query structures.
- **Marketing Optimization:** Use insights to refine brand marketing and ad targeting strategies.

This study demonstrates how **brand-related search queries drive higher engagement** and provides actionable strategies for improving CTR and conversion performance. Future research should focus on **refining analytical methodologies and integrating more diverse datasets, including demographic information and details on the pages where conversions were initiated**, to better capture consumer behavior and optimize marketing strategies.

