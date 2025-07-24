# IPL Data Analysis with Power BI 🏏📊

This project presents an interactive dashboard analyzing the Indian Premier League (IPL) using Microsoft Power BI. The goal is to extract actionable insights from IPL datasets to understand team performance, player statistics, match trends, and season-wise comparisons.

---

## 📁 Files in This Repository

| File / Folder | Description |
|---------------|-------------|
| `ipl (1).pbix` | Main Power BI project file |
| `images/`      | Exported visuals and dashboard screenshots |
| `README.md`    | Project documentation |

---

## 🎯 Project Objective

To perform exploratory data analysis on IPL match and player data using Power BI, transforming raw data into visual stories that provide strategic insights.

---

## 🧩 Project Workflow: Step-by-Step Breakdown

### 1. **Data Collection**
- Acquired IPL match and player data from Kaggle or other cricket data repositories.
- Combined datasets including:
  - Match-level details (venue, teams, toss, winner, etc.)
  - Player statistics (runs, wickets, strike rate, economy, etc.)

### 2. **Data Cleaning and Preparation**
- Cleaned and standardized columns in Power Query Editor.
- Removed null values, fixed inconsistent team/player names.
- Created relationships between tables:
  - Matches ↔ Players
  - Matches ↔ Deliveries (ball-by-ball data)

### 3. **Data Modeling**
- Built a star schema model using:
  - Fact tables: Matches, Deliveries
  - Dimension tables: Teams, Players, Seasons
- Defined relationships with appropriate cardinality and cross-filter direction.
- Created DAX measures for:
  - Total runs, wickets, strike rate
  - Win percentage, average scores, boundaries

### 4. **Dashboard Design**
Designed a multi-page interactive dashboard with:
- **Page 1**: Overview – Season summary, total matches, champions
- **Page 2**: Team Performance – Wins, toss decisions, venue stats
- **Page 3**: Player Stats – Orange Cap, Purple Cap, best strike rates
- **Page 4**: Match Insights – Toss impact, margin of victory, trends
- **Page 5**: Comparisons – Team head-to-head stats

### 5. **Visualization Tools Used**
- Bar Charts, Line Charts, Pie Charts
- Slicers and filters for interactivity
- KPI Cards and custom visuals
- Drill-through for match and player deep-dives

### 6. **Insights Derived**
- Teams that win the toss and choose to bowl first often have higher win rates.
- Certain players consistently perform across seasons (e.g., top run scorers).
- Venues like Wankhede favor high scores; others are more bowling-friendly.
- Teams with stable captains and top-order strength dominate more matches.

---

## 🖼️ Sample Visualizations

> _Screenshots below exported from the Power BI report:_

![images](images/)
![Top Batsmen](images/top_batsmen.png)
![Venue Analysis](images/venue_analysis.png)

---

## 🛠️ How to Use This Project

1. **Download or Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ipl-powerbi-dashboard.git
