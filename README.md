# DSA210-30852

# Exploring Listening Patterns Through Spotify and Decibel Data Analysis Using Apple Health

---

## Overview

This project combines personal Spotify listening data with environmental sound levels (decibels) tracked by the Apple Health app. The objective is to analyze how sound intensity correlates with listening habits, focusing on the relationship between decibel levels and listening frequency for specific artists. This analysis provides insights into personal listening behavior and the acoustic contexts in which music is enjoyed.

---

## Motivation

Music listening habits are influenced by a variety of factors, including the surrounding environment. This project aims to uncover how environmental sound intensity (measured in decibels) aligns with personal music preferences. Insights from this analysis can provide a deeper understanding of listening patterns and their connection to external auditory contexts.

---

## Data Sources

### 1. **Spotify Data**

- Extracted streaming data from Spotify.
- Relevant fields used:
  - Artist
  - Duration (ms played)
  - Listening Timestamp

### 2. **Decibel (dB) Data**

- Exported data from the **Apple Health app**, specifically focusing on:
  - **Timestamps**: To synchronize with Spotify playback data.
  - **Decibel Levels (dB)**: Measured environmental sound intensity during listening activity.

---

## Objective

The project seeks to explore the relationship between listening frequency (how often specific artists are listened to) and decibel levels. Key objectives include:

1. Identifying the correlation between decibel levels and listening frequency.
2. Highlighting the loudest and quietest artists based on average decibel levels.
3. Evaluating dependency between decibel levels and listening habits using hypothesis testing.

---

## Methodology

1. **Data Collection**:
   - Gathered Spotify streaming data and Apple Health dB data.
   - Synchronized timestamps to align listening activity with dB levels.

2. **Data Cleaning and Integration**:
   - Merged Spotify and Apple Health datasets on timestamps.
   - Focused on artist-level aggregation:
     - Average decibel levels per artist.
     - Listening frequency (number of plays per artist).

3. **Exploratory Data Analysis (EDA)**:
   - Identified the loudest and quietest artists based on average decibels.
   - Analyzed the relationship between decibel levels and listening frequency.
   - Visualized patterns using scatter plots, bar charts, and regression lines.

4. **Hypothesis Testing**:
   - **Spearman Correlation**:
     - Used to evaluate the monotonic relationship between decibel levels and listening frequency.
   - **Chi-Square Test of Independence**:
     - Binned decibel levels into 1-unit increments and assessed dependency with frequency ranges.
   - **Result**: Both tests yielded consistent results, confirming no significant dependency between listening frequency and decibel levels.

---

## Insights

1. **Top Artists by Decibel Levels**:
   - Identified the top 10 loudest and quietest artists based on average decibels.

2. **Hypothesis Testing Outcome**:
   - Spearman correlation suggested no strong monotonic relationship.
   - Chi-Square test indicated no significant dependency between decibel ranges and listening frequency ranges.

3. **Visualizations**:
   - Scatter plots and regression lines showed trends between decibel levels and listening frequency.
   - Bar charts highlighted the loudest and quietest artists.

---

## Technologies/Tools

- **Data Collection**:
  - Spotify Data Export
  - Apple Health app
- **Data Analysis**:
  - Python (pandas, numpy, scipy)
  - Jupyter Notebooks
- **Visualization**:
  - matplotlib
  - seaborn
- **Hypothesis Testing**:
  - Spearman Correlation
  - Chi-Square Test
# DSA210-30852

# Exploring Listening Patterns Through Spotify and Decibel Data Analysis Using Apple Health

---

## Overview

This project combines personal Spotify listening data with environmental sound levels (decibels) tracked by the Apple Health app. The objective is to analyze how sound intensity correlates with listening habits, focusing on the relationship between decibel levels and listening frequency for specific artists. This analysis provides insights into personal listening behavior and the acoustic contexts in which music is enjoyed.

---

## Motivation

Music listening habits are influenced by a variety of factors, including the surrounding environment. This project aims to uncover how environmental sound intensity (measured in decibels) aligns with personal music preferences. Insights from this analysis can provide a deeper understanding of listening patterns and their connection to external auditory contexts.

---

## Data Sources

### 1. **Spotify Data**

- Extracted streaming data from Spotify.
- Relevant fields used:
  - Artist
  - Duration (ms played)
  - Listening Timestamp

### 2. **Decibel (dB) Data**

- Exported data from the **Apple Health app**, specifically focusing on:
  - **Timestamps**: To synchronize with Spotify playback data.
  - **Decibel Levels (dB)**: Measured environmental sound intensity during listening activity.

---

## Objective

The project seeks to explore the relationship between listening frequency (how often specific artists are listened to) and decibel levels. Key objectives include:

1. Identifying the correlation between decibel levels and listening frequency.
2. Highlighting the loudest and quietest artists based on average decibel levels.
3. Evaluating dependency between decibel levels and listening habits using hypothesis testing.

---

## Methodology

1. **Data Collection**:
   - Gathered Spotify streaming data and Apple Health dB data.
   - Synchronized timestamps to align listening activity with dB levels.

2. **Data Cleaning and Integration**:
   - Merged Spotify and Apple Health datasets on timestamps.
   - Focused on artist-level aggregation:
     - Average decibel levels per artist.
     - Listening frequency (number of plays per artist).

3. **Exploratory Data Analysis (EDA)**:
   - Identified the loudest and quietest artists based on average decibels.
   - Analyzed the relationship between decibel levels and listening frequency.
   - Visualized patterns using scatter plots, bar charts, and regression lines.

4. **Hypothesis Testing**:
   - **Spearman Correlation**:
     - Used to evaluate the monotonic relationship between decibel levels and listening frequency.
   - **Chi-Square Test of Independence**:
     - Binned decibel levels into 1-unit increments and assessed dependency with frequency ranges.
   - **Result**: Both tests yielded consistent results, confirming no significant dependency between listening frequency and decibel levels.

---

## Insights

1. **Top Artists by Decibel Levels**:
   - Identified the top 10 loudest and quietest artists based on average decibels.

2. **Hypothesis Testing Outcome**:
   - Spearman correlation suggested no strong monotonic relationship.
   - Chi-Square test indicated no significant dependency between decibel ranges and listening frequency ranges.

3. **Visualizations**:
   - Scatter plots and regression lines showed trends between decibel levels and listening frequency.
   - Bar charts highlighted the loudest and quietest artists.

---

## Technologies/Tools

- **Data Collection**:
  - Spotify Data Export
  - Apple Health app
- **Data Analysis**:
  - Python (pandas, numpy, scipy)
  - Jupyter Notebooks
- **Visualization**:
  - matplotlib
  - seaborn
- **Hypothesis Testing**:
  - Spearman Correlation
  - Chi-Square Test
