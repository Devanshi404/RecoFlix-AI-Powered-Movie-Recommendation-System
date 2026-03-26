# RecoFlix-AI-Powered-Movie-Recommendation-System
A Netflix-style **content-based movie recommendation system** built using Machine Learning and NLP techniques. Developed a content-based movie recommendation system using Machine Learning and NLP techniques.
Utilized the TMDB dataset to analyze movie metadata such as genres, cast, crew, and keywords.
Performed data preprocessing and feature engineering to combine multiple attributes into a single representation.
Applied TF-IDF vectorization to convert text data into numerical form for analysis.
Used cosine similarity to identify and recommend movies similar to a given input.
Designed a scalable and efficient system that mimics real-world recommendation engines like Netflix.

---

## Features

- Content-based filtering
- Uses multiple features (cast, crew, genres, keywords, overview)
- NLP-based feature engineering
- TF-IDF vectorization for improved accuracy
- Cosine similarity for finding similar movies

---

## How It Works

1. **Data Collection**
   - TMDB 5000 Movies and Credits dataset

2. **Data Preprocessing**
   - Converted JSON-like columns into usable format
   - Extracted top 3 cast members
   - Extracted director from crew

3. **Feature Engineering**
   - Combined multiple features into one text column

4. **Vectorization**
   - Used TF-IDF Vectorizer to convert text into numerical vectors

5. **Similarity Calculation**
   - Applied cosine similarity to recommend similar movies

---

## Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- NLP (TF-IDF)
## Project Structure
  <img width="1360" height="450" alt="Screenshot 2026-03-26 114837" src="https://github.com/user-attachments/assets/9b834f79-a298-4a11-bd0e-ed8c681cfd67" />
