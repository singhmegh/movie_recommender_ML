# Movie Recommender System (ML + Streamlit)

A Movie Recommender System built using Machine Learning and deployed with Streamlit.
It suggests movies based on similarity scores computed from movie metadata.

# 🚀 Features
  1) Content-based recommendation system
  2) Suggests top movies similar to a selected movie
  3) Built with Python, Scikit-learn, Pandas, NumPy
  4) Interactive web app powered by Streamlit

# Model file (similarity.pkl) is hosted externally (Google Drive) to keep repo lightweight.

# Installation & Setup

# Create Virtual Environment
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate       # window

# Install Requirements
pip install -r requirements.txt

# Run the Streamlit App
streamlit run app.py

# Model File (Similarity Matrix)
The file similarity.pkl (173 MB) is not stored in this repository due to GitHub’s 100 MB file size limit.

# Future Improvements
  1) Use collaborative filtering or hybrid models
  2) Add movie posters & trailers from TMDB API
  3) Deploy publicly via Streamlit Cloud / Hugging Face Spaces
