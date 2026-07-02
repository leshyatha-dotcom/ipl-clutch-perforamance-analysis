# IPL Clutch Performance & Match-Winning Impact Analysis

## Problem Statement
Traditional IPL stats (total runs, wickets) don't show who actually
performs when it matters. This project identifies "clutch" players —
those who elevate their game in high-pressure chase situations — and
examines whether winning the toss provides a real advantage.

## Dataset
IPL Complete Dataset (2008–2020) — matches.csv + deliveries.csv
Source: Kaggle (link)

## Approach
1. Merged ball-by-ball data with match metadata
2. Defined "pressure situations" as chase scenarios with required run rate > 10
3. Calculated clutch factor = pressure performance - overall performance
   (strike rate for batsmen, economy differential for bowlers)
4. Analyzed toss-decision impact by venue

## Key Findings
- [Fill in: top 3-5 clutch batsmen and their clutch factor]
- [Fill in: top 3-5 clutch bowlers]
- [Fill in: which venues show strongest toss advantage]
- [Fill in: bat first vs field first win rate difference]

## Visualizations
- Scatter plot: Everyday Hero vs Big Match Player
- Bar chart: Clutch bowler rankings
- Heatmap: Toss advantage by venue

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Future Work
- Extend pressure definition to defending totals (1st innings pressure)
- Player consistency across seasons
