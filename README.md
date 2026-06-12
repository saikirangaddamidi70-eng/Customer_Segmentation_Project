
# Customer Segmentation Project

## 📌 Overview

This project focuses on customer segmentation using data analytics and machine learning techniques. By analyzing customer demographics and purchasing behavior, customers are grouped into meaningful segments that help businesses understand different customer profiles and improve marketing strategies.

The project includes data preprocessing, exploratory data analysis (EDA), feature scaling, K-Means clustering, visualization, and business insights.
<img width="1342" height="760" alt="Customer_Segmentation_Overview" src="https://github.com/user-attachments/assets/c71768db-facc-4ee8-b8d2-a0c9bb177d1e" />


---

## 🎯 Objectives

- Clean and preprocess customer data
- Perform Exploratory Data Analysis (EDA)
- Identify patterns in customer behavior
- Segment customers using K-Means Clustering
- Visualize customer groups and distributions
- Generate actionable business insights for decision-making

---

## 📂 Dataset

The dataset contains the following columns:

- Customer_ID
- Age
- Gender
- Annual_Income
- Spending_Score
- Purchase_Frequency
- Total_Purchase_Amount

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value detection
- Duplicate value checking
- Statistical summary
- Gender distribution
- Histograms
- Box plots
- Correlation matrix
- Correlation heatmap

---

## 🤖 Machine Learning

### Feature Selection

Selected features:

- Age
- Annual_Income
- Spending_Score
- Purchase_Frequency
- Total_Purchase_Amount

### Feature Scaling

StandardScaler was used to normalize numerical features before clustering.

### K-Means Clustering

- Optimal number of clusters determined using the Elbow Method
- K-Means algorithm applied to segment customers
- Cluster labels assigned to each customer

---

## 📈 Visualizations

The project includes:

- Histograms
- Box Plots
- Correlation Heatmap
- Elbow Method Graph
- Income vs Spending Score Scatter Plot
- Purchase Frequency vs Total Purchase Scatter Plot
- Cluster Distribution Chart
- Customer Segment Analysis

---

## 💡 Business Insights

The segmentation helps identify:

- High-value customers
- Frequent buyers
- Low-spending customers
- Potential loyal customers
- Customers requiring targeted marketing campaigns

These insights can improve customer retention, personalized marketing, and business growth.

---

## 📁 Project Structure

```
Customer-Segmentation/
│
├── Customer_Segmentation.ipynb
├── customer_data.csv
├── customer_segments.csv
├── Customer_Segments.pbix
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells in `Customer_Segmentation.ipynb`.

5. The segmented dataset will be generated as:

```
customer_segments.csv
```

---

## 📊 Results

The project successfully segments customers based on purchasing behavior and demographics. The generated clusters provide meaningful insights that can be used for:

- Customer targeting
- Marketing campaigns
- Product recommendations
- Loyalty programs
- Revenue optimization

---

## 🚀 Future Enhancements

- Interactive dashboards using Power BI or Tableau
- Additional clustering algorithms (DBSCAN, Hierarchical Clustering)
- Predictive customer lifetime value analysis
- Real-time customer segmentation
- Recommendation system integration

---

## 📌 Conclusion

This project demonstrates how machine learning and data analytics can be used to understand customer behavior and create actionable customer segments. The insights obtained from clustering can help organizations make data-driven marketing decisions and enhance customer engagement.

---

## 👨‍💻 Author

**GADDAMIDI SAIKIRAN**

Customer Segmentation Project using Python, Jupyter Notebook, and K-Means Clustering.
