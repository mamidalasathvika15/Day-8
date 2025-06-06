# Task 8: Clustering with K-Means

## 📌 Objective
Perform unsupervised learning using K-Means clustering on the Titanic dataset after preprocessing and dimensionality reduction.

---

## 🛠️ Tools & Libraries Used
- Python 3  
- Pandas – for data manipulation  
- NumPy – for numerical operations  
- Scikit-learn – for PCA, K-Means clustering, and evaluation metrics  
- Matplotlib – for visualization  

---

## 📈 Project Workflow (Code-wise)

### Cell 1: Load and Prepare Dataset
- Load the Titanic dataset from CSV file using `pandas.read_csv`.  
- Display initial dataset columns and summary info.  
- Drop irrelevant columns (`PassengerId`, `Name`, `Ticket`) and handle missing values.  
- Encode categorical columns (e.g., `Sex`, `Embarked`) if needed.  
- Scale numerical features using `StandardScaler`.

### Cell 2: Dimensionality Reduction using PCA
- Apply PCA to reduce the dataset to 2 principal components for visualization purposes.  
- Visualize the transformed 2D data using a scatter plot.

### Cell 3: Determine Optimal Number of Clusters Using Elbow Method
- Run K-Means clustering for a range of `k` values (e.g., 1 to 10).  
- Plot the sum of squared distances (inertia) against `k` to identify the elbow point.

### Cell 4: Fit K-Means with Chosen `k` and Assign Cluster Labels
- Fit K-Means with the optimal number of clusters obtained from the Elbow method.  
- Assign cluster labels to each data point.

### Cell 5: Visualize Clusters
- Visualize clusters on the 2D PCA scatter plot with color-coding for cluster membership.  
- Plot cluster centers on the scatter plot.

### Cell 6: Evaluate Clustering Quality using Silhouette Score
- Calculate and print the Silhouette Score to assess cluster separation and cohesion.

---

## 📊 Output & Results
- Data overview after preprocessing.  
- 2D PCA scatter plot of Titanic data points.  
- Elbow plot to decide optimal cluster count.  
- Clustered data visualization with color-coded clusters and cluster centers.  
- Silhouette score indicating the quality of the clustering.

---

## 📌 Conclusion
The project successfully performed unsupervised clustering on the Titanic dataset, leveraging PCA for visualization and using K-Means clustering with hyperparameter tuning (number of clusters). The Silhouette Score provided a quantitative measure of clustering effectiveness.

---

*M. Sathvika*  
*Date: 06-06-2025*
