# eCommerce Data Science Project

This repository contains the solutions to the Data Science Intern Assignment focused on exploratory data analysis (EDA), predictive modeling, and customer segmentation for an eCommerce transactions dataset. The project consists of three main tasks: EDA, Lookalike Modeling, and Clustering.

---

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Tasks and Deliverables](#tasks-and-deliverables)
- [File Structure](#file-structure)
- [How to Use](#how-to-use)
- [Results and Insights](#results-and-insights)
- [Technologies Used](#technologies-used)

---

## Overview

The project involves analyzing an eCommerce dataset to derive actionable business insights, build a recommendation system for similar customers (Lookalike Model), and perform customer segmentation using clustering techniques.

---

## Dataset Description

The dataset consists of three files:
1. **Customers.csv**: Contains details of customers such as ID, name, region, and signup date.
2. **Products.csv**: Contains details of products including ID, name, category, and price.
3. **Transactions.csv**: Contains transactional data including transaction ID, customer ID, product ID, date, quantity, and total value.

---

## Tasks and Deliverables

### 1. **Exploratory Data Analysis (EDA)**
- Analyze the dataset to identify trends, outliers, and business insights.
- Deliverables:
  - **`Vaishnavi_Pandey_EDA.ipynb`**: Jupyter Notebook with EDA code.
  - **`Vaishnavi_Pandey_EDA.pdf`**: Report summarizing business insights.

### 2. **Lookalike Model**
- Build a model to recommend the top 3 most similar customers for a given user based on profile and transaction history.
- Deliverables:
  - **`Vaishnavi_Pandey_Lookalike.ipynb`**: Jupyter Notebook with model development.
  - **`Lookalike.csv`**: File mapping each customer to their top 3 lookalikes with similarity scores.

### 3. **Customer Segmentation (Clustering)**
- Perform customer segmentation using clustering techniques.
- Deliverables:
  - **`Vaishnavi_Pandey_Clustering.ipynb`**: Jupyter Notebook with clustering code.
  - **`Vaishnavi_Pandey_Clustering.pdf`**: Report detailing the clustering results.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/ecommerce-data-science.git
   cd ecommerce-data-science
2.  Run Notebooks:
Open the Jupyter Notebooks to explore the analysis and models:
```bash
jupyter notebook
```

## Technologies Used

### Programming Language
- Python

### Libraries
- **Data Analysis**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`

### Tools
- **Jupyter Notebook**

  # Results and Insights

## Exploratory Data Analysis (EDA)
- Identified regional spending patterns and top product categories.
- Derived insights on customer behavior and transaction trends, highlighting:
  - Differences in spending across regions.
  - Popular product categories among different customer segments.
  - Key trends in transaction volumes over time.

## Lookalike Model
- Built a similarity-based recommendation system to identify lookalike customers.
- Provided top 3 lookalike customers for the first 20 users, along with similarity scores to facilitate personalized marketing strategies.

## Customer Segmentation
- Used DBSCAN (Density-Based Spatial Clustering of Applications with Noise) for clustering customers based on spending and transaction patterns.
- Achieved a **Davies-Bouldin Index of 1.25**, indicating moderately well-defined clusters, which suggests a good balance between cluster separation and intra-cluster coherence.

## Visualizations
- **Regional Spending**: A heatmap or bar chart visualizing regional spending patterns.
- **Customer Segments**: Scatter plots visualizing the customer segments created through DBSCAN.

## Conclusion
- Insights gained from the analysis provide actionable strategies for targeting high-value customer segments and enhancing the overall customer experience.

