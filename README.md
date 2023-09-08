# Customer Analysis and Segmentation

- The project uses a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and
registered non-store online retail. <a href = "https://archive.ics.uci.edu/ml/datasets/online+retail">Dataset Link</a>
- It focuses on segmenting customers into different categories; thereby answering the 
question: “How valuable is this customer?”.
- The data set was cleaned to retain only useful information for the said purpose.
- To evaluate the customer, RFM (Recency, Frequency, Monetary) Analysis is 
performed.
- K – Means clustering algorithm is used to perform segmentation.
- K-Means Clustering is an unsupervised learning algorithm that is used to solve the 
clustering problems in machine learning or data science. It is an iterative algorithm that 
tries to partition the dataset into K pre-defined distinct non-overlapping subgroups 
(clusters) where each data point belongs to only one group. 
- The number of suitable clusters, i.e. 3, was deduced using Elbow curve and silhouette score.
- Lastly, the category of a customer was predicted by finding the RFM values (3D coordinate) and calculating the point’s distance in the 3D space from the centers of 
all the 3 clusters and finding the minimum.

## Visualizations:
![image](https://github.com/kanuj-boora/Customer-Segmentation/assets/88098204/49df1256-7253-4034-a8dd-d1d6d9b8b4c3)

![image](https://github.com/kanuj-boora/Customer-Segmentation/assets/88098204/1b79b058-b23c-4d95-af12-c3ffeb68162e)

![image](https://github.com/kanuj-boora/Customer-Segmentation/assets/88098204/548dbab3-cae3-438e-8960-3933344be428)
  
![image](https://github.com/kanuj-boora/Customer-Segmentation/assets/88098204/372594bf-b3cd-45e2-97c7-ca2c7c16c0ff)
