# CLV-clustering
Clustering the customers using lifetime values

This project focuses on customer segmentation for a retail dataset using **Apache Spark** (PySpark). The pipeline includes data preprocessing, feature engineering, scaling, dimensionality reduction using **PCA**, and clustering using **KMeans**. The goal is to group customers into **tiers** based on purchasing behavior and allow prediction for **new customers** as well.

---

## 🚀 Features

- Load & clean transaction data
- Aggregate behavior at the customer level
- Feature vectorization & standard scaling
- Dimensionality reduction (PCA)
- Clustering using KMeans
- Tier mapping (Low-Tier, Mid-Tier, High-Tier)
- Predict cluster for new customers
- Save results and summaries as CSV
- Visualize clusters using matplotlib

---

## 📁 Dataset

- Input File: `synthetic_retail_data.csv`
- Key columns:
  - `CustomerID`, `InvoiceNo`, `Quantity`, `UnitPrice`, `StockCode`, `InvoiceDate`

---

## 📊 Output

- `customer_with_tier/`: Final customer cluster data with tier labels
- `customer_tier_summary/`: Cluster-wise summary statistics
- Cluster visualization (2D PCA space)

---

## 🧪 Technologies Used

- **PySpark**: Distributed data processing
- **Spark MLlib**: Feature engineering, scaling, PCA, KMeans
- **Pandas**: For visualization
- **Matplotlib**: Cluster visualization

---

## 🧠 Model Evaluation

- **Silhouette Score** is used to evaluate the cluster cohesion and separation.

---
