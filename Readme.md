# 🎬 Netflix Dataset Analysis (EDA Project)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Titles dataset to uncover insights about Netflix’s **content strategy, growth trends, genre distribution, ratings, and geographic presence**.

The analysis demonstrates practical skills in:

* Data cleaning
* Feature engineering
* Visualization
* Insight generation

using **Python data analysis libraries**.

---

## 📂 Dataset

* **Source:** Netflix Titles Dataset (Kaggle)
* **Records:** Movies & TV Shows available on Netflix
* **Key Columns:**

  * `type` (Movie / TV Show)
  * `title`
  * `director`
  * `cast`
  * `country`
  * `date_added`
  * `release_year`
  * `rating`
  * `duration`
  * `listed_in` (genres)

---

## 🛠️ Technologies & Libraries Used

```python
pandas
numpy
matplotlib
seaborn
```

---

## 🔧 Data Preprocessing Steps

1. Loaded dataset using pandas
2. Checked data types, shape, and missing values
3. Handled missing values in:

   * Director
   * Cast
   * Country
4. Converted `date_added` to datetime format
5. Created new features:

   * `year_added`
   * `month_added`
   * `duration_min` (for Movies)
   * `seasons` (for TV Shows)
6. Split multi-valued columns (genres, cast) using `explode`
7. Removed duplicates
8. Applied regex for numeric extraction

---

## 📊 Exploratory Data Analysis (Questions Answered)

### 🔹 Content-Based Analysis

* Movies vs TV Shows count
* Content rating distribution
* Most common genres
* Genre popularity by content type
* Average movie duration
* TV show season distribution

### 🔹 Time-Based Analysis

* Year-wise content growth
* Year with maximum content additions
* Monthly content addition trends
* Delay between release year and Netflix addition

### 🔹 Country-Based Analysis

* Top content-producing countries
* Country-wise Movies vs TV Shows
* US dominance analysis
* Country vs genre relationship

### 🔹 Cast & Director Analysis

* Top directors by content count
* Most frequent actors
* Movies with large ensemble casts

### 🔹 Advanced Insights

* Adult content trend over time
* Movie duration trend across years
* TV show season trend over time
* Genre trend analysis

---

## 📈 Key Insights

* Netflix has **more Movies than TV Shows**
* Majority of content targets **mature audiences (TV-MA, TV-14)**
* **Drama and International content** dominate Netflix
* Content growth accelerated significantly after **2015**
* **United States** is the largest content contributor
* Netflix prefers **short TV series (1–2 seasons)**
* Adult-oriented content has increased over time

---

## 📁 Project Structure

```
Netflix_Data_Analysis/
│
├── netflix_titles.csv
├── netflix_analysis.ipynb
├── README.md
```

---

## 🎯 Skills Demonstrated

* Data Cleaning & Wrangling
* Feature Engineering
* Exploratory Data Analysis
* Data Visualization
* Analytical Thinking
* Python Programming

---

## 🚀 Future Enhancements

* Build **Power BI / Tableau dashboards**
* Apply **sentiment analysis** on descriptions
* Create **recommendation system**
* Perform **time-series forecasting**

