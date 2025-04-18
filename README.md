# 🛒 Market Basket Analysis with K-Means Clustering

This project applies **clustering techniques** to **Market Basket Analysis (MBA)** in order to discover hidden customer purchase patterns within transactional data. The main focus is on using **K-Means clustering** to segment transactions and gain actionable insights for retail optimization.

---

## 📌 Objective

- Identify groups of similar transactions using **K-Means clustering**.
- Discover frequently bought-together items.
- Visualize and interpret customer behavior for **cross-selling**, **inventory planning**, and **marketing strategies**.

---

## 🧩 Methodology

1. **Data Preprocessing**  
   - Cleaned the dataset and structured each transaction as a list of purchased items.

2. **One-Hot Encoding**  
   - Converted transactions into a binary matrix using one-hot encoding.
   - Each row = one transaction  
   - Each column = one item

3. **Clustering with K-Means**  
   - Applied K-Means to cluster transactions based on item presence.
   - Chose optimal `K` using elbow method or silhouette score.

4. **Visualization**  
   - Used a **heatmap** to analyze item frequency across clusters.
   - Applied **Principal Component Analysis (PCA)** to reduce dimensionality.
   - Visualized clusters in 2D using PCA components.

---

## 📊 Technologies Used

- Python 🐍
- Pandas, NumPy for data manipulation
- Scikit-learn for K-Means and PCA
- Matplotlib & Seaborn for data visualization


---

## 🔍 Results

- Identified distinct transaction clusters with meaningful item patterns.
- Visualized clusters to understand customer behavior.
- Extracted actionable insights for retail decision-making.

---

## 📬 Contact
For questions, feedback, or collaboration:

Vikas Kumar Singh
Email: vikas.2428cseaiml174@kiet.edu  


## 📄 License
This project is licensed under the MIT License.

