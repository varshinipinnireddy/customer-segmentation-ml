# Customer Segmentation using Machine Learning

## Project Overview

Customer segmentation is an important technique used by businesses to understand their customers better and design targeted marketing strategies.

This project applies **Machine Learning clustering techniques** to group customers based on their purchasing behavior using the **Mall Customers dataset**.

By identifying distinct customer groups, businesses can improve marketing strategies, increase sales, and enhance customer satisfaction.

---

## Dataset

The dataset used in this project is the **Mall Customers dataset**, which contains customer demographic and spending information.

Features include:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

Dataset Source: Kaggle Mall Customers Dataset

---

## Problem Statement

Businesses often struggle to identify different types of customers within their market.

The goal of this project is to use **unsupervised machine learning** to segment customers into groups based on **income and spending behavior**, enabling businesses to:

* Identify high-value customers
* Design targeted marketing campaigns
* Improve customer retention strategies

---

## Machine Learning Approach

This project uses the **K-Means Clustering Algorithm**, a popular unsupervised learning technique.

Key steps include:

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature selection
4. Determining optimal number of clusters using the **Elbow Method**
5. Applying **K-Means clustering**
6. Visualizing customer segments

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Project Structure

```
customer-segmentation-ml
│
├── Mall_Customers.csv
├── CustomerSegmentationUsingKMeans.ipynb
└── README.md
```

---

## Results

The K-Means clustering algorithm successfully identified **distinct customer segments** based on income and spending behavior.

These segments can be used to:

* Identify **high-spending customers**
* Understand **budget-conscious shoppers**
* Develop **targeted marketing strategies**

---

## Visualization Example

The clusters are visualized using a scatter plot showing **Annual Income vs Spending Score**, where each color represents a different customer segment.

---

## Future Improvements

Possible enhancements for this project include:

* Using **PCA for dimensionality reduction**
* Comparing with other clustering algorithms (DBSCAN, Hierarchical Clustering)
* Deploying the model as a **web application**
* Building an interactive **dashboard**

---

## Author

**Varshini Pinnireddy**

GitHub: https://github.com/varshinipinnireddy
LinkedIn: https://linkedin.com/in/varshini-pinnireddy

---

## License

This project is open-source and available for educational and research purposes.
