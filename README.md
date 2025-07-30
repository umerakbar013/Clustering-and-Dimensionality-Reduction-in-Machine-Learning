tool used = chat-GPT
Clustering and Dimensionality Reduction in Machine Learning



# 🧠 Clustering and Dimensionality Reduction in Machine Learning

This project explores unsupervised machine learning techniques including **dimensionality reduction** (PCA and t-SNE) and **clustering algorithms** (KMeans, DBSCAN), applied on a real-world customer segmentation dataset.

---

## 📌 Objective

To analyze customer data and segment them into meaningful groups by:
- Reducing the dataset dimensions for better visualization and insight
- Clustering data to uncover hidden groupings
- Evaluating and comparing clustering results using various metrics

---

## 📂 Dataset

**Mall Customer Segmentation Dataset**

**Features:**
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## ⚙️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🧪 Project Steps

### 1. Data Preprocessing
- Loaded dataset and performed EDA
- Handled missing/duplicate values
- Encoded categorical features (`Gender`)
- Scaled numerical features using `StandardScaler`

### 2. Dimensionality Reduction
- Applied **PCA** to reduce features to 2D and interpret variance
- Applied **t-SNE** for non-linear dimensionality reduction
- Visualized results using 2D scatter plots

### 3. Clustering Techniques
- Used **KMeans** with Elbow Method to find optimal clusters
- Applied **DBSCAN** to detect dense clusters and noise
- Plotted clusters on PCA-reduced space

### 4. Evaluation Metrics
- **Silhouette Score**
- **Davies-Bouldin Index**
- Compared performance of KMeans vs DBSCAN

---

## 📊 Results & Insights

- PCA explained >95% variance using just 2 components.
- KMeans with 5 clusters showed distinct, well-separated groups.
- DBSCAN was sensitive to `eps` and detected noise effectively.
- KMeans performed better in terms of Silhouette and Davies-Bouldin scores.

---

## 📝 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/clustering-dim-reduction.git
   cd clustering-dim-reduction
