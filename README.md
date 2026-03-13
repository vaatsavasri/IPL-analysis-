 IPL Analysis Dashboard

An interactive Power BI dashboard analyzing Indian Premier League (IPL) data across
multiple seasons to uncover performance trends, player consistency, and match outcomes.


 Project Overview

This project dives deep into IPL statistics to provide cricket enthusiasts, analysts,
and team strategists with a comprehensive view of match performance, team dynamics,
and player metrics — all through visually rich, interactive Power BI dashboards.


 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation and interactive visuals |
| Excel / CSV | Raw IPL dataset storage |
| DAX | Calculated measures and KPIs |
| Power Query | Data cleaning and transformation |

 Project Structure
```
ipl-analysis-dashboard/
│
├── data/
│   ├── matches.csv           # Match-level data
│   ├── deliveries.csv        # Ball-by-ball data
│   └── players.csv           # Player information
│
├── dashboard/
│   └── IPL_Analysis.pbix     # Power BI dashboard file
│
├── screenshots/
│   ├── overview.png
│   ├── player_stats.png
│   └── team_performance.png
│
└── README.md
```



 Key Features

Season Overview** — Win/loss records, toss analysis, and season summaries per team
  Run Rate Trends** — Powerplay, middle overs, and death overs run-rate breakdowns
  Player Performance** — Top run-scorers, wicket-takers, and strike rate leaders
  Player Consistency** — Performance tracking across multiple seasons
  Match Outcomes** — Winning patterns by venue, toss decision, and batting order
  KPI Cards** — Total runs, wickets, sixes, fours, and economy rates at a glance
  Slicers & Filters** — Filter by season, team, venue, and player for deep-dives


 Dashboard Preview

 Add screenshots of your Power BI dashboards here

![Overview](screenshots/overview.png)
![Player Stats](screenshots/player_stats.png)
![Team Performance](screenshots/team_performance.png)

---

 Insights Derived

 Identified teams with the highest win rates when batting first vs chasing
 Revealed players with the most consistent performances across IPL seasons
 Detected venues with highest average scores, influencing toss decisions
 Highlighted run-rate patterns in powerplay overs that correlate with match wins
 Uncovered top performers in pressure situations (final overs, low-score chases)


How to Use

1. Clone the repository
```bash
   git clone https://github.com/vaatsavasri/ipl-analysis-dashboard.git
```
2. Open `dashboard/IPL_Analysis.pbix` in **Power BI Desktop**
3. If prompted, reconnect the data source to the `data/` folder
4. Use the slicers to filter by season, team, or player

---

 Dataset

- **Source:** [Kaggle IPL Dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- **Seasons Covered:** [Add your range, e.g. 2008–2023]
- **Records:** 900+ matches, 200K+ deliveries




This project is open source and available under the [MIT License](LICENSE).
