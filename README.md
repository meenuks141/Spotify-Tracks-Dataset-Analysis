# Spotify Tracks Dataset - Exploratory Data Analysis & Visualization

## Dataset Overview
This project performs Exploratory Data Analysis (EDA) and data visualization on the **Spotify Tracks Dataset** sourced from Kaggle. The dataset contains a comprehensive set of audio features (such as danceability, energy, loudness, tempo, and valence) along with metadata like track names, artists, albums, popularity, and track genres.

---

## Visualizations & Key Insights

### 1. Distribution of Track Popularity (Histogram)
* **Insight:** The popularity scores show a wide spread, with a high concentration of tracks clustered at lower popularity tiers (including zero) and a gradual decrease toward higher popularity scores.
  <img width="984" height="537" alt="image" src="https://github.com/user-attachments/assets/244977e4-6d4f-47b2-b148-a611557eee08" />


### 2. Danceability vs. Energy (Scatter Plot)
* **Insight:** There is a positive dispersion showing that tracks with higher energy levels also tend to span a wider range of danceability, though many high-energy tracks are heavily danceable.
  <img width="802" height="442" alt="image" src="https://github.com/user-attachments/assets/8508224b-c356-4b9e-875a-c0ba88ff1eb8" />


### 3. Top 10 Genres vs Popularity (Box Plot)
* **Insight:** Comparing the top 10 most common track genres reveals noticeable differences in median popularity and interquartile ranges across distinct musical categories.
 <img width="701" height="430" alt="image" src="https://github.com/user-attachments/assets/5419450c-a0ee-419d-a57c-56ff0b7496c3" />
 <img width="953" height="455" alt="image" src="https://github.com/user-attachments/assets/84650e18-eb08-45ef-9a4b-eece6dc273fc" />


### 4. Correlation Matrix Heatmap
* **Insight:** The correlation matrix highlights relationships between audio features; for instance, **loudness** and **energy** exhibit a strong positive relationship, while other features show milder linear correlations.
  <img width="808" height="439" alt="image" src="https://github.com/user-attachments/assets/1b922f98-e804-416a-be9b-5cd71b94cd9c" />


### 5. Loudness vs. Energy (Regression Plot)
* **Insight:** The regression line clearly demonstrates that as track loudness increases (moving closer to 0 dB), the overall energy rating of the track consistently scales upward.
 <img width="718" height="385" alt="image" src="https://github.com/user-attachments/assets/01ee4055-25ad-4ff5-95a0-3f6bb1acd14a" />

### 6. Top 10 Artists with Most Tracks (Bar Chart)
* **Insight:** The bar chart showcases the most prolific artists represented within the analyzed subset of the dataset, highlighting the distribution of tracks per artist.
 <img width="791" height="475" alt="image" src="https://github.com/user-attachments/assets/4abb321b-8ffb-4f71-bd93-4d372ff6b2e5" />

---

## Conclusions
* Audio characteristics like **energy** and **loudness** are tightly coupled, heavily influencing the acoustic profile of a song.
* Popularity varies significantly by genre and track features, proving that technical audio metrics alone do not solely dictate a track's success.
* Cleaning and handling missing values and duplicate rows were essential steps to ensure the exploratory analysis and visual storytelling remained accurate and reliable.
