# PCA_and_KMeans_Unsupervised_Learning_Employee_Segmentation
Employee segmentation using K-Means clustering and PCA visualization. An end-to-end unsupervised learning workflow for discovering hidden patterns in organizational data.

### Objectives
- Perform data cleaning and preprocessing.
- Apply K-Means clustering to uncover natural groupings.
- Use PCA for 2D visualization of high-dimensional data or 3D.
- Evaluate models using inertia and silhouette scores.

### Workflow

#### Data Preparation & EDA
- Check data types and convert as needed.
- Remove unnecessary columns (e.g., ID, Attrition).
- Inspect distributions and correlations.

#### Feature Scaling
- Standardize numeric features using StandardScaler.

#### K-Means Clustering
- Run K-Means for multiple values of k (2–15).
- Evaluate using inertia (Elbow Method) and silhouette score.
- Choose optimal k.

#### PCA Visualization
- Apply PCA with 2 components.
- Visualize clusters in 2D.
- Overlay color by cluster and department for interpretation.

#### Refined K-Means
- Remove categorical columns (e.g., Department).
- Re-run K-Means to improve cluster quality.
- Re-visualize and interpret results.


### Results
- Optimal number of clusters identified through Elbow and Silhouette analysis.
- PCA visualization reveals clear separation between clusters.
- Useful for HR analytics or customer segmentation tasks.

### Final Insight

##### Higher attrition:
* Long commuters: find remote options, create a more inclusive remote culture
* Men who dislike their jobs: have their managers have conversations with them
* Higher performers are leaving: find opportunities for more senior positions

##### Lower attrition:

* Senior employees: this makes sense that they have less attrition since they've been around a long time
* Female employees: this is an interesting finding
* Men who like their jobs: this make sense that people who like their job would stay

  

  
