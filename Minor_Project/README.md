# 🎵 Spotify Songs’ Genre Segmentation  
### 🧠 Corizo AI Internship Minor Project

## 📌 Project Overview
This project focuses on the application of Machine Learning techniques to perform **genre segmentation** of songs based on various audio features provided by Spotify. The model aims to identify and classify different music genres using clustering techniques, primarily unsupervised learning.

---

## 🚀 Objective
To segment songs into clusters (genres or sub-genres) by analyzing audio-based features like tempo, danceability, loudness, energy, etc., using data-driven methods.

---

## 🛠️ Tech Stack & Libraries Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- Numpy  
- Matplotlib  
- Seaborn  
- Scikit-learn (PCA, KMeans, Evaluation Metrics)
- Plotly (for interactive visualizations)

---

## 📁 Dataset
- **Source:** Spotify (pre-collected dataset with audio features and genres)
- **Attributes:**  
  - Acousticness  
  - Danceability  
  - Energy  
  - Instrumentalness  
  - Liveness  
  - Loudness  
  - Speechiness  
  - Tempo  
  - Valence  
  - Duration_ms  
  - Genre (for evaluation)

---

## 🔍 Key Steps

1. **Data Cleaning & Preprocessing**  
   - Null value handling  
   - Feature normalization  
   - Dimensionality reduction using PCA

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of features  
   - Correlation heatmaps  
   - Genre-wise feature behavior

3. **Modeling**  
   - KMeans Clustering  
   - Finding optimal `k` using Elbow Method  
   - Visualization of clusters in 2D space using PCA

4. **Evaluation**  
   - Confusion Matrix  
   - Accuracy Score  
   - Silhouette Score

---

## 📊 Results

- Songs were effectively segmented into meaningful clusters based on feature similarity.
- Clusters aligned well with genre labels, demonstrating the power of unsupervised learning in music classification.

---

## 🎯 Conclusion

This project demonstrates the capability of AI/ML in understanding complex patterns in audio data. The unsupervised learning approach helped reveal hidden groupings in the Spotify song dataset that correlate well with genres.

---

## 📌 How to Run

1. Clone the repository or download the `.ipynb` file  
2. Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn plotly
    ```
3. Run the notebook using Jupyter:
    ```bash
    jupyter notebook Spotify Songs’Genre Segmentation.ipynb
    ```

---

## 📬 Contact

**Sujith Kumar**  
AI Intern @ Corizo  
---

