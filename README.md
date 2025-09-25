# 🎬 Netflix EDA Project

## 📌 Project Overview
This project explores the **Netflix Movies and TV Shows dataset** to uncover insights about content distribution, genres, ratings, and growth trends over time.  
The dataset is cleaned, processed, and visualized to tell a story about how Netflix has evolved.  

---

## 📊 Dataset Information
- **Source**: [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
- **Rows**: ~8,800 titles  
- **Columns**:  
  - `type`: Movie or TV Show  
  - `title`: Title of the content  
  - `director`, `cast`, `country`: Metadata about production  
  - `date_added`: Date added to Netflix  
  - `release_year`: Original release year  
  - `rating`: Content rating (e.g., TV-MA, R, PG)  
  - `duration`: Length (minutes or seasons)  
  - `listed_in`: Genre(s)  
  - `description`: Short description  

---

## 🔎 Data Cleaning
- Converted `date_added` to datetime and extracted `year_added` & `month_added`.  
- Filled missing values in `director`, `cast`, and `country` with `"Unknown"`.  
- Dropped rows with missing values in `rating`, `date_added`, and `duration`.  
- Split `listed_in` into individual genres for analysis.  
- Cleaned `duration`:  
  - Movies → duration in minutes  
  - TV Shows → number of seasons  

---

## 📈 Exploratory Data Analysis
The following analyses and visualizations were performed:  

1. **Movies vs TV Shows count**  
2. **Content release trend by year**  
3. **Growth rate of Netflix content**  
4. **Content added by month**  
5. **Ratings distribution (Movies vs TV Shows)**  
6. **Heatmap: Titles added by Year × Month**  
7. **Top 10 genres**  
8. **Top 10 content-producing countries**  
9. **Movie duration distribution**  
10. **TV Show seasons distribution**  
11. **Top 10 directors**  

---

## 💡 Key Insights
- Netflix content **boomed after 2015**, peaking around 2019–2020.  
- **Movies dominate** Netflix’s catalog compared to TV Shows.  
- **TV-MA** is the most common rating, reflecting a focus on adult content.  
- **USA and India** are the top content producers.  
- **Drama, Documentaries, and Comedies** are the most popular genres.  
- Most movies are **90–120 minutes long**, while most TV Shows have **1–2 seasons**.  
- Netflix collaborates with a **wide variety of directors** rather than depending on a few.  

---

## 🛠 Tools Used
- Python 🐍  
- Pandas 📊  
- Matplotlib 🎨  
- Seaborn 📈  

---

## ✅ Conclusion
This analysis shows how Netflix has **grown globally**, diversified its genres, and targeted audiences with specific ratings and durations.  



