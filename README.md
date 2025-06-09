
# 📰 News Clustering with Sentence Transformers

This project demonstrates **unsupervised text clustering** of news headlines using **Sentence Transformers** and **clustering algorithms** like **KMeans**. The notebook walks through the entire process from data loading to visualization, offering a practical use case for semantic text embeddings.

---

## 📚 Overview

**Goal**: Group similar news headlines together by their semantic meaning using sentence embeddings and visualize the clusters.

### Key Steps:

* Load and preprocess news headline data
* Encode headlines using a pretrained Sentence Transformer
* Reduce dimensionality for visualization (via PCA or UMAP)
* Apply clustering (KMeans)
* Visualize clusters with word clouds and scatter plots

---

## 🛠️ Technologies Used

* [Sentence Transformers (`sentence-transformers`)](https://www.sbert.net/)
* [scikit-learn](https://scikit-learn.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib, seaborn](https://matplotlib.org/)
* [wordcloud](https://github.com/amueller/word_cloud)
* [UMAP](https://umap-learn.readthedocs.io/en/latest/)

---

## 📂 Dataset

The notebook uses a news headline dataset (`news_headlines.csv`) with short text snippets. These are passed through a transformer model to obtain sentence-level embeddings.

> 📌 *Note: The dataset used in the notebook is not provided in the repo. Make sure to include or link the `news_headlines.csv` file for reproducibility.*

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/manasdhir/News_clustering_transformers.git
cd News_clustering_transformers
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

Or manually install the key libraries:

```bash
pip install sentence-transformers pandas scikit-learn matplotlib seaborn wordcloud umap-learn
```

### 3. Run the Notebook

Use Jupyter or VS Code to open and run:

```bash
jupyter notebook Text_clustering_Sentence_Transformer.ipynb
```

---

## 📊 Results

* Visualizes clustered sentence embeddings in 2D.
* Shows the top words in each cluster via word clouds.
* Demonstrates the power of transformer-based embeddings in understanding text similarity.

---

## 🧠 Concepts Highlighted

* **Sentence Embeddings** with `all-MiniLM-L6-v2`
* **KMeans Clustering** on high-dimensional vectors
* **Dimensionality Reduction** using UMAP/PCA
* **Word Cloud Visualization** for cluster interpretation

---

## ✅ Example Output

![Sample scatter plot of clustered news headlines](https://raw.githubusercontent.com/manasdhir/News_clustering_transformers/main/clusters_visual.png)
*A scatter plot of clustered news headlines in 2D space.*

---
