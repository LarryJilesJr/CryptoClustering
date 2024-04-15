# CryptoClustering

# Cryptocurrency Clustering

This repository contains code for clustering cryptocurrency data using K-Means clustering and principal component analysis (PCA).

## Overview

Cryptocurrency markets have experienced significant growth and volatility in recent years, making it challenging for investors and analysts to understand the relationships between different cryptocurrencies. In this data analysis project, I aimed to cluster cryptocurrencies based on their market data to identify similarities and differences between them. I used K-Means clustering to cluster cryptocurrencies based on their market data. I also applied PCA to reduce the dimensionality of the data and visualize the clusters in a lower-dimensional space.

## Installation

To run the code in this repository, you'll need Python 3.x and the following libraries:

- pandas
- scikit-learn
- hvplot
- holoviews

## Data:
I collected market data for a diverse set of cryptocurrencies, including Bitcoin, Ethereum, Ripple, Litecoin, and many others. The dataset includes various features such as price change percentages over different time intervals (24 hours, 7 days, 30 days, etc.), trading volumes, market capitalization, and more.

## Methodology:
I employed the following methodology for my data analysis:

Data Preprocessing: I cleaned the dataset by handling missing values, scaling numerical features, and encoding categorical variables.

Feature Selection: To reduce the dimensionality of the dataset and focus on the most relevant features, I performed feature selection techniques such as correlation analysis and principal component analysis (PCA).

Clustering Analysis: I applied K-Means clustering algorithm to group cryptocurrencies into clusters based on their market data. I experimented with different numbers of clusters and evaluated the clustering performance using metrics such as inertia and silhouette score.

Visualization: I visualized the clusters using scatter plots and PCA projections to gain insights into the underlying structure of the data and the relationships between different cryptocurrencies.

## Results:
My analysis revealed several interesting insights:

1. Cryptocurrencies within the same cluster exhibit similar price change patterns and market behaviors.
2. Some clusters contain cryptocurrencies with high trading volumes and market capitalization, indicating their popularity and influence in the market.
3. PCA projections allowed me to visualize the clusters in a lower-dimensional space, making it easier to interpret the results and identify outliers.

## Conclusion:
Clustering analysis of cryptocurrency market data provides valuable insights into the relationships between different cryptocurrencies and helps investors and analysts make informed decisions. By understanding the clustering patterns, stakeholders can diversify their portfolios, manage risks, and capitalize on market opportunities effectively.

---
**Source Data: 

Chat GPT Provider: OpenAI Model Version: GPT-3.5 Training Data: Diverse internet text Training Duration: Training duration was about 2-3 hours @article{openai2023, author = {OpenAI}, title = {ChatGPT: A Language Model by OpenAI}, year = {2023}, url = {https://www.openai.com}, }

Class Videos

Stackoverflow