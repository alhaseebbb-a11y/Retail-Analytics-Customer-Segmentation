# 🛒 Quantium Retail Analytics Virtual Experience

> A comprehensive retail analytics project completed as part of the **Quantium Data Analytics Virtual Experience Program (Forage)**. This project analyzes customer purchasing behavior, evaluates store layout trials, and provides data-driven business recommendations using Python.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

---

# 📌 Project Overview

This project simulates a real-world retail analytics engagement for **Quantium**, where the objective is to analyze supermarket chip sales data and provide actionable business insights for the Category Manager.

The project covers the complete analytics workflow:

- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Segmentation
- Trial Store Analysis
- Statistical Evaluation
- Business Recommendations
- Executive Presentation

---

# 🎯 Business Objectives

- Understand customer purchasing behaviour.
- Identify high-value customer segments.
- Analyze sales by brand and pack size.
- Evaluate the effectiveness of trial store layouts.
- Provide commercial recommendations to improve chip category performance.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

# 📂 Project Structure

```
Quantium-Retail-Analytics-Virtual-Experience/
│
├── data/
│   ├── QVI_transaction_data.csv
│   ├── QVI_purchase_behaviour.csv
│   └── QVI_data.csv
│
├── notebooks/
│   ├── Task1_Data_Preparation.ipynb
│   └── Task2_Trial_Store_Analysis.ipynb
│
├── images/
│   ├── brand_sales.png
│   ├── pack_size_sales.png
│   ├── customer_segments.png
│   ├── trial_store_77.png
│   ├── trial_store_86.png
│   └── trial_store_88.png
│
├── report/
│   ├── Quantium_Task1_Report.pdf
│   ├── Quantium_Task2_Report.pdf
│   └── Quantium_Client_Presentation.pdf
│
├── README.md
└── requirements.txt
```

---

# 📊 Task 1 – Customer Analytics

### Objectives

- Clean and prepare transaction data.
- Merge customer and transaction datasets.
- Engineer new features.
- Identify purchasing patterns.

### Key Activities

- Removed non-chip products (e.g., Salsa).
- Detected and handled outliers.
- Created Brand and Pack Size features.
- Merged transaction and customer datasets.
- Performed exploratory data analysis.

### Key Insights

- **Kettle** generated the highest sales.
- **Smiths** and **Doritos** were among the top-performing brands.
- **175g** and **150g** pack sizes contributed the highest revenue.
- **Older Families** and **Young Families** generated the highest category sales.
- **Mainstream Young Singles/Couples** were the highest-spending customer segment.

---

# 🏪 Task 2 – Trial Store Analysis

### Objectives

Evaluate whether the new store layouts improved sales performance.

### Monthly KPIs

- Total Sales
- Number of Customers
- Average Transactions per Customer

### Control Store Selection

Control stores were selected using:

- Pearson Correlation
- Magnitude Distance
- Combined Similarity Score

### Trial Stores

| Trial Store | Control Store |
|-------------|---------------|
| 77 | 233 |
| 86 | 155 |
| 88 | 125 |

### Analysis Performed

- Monthly Sales Comparison
- Customer Count Comparison
- Average Transactions per Customer
- Statistical Significance Testing

### Key Findings

- Trial Store **77** demonstrated positive sales performance.
- Trial Store **86** also showed improved performance during the trial period.
- Trial Store **88** exhibited comparatively smaller improvements.

---

# 📈 Sample Visualizations

Examples include:

- Customer Segment Analysis
- Brand Sales Distribution
- Pack Size Analysis
- Monthly Sales Comparison
- Trial vs Control Store Performance

*(Screenshots can be added here after uploading images to the repository.)*

---

# 💡 Business Recommendations

### Customer Strategy

Focus promotional campaigns on:

- Older Families
- Young Families
- Mainstream Young Singles/Couples

### Product Strategy

Increase visibility and inventory for:

- Kettle
- Smiths
- Doritos

Maintain strong stock levels for:

- 175g
- 150g pack sizes

### Store Strategy

- Continue monitoring Trial Stores 77 and 86.
- Further evaluate Store 88 before expanding the new layout to additional locations.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Statistical Analysis
- Business Intelligence
- Data Visualization
- Retail Analytics
- Business Reporting

---

# 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/<your-username>/Quantium-Retail-Analytics-Virtual-Experience.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the `notebooks/` directory and run the cells sequentially.

---

# 📄 Reports

This repository includes:

- Customer Analytics Report
- Trial Store Analysis Report
- Client Presentation

---

# 🏅 Acknowledgement

This project was completed as part of the **Quantium Data Analytics Virtual Experience Program** hosted on **Forage**.

It is intended to demonstrate practical data analytics, business problem-solving, and reporting skills using a real-world retail case study.

---

# 👨‍💻 Author

**Hasib Shaikh**

- 🎓 PGCP in Big Data Analytics (C-DAC Bengaluru)
- 💻 Aspiring Data Analyst | Data Scientist | Machine Learning Enthusiast

---

## ⭐ If you found this project interesting, consider giving it a star!
