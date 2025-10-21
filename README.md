# NBA Schedule Analysis: Quantifying the Impact of Schedule Difficulty on Team Wins

## Overview

This project analyzes over a decade of NBA game data (2014-2024) to quantify the isolated impact of schedule difficulty on a team's regular-season performance. Using an Ordinary Least Squares (OLS) regression model with team and season fixed effects, this analysis determines how many wins a team gained or lost purely due to its schedule's structure—independent of the team's inherent quality.

The key finding is that a team's schedule is a significant and quantifiable factor that can alter the regular-season standings by several wins, confirming that not all 82-game schedules are created equal.

## Key Features & Methodologies

* Data Cleaning & EDA: Processed and analyzed 10 seasons of schedule data to identify historical trends in game density, back-to-backs, and travel load.

* Statistical Modeling: Developed an OLS regression model to predict individual game outcomes based on three key schedule factors while controlling for team and season effects:

* Opponent Strength: The win rate of the opponent.

* Days of Rest: Capturing immediate team fatigue.

* Schedule Density: The number of games played in the previous 6 days.

* Counterfactual Analysis: Compared each team's predicted performance under their actual schedule against a baseline "neutral" schedule to isolate and quantify the total number of wins gained or lost purely due to schedule luck.

* Interactive Visualization: Created a comprehensive dashboard to explore any team's schedule for a given season, visualizing game density, rest days, and performance trends over time.

## Executive Summary: Key Findings

The analysis revealed that schedule difficulty can account for a swing of several wins over a season. For instance, across the ten seasons analyzed (2014-2023), teams like the Los Angeles Lakers consistently faced one of the league's toughest schedules, costing them an estimated 6-7 wins, while teams like the Toronto Raptors benefited from comparatively lighter schedules. The model confirms that while team strength is the primary driver of wins, schedule luck is a statistically significant factor in a team's final record.

## View the Interactive Dashboard

The full, interactive schedule analysis dashboard cannot be rendered directly on GitHub. Please view the standalone HTML file to explore the visualization tool.
<img width="1083" height="850" alt="interactive_schedule" src="https://github.com/user-attachments/assets/2935aa10-8eb8-45ec-9417-d3e1f26b12ee" />

[➡️ Click here to access the Interactive Schedule Dashboard HTML file](https://github.com/leonhsuportfolio/nba_schedule_analysis/blame/4ad14729dccdab0b42e4d950e5f7184fcfe85579/interactive_dashboard.html)


## How to Run This Project

Clone the repository:

git clone [https://github.com/leonhsuportfolio/nba_schedule_analysis](https://github.com/leonhsuportfolio/nba_schedule_analysis)


Install the required libraries:

pip install pandas plotly scikit-learn statsmodels


Open and run the NBA Schedule Analysis.ipynb notebook in a Jupyter environment.
