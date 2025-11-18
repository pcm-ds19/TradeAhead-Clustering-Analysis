
# TradeAhead Clustering Analysis

Unsupervised Learning project analyzing TradeAhead stock market data using K-Means, Hierarchical Clustering, and Principal Component Analysis (PCA). The goal is to segment stocks based on performance variables and identify meaningful patterns for portfolio insights and risk-based grouping.

---

## 1. Project Overview

This project applies Unsupervised Machine Learning techniques to cluster stocks from the TradeAhead dataset. The dataset contains daily market indicators such as trading volume, price variations, volatility, and returns. Since the data does not include predefined labels, clustering is used to uncover natural groupings within the stock universe.

The project was completed as part of the Unsupervised Learning module of the PGP-DSBA program (Great Lakes Institute of Management & Texas McCombs).

**The analysis covers:**
- Exploratory Data Analysis (EDA)
- Data preprocessing and scaling
- K-Means clustering with Silhouette Score evaluation
- Hierarchical Clustering with dendrogram analysis
- PCA for dimensionality reduction and visualization
- Interpretation of cluster characteristics
- Business insights for portfolio grouping and stock strategy

---

## 2. Problem Statement

TradeAhead needs help segmenting stocks into meaningful groups to support:

- Portfolio diversification  
- Identification of similar-performing assets  
- Risk-based categorization  
- Improved investment decision-making  

Since the dataset has no labelled outcomes, clustering is the most suitable approach for revealing underlying structure.

---

## 3. Dataset Description

The dataset `stock_data.csv` contains stock-level market variables such as:

- Open, High, Low, Close prices  
- Trading Volume  
- Price volatility  
- Daily returns  
- Other derived performance metrics  

**Key preprocessing steps:**
- Handling missing values  
- Outlier investigation  
- Scaling numerical features using StandardScaler  
- Feature selection for clustering suitability  

---

## 4. Methods Used

### 4.1 K-Means Clustering
- Elbow Method used to estimate optimal k  
- Silhouette Score computed for cluster quality  
- Cluster interpretation based on feature means  

### 4.2 Hierarchical Clustering
- Agglomerative clustering  
- Complete linkage with Euclidean distance  
- Dendrogram plotted to visualize merging patterns  

### 4.3 Principal Component Analysis (PCA)
- PCA applied to reduce dimensionality  
- First two principal components captured majority of variance  
- Cluster separation visualized in reduced feature space  

---

## 5. Key Results

- Optimal K-Means cluster count determined using the Elbow Method  
- Silhouette Score indicated moderate cluster separation  
- Hierarchical clustering supported similar grouping trends  
- PCA showed clear separation for some clusters, while others overlapped  
- Clusters displayed distinct characteristics in terms of volatility, returns, and trading activity  

(Insert your exact K value, Silhouette Score, and detailed interpretations after reviewing the notebook output.)

---

## 6. Business Insights

The clustering analysis provides the following insights:

- High-volatility stocks grouped together, indicating higher risk but potentially higher reward.  
- Stable, low-variance stocks formed a separate cluster suitable for conservative investors.  
- High-volume, high-liquidity stocks created their own cluster, helpful for intraday strategies.  
- PCA visualizations supported the presence of clear groups that assist in:  
  - Portfolio diversification  
  - Risk management  
  - Asset allocation  

---

## 7. Files in This Repository

TradeAhead-Clustering-Analysis/
│
├── stock_data.csv # Dataset
├── UL_Project_Notebook.ipynb # Full notebook (EDA + clustering + PCA)
├── UL_Project_Report.pdf # Project report
└── README.md # Documentation


---

## 8. Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- PCA  
- K-Means Clustering  
- Hierarchical Clustering  

---

## 9. Conclusion

This project successfully groups stocks into meaningful clusters using unsupervised learning.  
These insights help in building diversified portfolios, understanding risk profiles, and identifying investment opportunities based on natural stock behavior patterns.


