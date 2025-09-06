# 🛍️ Customer Segmentation with Machine Learning

This project applies **unsupervised learning** techniques to segment mall customers based on their demographic and behavioral data.  
The goal is to identify meaningful groups of clients that can help businesses target marketing strategies.

---

## Dataset
Dataset used: [Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

It contains:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🔧 Project Workflow
1. **Data Cleaning**  
   - Dropped unnecessary columns (`CustomerID`)  
   - Encoded categorical feature (`Gender`)  
   - Handled **outliers** using the IQR method  

2. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Missing values check  
   - Correlation matrix heatmap  

3. **Feature Engineering**  
   - Created new features:  
     - `Income_per_Age`  
     - `Spending_Ratio`  

4. **Preprocessing**  
   - Data normalization with `StandardScaler`  

5. **Clustering Models**  
   - **KMeans** with Elbow method  
   - **Hierarchical Agglomerative Clustering (HC)** with dendrogram  

6. **Dimensionality Reduction**  
   - Applied **PCA** for visualization in 2D  


---

##  Results
- Best number of clusters ≈ **4**  
Visualizations:
- Correlation heatmap  
- PCA projection (2D clusters)  
- Dendrogram (HC)  
- Income vs Spending Score colored by clusters  

---

## Technologies Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Scipy  

---

---

## 👩‍💻 Author
Project developed by **[Ton Nom]** as part of practice in **Machine Learning & Data Science**.
