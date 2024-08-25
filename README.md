# Customer Segmentation In Retail Domain

# 🌐 Project Overview

This repository is dedicated to a comprehensive project that explores the dynamic landscape of online retail, centered around a dataset from a UK-based retailer available through the UCI Machine Learning Repository. The dataset captures all transactions made between 2010 and 2011, offering a robust foundation for developing advanced customer segmentation and recommendation systems aimed at refining marketing strategies and driving sales growth.

## 🌟 Problem Statement

The core objective of this project is to transform raw transactional data into a customer-centric dataset by creating new features that enable the segmentation of customers into distinct groups using the K-means clustering algorithm. This segmentation will provide insights into the unique profiles and preferences of different customer segments, thereby enhancing the effectiveness of marketing strategies and driving higher sales. Additionally, the project will develop a recommendation system to suggest top-selling products to customers within each segment who have not yet purchased those items, further optimizing marketing efforts and increasing sales.

## 🎯 Project Objectives

The specific objectives of this project include:

1. **Data Cleaning & Transformation:** Perform data cleaning by addressing missing values, duplicates, and outliers, preparing the dataset for effective clustering.
2. **Feature Engineering:** Create new features derived from the transactional data to develop a customer-centric dataset, setting the groundwork for effective customer segmentation.
3. **Data Preprocessing:** Apply feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency and accuracy of the clustering process.
4. **Customer Segmentation with K-Means Clustering:** Segment customers into distinct groups using K-means clustering, enabling targeted and personalized marketing strategies.
5. **Cluster Analysis & Evaluation:** Analyze and profile each customer segment to devise targeted marketing strategies and evaluate the quality of the clusters.
6. **Recommendation System:** Build a system that recommends best-selling products to customers within the same cluster who have not yet purchased them, aiming to boost sales and improve marketing effectiveness.

## 📚 Dataset Description

The dataset contains various metrics related to online retail transactions. Below is a summary of the features:

| **Variable**   | **Description** |
| -------------- | --------------- |
| **InvoiceNo**  | Code representing each unique transaction. If this code starts with the letter 'C', it indicates a cancellation. |
| **StockCode**  | Unique code assigned to each distinct product. |
| **Description**| Description of each product. |
| **Quantity**   | The number of units of a product in a transaction. |
| **InvoiceDate**| The date and time of the transaction. |
| **UnitPrice**  | The unit price of the product in sterling. |
| **CustomerID** | Identifier uniquely assigned to each customer. |
| **Country**    | The country of the customer. |

## 📁 File Descriptions

- **📓 Retail_Customer_Segmentation_Recommendation_System.ipynb:** Jupyter notebook containing code for data exploration, visualization, modeling, and evaluation.
- **📁 Online_Retail.csv:** CSV file containing the online retail dataset.
- **📘 README.md:** This file, offering an overview of the project.
