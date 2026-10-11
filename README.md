# Spotify 2023 Analysis & Chart Success Prediction

This repository explores the most streamed Spotify songs of 2023, performing data cleaning, exploratory data analysis (EDA), and building predictive classification models to determine whether a track enters Spotify charts.

---

## Project Structure

- `notebooks/spotify_analysis.ipynb` – Main Jupyter Notebook containing EDA, data preprocessing, and ML modeling  
- `data/raw/spotify-2023.csv` – Raw dataset of top streamed Spotify songs  

---

## Data Cleaning & Preprocessing

- Handling missing values across columns (e.g., `in_shazam_charts`, `key`, `streams`)  
- Mapping musical notes (`key`) to numerical pitch classes  
- Cleaning string/numeric columns and handling streams data  
- Creating a binary target variable (`in_spotify_charts_target`: 1 if in charts, 0 otherwise)  

---

## Exploratory Data Analysis (EDA)

- Distribution analysis by artist count, release year, and release month (seasonality trends)  
- Feature distributions and outlier analysis  
- Pearson & Spearman correlation matrices  
- Cross-platform comparison (Spotify, Apple Music, Deezer, and Shazam charts/playlists)  

---

## Classification Models

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Hyperparameter tuning using `GridSearchCV` and model evaluation  
- **Key Result:** Random Forest achieved the best performance with an accuracy of ~81%.

---

## Tools & Technologies

- Python 3.x  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Scikit-Learn  
- Jupyter Notebook
