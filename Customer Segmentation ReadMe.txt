# Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project performs customer segmentation using the K-Means clustering algorithm on the Mall Customers dataset. The objective is to group customers based on their annual income and spending score, helping businesses better understand customer behavior and create targeted marketing strategies.

## 🎯 Objectives

- Analyze customer purchasing behavior.
- Segment customers into meaningful groups.
- Identify patterns based on income and spending habits.
- Demonstrate the use of unsupervised machine learning for business analytics.

## 📂 Dataset

The project uses the **Mall Customers** dataset, which contains the following attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 🚀 Workflow

1. Load the dataset.
2. Perform basic data exploration and preprocessing.
3. Select relevant features for clustering.
4. Use the Elbow Method to determine the optimal number of clusters.
5. Train the K-Means clustering model.
6. Assign customers to clusters.
7. Visualize the resulting customer segments.
8. Interpret the business insights from the clusters.

## 📊 Results

The K-Means algorithm successfully groups customers into distinct segments based on their annual income and spending score. These segments can help businesses:
- Identify high-value customers.
- Design personalized marketing campaigns.
- Improve customer retention strategies.
- Make data-driven business decisions.

## 📁 Project Structure

```
Customer-Segmentation-Using-KMeans/
│── Customer_Segmentation.ipynb
│── Mall_Customers.csv
│── README.md
└── requirements.txt
```

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open `Customer_Segmentation.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce the analysis and visualizations.

## 🔮 Future Improvements

- Add Silhouette Score evaluation.
- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Build an interactive dashboard for customer analysis.
- Extend the project with additional customer features.

## 👩‍💻 Author

Developed as a machine learning mini project to demonstrate customer segmentation using unsupervised learning techniques.