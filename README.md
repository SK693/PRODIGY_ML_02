# PRODIGY_ML_02
## Customer Segmentation using K-means Clustering

### Task Overview
This task involves creating a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to identify distinct customer segments to understand purchasing behavior and tailor marketing strategies accordingly.

### Dependencies
The task requires the following libraries:

pandas
scikit-learn
matplotlib

### How the Code Works?
#### 1. Load and Preprocess Data
Data is loaded from a CSV file using Pandas. Irrelevant columns such as Customer ID, Purchase Date, and Customer Name are removed. Missing values are filled with zero, and categorical features are encoded using one-hot encoding.

#### 2. Feature Selection and Scaling
Key features for clustering, such as Quantity and Customer Age, are selected. The data is scaled using StandardScaler to normalize the feature values.

#### 3. K-means Clustering
A K-means clustering algorithm is applied to the scaled data with a predefined number of clusters (e.g., 3 clusters). The model is trained, and each customer is assigned a cluster label.

#### 4. Visualization
Several scatter plots are created to visualize the clustering results:

##### Quantity vs. Customer Age: Customers are plotted based on Quantity and Customer Age, with colors indicating different clusters.
##### Total Purchase Amount vs. Customer Age: Customers are plotted based on their Total Purchase Amount and Customer Age, with colors indicating different clusters.
##### A legend is provided in each plot to identify the clusters.

#### 5. Conclusion
This task demonstrates the application of K-means clustering to group customers based on their purchase history. The clustering results help in identifying distinct customer segments, which can be used for targeted marketing and improving customer satisfaction.
