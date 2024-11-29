# DSA210-30852

# Exploring Genre Preferences Through Spotify and Decibel Data Analysis Using Apple Health

---

## Overview

This project combines personal Spotify listening data with environmental sound levels (decibels) tracked by the Apple Health app. The goal is to analyze how sound intensity influences music preferences. By comparing genres with their respective listening dB levels, we aim to uncover patterns—such as whether certain genres are associated with high, medium, or low sound environments. This analysis will provide insights into listening habits and how they align with different acoustic contexts.

---

## Motivation

Music is deeply personal, and listening habits often vary based on mood, activity, or environment. This project seeks to uncover correlations between decibel levels and genre preferences, offering a unique perspective on how sound intensity aligns with musical taste. Insights from this analysis can be useful for understanding personal listening patterns and improving future audio experiences.

---

## Data Sources

### 1. **Spotify Data**

- Extracting my streaming data from Spotify.
- Relevant fields include:
  - Song Title
  - Artist
  - Genre
  - Duration
  - Listening Timestamp

### 2. **Decibel (dB) Data**

- Using the **Apple Health app** to gather environmental dB levels.
  - The exported data should include:
    - **Timestamps**: To align with Spotify playback data.
    - **Decibel Levels (dB)**: Measured environmental sound intensity.
- Synchronize Spotify timestamps with Apple Health dB recordings to compare genres with corresponding dB levels.

---

## Objective

Analyze how listening habits vary based on sound intensity. Key objectives include:

1. Identifying genres associated with high, medium, and low decibel levels.
2. Exploring correlations between sound intensity and genre preferences across different contexts, such as time of day or activity.

---

## Methodology

1. **Data Collection**:
   - Gather Spotify streaming data and Apple Health dB data.
   - Ensure both datasets have a common timestamp for integration.
   
2. **Data Cleaning**:
   - Merge Spotify and Apple Health data based on timestamps.
   - Categorize genres for each song using Spotify API or genre mapping.
   - Normalize decibel levels into three categories:
     - **Low** (<50 dB)
     - **Medium** (50–70 dB)
     - **High** (>70 dB)
   
3. **Exploratory Data Analysis (EDA)**:
   - Analyze trends like:
     - Which genres dominate each dB category?
     - Time-of-day patterns for genre-dB combinations.
   - Use bar charts, scatter plots, and heatmaps for visualization.
   
4. **Visualization**:
   - Compare genres with respect to dB levels.
   - Create plots showing the proportion of listening habits across dB ranges.

5. **Insights**:
   - Highlight patterns, such as whether rock is consistently listened to at high dB levels or classical music at lower dB levels.

---

## Technologies/Tools

- **Data Collection**:
  - Spotify API
  - Apple Health app (Noise feature)
- **Data Analysis**:
  - Python (pandas, numpy)
  - Jupyter Notebooks
- **Visualization**:
  - matplotlib
  - seaborn
  - plotly
- **Version Control**:
  - GitHub repository
