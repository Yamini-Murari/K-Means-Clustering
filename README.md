# K-Means-Clustering

### DESCRIPTION : 
This task uses K-Means Clustering to group mall customers based on their annual income and spending habits. The goal is to identify different types of customers so businesses can tailor their marketing strategies.

### DATASET : Mall Customer segmentation
features used

- anual income and spending

### tools used :
- python

- pandas – for handling data

- matplotlib – for visualization

- scikit-learn – for KMeans and silhouette evaluation

### steps involved :
- importing  necessary libraries

- load the dataset
   read Mall_Customers.csv using pandas

- select features
   use only annual income and spending columns for clustering

- visualize the raw data
   plot a scatter plot to see how the data looks before clustering

- use the Elbow Method
   try different values of k (no of clusters)
   plot inertia vs k to find the  elbow point
   choose the best k 

- fit the KMeans model
   apply KMeans with the chosen no of clusters

- assign cluster labels
   add the predicted cluster labels to the original DataFrame

- Visualize the clusters
   plot the data with different colors for each cluster and mark the centroids

- evaluate the model
  calculate the Silhouette Score

### OUTPUT :

<img width="454" height="622" alt="Image" src="https://github.com/user-attachments/assets/4f6ee07d-f133-4d80-89b2-e9abee039965" />

<img width="437" height="355" alt="Image" src="https://github.com/user-attachments/assets/11cd96b9-7643-49c4-b6cc-0f35bb2e675e" />
