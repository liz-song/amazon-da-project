# Data Analysis of the Impact of Queries Containing Brand Names on CTR and Conversion Rate - Identifying Patterns and Strategies for Brand Name Queries

## Overview
This is a data analysis project focused on examining the impact of queries containing brand names on click-through rates (CTR) and further conversion rate. The primary objective is to test the hypothesis that there is a significant difference in CTR between search queries containing brand names(brand queries) and non-brand search queries(non-brand queries).
The project employs exploratory data analysis (EDA) to investigate the characteristics of search queries that incorporate brand names, aiming to uncover patterns and insights into how these queries affect essential variables for purchase decisions. By analyzing CTR and user engagement metrics, this study aims to identify current issues through performance assessment by brand and propose strategies to enhance key metrics.

## Objective
The primary goal of this project is to **analyze the impact of brand names** in search queries on **click-through rates (CTR)** and explore how **brand presence** influences **further conversion ratet**. The analysis tests the hypothesis that there is a significant difference in CTR between search queries containing brand names(brand queries) and non-brand search queries(non-brand queries). Additionally, the project aims to conduct deeper data exploration focused on brand queries to identify detailed patterns specific to each brand.

## Data Source
- **Dataset**: Kaggle - Amazon Advertising Performance Metrics
- **Link**: [Amazon Advertising Performance Metrics](https://www.kaggle.com/datasets/mayuriawati/amazon-advertising-performance-metrics/data)


## Requirements
To run the analysis, the following Python libraries are required:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Warning
Ensure that the dataset file is located in the **same directory** as the Jupyter notebook file. If the dataset is not in the correct path, you may encounter errors when running the notebook.

**Key Findings:**
- **Brand-related queries** generally attract more **user engagement**, as demonstrated by the significant difference in **CTR** between brand-related and non-brand-related queries.
- Brand performance varied across the funnel:
  - Bunmo: Balanced performance with high conversion rates.
  - Chewigem and Oombee: High initial interest but low final conversions.
  - Fidgetland, Tangle, and Speks: High brand awareness but low purchase rates.
  - Tailored strategies are needed to address specific funnel weaknesses for each brand.

**Future Work:**
- **Expand the dataset** to include diverse variables such as demographic and behavioral information for improved analysis robustness.
- **Address data imbalance and skewness** issues to enable better parametric analyses and advanced modeling.

**Conclusion:**
- The project revealed that **queries containing brand names generally attract more user engagement compared to non-brand queries.**
- **Specific funnel weaknesses for each brand must be addressed to enhance overall performance.**
- Brands like Bunmo demonstrated effective conversion strategies, while others like Chewigem and Oombee have potential for improvement in converting initial interest into final purchases.
- Future efforts should focus on optimizing marketing strategies, expanding datasets for detailed customer behavior insights, and refining analytical methods to better capture consumer behavior and drive sales.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
