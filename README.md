# Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using the **K-Means machine learning algorithm**.  
The goal is to group customers based on their **Annual Income** and **Spending Score** to better understand customer behavior and help businesses target each group effectively.

---

## 📊 Project Overview

This project includes:

- Loading and preprocessing the customer dataset  
- Selecting relevant features (Annual Income & Spending Score)  
- Using the **Elbow Method** to find the optimal number of clusters  
- Training the **K-Means clustering model**  
- Visualizing customer clusters on a 2D plot  
- Plotting cluster centroids  

---

## 📁 Dataset

The dataset contains customer information including:

- Customer ID  
- Gender  
- Age  
- Annual Income  
- Spending Score  

Only the following features were used for clustering:

- **Annual Income**
- **Spending Score**

---

## 🧠 Machine Learning Algorithm

### **K-Means Clustering**

- Unsupervised learning algorithm  
- Groups data points into *k* clusters  
- Minimizes the distance between points and the cluster centroid  

### **Elbow Method**
Used to determine the best number of clusters by analyzing WCSS (Within-Cluster Sum of Squares).

---
