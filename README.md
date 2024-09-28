# Customer-Segmentation_Group-14

Project Report: Customer Segmentation Using K-Means Clustering
1. Introduction
Customer segmentation is a crucial marketing strategy used by businesses to categorize their customers into different groups based on common characteristics. By doing so, companies can tailor their marketing efforts, improve customer satisfaction, and increase revenue. This project aims to perform customer segmentation using the K-Means clustering algorithm, which is an unsupervised machine learning technique.

The dataset used consists of customer information such as annual income and spending scores, which are analyzed to group customers into meaningful segments. The ultimate goal is to identify distinct customer profiles to enable better marketing strategies.

2. Objectives
The main objectives of this project are:

To preprocess and explore the customer dataset.
To apply K-Means clustering to segment customers.
To visualize the clusters and interpret the results for actionable insights.
3. Dataset Description
The dataset used in this project is a sample of customer data from a mall. It includes:

Customer ID: Unique identification for each customer.
Age: The age of the customer.
Annual Income: The annual income of the customer in thousands of dollars.
Spending Score: A score assigned based on customer behavior and purchasing habits, ranging from 1 to 100.
4. Data Preprocessing
Before applying the clustering algorithm, the data was cleaned and preprocessed:

Handling Missing Data: Any missing or null values were handled, ensuring a complete dataset.
Normalization: The dataset was scaled to bring all features to a similar range, preventing features with larger values (like income) from dominating the clustering process.
5. K-Means Clustering Algorithm
K-Means is a popular clustering algorithm that aims to partition the dataset into K clusters by minimizing the distance between the points in a cluster and the cluster's centroid. In this project, the steps followed are:

Choosing the number of clusters (K): The Elbow method was used to determine the optimal number of clusters by plotting the sum of squared distances for a range of K values and selecting the value where the curve starts to bend ("elbow").
Initialization: Initial cluster centroids were selected randomly.
Assignment: Each data point was assigned to the nearest centroid.
Centroid Update: The cluster centroids were recalculated based on the mean of the points in each cluster.
Convergence: The algorithm iterated until the centroids stopped moving significantly.
6. Results and Visualization
After applying the K-Means algorithm, customers were grouped into distinct clusters. These clusters were visualized using scatter plots where the axes represented features like annual income and spending scores.

Key findings include:

High-income, high-spending: Customers with high annual income and high spending scores were clustered together, representing a segment of premium customers who are likely to spend more.
Low-income, low-spending: Another group was identified with low income and low spending scores, representing a segment of cost-conscious customers.
Young, high-spending: Some younger customers with moderate income but higher spending scores formed a distinct group, indicating a potential target for luxury products.
7. Insights and Recommendations
Based on the segmentation analysis:

High-income, high-spending customers: Businesses should focus premium services and luxury product marketing on this segment.
Low-income, low-spending customers: Cost-effective product offerings and promotions can help retain and engage this customer group.
Young, high-spending customers: This segment might respond well to lifestyle and experiential marketing aimed at younger, aspirational consumers.
8. Conclusion
The K-Means clustering algorithm successfully segmented customers into distinct groups based on their purchasing behavior. This customer segmentation can help businesses tailor their marketing efforts to different segments, leading to more personalized marketing strategies and improved customer satisfaction. Future work could involve applying different clustering techniques or incorporating additional features to refine the segmentation.
