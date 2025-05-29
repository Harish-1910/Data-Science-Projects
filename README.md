## Customer Segmentation using K-Means Clustering

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/your-repo-name/blob/main/your-notebook.ipynb)

## Overview

This project performs customer segmentation using the **K-Means Clustering** algorithm. It segments mall customers based on their **Annual Income** and **Spending Score**, helping businesses better understand and target customer groups.

---

## 📁 Dataset

The dataset used is `Mall_Customers.csv`, which includes the following features:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 📊 Steps Performed

1. **Importing Libraries**  
   Used libraries: NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

2. **Data Loading and Preprocessing**  
   - Loaded the CSV file using Pandas.
   - Checked for null values and data types.
   - Selected features: `Annual Income` and `Spending Score`.

3. **Elbow Method for Optimal Clusters**  
   - Used the elbow method to find the optimal number of clusters (WCSS).
   - Optimal clusters found: **5**

4. **Training the K-Means Model**  
   - Applied the KMeans algorithm with 5 clusters.
   - Predicted customer group labels.

5. **Visualization**  
   - Visualized all 5 clusters using different colors.
   - Highlighted cluster centroids.

---

## 📈 Output

- Five distinct customer segments visualized in a scatter plot.
- Each cluster represents a different customer behavior group based on income and spending.

---

## 🔧 Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
