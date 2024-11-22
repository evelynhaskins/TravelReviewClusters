# Travel Review Ratings - Unsupervised Learning Project

This project aims to apply unsupervised learning techniques to cluster travel-related data based on various factors such as user ratings for different types of places (e.g., parks, beaches, museums, etc.). The dataset is sourced from the UCI Machine Learning Repository, with the following citation:

**Data Source:**  
Renjith, S. (2018). *Travel Review Ratings* [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C5C31Q](https://doi.org/10.24432/C5C31Q).

## Project Overview

### 1. Data Collection and Provenance

The dataset, *Travel Review Ratings*, was sourced from the UCI Machine Learning Repository, providing information on travel reviews across different categories. This data is publicly available and includes user ratings for various travel-related activities and destinations. It was collected and made accessible for educational and research purposes.

### 2. Unsupervised Learning Problem

The primary unsupervised learning technique used in this project is **K-means clustering**. This technique is applied to identify groups of users based on their ratings across different categories such as beaches, parks, zoos, museums, etc. The goal is to discover patterns and groupings in the data without any prior labels or supervision.

### 3. Exploratory Data Analysis (EDA)

Before applying the clustering model, the data was thoroughly inspected and visualized. Key steps in the data cleaning and exploration process included:

- **Feature Inspection**: The dataset contains features such as ratings for various types of places (e.g., parks, beaches, zoos).
- **Visualization**: Box-plots, histograms, and scatter plots were used to visualize the distribution and correlations of the features.
- **Data Transformation**: Scaling and normalization were applied to ensure the data's features are on a similar scale, which is crucial for clustering models like K-means.
- **Outlier Detection and Handling**: Outliers were detected and addressed, as they could significantly impact the performance of the clustering algorithm.
- **Missing Data Handling**: Any missing values were imputed or removed based on the analysis of their significance.

### 4. Model Building and Evaluation

**K-means Clustering** was applied to the dataset to cluster users based on their ratings. The number of clusters was selected using the **Elbow Method**, which helps determine the optimal number of clusters by minimizing the within-cluster sum of squares.

The clustering results were visualized, and the centroids of each cluster were analyzed to interpret the types of users in each group. For example, clusters with users who rated parks and beaches similarly might represent users who enjoy outdoor activities, while other clusters might represent users who prefer cultural attractions like museums and theatres.

### 5. Conclusion

The K-means clustering analysis revealed several distinct user groups based on their travel preferences. These findings can help in understanding user behavior and preferences for different types of travel destinations. Additionally, the model can be used for personalized travel recommendations and insights.
