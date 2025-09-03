# Skillcraft
Task 2
Customer Segmentation using K-Means Clustering

This project focuses on segmenting customers of a retail store using unsupervised machine learning techniques. By analyzing customer demographic information and purchase behavior from the Mall Customer Dataset, the project applies K-Means clustering to group customers into distinct segments. These clusters help businesses better understand their customer base and create targeted marketing strategies, personalized offers, and improved customer experiences.

Project Overview

Customer segmentation is a critical aspect of modern business analytics. Instead of treating all customers as one group, segmentation divides them based on similar purchasing patterns and demographics.
In this project:

We use K-Means Clustering, a popular unsupervised learning algorithm, to segment customers.

We determine the optimal number of clusters using the Elbow Method.

We visualize the resulting clusters to interpret them in terms of income, spending behavior, and demographics.

Dataset Details

The project uses the Mall Customers dataset, which contains the following fields:

CustomerID – Unique identifier for each customer

Gender – Male/Female

Age – Age of the customer

Annual Income (k$) – Annual income in thousands of dollars

Spending Score (1-100) – Score assigned by the mall based on customer spending behavior and purchasing data

Steps Implemented in This Project

Data Collection – Load the dataset into the project.

Data Preprocessing – Select relevant features (e.g., Age, Income, Spending Score), handle missing values if any.

Exploratory Data Analysis (EDA) – Perform basic statistical analysis and visualize distributions.

Choosing Features for Clustering – Focus on key features like Annual Income and Spending Score for meaningful segmentation.

Applying the K-Means Algorithm – Use scikit-learn to train the model and generate clusters.

Finding the Optimal Number of Clusters – Implement the Elbow Method to decide how many clusters best represent the data.

Visualizing Results – Use matplotlib to display customer segments with different colors and centroids.

Insights & Business Applications – Derive interpretations for each cluster, such as:

High Income, High Spending → Premium Target Segment

High Income, Low Spending → Potentially Retargeted Segment

Low Income, High Spending → Price-sensitive segment but engaged customers

Low Income, Low Spending → Low-priority segment
