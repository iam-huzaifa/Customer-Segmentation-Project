**Customer Segmentation using K-Means**
**📌 Overview**

This project focuses on customer segmentation using the Mall Customers dataset. The goal is to group customers into meaningful clusters based on their Annual Income and Spending Score, which helps businesses understand different customer groups and design targeted marketing strategies.

We use the K-Means clustering algorithm, one of the most popular unsupervised learning techniques, to identify patterns and visualize customer segments.

📂** Dataset**

The dataset can be downloaded from Kaggle:
**👉 Mall Customers Dataset

Features in the dataset:

CustomerID – Unique ID for each customer

Gender – Male/Female

Age – Age of the customer

Annual Income (k$) – Annual income in thousands

Spending Score (1-100) – Score assigned by the mall based on customer behavior

⚙️ Steps in the Project

Load and explore the dataset

Preprocess the data (rename columns, check missing values)

Exploratory Data Analysis (EDA) – histograms, scatterplots, and income vs spending analysis

Elbow Method – to find the optimal number of clusters

K-Means Clustering – apply KMeans and assign cluster labels

Visualization – plot customer segments and analyze cluster centers

📊 Results

Customers were grouped into 5 clusters based on income and spending habits.

Each cluster shows a distinct profile (e.g., high-income high-spenders, low-income low-spenders).

Visualizations help interpret how customer behavior differs across groups.

🚀 Tech Stack

Python

Pandas – data handling

Matplotlib & Seaborn – data visualization

Scikit-learn – clustering (KMeans)
