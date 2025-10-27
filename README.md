
# 🧠 Unveiling Hidden Patterns: Dimensionality Reduction and Visualization using PCA & t-SNE  

This repository presents a **hands-on exploration of dimensionality reduction** techniques using high-dimensional datasets. The focus is to demonstrate how **PCA (Principal Component Analysis)** and **t-SNE (t-Distributed Stochastic Neighbor Embedding)** help compress features and visualize complex data structures — all while maintaining strong model performance and interpretability.  

---

## 📌 Overview  
📂 Loaded and preprocessed a high-dimensional dataset  
⚙️ Standardized features using **StandardScaler** to normalize input data  
📉 Applied **PCA** to extract principal components capturing maximum variance  
🌀 Used **t-SNE** to project the dataset into 2D and 3D visual spaces  
🤖 Compared baseline and reduced-dimension models using **Logistic Regression**  
📊 Evaluated trade-offs between accuracy, variance retention, and visualization clarity  

---

## 💡 Key Insights  
🔹 **PCA** efficiently compresses features while preserving most of the data’s variance  
🔹 **t-SNE** uncovers hidden structures and clusters that linear methods might miss  
🔹 **Dimensionality reduction** improves visualization and reduces model complexity  
🔹 Visual comparisons highlight the strengths of linear (PCA) vs. non-linear (t-SNE) approaches  

---

## 🛠 Tech Stack  
**Language:** Python  
**Libraries:** NumPy • Pandas • Scikit-learn • Matplotlib • Seaborn  

---

## 📊 Results  
📈 Baseline Logistic Regression Accuracy: **98%**  
📉 Logistic Regression with PCA (Reduced Dimensions): **97%**  
🌀 **t-SNE visualizations** reveal clear separations among classes with minor overlaps  
🎯 Dimensionality reduction achieved ~40% compression while retaining interpretability  

---

## 🚀 Conclusion  
This project showcases how **dimensionality reduction** techniques can make complex datasets more interpretable and visually meaningful. By combining **PCA’s efficiency** with **t-SNE’s expressiveness**, this notebook provides a strong foundation for exploratory data analysis, visualization, and feature optimization in real-world machine learning tasks.  
```
