# 🎬 Movie Recommender System

This is a simple content-based movie recommender system built using Python. It recommends similar movies based on the selected movie using cosine similarity.

## 🚀 Features

- Recommend movies based on similarity score
- Uses `scikit-learn`, `pandas`, and `numpy`
- Flask web application
- Frontend styled with HTML/CSS
- Efficient movie poster retrieval via TMDb API

## 🛠 Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- Numpy
- TMDb API
- HTML/CSS
- JavaScript

## ⚙️ Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/NisargaRamesh/Movie_Recommender_System.git
    cd Movie_Recommender_System
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate   # On Windows
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file and add your TMDb API key:
    ```
    TMDB_API_KEY=your_api_key_here
    ```

5. Run the app:
    ```bash
    python app.py
    ```

6. Open your browser and visit `http://127.0.0.1:5000/`.

## ⚠️ Notes

- `similarity.pkl` is a large file (>100MB) and is **excluded** from version control via `.gitignore`.
- Secrets (like API keys) are stored securely in a `.env` file and also excluded from Git.


