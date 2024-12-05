# Spotify Top Hits Analysis (1990-2020)

This repository contains the code, documentation, and resources for the **Spotify Top Hits Analysis Project**, which explores trends, insights, and recommendations based on the most popular songs from 1990 to 2020. Using **Power BI** and **Tableau**, the project visualizes data to uncover key patterns in music popularity and provides actionable recommendations for stakeholders in the music industry.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Architecture](#architecture)  
3. [Dataset](#dataset)  
4. [Components and Workflow](#components-and-workflow)  
5. [Repository Structure](#repository-structure)  
6. [Acknowledgments](#acknowledgments)  

---

## Project Overview
The project focuses on analyzing Spotify’s top hits from 1990 to 2020.  
**Key Features:**
- **Data Analysis:** Investigate song features such as danceability, energy, tempo, duration,etc.
- **Visualizations:** Create dashboards to identify trends in genre, artist dominance, and regional streaming growth.
- **Recommendations:** Provide actionable insights for aspiring artists and music producers.

**Use Case:** Understand the factors driving song popularity and emerging music trends over several decades.

---

## Architecture
The project follows a structured workflow for streamlined analysis.  
**High-Level Process Flow:**
1. **Team Discussion:** Collaborated to identify interests and finalize the Spotify Top Hits topic.  
2. **Data Preprocessing:** Cleaned and prepared the dataset for analysis.  
3. **Visualization:** Built interactive dashboards in Power BI and Tableau to derive insights.  
4. **Recommendations:** Synthesized findings into actionable insights for stakeholders.  

![image](https://github.com/user-attachments/assets/e098c84e-8e31-4f94-8b85-79e0fe17b8ab)

---

## Dataset
- **Source:** [Kaggle - Spotify Top Hits Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019))
- **Details:**  
  - Metadata: Track title, artist name, release year.  
  - Audio Features: Danceability, energy, loudness, tempo, duration, etc.  
  - Popularity Metrics: Spotify popularity score.  
- **Size:** Contains 2M+ records of top hits over several decades.  

---

## Components, Workflow, Insights

### Data Preprocessing and Visualization  
- **Data Preparation:**  
  - Handled missing or null values to ensure dataset integrity.  
  - Consolidated artist names for consistency and clarity.  
  - Converted song durations from milliseconds to minutes for better interpretability.  
  - Grouped years into decades to analyze temporal trends effectively.  

- **Dashboards:**  
  - **Power BI:**  
    - Visualized trends in audio features, artist dominance, and popularity metrics.  
    - Enabled interactive filtering by artist, genre, and year for detailed exploration.
   
  <img width="835" alt="image" src="https://github.com/user-attachments/assets/ed6cae6e-28cc-4b6a-a247-ba84d10534b2">

  
  - **Tableau:**  
    - Focused on regional streaming trends through geospatial analysis.  
    - Highlighted genre evolution and regional preferences using dynamic visuals.
   
    
<img width="1416" alt="image" src="https://github.com/user-attachments/assets/4714796c-524f-46a3-ae25-cd45e758c09e">


### Insights and Recommendations  
- **Insights:**  
  - High-energy, danceable songs with 3-4 minute durations dominate the charts.  
  - Pop and hip hop are consistently the most popular genres over the analyzed period.  
  - While the US leads in streaming activity, Asian markets are rapidly growing in significance.  

- **Recommendations:**  
  - Create songs with high energy and danceability to align with listener preferences.  
  - Blend pop and hip hop genres to appeal to a broader audience.  
  - Focus marketing strategies on regions with increasing streaming activity, such as Asia.  
---

## Repository Structure
```plaintext
spotify_top_hits/
├── data/
│   ├── spotify_dataset.csv       
│   ├── Merged_dataset.csv           
├── dashboards/
│   ├── spotify_dashboard_PowerBI.pbix    
│   ├── spotify_dashboard_Tableau.twb      
├── insights/
│   ├── DATA@#)-Team8-ProjectPresentation.pdf
├── README.md                      
           
```

---

## Acknowledgments
- **San Jose State University (SJSU):** For supporting this academic project.
- **Professor Venkata Duvvuri:** For guidance and support throughout the class and lab.
- **Spotify and Kaggle:** For providing access to the data.  
- **Team Members:** Sreenidhi Hayagreevan, Saumya Varshney, Victor Dumaslan, Bence Danko.  
