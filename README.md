# Customer Segregation using KMeans clustering algorithm
Customer segmentation using RFM technique for an e-commerce website by implementing KMeans Clustering algorithm. 
Segmentation was required to identify customers based on similar byuing habits, and do **targeted marketing** that is more personalized for each group.

## Methodolgy
- Recency Frequency Monetory (RFM) features are created in the data.
- Recency: The number of days between a customer's last transaction and the day on analysis.
- Frequency: The number of times a customer has made a purchase.
- Monetory: The total amount a customer has spent on all the purchase.
- Log, Square root, Box-cox transformations were done on each of the above metrics to get normal distribution.
- Skewness was checked for each transformations and the one with lowest skewness were chosen accoringly.
- This data was then normalized using StandardScalar so that each variable has same mean and variance.
- Ideal number of clusters (3) was obtained using elbow method.
- Different marketing techniques were lined out for different category of customers based on the cluster.
