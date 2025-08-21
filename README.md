# Customer Segmentation using K-Means

This project applies **K-Means clustering** to the popular **Mall Customers dataset** to segment customers based on their **Annual Income** and **Spending Score**. It helps businesses understand customer behavior and create targeted marketing strategies.

## Features
- Data preprocessing and scaling using `StandardScaler`
- Elbow method to find the optimal number of clusters
- K-Means clustering for customer segmentation
- Visual cluster representation (Income vs Spending Score)
- Cluster profiling with average Age, Income, Spending
- Ready for business interpretation & marketing insights

## Dataset
- **Source:** Mall Customers dataset (Kaggle)
- Columns:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

## Steps in the Project
1. Import dataset and explore data
2. Select features: Annual Income & Spending Score
3. Scale the features
4. Determine optimal K using the **Elbow method**
5. Apply K-Means clustering
6. Visualize the clusters
7. Analyze cluster profiles

## Results
Clusters represent different customer groups:
- High Income – High Spending
- High Income – Low Spending
- Low Income – High Spending
- Low Income – Low Spending
- Average Income – Average Spending


