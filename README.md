# Netflix Data Analysis

## Project Overview
This project explores a Netflix dataset to uncover insights about content distribution, movie duration patterns, genre popularity, country-level production, and content growth over time.

The project is divided into two major stages:
1. **Data Cleaning** – preparing the raw dataset for analysis
2. **Exploratory Data Analysis (EDA)** – generating insights and visualizations from the cleaned dataset

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Objectives
The main goals of this project were to:

- clean and prepare the Netflix dataset for analysis
- examine the balance between Movies and TV Shows
- analyze trends in content added over time
- identify the most common genres on Netflix
- compare movie duration patterns across years and countries
- investigate how major countries have grown on Netflix over time

---

## Dataset
- Source: The data was gotten from Kaggle
- Records: approximately 8,800 titles
- Key columns used:
  - `type`
  - `title`
  - `country`
  - `date_added`
  - `release_year`
  - `rating`
  - `duration`
  - `listed_in`

---

## Data Cleaning Summary
The raw dataset required several preprocessing steps before analysis:

- handled missing values in columns such as `director`, `cast`, `country`, `rating`, and `duration`
- converted `date_added` to datetime format
- created `month_added` and `year_added` features
- standardized the `duration` column into numeric format
- created `main_country` from the `country` column for cleaner country-level analysis
- removed invalid values in the `rating` column caused by misplaced duration entries

The cleaned dataset was then saved for downstream analysis.

---

## Key Insights

### 1. Movies dominate Netflix content
Netflix contains significantly more Movies than TV Shows, suggesting a stronger emphasis on film distribution.

### 2. Netflix expanded rapidly after 2016
The number of titles added to Netflix increased sharply between 2016 and 2019, reflecting a major growth phase.

### 3. International Movies and Dramas are the most common genres
Genre analysis showed that Netflix has a strong global content strategy, with International Movies, Dramas, and Comedies appearing most frequently.

### 4. The most common movie duration is 90 minutes
This suggests that Netflix movies often follow a standard feature-length format.

### 5. Modern movies are shorter than older ones
Movies released after 2000 are about 10 minutes shorter on average than those released before 2000, indicating a shift toward more concise content.

### 6. India produces longer movies
Among major content-producing countries, India had the highest median movie duration, reflecting longer storytelling formats.

### 7. The United States leads content production
The United States produces the largest volume of Netflix content, with India as the second-largest contributor.

### 8. Netflix has become more globally diversified
Growth analysis showed that while the U.S. remains dominant, countries like India, the UK, Canada, and Japan have shown steady growth over time.

---
## Visualizations

### Movies vs TV Shows
![Movie Vs Tvshow](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Movie%20Vs%20Tvshow.png)

### Content Added Over Time
![Number of Titles added](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Number%20of%20Titles%20added.png)

## Genre Distribution
![Top 10 common genre](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Top%2010%20common%20genre.png)

### Movie Duration Trend
![Duration Trend](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Duration%20trend.png)

### Top Content-Producing Countries
![Top 10 countries](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Top%2010%20countries1.png)

### Growth of Top Countries on Netflix
![Growth of Top Countries](https://github.com/OchePrince/Netflix-Data-Analysis/blob/main/Growth%20of%20Top%20Countries.png)



---



---

