# Detecting Credit Card Fraud

## Overview
This project implements a machine learning solution for credit card fraud detection, addressing one of the most critical challenges in the financial technology sector. With the rapid growth of digital payments and e-commerce, particularly accelerated by global shifts in consumer behavior, fraud detection systems have become more crucial than ever.

## Project Significance
Credit card fraud results in billions of dollars in losses annually worldwide. In 2024, as digital transactions continue to surge, the importance of robust fraud detection systems has never been greater. This project demonstrates modern approaches to detecting fraudulent transactions using machine learning, incorporating best practices for handling imbalanced datasets and sensitive financial data.

## Dataset
The dataset is sourced from a collaboration between Worldline and the Machine Learning Group (MLG) of Université Libre de Bruxelles (ULB). This collaboration represents a bridge between industry and academia, focusing on real-world applications of big data mining and fraud detection.

### Dataset Access
You can find and download the dataset on Kaggle:
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

To access the dataset:
1. Visit the Kaggle link above
2. Sign in to your Kaggle account (or create one if you don't have it)
3. Click the "Download" button
4. Place the downloaded 'creditcard.csv' file in your project's `Data/Raw/` directory

### Dataset Characteristics
- Features are transformed using PCA for confidentiality
- Contains real-world transactions made by credit cards
- Includes transactions occurring over a 48-hour period
- Features a typical class imbalance problem, reflecting real-world fraud patterns
- Timestamps allow for temporal analysis of transaction patterns
