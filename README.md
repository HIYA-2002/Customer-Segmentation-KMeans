# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers based on their purchasing behavior. The goal is to identify distinct customer groups and enable **targeted marketing strategies**.

---

## 🎯 Business Objective
- Understand customer purchasing patterns  
- Identify high-value and low-value customer segments  
- Enable data-driven decision-making for marketing  

---

## 📊 Dataset Information
- **Dataset:** Mall Customers Dataset  
- **Features Used:**
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  

---

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed distributions of Age, Income, and Spending Score  
- Identified spending behavior trends across different age groups  
- Observed natural grouping patterns in **Income vs Spending Score**

### Key Observations:
- Younger customers tend to spend more  
- Income is not strongly correlated with spending  
- Clear segmentation patterns visible before modeling  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed irrelevant feature (`CustomerID`)  
- Checked for missing values (none found)  

### 2. Feature Selection
- Selected:
  - Annual Income  
  - Spending Score  

### 3. Feature Scaling
- Applied **StandardScaler** to normalize data  
- Ensured equal contribution of all features  

### 4. Finding Optimal Clusters
- Used **Elbow Method**  
- Selected **K = 5** based on inertia curve  

### 5. Model Building
- Applied **K-Means Clustering**  
- Assigned cluster labels to each customer  

---

## 📈 Model Evaluation

### Silhouette Score
- **Score:** 0.55  
- Indicates reasonably well-separated and meaningful clusters  

---

## 🧠 Customer Segments Identified

1. **Premium Customers**
   - High Income, High Spending  

2. **Potential Customers**
   - High Income, Low Spending  

3. **Impulsive Customers**
   - Low Income, High Spending  

4. **Low-Value Customers**
   - Low Income, Low Spending  

5. **Average Customers**
   - Moderate Income & Spending  

---

## 💡 Business Recommendations

- Focus on **Premium Customers** with loyalty programs  
- Target **High-Income Low-Spenders** with personalized marketing  
- Manage **Impulsive Customers** with budget-friendly offers  
- Reduce spend on **Low-Value Customers**  
- Upsell **Average Customers**  

---

## 🚀 Key Insight

Not all high-income customers are high spenders, highlighting the importance of behavior-based segmentation.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📁 Project Structure
Customer-Segmentation-KMeans/
│
├── Customer_Segmentation_KMeans_Project.ipynb
├── Mall_Customers.csv
├── README.md
