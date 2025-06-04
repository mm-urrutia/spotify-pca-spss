# Principal Component Analysis on Spotify Dataset (SPSS Project)

This project applies **Principal Component Analysis (PCA)** to a large dataset of Spotify tracks (1921–2020) using **SPSS**. The goal is to reduce dimensionality while preserving interpretability for future statistical analyses.

## Project Summary

- **Tool Used**: IBM SPSS Statistics
- **Dataset**: Spotify Tracks 1921–2020 (170,654 songs)
- **Technique**: Principal Component Analysis (PCA)
- **Objective**: Reduce multicollinear numerical variables into uncorrelated principal components
- **Result**: 4 principal components explain 66.17% of the variance

## Contents

- `report`: Contains the final report (PDF) and analysis images exported from SPSS
- `data`: Sample dataset used (CSV)
- `README.md`: Project overview and context

## Key Findings

| Component | Interpretation         | Key Variables                                     |
|-----------|------------------------|---------------------------------------------------|
| PC1       | Modernity              | Year, Popularity, Energy, Loudness                |
| PC2       | Danceability           | Danceability, Valence, Duration_ms (negative)     |
| PC3       | Rhythm                 | Tempo, Energy                                     |
| PC4       | Live Music             | Liveness, Speechiness                             |

## Interpretation

Each component was translated into a practical use case:
- **Modernity**: High energy, popular recent tracks
- **Danceability**: Happy, short-duration songs ideal for parties
- **Rhythm**: High-tempo tracks useful for training or workouts
- **Live Music**: Songs recorded live or with spoken interaction

## Dataset Source

- Original Dataset: [Spotify Dataset 1921–2020 on Kaggle] (https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks)
- Extracted using Spotify Web API

## Next Steps

- Extend the analysis using Python or R for reproducibility
- Combine PCA results with clustering or recommendation systems

## Note

This project was originally developed as part of a university course in statistics.
