# Mall-Customer-Segmentation

A lot of customers buy products from the mall and to generate more revenue for the mall, the
authorities need to attract these customers and for this large amount of capital is required. After
the advertisement, the output is only around 30-40%. Hence customer segmentation comes into
the picture.
Customer Segmentation is a popular application of unsupervised learning and by using this
technique we'll only focus on the potential customers (customers whose probability of buying the
product is very high). With this technique, the output will drastically increase to 90-95%.
Our project aims to build clusters of customers based on their Spending Score and Annual
Income. The algorithm used in this project is K-means.

## Introduction
To make predictions and find the clusters of potential customers of the mall and thus find
appropriate measures to increase the revenue of the mall is one of the prevailing applications
of unsupervised learning.
For example, a group of customers have high income but their spending score (amount spent in
the mall) is low so from the analysis we can convert such type of customers into potential
customers (whose spending score is high) by using strategies like better advertising, accepting
feedback and improving the quality of products.
To identify such customers, this project analyses and forms clusters based on different criteria
which are discussed in the further sections.

## Dataset
The dataset name is ‘Mall_Customers.csv’ consists of 5 columns which are CustomerID,
Gender, Age, Annual Income (k$), Spending Score (1-100) where Gender is a categorical value
and rest all features are numeric. 
### The size of the dataset is (200, 5) which is 200 rows and 5 columns.

## Proposed Method and Architecture

### Problem Statement
Customer Segmentation is a popular application of unsupervised learning. Using clustering,
identify segments of customers to target the potential user base. They divide customers into
groups according to common characteristics like gender, age, interests, and spending habits so
they can market to each group effectively.
Use K-means clustering and also visualize the gender and age distributions. Then analyze their
annual incomes and spending scores.

### Algorithms
K-means algorithm is used in this project to analyze and form clusters of customers based on
their income and spending score features.

### Model
K-means model is used and is hyper tuned parameters like n_clusters=5 using elbow method to
find the optimal number of clusters also init=’k-means++’ to avoid random initialization traps.

### Programming and Environment
Programming Language: Python 3.6
Environment (Libraries and Technologies): Numpy, Pandas, Matplotlib, Seaborn, Jupyter
Notebook, Google Colab.
