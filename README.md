# Dimensionality Reduction Techniques: A Comparative Study

## Overview
This project explores and compares various dimensionality reduction techniques, providing implementations for both image and tabular datasets. The goal is to demonstrate the effectiveness of these techniques in reducing high-dimensional data into meaningful lower-dimensional representations while preserving key features and relationships.

## Objectives
- Implement and visualize dimensionality reduction techniques using Python and Jupyter notebooks.
- Compare the performance of these techniques across distinct datasets.
- Provide interactive visualizations for t-SNE and UMAP.
- Demonstrate implementations in Databricks for scalability.

---

## Techniques Implemented
1. **Linear Techniques**
   - Randomized PCA
   - Kernel PCA
   - Incremental PCA
   - Factor Analysis

2. **Manifold Learning Techniques**
   - Locally Linear Embedding (LLE)
   - Isomap
   - Multidimensional Scaling (MDS)
   - t-SNE (Interactive visualization using Plotly)
   - UMAP (Interactive visualization using UMAP Explorer)

3. **Deep Learning**
   - Autoencoders (using TensorFlow/Keras)

---

## Datasets
1. **Image Dataset**
   - MNIST Digits Dataset (from Scikit-learn)
   - [Additional medical dataset](https://www.kaggle.com/datasets) for exploratory analysis.

2. **Tabular Dataset**
   - Iris Dataset (from Scikit-learn)
   - [Medical tabular dataset](https://www.kaggle.com/datasets) for dimensionality reduction.

---

## Sample Colab Links
Here are Colab notebooks to understand and explore dimensionality reduction techniques:

- [Hands-On ML: Dimensionality Reduction](https://github.com/ageron/handson-ml2/blob/master/08_dimensionality_reduction.ipynb)
- [Dimensionality Reduction Techniques](https://colab.research.google.com/github/ML-Challenge/week4-unsupervised-learning/blob/master/L3.Decorrelating%20data%20and%20dimension%20reduction.ipynb)
- [Dimensionality Reduction with Autoencoders](https://colab.research.google.com/drive/1J9hbUkKvl6bM6rEHH7OTZZQlta1PC2dy)

---

## Results and Comparisons
- Visualizations include scatter plots, cluster separations, and embedding spaces.
- Observations highlight the preservation of data structure and clustering effectiveness.
- Runtime comparisons for large datasets across techniques.

---
