# Amazon Music Clustering
## Project Overview

This project applies K-Means clustering to Amazon Music audio features to group songs into meaningful categories based on their musical characteristics. The goal is to uncover hidden patterns in music data and interpret clusters as distinct music styles (e.g., party tracks, chill acoustic, speech-heavy tracks).


### Dataset

The dataset contains audio features commonly used in music analysis:

- Danceability

- Energy

- Loudness

- Speechiness

- Acousticness

- Instrumentalness

- Liveness

- Valence

- Tempo

- Duration (ms)

Each song is represented by numerical values for these features.


## Methodology

### 1.Data Preprocessing

Selected relevant numeric audio features

Removed non-informative or categorical columns

Standardized features to ensure equal contribution

### 2.Clustering

Applied K-Means clustering

Optimal number of clusters chosen as K = 3

Each song was assigned a cluster label (0, 1, or 2)

### 3.Cluster Profiling

Computed mean values of each feature per cluster

Interpreted clusters based on dominant characteristics

### 4.Visualization

Bar charts for average feature values per cluster

Heatmaps for overall cluster comparison

Scatter plots and PCA-based plots for visual separation


Tools & Libraries Used

- Python

- Pandas

- NumPy

- Scikit-learn

- Matplotlib / Seaborn

## Conclusion

This project demonstrates how unsupervised learning can be used to analyze and categorize music based on audio features. The resulting clusters provide valuable insights for playlist generation, music recommendation systems, and exploratory music analysis.
