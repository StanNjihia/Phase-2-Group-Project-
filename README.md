# 🎬 Data-Driven Insights for a Modern Film Studio

## 📌 Project Overview

This project aims to provide **actionable insights** to guide the strategic decisions of a *new movie production studio*. By analyzing publicly available movie datasets from platforms such as **IMDb, TMDb, Rotten Tomatoes, Box Office Mojo, and The Numbers**, we investigate what drives a movie's **commercial and critical success** across theatrical and streaming releases.

With the evolving landscape of content consumption—particularly the rise of streaming services—understanding the determinants of a movie's performance is essential. We conducted exploratory data analysis (EDA), data cleaning, correlation analysis, and visual storytelling to uncover patterns that can shape business and production strategies.

---

## 🎯 Objectives

- Identify key factors influencing a movie’s success: *ratings, box office revenue, genre, cast, budget, release strategy*, and more.
- Recommend optimal *budget allocations, release timing, and genre selections*.
- Support business decisions through clear data storytelling and interactive dashboards.

---

## 🧩 Data Sources

We used datasets from the following:

- 📈 **Box Office Mojo** – `bom.movie_gross.csv`
- 💸 **The Numbers** – `tn.movie_budgets.csv`
- 🍅 **Rotten Tomatoes** – `rt.movie_info.tsv`, `rt.reviews.tsv`
- 🎬 **The Movie DB (TMDb)** – `tmdb.movies.csv`
- 🎞️ **IMDb** – `im.db` (SQLite database)

---

## 🛠 Tools & Technologies

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `sqlite3`
- **Jupyter Notebook** for development and analysis
- **Git & GitHub** for version control
- **Trello** for task tracking
- **Google Docs/Slides** for reporting
- **Tableau** for interactive dashboarding

---

## 📈 Visualizations & Dashboards

Our analysis was complemented by various visuals including:

- Correlation Heatmaps  
- Profitability vs Budget Scatterplots  
- Revenue Distribution by Genre  
- Release Date Trends and Seasonality  
- Genre and Rating Performance Analysis  

👉 **[Interactive Tableau Dashboard](https://public.tableau.com/app/profile/stanley.njihia/viz/Movie_Studio_Project/Dashboard3?publish=yes)**

---

## 🧠 Key Findings

- 🎯 **Budget vs ROI**: Low-budget films can achieve high ROI, though blockbuster films typically bring higher total profits.
- 🎭 **Genre Trends**: Action, Drama, and Comedy are consistently strong performers in both revenue and ratings.
- 📆 **Release Timing**: Summer and December are peak profitability months for theatrical releases.
- 🌍 **Foreign vs Domestic**: Many films perform better in international markets—emphasizing global strategy.
- ⭐ **Ratings & Success**: Critical ratings correlate more strongly with long-term value than with immediate box office performance.

---

## ✅ Business Recommendations

- 🎬 Focus on **mid-to-low budget productions** to optimize risk and ROI.
- 🧠 **Data-driven genre selection**: Invest in Action, Comedy, Drama.
- 📆 Align releases with **high-traffic windows** (e.g., holidays, summer).
- 🌐 Expand focus on **international revenue streams**.
- 🎥 Base **casting and directing decisions** on historic data and audience response.

---

## 🔍 Methodology

Following the **CRISP-DM** framework:

1. **Business Understanding** – Defined studio-specific KPIs and goals.  
2. **Data Understanding** – Collected and explored datasets from diverse sources.  
3. **Data Preparation** – Cleaned, merged, and transformed data.  
4. **EDA** – Identified key relationships and anomalies.  
5. **Modeling** – Performed basic statistical tests and correlation analysis.  
6. **Evaluation** – Interpreted results to derive actionable insights.

---

## 📂 Project Structure

```bash
├── data/                         # Raw and cleaned datasets
├── notebooks/                   # Jupyter Notebooks for analysis
│   ├── rotten_tomatoes_analysis.ipynb
│   ├── tmdb_analysis.ipynb
│   ├── movie_budgets_analysis.ipynb
│   ├── imdb_analysis.ipynb
│   └── final_combined_group_project.ipynb
├── visuals/                     # Saved visualizations
├── presentation/               # Final slide decks
└── README.md                   # Project documentation
```

---

## 👥 Contributors

This project was collaboratively developed by:

- Huldah Chepkoech  
- Stanley Njihia  
- Jeff Kandie  
- Stacy Mogeni  
- Peris Kigo  
- Kitts Kikumu  
- Ernest Gichichi

---

## 📬 Contact

Feel free to connect with us on LinkedIn:

- [Huldah Chepkoech](http://www.linkedin.com/in/huldah-rotich)  
- [Stanley Njihia](https://www.linkedin.com/in/stanley-njihia-3506a4355)  
- [Peris Kigo](https://www.linkedin.com/in/peris-kigo-098170302)  
- [Jeff Kandie](https://www.linkedin.com/in/jeff-kandie)  
- [Kitts Kikumu](https://www.linkedin.com/in/kitts-kikumu)  
- [Stacy Mogeni](https://www.linkedin.com/in/stacy-mogeni-9876ba274)

---
