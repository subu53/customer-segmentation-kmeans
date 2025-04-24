# Customer Segmentation using K-Means Clustering

[Customer Segments Visualization](Customer_Segments_PCA.png)

## 📌 Project Overview
This project segments mall customers into distinct groups using **K-Means clustering** based on their demographic and behavioral traits (Age, Annual Income, Spending Score). The goal is to enable targeted marketing strategies for each segment.

## 📂 Files in This Repository
customer-segmentation-kmeans/
├── kmeans_customer_segmentation.ipynb # Jupyter Notebook with full analysis
├── Mall_Customers.csv # Original dataset (200 customers)
├── Mall_Customers_with_Clusters.csv # Dataset with cluster labels
├── Customer_Segments_PCA.png # PCA visualization of clusters
├── Customer_Segmentation_Report.pdf # Detailed insights and conclusions
└── README.md # This file


## 🔍 Key Findings
### Identified Clusters (5 Segments)
| Cluster | Profile Description                     |
|---------|-----------------------------------------|
| 0       | Young females, low income, high spending|
| 1       | High-income males, low spending         |
| 2       | Older customers, moderate spending      |
| 3       | High-income females, medium spending    |
| 4       | Budget-conscious (low income/spending)  |

**Business Insight**: Target Cluster 0 with loyalty programs and Cluster 3 with premium offers.

## 🛠️ How to Reproduce
1. **Requirements**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Run the Notebook:

Open kmeans_customer_segmentation.ipynb in Jupyter.

Execute cells to:

Preprocess data.

Apply K-Means (Elbow Method for optimal k=5).

Generate visualizations (PCA/scatter plots).

Outputs:

Clustered dataset: Mall_Customers_with_Clusters.csv.

Visualizations: Customer_Segments_PCA.png.

📊 Data Sources
Original Dataset: Mall_Customers.csv

Columns: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100).

Processed Data: Mall_Customers_with_Clusters.csv adds a Cluster column.

📄 Report Summary
Refer to Customer_Segmentation_Report.pdf for:

Detailed cluster characteristics.

PCA analysis.

Actionable business recommendations.

👩‍💻 Author
Sammy S Mutuku
@subu53
subusam5@gmail.com
