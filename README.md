# 🎬 **Netflix Movies and TV Shows Clustering**  
## 📌 **Project Overview**  
The goal of this project is to apply clustering techniques on the Netflix Movies and TV Shows 
dataset to identify meaningful groups of content based on numerical and textual features. 
---

## 📁 Dataset Overview

- **Source**: Netflix Titles Dataset (CSV)
- **Total Records**: 7,787
- **Key Features**:
  - Type (Movie/TV Show)
  - Genre (listed_in)
  - Rating
  - Duration
  - Description
  - Release Year

---

## 🛠️ Tools and Technologies

- Python (Pandas, NumPy)
- Scikit-learn (TF-IDF, KMeans, DBSCAN, Hierarchical)
- Matplotlib, Seaborn (Visualization)
- Jupyter Notebook

---

## 🔧 Key Steps

1. **Data Preprocessing**  
   - Handled missing values  
   - Converted duration to minutes  
   - Encoded categorical columns  

2. **Feature Engineering**  
   - Extracted main genre  
   - Calculated content age  
   - One-hot encoded genre
   - Label Encoded type

3. **Text Vectorization**  
   - Applied **TF-IDF** on the listed_in and description column  
   - Selected 20 for listed_in and 800 for description TF-IDF features  

4. **Clustering Models Used**  
   - K-Means (best performance)  
   - Hierarchical Clustering  
   - DBSCAN (noise-based clustering)

---

## 🔍 Cluster Insights

- **Cluster 0**: Older, long-duration content  
- **Cluster 1**: Modern mainstream Netflix content    
- **Cluster 2**: Very recent content, short duration 

---

## ✅ Conclusion 

The clustering approach successfully grouped Netflix content into three meaningful clusters, 
providing insights into content age, duration, and structure. 

---
