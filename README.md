# Mall Customer Segmentation using Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Mall Customers dataset. The goal is to understand customer demographics, income levels, and spending behaviour using Python and data visualisation techniques.

---

## 🎯 Objective

- Analyze customer demographics.
- Study annual income and spending patterns.
- Visualize relationships between different features.
- Draw meaningful insights from the data.

---

## 📂 Dataset Information

- **Dataset:** Mall Customers Dataset
- **Records:** 200
- **Features:** 5

Columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset overview
- Statistical summary
- Missing value analysis
- Duplicate value analysis
- Gender distribution
- Age distribution
- Annual income distribution
- Spending score distribution
- Age vs Spending Score
- Annual Income vs Spending Score
- Income distribution by Gender
- Correlation Heatmap

---

## 📁 Project Structure

```
Mall-Customer-EDA/
│
├── data/
│   └── Mall_Customers.csv
│
├── images/
│   ├── gender_distribution.png
│   ├── age_distribution.png
│   ├── income_distribution.png
│   ├── spending_score_distribution.png
│   ├── age_vs_spending.png
│   ├── income_vs_spending.png
│   ├── income_by_gender.png
│   └── correlation_heatmap.png
│
├── notebooks/
│   └── Mall_Customer_EDA.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📈 Key Findings

- The dataset contains customer demographic and spending information.
- Customer spending behaviour varies across different age groups.
- Annual income alone does not determine spending behaviour.
- Different customer segments can be identified based on income and spending score.
- Correlation analysis helps understand relationships among numerical features.

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```
notebooks/Mall_Customer_EDA.ipynb
```

4. Run all cells.

---



## 📌 Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can be used to understand customer behaviour through statistical summaries and visualizations. The insights obtained can support customer segmentation and future machine learning applications.

