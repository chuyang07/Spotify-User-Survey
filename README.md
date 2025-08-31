# Spotify-User-Survey
Interactive Tableau dashboard and info graphic for music creator and researcher, showing the characteristics of Spotify music and user preferences.

# Spotify Music Analysis: Popularity Trends & Song Characteristics  
**Johns Hopkins University Academic Project**  

## Table of Contents  
- [Project Overview](#project-overview)  
- [Background & Problem Statement](#background--problem-statement)  
- [Methodology](#methodology)  
- [Key Takeaways & Impact](#key-takeaways--impact)  
- [Deliverables](#deliverables)
- [File Structure](#file-structure) 
- [Acknowledgments](#acknowledgments)  

----------------------------------------------------------------------------------------

## Project Overview  
- **Issue**
- 1. Music creators and fans may lack clarity on what characteristics make songs popular on Spotify
  2. Spotify's R&D team also needs to understand audience preferences to improve the overall Spotify user experience  
- **Goal**
- Analyze Spotify's track data to uncover popularity trends, correlations between music properties, and cultural preferences to provide insights for creators, listeners, and Spotify's R&D or Personalization team

----------------------------------------------------------------------------------------

## Background & Problem Statement    
- **Spotify**  
- Spotify is one of the world's largest music streaming platforms, launched in 2008. Since then, it has transformed global music consumption by making songs widely accessible across devices and regions
- **Music Properties**  
- The analysis contains key attributes that shape how listeners perceive and engage with music, including Duration, Tempo, Energy, Danceability, Loudness, Valence, Acousticness, and Mode, some of them are index without unit  
- These properties allow us to study how technical song features translate into popularity patterns and audience moods
- For more details, see [Final Presentation Slides](./Final%20Presentation%20Slides.pptx)  
- **Challenges**  
- 1. The dataset spans multiple decades and genres, requiring careful filtering and normalization  
  2. Cultural and regional differences in music preferences make generalized conclusions difficult  
- **Problem Statement**  
- Spotify and its stakeholders seek to better understand how song properties influence popularity and how audience preferences differ across regions, which can provide insights for both creators and platform strategy 
  
----------------------------------------------------------------------------------------

## Methodology  
- **Dataset Selection**  
- Extracted Spotify track-level dataset with enough samples and parameters from Kaggle, due to GitHub file size limits, only a sample dataset is uploaded.
- The full dataset is available on [Kaggle 1](https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated), [Kaggle 2](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks)  
- Key parameters includes music properties like duration, loudness, danceability, tempo, energy, valence, acousticness, mode, etc.  
- **Analysis Process**  
- Imported dataset into Tableau for data analysis and visualization  
- 1. Time trend analysis
     Popularity since 1950, Spotify launch impact in 2008, boost in 2010s.  
  2. Correlation analysis
     Loudness–Energy, Tempo–Danceability, Energy–Valence, Energy–Acousticness, etc.  
  3. Regional preferences
     Built Preference Maps with typical regions (Japan, Mexico, South Africa, etc.).  
- **Tools**  
- Tableau (interactive dashboards and info graphic, static visualizations)  
- Excel (data preprocessing)  

----------------------------------------------------------------------------------------

## Key Takeaways & Impact 
- **Findings and Recommendations**
- 1. F: Music popularity has risen steadily since the 1950s, with a major boost after Spotify's launch in 2008 and there's a streaming expansion in the 2010s  
- 2. F: Hit songs typically share characteristics
     R: To create the most enjoyable song, the 210 seconds duration (optimal for engagement), 120 BPM tempo (balanced speed for listening), energy value around 0.66 and danceability value around 0.54 (mid-to-high levels) can be a well-balanced choice  
- 3. F: Higher loudness tends to increase energy and valence, while reducing acousticness, and Tempo follows an inverted-U with Danceability (90–130 BPM optimal)
     R: Using moderate energy to create songs can yields highest Valence (too low sounds sad and too high sounds tense)  
- 4. F: Japan favors loud, high-energy tracks, Mexico shows highest Valence preference， Indonesia prefers calmer music with lowest Valence/Danceability
     R: Spotify can enhance its regional recommendation system, and artists aiming to enter specific markets can adjust their song attributes based on local preferences  
- **Impact**:  
- This analysis helps artists design songs aligned with global and local tastes and provides Spotify data-driven strategies for user experience improvement  
- Enriches academic and audience understanding of how song characteristics shape popularity.  

----------------------------------------------------------------------------------------

## Deliverables  
- This repository includes:  
- [Dashboard Image](./Dashboard.png)  
- [Infographic Image](./Infographic.png)  
- [Data](./data/)  
- [Final Presentation Slides](./Final%20Presentation%20Slides.pptx)  
- [Spotify Analysis Proposal](./Spotify%20Analysis%20Proposal.pdf)
- Note: The full interactive dashboard and info graphic file (.twbx) exceeds GitHub's upload limit. You can view the interactive version via [Tableau Public](https://public.tableau.com/app/profile/chuyang.yu/vizzes)

----------------------------------------------------------------------------------------

## File Structure
- |-Dashboard.png
- |-Infographic.png
- |-data/
-  --preference data.xlsx
-  --universal_top_spotify_songs.xlsx
- |-Final Presentation Slides.pptx
- |-Spotify Analysis Proposal.pdf
- |-README.md

----------------------------------------------------------------------------------------

## Acknowledgments  
- **Data Web** Kaggle
- **JHU Advisor** Shadi Esnaashari  


  
