# 🎬 Video Recommender System

A simple and effective **Video Recommendation System** built using Python and Jupyter Notebook.  
This project recommends videos based on similarity metrics derived from the dataset.

---

## 📌 Project Overview

This project analyzes a dataset of videos and builds a recommendation engine that suggests similar videos based on content features.

It uses:

- Data preprocessing with **Pandas**
- Text vectorization
- Similarity calculation (e.g., Cosine Similarity)
- Jupyter Notebook for experimentation and demonstration

---

## 📂 Project Structure
```bash
├── Video Recommender.ipynb # Main notebook containing implementation)
├── Dataset.csv # Dataset used for training and recommendations
├── README.md # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️. Clone the Repository

```bash
git clone https://github.com/anandh1709/video-recommender.git
cd video-recommender
```

### 2. Install Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3. Run the Notebook
```bash
Video Recommender.ipynb
```
---

## 📊 Dataset

The dataset (`Dataset.csv`) contains video-related information such as:

- Title  
- Description  
- Tags / Keywords  
- Category  
- Other relevant metadata  

The recommendation system uses this data to compute similarity between videos.

---

## 🧠 How It Works

1. **Data Cleaning**
   - Handle missing values
   - Remove duplicates
   - Combine relevant text fields (e.g., title + tags + description)

2. **Feature Engineering**
   - Convert text data into numerical vectors using:
     - Count Vectorization  
     - TF-IDF (Term Frequency – Inverse Document Frequency)

3. **Similarity Calculation**
   - Compute cosine similarity between video vectors
   - Create a similarity matrix

4. **Recommendation Function**
   - Input: A video title
   - Process: Find similarity scores with all other videos
   - Output: Top N most similar videos

## Future Improvements

* Add a web interface using Flask or Streamlit
* Deploy as a web application
* Implement collaborative filtering
* Improve ranking algorithm
* Add user-based personalization
* Include evaluation metrics (Precision, Recall, F1-score)
* Optimize performance for large datasets

## Technologies Used
🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
