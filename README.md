# 🎬 Movie Recommendation System

A powerful **content-based movie recommendation system** built using **Python, Machine Learning, and Streamlit**.  
This application suggests movies similar to a selected movie by analyzing metadata such as genres, cast, keywords, and overview using **Natural Language Processing (NLP)** techniques.
 
---

## 📌 Overview

The goal of this project is to build a recommendation engine that helps users discover movies based on their preferences.  
Unlike basic filtering, this system uses **content-based filtering** to analyze movie attributes and provide relevant suggestions.

---

## ✨ Features

- 🔍 **Search Functionality** – Easily search and select movies  
- 🎯 **Smart Recommendations** – Suggests similar movies using ML algorithms  
- 🖼️ **Movie Posters** – Displays posters for better visualization  
- ⚡ **Fast Performance** – Uses precomputed similarity matrix  
- 💻 **Interactive UI** – Built with Streamlit for seamless experience  
- 📊 **Efficient Processing** – Optimized for quick recommendations  

---

## 🧠 How It Works

### 1. Data Collection
- Dataset: `movies_metadata.csv`
- Contains movie details such as title, genres, cast, keywords, and overview

### 2. Data Preprocessing
- Handles missing values  
- Extracts relevant features  
- Combines features into a single column (`tags`)  

### 3. Feature Engineering
- Converts textual data into numerical form using:
  - **TF-IDF Vectorization**

### 4. Similarity Calculation
- Computes similarity between movies using:
  - **Cosine Similarity**

### 5. Recommendation System
- When a user selects a movie:
  - Finds its index  
  - Retrieves top similar movies  
  - Displays recommendations with posters  

---

## 🛠️ Tech Stack

### 🔹 Frontend
- Streamlit  

### 🔹 Backend
- Python  

### 🔹 Libraries & Tools
- Pandas  
- NumPy  
- Scikit-learn  
- Pickle  

---

## 📂 Project Structure
```
Movie_recommendation_system/
│
├── app.py # Main Streamlit application
├── main.py # Model building and preprocessing
├── movies_metadata.csv # Dataset
├── tfidf.pkl # TF-IDF model
├── tfidf_matrix.pkl # Similarity matrix
├── indices.pkl # Movie index mapping
├── requirements.txt # Project dependencies
└── README.md # Documentation
```


---

## 🎯 Use Cases

- 🎬 Movie recommendation platforms  
- 📺 OTT services (Netflix, Prime-like systems)  
- 📊 Content filtering systems  
- 🤖 Beginner ML/NLP projects  

---

## 🔮 Future Improvements

- 🔐 User login & personalization  
- 🤝 Collaborative filtering  
- 🌐 Deploy on cloud platforms  
- 📈 Improve recommendation accuracy  
- 🎨 Better UI with React frontend  
- 🔗 Integration with TMDB/IMDb APIs  

---

## 💡 Key Learnings

- Natural Language Processing (NLP)  
- TF-IDF Vectorization  
- Cosine Similarity  
- Building recommendation systems  
- Developing interactive ML apps using Streamlit  

---

