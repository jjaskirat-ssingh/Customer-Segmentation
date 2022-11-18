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
