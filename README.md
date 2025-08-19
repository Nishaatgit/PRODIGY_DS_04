# Twitter Sentiment Analysis 
This project focuses on **Sentiment Analysis of Twitter data** as part of my Data Science Internship at Prodigy Infotech.  
The goal is to analyse sentiment patterns in tweets related to various entities (brands, products, games, etc.) and visualize public opinions.

---

##  Dataset
- **Source**: Kaggle.com
- **Shape**: 74,682 rows × 4 columns  
- **Columns**:
  - `ID` → Unique identifier  
  - `Entity` → The subject/brand/game mentioned  
  - `Sentiment` → Sentiment label (`Positive`, `Negative`, `Neutral`, `Irrelevant`)  
  - `Text` → Actual tweet  

---

##  Exploratory Data Analysis
- Checked missing values (`686` missing tweets were dropped).  
- Distribution of sentiments:  
  - Negative: **22,542**  
  - Positive: **20,832**  
  - Neutral: **18,318**  
  - Irrelevant: **12,996**

---

##  Visualizations
1. **Overall Sentiment Distribution** – Bar chart showing sentiment counts.  
2. **Entity-wise Sentiment Analysis** – Stacked bar plot across top 10 entities like *CallOfDuty, Microsoft, Facebook, LeagueOfLegends,* etc.  
3. **Word Clouds** – Generated for Positive, Negative, and Neutral tweets to highlight common keywords.  

---

##  Key Insights
-Negative tweets were slightly higher than positive ones, showing more critical opinions.  
- Entities like CallOfDuty and Microsoft received a large mix of negative and neutral mentions.  
- Positive tweets often included words like love, good, game, fun.  
- Negative tweets contained words like fix, problem, shit, fuck*, indicating dissatisfaction.  
- Neutral tweets revolved around general mentions like game, twitter, new, update.  
---

##  Tech Stack
- **Python**  
- **Pandas, Matplotlib, Seaborn** (for data cleaning & visualization)  
- **WordCloud** (for keyword visualization)  
- **Jupyter Notebook**  

---

##  Results
This analysis provides an understanding of how people express opinions towards brands and games on Twitter.  
The sentiment distribution and word clouds can help companies monitor brand perception and identify areas of concern.
---

