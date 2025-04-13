# 🛍️ Customer Segmentation Using RFM Analysis and K-Means Clustering

This project focuses on understanding and segmenting customers based on their purchasing behavior using the **Online Retail dataset** from the UCI Machine Learning Repository. By leveraging **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering**, the goal is to categorize customers into meaningful segments for targeted marketing and business strategies.

---

## 📌 Project Summary

Understanding customer behavior is critical for any business. In this project, I performed:

- 📊 **Exploratory Data Analysis (EDA)** to explore trends and transaction patterns  
- 📦 **RFM analysis** to assign behavior-based scores to customers  
- 🧠 **K-Means clustering** to group customers based on RFM behavior  
- 🎯 **Segmentation** into categories like Champions, Loyal, At Risk, Lost  
- 📈 **Visualizations** to present insights clearly and drive actionable strategies

---

## 🧰 Tools & Libraries Used

- Python 3.11  
- Pandas, NumPy for data manipulation  
- Seaborn, Matplotlib for visualization  
- Scikit-learn for K-Means clustering and preprocessing  
- Jupyter Notebook for development

---

## 📂 Dataset

**Source:** [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)  
The dataset contains over 500,000 transactions from a UK-based online retailer between 2010 and 2011.

---

## ✅ Key Features of the Project

### 🔍 Exploratory Data Analysis (EDA)
- Total spending and frequency per customer
- Cancelled orders and basket size analysis
- Revenue trends over time and by country

### 📊 RFM (Recency, Frequency, Monetary) Analysis
- Recency: Days since last purchase
- Frequency: Number of purchases
- Monetary: Total amount spent
- Quantile-based scoring system (1 to 5)
- Customer segmentation based on combined RFM scores

### 🤖 K-Means Clustering
- Standardized RFM values
- Elbow method to determine optimal `k`
- K-Means applied with `k=4`
- Cluster labeling into:
  - Champions
  - Loyal
  - Potential Loyalists
  - At Risk
  - Lost

### 📈 Visualizations
- Histograms, heatmaps, box plots
- Monthly revenue trend
- Top 10 spenders
- Cluster distribution
- Correlation heatmap

---

## 📌 How to Run This Project

1. Clone the repository  
   ```
   git clone https://github.com/your-username/customer-segmentation-rfm.git
   cd customer-segmentation-rfm
   ```

2. Install dependencies  
   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook  
   ```
   jupyter notebook CustomerSegmentation.ipynb
   ```

---

## 📈 Output Highlights

- Segmented over 4,000 customers
- Identified high-value customers for targeted campaigns
- Visual reports for business and marketing decisions

---

## 📚 References

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [scikit-learn Clustering](https://scikit-learn.org/stable/modules/clustering.html#k-means)  
- [Seaborn Documentation](https://seaborn.pydata.org/)  
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)  

---

## 👋 Let’s Connect

If you're working on customer analytics, segmentation, or machine learning projects, feel free to connect or reach out — I’m always open to feedback and collaboration!
