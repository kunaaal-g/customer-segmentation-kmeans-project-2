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

![Scatter Plot]

<img width="562" height="455" alt="scatter_plot" src="https://github.com/user-attachments/assets/bfe8fe7f-a230-48c1-9df7-ceddb5f5aa6b" />


---

### 4. Elbow Method
- Used WCSS to find optimal clusters  
- Found optimal K = 4  

![Elbow Method]

<img width="567" height="455" alt="elbow_method" src="https://github.com/user-attachments/assets/cc4c266b-7ffe-4afa-94f1-53d8ab1f8878" />


---

### 5. K-Means Clustering
- Applied K-Means algorithm  
- Segmented customers into 4 groups  

![Clusters]

<img width="686" height="547" alt="clusters" src="https://github.com/user-attachments/assets/c1724cca-2103-4b8f-a447-cab1d8526ed7" />


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
