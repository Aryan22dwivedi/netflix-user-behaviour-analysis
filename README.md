# netflix-user-behaviour-analysis
This is a 2 pages of dashboard for visualize Netflix user behaviour according to the dataset 

# 📺 Netflix User Behavior Analysis

## 🧠 Problem Statement
Streaming services aim to understand **what content users prefer** to improve recommendations, personalize user experience, and drive viewer retention.

## 🎯 Objective
Analyze a Netflix-style viewing dataset to identify:
- Top genres and watch patterns
- User-level engagement through watch hours
- Binge-watching behavior across genres
- Relationship between ratings and genres

---

## 📁 Dataset Overview

A Netflix behavior including real show names.

### 📌 Attributes:
| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| `user_id`           | Unique user identifier                       |
| `show_id`           | Unique show/movie identifier                 |
| `title`             | Show or movie title                          |
| `genre`             | Genre (e.g., Drama, Comedy, Sci-Fi)          |
| `duration_minutes`  | Total duration of the show/movie             |
| `watch_date`        | Date of user watch activity                  |
| `watch_time_minutes`| Time user spent watching on that date        |
| `rating`            | User rating (1–5 scale)                      |
| `is_binge_watch`    | Boolean indicating if it's binge behavior    |
| `watch_time_hours`  | Watch time in hours (derived column)         |

---

## 🔍 Key Analysis Performed
![Power BI Desktop 04_07_2025 20_16_03](https://github.com/user-attachments/assets/8e839222-39ba-49ac-b425-dbb896e9ff61)


1. **Top Genres by Watch Time**  
   → Which genres dominate total watch hours

2. **Watch Hours Per User**  
   → Identify most engaged viewers

3. **Binge-Watching Behavior**  
   → Frequency of binge sessions by genre

4. **Ratings vs Genre**  
   → How genres are rated by users

---

## 📈 Visualizations (Power BI)
![Power BI Desktop 04_07_2025 20_17_36](https://github.com/user-attachments/assets/d354efe5-01fa-4a8d-805c-2ff0f800a7b7)

- **Bar Chart**: Top genres by total watch hours
- **Column Chart**: Watch hours per user
- **Filtered Chart**: Binge-watching frequency by genre (`is_binge_watch = True`)
- **Box/Column Chart**: Average user rating across genres
- **Slicers**: Filter by user ID, genre, or watch date for interactive dashboard

---

## ⚙ Tools & Technologies

- 💻 Power BI
- 📄 CSV Dataset
- 🧠 Data Analysis & Visualization

---

## 💡 Expected Outcome

Actionable insights for content teams:
- Which genres are most engaging
- What users binge-watch
- How different genres are perceived via ratings
- Personalized recommendations based on behavior patterns
- list of Benz watch content by users

---

## 📂 Files Included

- `netflix_titles_dataset.csv` — The dataset used
- `Netflix_dashboard.pbix` — Power BI Dashboard 
- screenshots of the dashboard 

---

## 👨‍💻 Author
Aryan — *Data Analyst | ML Enthusiast*

