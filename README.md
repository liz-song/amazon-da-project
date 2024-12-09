# Brand vs. Non-Brand Queries - Exploring CTR Trends through Data Analysis

## Overview
This is a self-initiated data analysis project using the Amazon sales dataset from Kaggle. The goal is to analyze the relationship between brand-related and non-brand-related search queries and their click-through rates (CTR). The project also includes hypothesis testing, exploratory data analysis (EDA), and clustering analysis to identify patterns in user behavior.

## Objective
The primary goal of this project is to **analyze the impact of brand names** in search queries on **click-through rates (CTR)** and explore how **brand presence** influences **user engagement**. The analysis tests the hypothesis that there is a **significant difference in CTR** between **brand-related search queries** and **non-brand-related search queries**.

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

## Key Findings
- **Branded queries** tend to have **higher CTR** compared to non-branded queries.
- **Clustering analysis** revealed that specific clusters of data exhibited significantly different CTR behaviors.
- **Data imbalances** were observed, which impacted the clustering process and highlighted the need for further data collection.

## Limitations
- Data imbalance and high skewness.

## Future Work
- Acquire more data to satisfy normality and conduct parametric tests.
- Develop predictive models using machine learning or deep learning with an enhanced dataset.

## Conclusion
This project provides valuable insights into the impact of brand presence in search queries on CTR. It serves as a foundation for future work to improve predictive models and further analyze user engagement.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
