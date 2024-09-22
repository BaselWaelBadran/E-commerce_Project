# E-commerce_Project
### This project focuses on customer segmentation using unsupervised machine learning techniques, specifically K-Means clustering

# 1. Data Cleaning
The goal of data Cleaning is To prepare it and make it ready for analysis or model training, The benefit of that step is that Cleaned data results in more accurate analysis and models.
Then merged the tables to create a comprehensive dataset to start with.

# 2. Data Preprocessing
### Selecting Transactional Features:
transaction_count: The number of transactions each customer has made. This gives an idea of how often they interact with the platform.
burn_rate: The percentage of coupons that were actually used by each customer. This shows how responsive they are to discounts.g

# 3. Model Development
applying K-Means Clustering for customer segmentation 
Experimenting with different values of k (number of clusters) to find the optimal number of clusters.
Evaluating the clustering results using metrics like inertia and the silhouette score.

# 4. Model Evaluation
### 1. Plot the Elbow Curve 
Helps determine the optimal number of clusters by finding the "elbow" point, where adding more clusters doesn’t significantly improve the model.
### 2. Plot the Silhouette Score:
Measures how similar each point is to its own cluster compared to other clusters.

# 5. Segment Analysis
Each cluster was analyzed to understand customer behavior, including transaction counts, coupon usage, and demographic trends.
