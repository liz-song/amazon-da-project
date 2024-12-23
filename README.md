# Data Analysis of the Impact of Brand-Related Queries on CTR and Conversion Rate - Insights from Clustering

## Overview
This is a self-initiated data analysis project using the Amazon sales dataset from Kaggle. The goal is to analyze the impact of brand-related queries on click-through rates (CTR) and explore how brand presence influences user engagement. This analysis tests the hypothesis that there is a significant difference in CTR between brand-related search queries and non-brand-related search queries. The project involves exploratory data analysis (EDA) and clustering analysis, particularly using DBSCAN, to uncover patterns in brand-related search queries. Despite challenges such as data imbalances, this project offers valuable insights into how segmented targeting strategies can enhance advertising performance.

## Objective
The primary goal of this project is to **analyze the impact of brand names** in search queries on **click-through rates (CTR)** and explore how **brand presence** influences **user engagement**. The analysis tests the hypothesis that there is a **significant difference in CTR** between **brand-related search queries** and **non-brand-related search queries**. Additionally, **DBSCAN clustering** is applied to uncover patterns within **search queries that include brand-related terms** and explore how different **clusters of queries** exhibit distinct **user behaviors**.

## Data Source
- **Dataset**: Kaggle - Amazon Advertising Performance Metrics
- **Link**: [Amazon Advertising Performance Metrics]([https://www.kaggle.com/datasets/amazon](https://www.kaggle.com/datasets/mayuriawati/amazon-advertising-performance-metrics/data))

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
- The word '**fidget**' was identified as a key contributor to **higher CTR**, suggesting that using this keyword can enhance **customer targeting**.
- **Search queries related to the brand 'bunmo'** showed higher **conversion rates**, highlighting the impact of **brand awareness** and **trust** on purchasing decisions.
- **Narrower search query ranges** are associated with higher **conversion rates**, indicating that **segmented targeting** focusing on specific products or brands is more effective.

**Future Work:**
- Expand the dataset by including more diverse variables, such as **demographic and behavioral information**, to strengthen the analysis.
- Address data issues like **imbalance** and **skewness** to improve the accuracy and robustness of the analysis.

**Conclusion:**
This project revealed that **brand-related queries** generally lead to higher **CTR**, with the word '**fidget**' being a key contributor. It also highlighted that **brand awareness** and **trust** significantly impact **conversion rates**, particularly for the brand '**bunmo**'. Furthermore, more **specific and targeted marketing** leads to higher conversion rates, especially for narrower search queries. For broader queries, ads should emphasize the specific **brand** or **features** to attract relevant users.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
