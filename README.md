
# 🏀 MDC Women's Basketball Stats (2024–2025 Season)

This repository contains structured player performance data for the **Miami Dade College Women's Basketball Team** during the 2024–2025 season.

It includes season-level statistics for each player, covering shooting, playmaking, rebounding, and defensive metrics. The data is prepared for exploratory data analysis, visualization, and advanced performance modeling in Python (e.g., using pandas, seaborn, scikit-learn).

---

## 📁 Contents

- `MDC Women's Basketball Stats.csv`: Cleaned dataset of player statistics
- `notebooks/`: (optional) Jupyter/Colab notebooks for analysis and visualizations
- `README.md`: Column definitions and project overview
- `Source of Data`: https://www.mdcathletics.com/sports/wbkb/2024-25/teams/miamidadecollege

---

## 📊 Column Definitions

| Column Name   | Description |
|---------------|-------------|
| `#`           | Jersey number of the player. |
| `Player`      | Full name of the player. |
| `GP`          | Games Played – total number of games the player participated in. |
| `GS`          | Games Started – number of games the player was in the starting lineup. |
| `MIN`         | Total minutes played across all games. |
| `AVG_MIN`     | Average minutes played per game. |
| `FG`          | Field Goals Made – total number of made two- and three-point field goals. |
| `FGA`         | Field Goals Attempted – total number of shot attempts (excluding free throws). |
| `FG_PCT`      | Field Goal Percentage – ratio of field goals made to attempted (FG ÷ FGA). |
| `3FG`         | Three-Point Field Goals Made. |
| `3FGA`        | Three-Point Field Goals Attempted. |
| `PCT`         | Three-Point Field Goal Percentage – ratio of 3FG made to 3FGA. |
| `FT`          | Free Throws Made. |
| `FTA`         | Free Throws Attempted. |
| `FT_PCT`      | Free Throw Percentage – ratio of FT made to FTA. |
| `OFFR`        | Offensive Rebounds – rebounds collected on the offensive end. |
| `DEFR`        | Defensive Rebounds – rebounds collected on the defensive end. |
| `TOTR`        | Total Rebounds – sum of offensive and defensive rebounds. |
| `AVGR`        | Rebounds per Game – average total rebounds per game. |
| `PFOUL`       | Personal Fouls – number of fouls committed by the player. |
| `DISQ`        | Disqualifications – games where a player fouled out (typically 5 fouls). |
| `ASSIST`      | Total number of assists (passes leading directly to a score). |
| `A_G`         | Assists per Game – average assists per game. |
| `TO`          | Turnovers – number of times the player lost possession. |
| `TO_G`        | Turnovers per Game – average turnovers per game. |
| `A_TO_RATIO`  | Assist-to-Turnover Ratio – measures playmaking efficiency (ASSIST ÷ TO). |
| `BLK`         | Blocks – total number of shots blocked. |
| `BLK_G`       | Blocks per Game – average blocks per game. |
| `STL`         | Steals – total number of times the player took possession from the opponent. |
| `STL_G`       | Steals per Game – average steals per game. |
| `PTS`         | Total Points Scored – sum of all points from FG, 3FG, and FT. |
| `AVG_P`       | Points per Game – average number of points scored per game. |

---

## 📈 Use Cases

- Player efficiency analysis
- Offensive/defensive breakdowns
- Visualization with matplotlib/seaborn
- Creating dashboards with Streamlit or Tableau
- Advanced metrics modeling (e.g., PER, usage rate)

---

## 📎 License

This dataset is intended for educational and non-commercial use only. Please credit MDC Athletics if redistributed.

---
