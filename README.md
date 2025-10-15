# Movie Recommendation System

This repository contains a simple movie recommendation system built with Python and Streamlit.

Contents:
- `app.py` - Streamlit app that provides movie recommendations.
- `Movie_Recommendation_System.ipynb` - Notebook used to preprocess data and build the recommendation pipeline.
- `tmdb_5000_movies.csv`, `tmdb_5000_credits.csv` - datasets used to build the model.
- `artifacts/` - precomputed artifacts (similarity matrix, vectorizer, indices).

Quick start
1. Create and activate a virtual environment (Windows PowerShell):

```powershell
C:/Users/princ/Desktop/movie/.venv/Scripts/Activate.ps1
```

Or create one:

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
C:/Users/princ/Desktop/movie/.venv/Scripts/python.exe -m pip install -r requirements.txt
```

3. Run the app:

```powershell
C:/Users/princ/Desktop/movie/.venv/Scripts/python.exe -m streamlit run app.py
```

Notes:
- The TMDB API key in `app.py` is a placeholder — replace it with your own key for poster fetching.
- If you plan to push to GitHub, ensure you don't commit large environment files like `.venv`.
