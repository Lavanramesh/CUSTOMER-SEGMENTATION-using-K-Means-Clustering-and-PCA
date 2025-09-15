# CUSTOMER-SEGMENTATION-using-K-Means-Clustering-and-PCA

📌 Overview

This project applies data analysis and machine learning to U.S. shopper purchase data. The aim is to identify discount opportunities, analyze spending patterns by age, season, and location, and perform customer segmentation using KMeans clustering. Principal Component Analysis (PCA) was used to reduce dimensionality for visualization, making clusters easier to interpret.

🎯 Objectives

Identify low-performing product categories for discount strategies

Explore credit card spending behavior across age groups, seasons, and locations

Segment customers using KMeans clustering

Visualize clusters with PCA for better insights

Provide targeted marketing strategies for each cluster

🗂 Dataset

The dataset contains U.S. shopper purchase records with attributes such as:

Demographics: Age, Gender, Location

Shopping Behavior: Item Purchased, Category, Purchase Amount, Review Rating

Preferences: Payment Method, Subscription Status, Discount Applied, Promo Code Used

History: Previous Purchases, Frequency of Purchases

🛠 Tools & Technologies

Python – Core programming language

Pandas, NumPy – Data cleaning & manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – KMeans clustering, PCA, StandardScaler

Jupyter Notebook / VS Code – Development environment

📊 Methodology

Data Preprocessing – Cleaned categorical variables, handled missing values, normalized numerical features

Exploratory Data Analysis (EDA):

Found discount opportunities in categories like Outerwear & Footwear

Observed 50+ age group spent the most via credit cards

Seasonal spikes seen in Winter & Fall

Regional differences with Utah, Tennessee, and New Hampshire showing higher card usage

Clustering:

Selected features: Age, Purchase Amount, Previous Purchases, Subscription Status, Discounts, etc.

Applied KMeans (k=3) for segmentation

Reduced to 2D using PCA for visualization

Cluster Insights:

Cluster 0: Budget-conscious shoppers

Cluster 1: Premium buyers, highly engaged

Cluster 2: Occasional deal seekers

📈 Results & Insights

Discounts recommended for low-performing categories to boost sales

Credit card spending highest among older age groups (50+)

Seasonal demand peaks during Winter and Fall (holiday shopping)

Clustering revealed three distinct customer groups enabling targeted marketing
