# Spotify Tracks Dataset Analysis

## Overview
This project analyzes a subset of the Spotify Tracks dataset to uncover insights about track popularity and its relationship with various audio features. The analysis includes descriptive statistics, hypothesis testing, and regression modeling, with a focus on predicting a track's popularity.

## Dataset
- **Source**: [Spotify Tracks Dataset (Kaggle)](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data)
- **Scope**: 7,279 tracks across 10 popular genres
- **Features**:
  - **Numerical**: Popularity, Valence, Loudness, Acousticness
  - **Categorical**: Explicit (Yes/No), Track Genre

## Goals
1. Explore descriptive statistics and visualize feature distributions.
2. Analyze relationships between audio features and track popularity.
3. Develop predictive models for track popularity.

## Methodology
1. **Descriptive Analysis**:
   - Visualizations: Histograms, KDE plots, box plots.
   - Summary statistics to understand feature distributions.
2. **Inferential Analysis**:
   - Non-parametric tests: Kruskal-Wallis, Mann-Whitney, and Chi-Square.
3. **Regression Models**:
   - Multiple Linear Regression
   - Lasso Regression
   - Support Vector Regression (SVR)

## Key Findings
- Tracks with **higher acousticness** and **lower loudness** are generally more popular.
- Popularity varies significantly across genres and explicit content.
- Regression models achieved an R² of up to 0.768.
  
## Contributors
- Vrushali Khatane
- Achintya
- Shravan Doda
