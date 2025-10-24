🍷 Wine Clustering Analysis
📘 Overview

This project explores clustering techniques to uncover meaningful patterns and natural groupings within a wine dataset. By analyzing various chemical properties of wines, different clustering algorithms were applied to identify similarities and differences between wine samples.

🎯 Objective

The goal is to perform unsupervised learning using multiple clustering methods such as K-Means, Hierarchical Clustering, and DBSCAN, and to compare their performance using metrics like the Silhouette Score.

📊 Dataset

The dataset wine-clustering.csv contains several attributes describing the physicochemical characteristics of wine samples. Each feature helps in understanding how wines differ based on their composition.

🧠 Methods Used

Data Preprocessing — Scaling, normalization, and handling outliers

Dimensionality Reduction — PCA for visualization and efficient clustering

Clustering Algorithms

K-Means Clustering

Hierarchical Clustering

DBSCAN

Evaluation Metrics — Silhouette Score, cluster visualization, and interpretation

🔍 Key Insights

K-Means performed best with an optimal cluster count determined by the Elbow Method and Silhouette Analysis.

Hierarchical Clustering helped in visualizing the relationship between samples through a dendrogram.

DBSCAN was effective in detecting noise points and identifying natural cluster boundaries without predefining cluster numbers.

🧩 Project Structure

task.ipynb — Complete clustering analysis and visualization notebook

wine-clustering.csv — Dataset file

requirements.txt — List of required dependencies

🏁 Conclusion

This analysis demonstrates how unsupervised learning can reveal hidden structures in data without labels.
It provides valuable insights into how wines can be grouped based on shared properties, which can assist in quality control, product categorization, and consumer preference analysis.