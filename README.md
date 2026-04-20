# Customer Segmentation using K-Means Clustering

## 📌 Overview
This project focuses on analyzing customer behavior using Annual Income and Spending Score.  
The objective is to group customers into meaningful segments using machine learning.

---

## 🎯 Objective
To identify different types of customers and help businesses make data-driven marketing decisions.

---

## 📊 Dataset
The dataset includes:
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

---

## ⚙️ Steps Performed

### 1. Data Loading & Understanding
- Loaded dataset using Pandas  
- Explored structure and summary statistics  

---

### 2. Data Cleaning
- Removed missing values to ensure accuracy  

---

### 3. Data Visualization
- Plotted Income vs Spending Score to observe patterns  

![Scatter Plot](images/scatter_plot.png)

---

### 4. Elbow Method
- Used WCSS to find optimal clusters  
- Found optimal K = 4  

![Elbow Method](images/elbow_method.png)

---

### 5. K-Means Clustering
- Applied K-Means algorithm  
- Segmented customers into 4 groups  

![Clusters](images/clusters.png)

---

## 📈 Key Insights

- Low income, high spending → highly engaged but risky customers  
- Medium income, medium spending → stable customer base  
- High income, moderate spending → growth opportunity  
- High income, low spending → untapped potential  

---

## 🛠 Tools Used
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🚀 Conclusion
Customer segmentation helps businesses understand customer behavior and improve marketing strategies.

---

## 📌 Author
Kunal Gadhave  
Mechatronics Engineering Student
