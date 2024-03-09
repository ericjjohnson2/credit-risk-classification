# Credit Risk Classification

## Overview
This project explores various techniques to train and evaluate a loan risk model using historical lending data.  

### Objective
The goal of this project is to learn from past customer data and predict loan performance. 

## Techniques 

### Data Preparation
- **Data Loading**: Loaded `lending_data.csv`, which comprises of various risk indicators of various loans and whether each loan performed.
- **Splitting Into Training and Testing Sets**: Utilized `train_test_split` to split the original data into two sets for training and testing the model.
- **Logistic Regression Model**: Created a logistic regression model using the .

## Key Findings

- **PCA Effectiveness**: Using PCA significantly improved the clustering quality, making the clusters more distinct and easy to interpret.
- **Optimal Cluster Count**: Using the PCA-transformed data and elbow curves helped to determine that four clusters was the optimal number in this case.
- **Impact of Dimensionality Reduction**: The use of PCA not only simplifies the dataset but also enhances the clustering, facilitating a more nuanced understanding of cryptocurrency market dynamics.

## Conclusion

This project underscores the utility of PCA in enhancing data clustering, particularly in the complex and fast-evolving cryptocurrency market. Through thoughtful analysis and strategic data manipulation, we uncover patterns and insights that could inform investment strategies and market analysis. Currencies that form their own clusters, like Etherlend and Celsius-degree, exhibit volatility patterns not found in the majority of currencies. Reducing the dimensions by utilizing PCA helped identify these outliers. 

## Future Directions

In future projects, I plan to explore other dimensionality reduction techniques to compare their effectiveness in clustering cryptocurrencies which could hopefully offer different insights into market dynamics. 