# 🎬 Netflix Movies & TV Shows – Clustering with Unsupervised Learning

This project explores the Netflix dataset to uncover patterns and group similar content using **KMeans Clustering**, a popular unsupervised machine learning algorithm. The goal is to segment titles based on attributes like type, genre, release year, and duration, which can help in personalization, recommendation systems, or content strategy decisions.

---

## 📊 Tools & Technologies
- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Clustering & evaluation
- **PCA** – Dimensionality reduction

---

## 📁 Dataset Overview
- Contains information like title, type, genre, cast, release year, country, duration, and description.
- Preprocessed and encoded for unsupervised analysis.

---

## 🔍 Problem Statement
Group Netflix titles into meaningful clusters based on their features to identify patterns in content types and explore potential use in recommendation engines or marketing strategies.

---

## 🧹 Data Wrangling & Preprocessing
- Removed duplicates and null values
- Extracted key features like duration in minutes
- Encoded categorical features (genre, type)
- Scaled numerical features for clustering
- Applied PCA for 2D visualization

---

## 🤖 Clustering Approach
- Chose **KMeans** algorithm for its simplicity and scalability
- Used **Elbow Method** and **Silhouette Score** to find the optimal number of clusters
- Visualized clusters using **PCA** 

---

## 📈 Key Insights
- Titles were grouped into clusters with similar genres, durations, and release years
- Identified dominant content types in each cluster (e.g., short comedies, long thrillers, classic movies)
- Helped in understanding the diversity of Netflix's catalog

---

## 🧠 Evaluation
- Used **Silhouette Score** to evaluate cluster cohesion and separation
- Visualized clusters to assess logical groupings

---

## 🚀 Future Scope
- Integrate content-based filtering with clustering for hybrid recommendations
- Use NLP to cluster based on content descriptions
- Deploy as a web app to explore cluster-wise recommendations interactively




