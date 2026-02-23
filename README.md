# 🎬 FlixPredict — Intelligent Movie Recommendation System (ML + NLP)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![ML](https://img.shields.io/badge/MachineLearning-NLP-green)

🔗 **Live Demo:**  
https://flix-predict-movie-recommender.streamlit.app/

FlixPredict is a **content-based movie recommendation system** built using **Machine Learning (ML)** and **Natural Language Processing (NLP)**.  
It helps users discover movies by analyzing metadata such as genre, cast, keywords, and plot descriptions to generate smart, similarity-based recommendations.

Designed as an end-to-end ML application, the project combines data preprocessing, NLP feature engineering, similarity modeling, and an interactive Streamlit interface to deliver a smooth movie discovery experience.

---

## ✨ Key Features

### 🎯 Smart Movie Recommendations
- Recommend movies similar to a selected title
- Content-based filtering using NLP features
- Cosine similarity ranking for accurate suggestions

### 📖 Movie Description Module
- Displays detailed movie information:
  - Overview
  - Rating
  - Runtime
  - Genre
  - Cast details

### 🎬 Browse All Movies
- Paginated movie exploration
- Fast UI rendering with Streamlit components

### ⚡ Interactive UI
- Clean Streamlit interface
- Real-time recommendations
- Smooth navigation between modules

---

## 🧠 Machine Learning Pipeline

The system follows a structured recommendation workflow:

```

Movie Metadata (TMDB)
↓
Data Cleaning & Feature Engineering
↓
NLP Preprocessing (tokenization, stopwords, stemming)
↓
Vectorization (Bag of Words / TF-IDF)
↓
Cosine Similarity Computation
↓
Top-N Similar Movie Recommendations

```

---

## 🏗️ System Architecture

```

User Input (Select Movie)
↓
Feature Extraction (NLP)
↓
Vectorization
↓
Similarity Matrix
↓
Recommendation Engine
↓
Streamlit UI Display

```

---

## 🛠️ Tech Stack

### Core Technologies
- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- NLTK

### Machine Learning & NLP
- Content-Based Filtering
- Bag of Words (BoW)
- TF-IDF Vectorization
- Cosine Similarity

### Deployment
- Streamlit Cloud

---

## 📂 Project Structure

```

FlixPredict/
│
├── Files/                     # Dataset + serialized data files
├── processing/
│   ├── preprocess.py          # Data preprocessing & feature generation
│   ├── display.py             # UI rendering and display logic
│   └── **init**.py
│
├── main.py                    # Streamlit entry point
├── requirements.txt
├── runtime.txt                # Python version for deployment
└── README.md

````

---

## ⚙️ Local Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/anjana-474/Flix-Predict.git
cd Flix-Predict
````

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Application

```bash
streamlit run main.py
```

---

## ☁️ Deployment

This application is deployed using **Streamlit Cloud**.

🌐 Live App:
[https://flix-predict-movie-recommender.streamlit.app/](https://flix-predict-movie-recommender.streamlit.app/)

---

## 📊 Model Overview

* Recommendation Type: **Content-Based Filtering**
* Input Features:

  * Genres
  * Cast
  * Keywords
  * Movie Overview
  * Production Information
* Similarity Metric: **Cosine Similarity**
* Vector Space Representation: NLP-based feature vectors

---

## 📈 Future Enhancements

* Hybrid recommendation system (Content + Collaborative Filtering)
* User profile personalization
* Real-time movie metadata via TMDB API
* Model optimization for faster similarity lookup
* Mobile-first responsive UI
* Cloud-scale deployment architecture

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

icite:0]{index=0}
```
