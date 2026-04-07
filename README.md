# 🏏 IPL Data Analysis Project (Syntecxhub Internship)

## 📌 Overview

This project is part of my **Data Science Internship at Syntecxhub**.
The goal was to perform **data analysis on IPL datasets** using Python and extract meaningful insights from real-world cricket data.

The dataset consists of **two CSV files**:

* `matches.csv` → Match-level data
* `deliveries.csv` → Ball-by-ball data

---

## 🚀 Objectives

* Load and explore IPL datasets using Pandas
* Perform statistical and exploratory data analysis
* Merge datasets for deeper insights
* Analyze player and team performance
* Generate advanced cricket metrics like **Strike Rate** and **Economy Rate**

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**

---

## 📊 Key Analysis Performed

### 🔹 Basic Analysis

* Matches won by each team
* Toss winner distribution
* Dataset inspection (head, info, describe)

### 🔹 Player Performance

* Top batsmen by total runs
* Top bowlers by wickets

### 🔹 Advanced Insights

* 🏏 **Strike Rate Analysis**

  * Calculated using: `(Runs / Balls Faced) × 100`
  * Filtered out wides for accurate calculation

* 🎯 **Economy Rate Analysis**

  * Calculated using: `(Runs Conceded / Overs)`
  * Excluded wides and no-balls for precision

### 🔹 Data Processing

* Merged `matches` and `deliveries` datasets using keys (`id` & `match_id`)
* Cleaned and filtered data for meaningful insights

---

## 📈 Sample Insights

* High strike rate players contribute significantly in T20 formats
* Economical bowlers play a crucial role in controlling the game
* Certain teams dominate consistently across seasons

---

## 📁 Project Structure

```
📦 IPL-Data-Analysis
 ┣ 📜 analysis.py
 ┣ 📊 matches.csv
 ┣ 📊 deliveries.csv
 ┣ 📁 outputs
 ┃ ┣ 📄 top_players.csv
 ┃ ┣ 📄 top_strike_rate.csv
 ┃ ┗ 📄 top_economy.csv
 ┗ 📄 README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/IPL-Data-Analysis.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib
```

3. Run the script:

```
python analysis.py
```

---

## 📌 Results

* Generated CSV outputs for top players, strike rates, and economy
* Visualized performance using bar charts
* Built a complete end-to-end data analysis pipeline

---

## 🎯 Learning Outcomes

* Hands-on experience with **real-world datasets**
* Strong understanding of **data cleaning & preprocessing**
* Improved skills in **Pandas and data analysis**
* Learned how to derive **actionable insights from data**

---

## 🔗 Connect With Me

* LinkedIn: https://www.linkedin.com/in/tejassalunkhe1234
* Email: [tejasalunkhe1233@gmail.com](mailto:tejasalunkhe1233@gmail.com)

---

## ⭐ Acknowledgment

This project was completed as part of the **Syntecxhub Internship Program**, focusing on practical data science skills and real-world applications.

---

💡 *If you like this project, feel free to star ⭐ the repository!*
