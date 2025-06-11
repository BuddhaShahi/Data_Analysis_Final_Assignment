# 🇳🇵 Nepal Earthquake Data Analysis (2015–2025)

This project presents a complete data analysis and visualization of earthquake events in Nepal from 2015 to 2025. The original dataset was obtained from [Kaggle](https://www.kaggle.com/code/sangampaudel530/nepal-earthquake-2015-2025/notebook), cleaned, and analyzed to extract meaningful insights about seismic activity in Nepal, especially focusing on the major Gorkha Earthquake of 2015.

---

##  Dataset

- **Source**: Kaggle - [Nepal Earthquake 2015–2025](https://www.kaggle.com/code/sangampaudel530/nepal-earthquake-2015-2025/notebook)
- **File Used**: `cleaned_nepal_earthquake.csv`
- **Cleaning Steps**:
  - Removed empty rows and shells
  - Merged `Date` and `Time` into a new `Datetime` column
  - Set `Datetime` as the index for time-based analysis

---

##  Analysis Performed

### Exploratory Data Analysis (EDA)
- Calculated mean, min, and max earthquake magnitudes
- Analyzed year-wise and month-wise trends
- Created histograms for magnitude distribution
- Generated heatmaps and correlation matrices

### Spatial Insights
- Mapped locations using latitude and longitude
- Visualized earthquake hotspots (Bagmati Province being most frequent)
- Scatter plots to analyze location vs magnitude/depth

###  Temporal Insights
- Identified 2015 as the year with the most activity (Gorkha Earthquake)
- Detected seasonal/monthly spikes (April–May 2015, Jan 2025)

---

## Key Findings

- **Average Magnitude**: ~4.47
- **Strongest Quake**: Magnitude 7.8 in 2015
- **Most Active Year**: 2015, with over 120 quakes
- **Hotspot**: Central Nepal (Bagmati Province)
- **Pattern**: Most quakes between 4.0–5.0, few extreme events

---

## Suggestions & Preparedness Plan

To reduce risks in high-impact zones like Bagmati Province:

-  **Early Warning Systems**
-  **Stricter Building Codes**
-  **Public Awareness Campaigns**
-  **Emergency Disaster Teams & Drills**
-  **Resilient Infrastructure**
-  **Continuous Monitoring & Research**

---

##  Conclusion

This project shows how data can guide disaster management and preparedness. By learning from the past and acting now, Nepal can become more resilient to future seismic events.

---

##  Tools Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Markdown** for reporting

---

##  Output Files

- `cleaned_nepal_earthquake.csv` – Cleaned dataset
- `correlation_matrix_heatmap.png` – Heatmap image
- Final graphs (scatter, histogram, boxplot, etc.)

---

##  Author’s Note

This project was created with the goal of understanding Nepal’s seismic patterns and preparing useful insights for future disaster response. The lessons of the 2015 Gorkha Earthquake remind us to always be ready, together we can build a safer future.
