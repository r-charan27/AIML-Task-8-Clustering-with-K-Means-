# AIML-Task-8-Clustering-with-K-Means-
# 🤖 Task 8: K-Means Clustering – Customer Segmentation

## 📌 Objective
Cluster customers into groups using the **K-Means** algorithm based on their **Annual Income** and **Spending Score**. Evaluate clusters and visualize using Elbow Method and Silhouette Score.

---

## 🛠 Tools & Libraries
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn

---

## 📁 Dataset
- **Name**: Mall Customer Segmentation Dataset
- path = kagglehub.dataset_download("vjchoudhary7/customer-segmentation-tutorial-in-python")


---

## 🚀 Steps Performed

1. Loaded and explored dataset
2. Selected two features: `Annual Income (k$)` and `Spending Score`
3. Scaled data using `StandardScaler`
4. Applied **Elbow Method** to find optimal `K`
5. Fitted `KMeans` with K=5
6. Visualized clusters using:
   - Scatter plot with `hue=Cluster`
   - PCA-based 2D view
7. Evaluated clustering using **Silhouette Score**

---

## 📊 Results

| Metric            | Value |
|-------------------|-------|
| Optimal Clusters  | 5     |
| Silhouette Score  | ~0.55 |

---
📃Created by: [MUMMADI RAMCHARAN]
