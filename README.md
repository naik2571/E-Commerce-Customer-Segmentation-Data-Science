# E-Commerce Customer Segmentation 🛒📊

This data science project applies unsupervised machine learning to segment e-commerce customers into distinct groups based on their purchasing behavior. This type of analysis is crucial for businesses to execute targeted marketing campaigns, optimize ad spend, and increase customer retention.

## 🎯 Project Goal
To identify underlying patterns in customer data and group them into actionable business segments using clustering algorithms.

## 🧠 Machine Learning Pipeline
1. **Synthetic Data Generation:** Created a highly realistic dataset of 1,000 customers (tracking Age, Annual Income, Total Spend, and Purchase Frequency).
2. **Data Preprocessing:** Standardized features using `StandardScaler` to optimize distance calculations.
3. **Model Selection (K-Means):** Utilized the **Elbow Method** and **Silhouette Score** to mathematically determine the optimal number of clusters ($K=4$).
4. **Dimensionality Reduction (PCA):** Applied Principal Component Analysis to reduce the 4D feature space into 2D for visual cluster separation.

## 💡 Business Insights Discovered
The algorithm successfully identified 4 unique customer profiles:
* **Premium Loyalists:** High income, high spend, frequent shoppers. (Target with VIP programs & high-ticket items).
* **Bargain Hunters / Impulse Buyers:** Low income, high spend. (Target with trendy items & flash sales).
* **Conservative Spenders:** High income, low spend. (Target with quality guarantees & luxury practical items).
* **Occasional Shoppers:** Low income, low spend. (Target with high-discount activation campaigns).

## 🛠️ Technology Stack
* **Python** 
* **Scikit-Learn** (Machine Learning: K-Means, PCA, Metrics)
* **Pandas & NumPy** (Data Manipulation)
* **Seaborn & Matplotlib** (Data Visualization)

## 🚀 How to View
You can view the full code in the `customer_segmentation.ipynb` file. Alternatively, you can download the `customer_segmentation_completed.html` file and open it in your browser to view the executed code with all interactive charts and graphs intact.
