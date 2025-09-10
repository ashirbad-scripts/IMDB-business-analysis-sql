# 🎬 IMDB SQL Data Analysis

This repository contains a structured SQL-based analysis of the IMDB database. It highlights trends in movie production, genres, ratings, and key industry players. The project was developed to support **RSVP Movies** in making strategic decisions for their upcoming cinematic ventures.

---

## 📂 Project Structure

```
├── database.sql          # Database schema & sample data
├── analysis.sql          # SQL queries for insights
├── executive_summary.pdf # Business insights & recommendations
└── README.md             # Project documentation
```

---

## 🚀 Getting Started

1. **Import the database**

   ```bash
   mysql -u username -p database_name < database.sql
   ```

2. **Run the analysis queries**

   ```bash
   mysql -u username -p database_name < analysis.sql
   ```

3. **Review insights**
   Open `executive_summary.pdf` to view the findings and recommendations.

---

## 📈 Key Insights

### 🎥 Movie Trends

* **2017** saw the highest number of releases with **3,052 movies**.
* **March** is the most productive month with **824 releases**.
* **USA and India** together produced over **1,000 movies in 2019**.

### 🎭 Genres

* **Drama** is the most produced genre, followed by **Thriller** and **Comedy**.
* Drama has the **highest average runtime (106.7 minutes)**.

### ⭐ Ratings Insights

* *Love in Kilnerry* & *Kirket* top the list with **10.0 average rating**.
* Median movie rating is **7**, showing balanced viewer sentiment.
* Thriller consistently ranks in the **top 3 genres by quality and count**.

### 🏢 Production Houses

* **Dream Warrior Pictures** and **National Theatre Live** lead in highly-rated hits.
* **Marvel Studios** commands the **highest global votes**.
* **Star Cinema** leads in **multilingual productions** with 7 titles.

### 👥 Actors & Directors

* **Vijay Sethupathi** and **Taapsee Pannu** are standout regional actors.
* **James Mangold** shines among directors with multiple acclaimed titles.
* **Mohanlal & Mamootty** consistently deliver in **high-rated films (≥8 median rating)**.

---

## 🎯 Strategic Recommendations

* Prioritize **Drama** and **Thriller** genres.
* Partner with **top-rated directors and production houses**.
* Leverage actors with **regional and international appeal**.
* Target **March releases** for maximum reach.

---

## 🛠️ Tech Stack

* **Database:** MySQL
* **Analysis:** SQL queries (joins, aggregations, subqueries)
* **Documentation:** Executive summary report

---

## 📜 License

This project is created by Ashirbad Routray
