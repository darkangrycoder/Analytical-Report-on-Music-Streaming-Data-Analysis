# Spotify Data Analysis and Machine Learning

## Overview
This project analyzes Spotify's most streamed songs in 2024, leveraging data from platforms like YouTube, TikTok, and Apple Music. The analysis includes visualizations and machine learning models to understand patterns and predict track popularity.

### Dataset Features:
- **Track Details**: Name, Album, Artist, Release Date
- **Metrics**: Spotify Streams, YouTube Views, TikTok Engagement
- **Reach**: Playlist reach on Spotify, YouTube, and Apple Music
- **Explicit Content**: Explicit vs. non-explicit tracks

---

## Data Visualizations
### Explicit vs. Non-Explicit Tracks
A bar chart highlights the predominance of non-explicit tracks over explicit ones.

### Spotify Popularity vs. YouTube Views
Scatter plot analysis reveals:
- High Spotify popularity does not always correlate with high YouTube views.
- Explicit and non-explicit tracks show varying performance trends.

### Top Artists by Track Count
The top 10 artists include Drake, Taylor Swift, and Bad Bunny, with Drake leading in track numbers.

---

## Machine Learning Models

We used various machine learning algorithms to predict track popularity. Below are the performance metrics for each model:

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | 0.6957   | 0.6970    | 0.3333 | 0.4510   |
| SGD Classifier         | 0.6272   | 0.5029    | 0.4986 | 0.5007   |
| Support Vector Machine | 0.7185   | 0.7590    | 0.3652 | 0.4932   |
| KNN (k=3)              | 0.7022   | 0.6134    | 0.5565 | 0.5836   |
| KNN (k=5)              | 0.7196   | 0.6445    | 0.5623 | 0.6006   |
| Gaussian Naive Bayes   | 0.4891   | 0.4116    | 0.8435 | 0.5532   |
| Decision Tree          | 0.6576   | 0.5431    | 0.5478 | 0.5455   |
| Random Forest          | 0.7739   | 0.7915    | 0.5391 | 0.6414   |
| Gradient Boosting      | 0.7630   | 0.7550    | 0.5449 | 0.6330   |
| LightGBM               | **0.7870** | **0.7729** | **0.6116** | **0.6828** |
| XGBoost                | 0.7609   | 0.7208    | 0.5913 | 0.6497   |
| AdaBoost               | 0.7304   | 0.7100    | 0.4754 | 0.5694   |
| Bagging                | 0.7380   | 0.7114    | 0.5072 | 0.5922   |
| Voting Classifier      | 0.7674   | 0.7937    | 0.5130 | 0.6232   |
| Stacking Classifier    | 0.7859   | 0.7891    | 0.5855 | 0.6722   |

---

## Key Insights
- **Best Model**: LightGBM achieved the highest accuracy (0.7870) and F1 Score (0.6828).
- **Notable Performers**: Random Forest and Gradient Boosting also demonstrated strong predictive capabilities.
- **Explicit Content Analysis**: Explicit content impacts popularity and engagement differently across platforms.

---

