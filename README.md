# Movie Recommendation System

This project is a content-based movie recommendation system built with Python and Streamlit. It uses the TMDB 5000 Movies and Credits datasets to recommend movies similar to a selected title based on their content (overview, genres, keywords, cast, and crew).

## Setup Instructions
1. **Clone the repository and navigate to the project directory:**
   ```bash
   git clone <repo-url>
   cd movie_recommendation-system
   ```
2. **Install dependencies:**
   ```bash
   pip install streamlit pandas numpy scikit-learn
   ```
3. **Prepare the data:**
   - Run the Jupyter notebook `movie_recommender_system.ipynb` to process the data and generate `movies.pkl` and `similarity.pkl`.
   - Ensure `movies.pkl` and `similarity.pkl` are in the same directory as `app.py`.
4. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## Data Sources
- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
