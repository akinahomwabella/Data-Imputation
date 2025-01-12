# Data Imputation: Numerical Analysis in Data Science

**Author:** Akinahom Wabella  
**Institution:** Department of Mathematics and Statistics, Minnesota State University, Mankato  
**Date:** December 5, 2024  

## Overview

This project explores the application of **numerical analysis techniques** for improving prediction accuracy and data imputation in data science, with a focus on high-stakes domains like **financial stock markets** and **social media engagement**. By leveraging methods such as **Spline Interpolation**, **Polynomial Interpolation**, and **KNN Imputation**, the research demonstrates improvements in machine learning model performance through addressing missing or incomplete data.

## Objectives

1. **Evaluate Advanced Imputation Techniques**  
   Assess the impact of imputation methods like spline interpolation and KNN-based approaches on data quality and model accuracy.
   
2. **Enhance Feature Engineering**  
   Introduce transformations such as log changes, rolling averages, and sentiment analysis tailored to financial forecasting and social media engagement classification.

3. **Compare Domain-Specific Outcomes**  
   Analyze the effectiveness of these methods across financial and social media datasets to derive cross-domain insights.

## Methodology

### Data Collection

- **Financial Data**: Stock market data for companies like Apple, Tesla, Meta, and Microsoft, sourced from Yahoo Finance (2021-2024).  
- **Social Media Data**: Twitter engagement dataset from Kaggle, enriched with features like sentiment analysis, text length, and hashtags.

### Techniques

- **Interpolation Methods**: Linear, spline, and KNN imputation for handling missing data.  
- **Feature Engineering**: Lagged features, moving averages, and TF-IDF vectorization for enriched datasets.  
- **Predictive Models**: ARIMA, Prophet, LSTM, Logistic Regression, Random Forest, and Neural Networks.

## Results

### Financial Data

- **Models Used**: ARIMA, Prophet, LSTM  
- **Key Findings**: LSTM outperformed others for volatile stocks like Tesla and Meta, while Prophet excelled in capturing smooth trends.  
- **Imputation Impact**: Spline interpolation and KNN significantly enhanced data completeness and model accuracy.

### Social Media Data

- **Models Used**: Logistic Regression, Random Forest, Neural Networks  
- **Key Findings**: Random Forest achieved the best overall performance (F1-Score: 92.28%), excelling in sentiment classification tasks with TF-IDF integration.

## Key Insights

1. **Imputation Methods**: KNN is effective for non-linear datasets, while linear interpolation suits smooth trends.  
2. **Model Selection**: LSTM is ideal for highly volatile data, while Prophet is best for long-term trends with seasonality.  
3. **Real-World Applications**: Improved forecasting models aid in portfolio management, risk assessment, and engagement classification.

## Data and Code

- **Datasets**:  
  - Twitter Sentiment Analysis ([Kaggle](https://www.kaggle.com))  
  - Yahoo Finance ([API](https://finance.yahoo.com))  
- **Code Repository**: [GitHub - Data Imputation Project](https://github.com/akinahomwabella/Data-Imputation)
- **Research Paper**:https://www.researchgate.net/profile/Akinahom-Wabella

## References

1. Little, R. J. A., & Rubin, D. B. (2019). *Statistical Analysis with Missing Data*. Wiley.  
2. Evan Buuren, S. (2018). *Flexible Imputation of Missing Data*. Chapman and Hall/CRC.  
3. Jordan, M. I., & Mitchell, T. M. (2015). Machine learning: Trends, perspectives, and prospects. *Science, 349(6245)*.  
4. Floridi, L., & Cowls, J. (2019). A unified framework of five principles for AI in society. *Harvard Data Science Review*.  

---

This research emphasizes the importance of high-quality data and numerical analysis in building robust AI systems, paving the way for more reliable applications in finance and social media analytics.
