# 🏏 IPL Ball-by-Ball Data Analysis

A comprehensive data analysis project exploring Indian Premier League (IPL) ball-by-ball data using Python, Pandas, NumPy, and Matplotlib.

This project analyzes over 260,000 delivery records across multiple IPL seasons to uncover team performance trends, scoring patterns, batting dominance, bowling pressure, and match-phase dynamics through data cleaning, feature engineering, statistical analysis, and visualization.

---

## 📌 Project Overview

The Indian Premier League (IPL) generates massive amounts of ball-by-ball data every season. This project leverages data science techniques to extract meaningful insights from historical IPL matches and answer key cricket analytics questions.

The analysis focuses on:

- Team scoring performance
- Boundary distribution
- Match phase scoring patterns
- Top run-scorers
- Bowling pressure through dot balls
- Statistical outlier detection

---

## 🎯 Objectives

### Research Question 1
Which teams have scored the most total runs in IPL history, and how are boundaries distributed across teams?

### Research Question 2
How do scoring rates differ across the three match phases?

- Powerplay (Overs 1–6)
- Middle Overs (Overs 7–15)
- Death Overs (Overs 16–20)

### Research Question 3
Who are the top run-scorers in IPL history, and which bowling teams apply the most pressure through dot balls?

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Dataset

**Dataset:** IPL Ball-by-Ball Dataset

**Source:** Kaggle

The dataset contains:

- 260,000+ ball-by-ball records
- Batting and bowling teams
- Batter and bowler information
- Runs scored
- Extras
- Wickets and dismissals
- Match over information

---

## 🧹 Data Cleaning

The dataset underwent several preprocessing steps:

- Handled missing values
- Filled null wicket-related fields with meaningful labels
- Removed super-over deliveries
- Standardized franchise names
- Removed duplicate records
- Corrected data types for numerical analysis

### Team Name Standardization

Examples:

- Delhi Daredevils → Delhi Capitals
- Kings XI Punjab → Punjab Kings
- Royal Challengers Bangalore → Royal Challengers Bengaluru

---

## ⚙️ Feature Engineering

Four new analytical features were created:

| Feature | Description |
|----------|-------------|
| over_phase | Categorizes overs into Powerplay, Middle, and Death |
| is_boundary | Flags fours and sixes |
| is_dot_ball | Identifies pressure deliveries |
| run_category | Categorizes runs into Dot, Single, Double, Triple, Four, and Six |

---

## 📈 Analysis Performed

### Team Performance Analysis

- Total runs scored by each IPL franchise
- Boundary frequency across teams

### Phase-wise Scoring Analysis

- Average runs per ball by phase
- Total runs scored by phase

### Batter Performance Analysis

- Top 10 IPL run-scorers
- Contribution comparison

### Bowling Pressure Analysis

- Dot-ball percentage by bowling team

### Statistical Analysis Using NumPy

- Mean and standard deviation calculations
- Run distribution analysis
- Correlation analysis
- Z-score based outlier detection

---

## 📊 Visualizations

The project includes:

- Team total runs bar chart
- Top 10 batters bar chart
- Dot-ball percentage pie chart
- Boundary distribution histogram
- Phase-wise scoring comparison charts

---

## 🔍 Key Findings

### Team Performance

- Mumbai Indians and Chennai Super Kings have scored the highest total runs in IPL history.

### Match Phases

- Death Overs (16–20) produce the highest scoring rate.
- Middle Overs are generally the most restrictive phase.

### Batting Insights

- A small group of elite batters contribute a significant portion of total IPL runs.
- Virat Kohli consistently appears among the leading run scorers.

### Bowling Insights

- Strong bowling teams maintain higher dot-ball percentages.
- Dot-ball percentage serves as a useful indicator of bowling pressure.

### Statistical Insights

- Z-score analysis identified rare high-impact deliveries that can influence aggregate statistics.

---

## 📂 Project Structure

```text
IPL-Ball-by-Ball-Analysis/
│
├── Dataset.csv
├── Pandas_Analysis.ipynb
├── NumPy_Analysis.ipynb
├── Matplotlib_Visualizations.ipynb
├── images/
│   ├── team_runs.png
│   ├── top_batters.png
│   ├── dot_ball_percentage.png
│   └── boundary_distribution.png
│
└── README.md
```

---

## 📚 Skills Demonstrated

This project showcases:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Wrangling
- Feature Engineering
- Statistical Analysis
- Data Visualization
- Python Programming
- Pandas
- NumPy
- Matplotlib

---

## 🚀 Future Improvements

- Predictive modeling for match outcomes
- Player performance forecasting
- Venue-based analysis
- Toss impact analysis
- Advanced visualizations using Seaborn and Plotly
- Machine learning models for run prediction

---

## 👩‍💻 Authors

- Mahdiat Rahman
- Md. Golam Rabbani Sajib
- Rabeta Tanjum Arni

---

## 📖 Dataset Reference

IPL Complete Dataset (2008–2020)

Source:
https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020
