Customer segmentation analysis using K-Means Clustering to group mall customers based on their annual income and spending behavior.

📊 Project Overview

This project analyzes 200 mall customers and segments them into 5 distinct groups using unsupervised machine learning (K-Means Clustering). The goal is to help businesses understand customer behavior and create targeted marketing strategies.

🛠️ Tools & Technologies

Python (pandas, scikit-learn, matplotlib)
Power BI (for interactive dashboard)
Dataset: Mall Customers Dataset (Kaggle)
📁 Dataset

The dataset contains 200 customer records with the following features:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
🔍 Project Workflow

Data loading and cleaning (checked for missing values)
Used the Elbow Method to determine the optimal number of clusters (k=5)
Applied K-Means Clustering on Annual Income and Spending Score
Visualized clusters using scatter plots with centroids
Analyzed average Age, Income, and Spending Score per cluster
Assigned meaningful names to each cluster based on behavior
Built an interactive Power BI dashboard with Python-integrated clustering visual
🎯 Customer Segments Identified

Cluster	Segment Name	Characteristics
0	Standard Customers	Average income, average spending
1	Premium Customers	High income, high spending
2	Impulsive Young Spenders	Low income, high spending
3	Potential Customers	High income, low spending
4	Budget Customers	Low income, low spending
📈 Results

Successfully segmented customers into 5 meaningful groups
Identified "Premium Customers" as the most valuable segment
Identified "Potential Customers" as a key opportunity for targeted marketing
📂 Files in this Repository

Mall_Customers.csv — Original dataset
Customer Segmentation.pbit — Power BI dashboard file
Customer Segmentation.pdf — Project report
🚀 How to Run

Clone this repository
Install required libraries: pip install pandas scikit-learn matplotlib
Run the Python script to generate clustering analysis
Open the .pbit file in Power BI Desktop to view the interactive dashboard
👤 Author

Abhay Tiwari
