# 🧠 CryptoClustering

## 📈 Project Overview

This project applies **unsupervised machine learning** techniques to cluster cryptocurrencies based on market data. The goal is to identify natural groupings using attributes such as daily and weekly price changes, and visualize these clusters to uncover insights about market behavior.

Built for the **Module 19 Challenge**, this project focuses on:
- Feature engineering
- Dimensionality reduction
- K-means clustering
- PCA visualization

## 🧰 Tools & Technologies

- Python
- Pandas
- Scikit-learn
- Plotly
- hvPlot
- Jupyter Notebooks

## 📂 Project Structure


## 🔍 Methodology

1. **Data Preprocessing**
   - Load and clean crypto market data
   - Handle missing values and convert text features to numeric where applicable

2. **Feature Engineering**
   - Focus on `price_change_percentage_24h` and `price_change_percentage_7d`
   - Normalize values

3. **Clustering**
   - Apply **K-Means** clustering
   - Choose optimal number of clusters using the Elbow Method

4. **Dimensionality Reduction**
   - Use **PCA** to reduce to 3 components for visual inspection

5. **Visualization**
   - 2D and 3D scatter plots using `hvPlot` and `Plotly`
   - Cluster label visualizations for interpretation

## 🧪 Results

- Identified **distinct clusters** of cryptocurrencies that share similar behavior over short- and medium-term timeframes
- PCA revealed strong separability, indicating meaningful groupings
- Visualizations provide insights for further market segmentation or investment strategies

## 📌 Future Work
 - Expand dataset to include volume, market cap, volatility

 - Experiment with DBSCAN or Hierarchical Clustering

 - Add real-time crypto clustering using API integration
