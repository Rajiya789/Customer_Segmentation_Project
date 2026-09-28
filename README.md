# Customer Segmentation Project

## Project Overview

This project focuses on segmenting customers based on their purchasing behavior and demographic characteristics using Machine Learning.

K-Means clustering is used to identify groups of customers with similar income and spending patterns.

## Objective

The main objectives of this project are:

- Analyze customer behavior and demographics
- Identify meaningful customer segments
- Apply K-Means clustering
- Visualize customer groups
- Generate business insights for targeted marketing

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset

The project uses the Mall Customer Segmentation dataset.

The dataset contains information such as:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

## Methodology

1. Load the customer dataset
2. Perform data exploration
3. Check missing values and duplicates
4. Analyze customer demographics
5. Select income and spending score for clustering
6. Standardize the data
7. Determine the number of clusters using the Elbow Method
8. Apply K-Means clustering
9. Evaluate the clustering using Silhouette Score
10. Visualize the customer segments
11. Analyze and interpret the customer groups

## Customer Segments

The analysis identified five customer segments:

| Segment | Description |
|---|---|
| Average Customers | Moderate income and moderate spending |
| High-Value Customers | High income and high spending |
| Young High-Spending Customers | Lower income with high spending |
| High-Income Low-Spending Customers | High income with low spending |
| Low-Income Low-Spending Customers | Low income with low spending |

## Business Insights

Customer segmentation can help businesses:

- Identify high-value customers
- Create personalized marketing campaigns
- Improve customer engagement
- Develop targeted offers
- Understand different customer behaviors
- Improve customer retention strategies

## Project Files

- `Customer_Segmentation_Project.ipynb` — Complete Python analysis
- `customer_segmentation_final.csv` — Final dataset with cluster and segment information
- `README.md` — Project documentation

## Conclusion

The project demonstrates how K-Means clustering can be used to analyze customer behavior and identify meaningful customer segments. These insights can support targeted marketing and customer relationship strategies.
