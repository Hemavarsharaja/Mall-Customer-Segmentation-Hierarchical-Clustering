
# Mall Customer Segmentation using Hierarchical Clustering

## 📌 Project Overview
This project focuses on customer segmentation using **Hierarchical Clustering** on mall customer data.  
The goal is to group customers based on their **Annual Income** and **Spending Score** to help businesses
understand customer behavior and plan targeted marketing strategies.

---

## 📊 Dataset
The dataset used is **Mall Customers Dataset**, which contains the following attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

For clustering, the following features were selected:
- Annual Income (k$)
- Spending Score (1–100)

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  
- Scikit-learn  

---

## 🧪 Steps Performed
1. Data loading and exploration  
2. Feature selection  
3. Feature scaling using StandardScaler  
4. Dendrogram creation to determine optimal number of clusters  
5. Applying Hierarchical Clustering using Ward linkage  
6. Visualizing customer clusters  
7. Interpreting clusters for business insights  

---

## 🌳 Dendrogram Analysis
A dendrogram was plotted using Ward’s method to determine the optimal number of clusters.
Based on the largest vertical distance, **5 clusters** were selected.

📌 *Dendrogram visualization is saved in the `images/` folder.*

---

## 📈 Cluster Visualization
Customers were segmented into 5 distinct groups based on their income and spending behavior.
Each cluster represents a different type of customer group.

📌 *Cluster visualization is saved in the `images/` folder.*

---

## 🧠 Business Insights
| Cluster Type | Description | Strategy |
|-------------|------------|----------|
| High Income – High Spending | Premium customers | Loyalty programs |
| High Income – Low Spending | Potential customers | Upselling |
| Low Income – High Spending | Value-driven customers | Discounts |
| Low Income – Low Spending | Low priority customers | Minimal marketing |
| Average Income – Average Spending | Regular customers | Standard offers |

---
## 📁 Project Structure
Mall_Customer_hierarchical/
│
├── images/
│ ├── dendrogram.png
│ └── clusters.png
│
├── notebooks/
│ └── Mall_Customer_Hierarchical_Clustering.ipynb
│
└── README.md
##  Conclusion
Hierarchical clustering successfully grouped mall customers into meaningful segments.
These insights can be used by businesses to improve customer targeting, marketing efficiency,
and customer satisfaction.

---

