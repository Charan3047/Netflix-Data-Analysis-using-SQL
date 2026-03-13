# 🎬 Netflix Movies & Shows SQL Analysis

## 📌 Project Overview

This project analyzes a dataset of **Netflix movies and TV shows** using SQL to extract meaningful insights such as ratings, genres, actors, directors, runtime, and content trends across decades.

The goal of this project is to practice **SQL querying, data exploration, aggregation, joins, and analytical queries** to understand patterns in streaming content.

---

## 🎯 Project Purpose

* Explore Netflix movie and TV show data.
* Perform **data analysis using SQL queries**.
* Extract insights related to **ratings, genres, actors, directors, and release trends**.
* Strengthen SQL skills such as **GROUP BY, JOIN, aggregation functions, filtering, and sorting**.

---

## 🛠 Tech Stack

The following technologies were used to build this project:

* **SQL (MySQL / PostgreSQL compatible queries)**
* **Relational Database**
* **GitHub** for version control
* **Netflix dataset (titles & credits tables)**

---

## 📂 Dataset Information

The project uses two main tables:

### 1️⃣ `titles`

Contains information about Netflix movies and TV shows.

Important fields include:

* `id`
* `title`
* `type` (Movie or Show)
* `release_year`
* `runtime`
* `genres`
* `imdb_score`
* `tmdb_score`
* `tmdb_popularity`
* `age_certification`
* `production_countries`
* `seasons`

### 2️⃣ `credits`

Contains information about cast and crew.

Important fields include:

* `id`
* `name`
* `role` (actor, actress, director)
* `character`

These tables are used together through **JOIN operations** to perform deeper analysis. 

---

# 📊 SQL Analysis Performed

The project includes multiple analytical SQL queries such as:

### ⭐ Rating Analysis

* Top 10 movies based on IMDB score
* Top 10 shows based on IMDB score
* Bottom 10 movies and shows
* Average IMDB and TMDB scores

### 🎬 Content Insights

* Number of movies and shows released per decade
* Total titles released each year
* Average runtime of movies vs shows

### 🌍 Production Analysis

* Average ratings by production country
* Ratings by age certification category

### 🎭 Cast & Crew Insights

* Top 20 actors appearing in most titles
* Top 20 directors with the most projects
* Actors appearing in multiple titles with the same character
* Actors appearing in highly rated titles

### 🎥 Genre Analysis

* Most common movie genres
* Most common show genres
* Top 3 most common movie genres

### 📈 Advanced Queries

* Movies released after 2010 with directors
* Highly rated movies with high TMDB popularity
* Shows with the most seasons
* Average IMDB score for leading actors/actresses

---

# 📁 Project Structure

```
Netflix-SQL-Analysis
│
├── Netflix_SQL_Analysis.sql
├── dataset/
│   ├── titles.csv
│   └── credits.csv
└── README.md
```

---

# 🚀 Key SQL Concepts Used

This project demonstrates the use of:

* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* `LIMIT`
* `JOIN`
* `COUNT()`
* `AVG()`
* `ROUND()`
* `UNION`
* `HAVING`
* `DISTINCT`
* `CONCAT()`
* `FLOOR()`

---

# 📌 Key Insights

Some insights obtained from this analysis include:

* Identification of **top-rated movies and shows on Netflix**
* Understanding **genre popularity**
* Recognizing **actors and directors with the most appearances**
* Observing **content growth across decades**
* Comparing **average runtime of movies and TV shows**

---

# 💡 Future Improvements

Possible improvements for the project:

* Add **data visualizations using Power BI / Tableau**
* Create **SQL dashboards**
* Perform **advanced analytics with Python**
* Build an **interactive dashboard**

---

# 👨‍💻 Author

**Charan Teja Kolipakula**
