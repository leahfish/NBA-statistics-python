# NBA-statistics-python

A Python-based statistical analysis of NBA player salaries, built on the same team dataset used in our Excel coursework, extended with hypothesis testing, confidence intervals, and probability analysis in pandas/SciPy/statsmodels.

## The dataset

566 NBA players from the 2025-26 season, combining contract data from [Spotrac](https://www.spotrac.com/nba/contracts), performance stats from Basketball-Reference, and international-roster status from the NBA. Variables include player, team, conference, position group, age, games played, minutes/rebounds/assists/points per game, salary, and birth origin (US vs. international).

Primary variable of interest: **player salary**. Secondary variable: **birth origin (US/INT)** — chosen to test whether the NBA's rising international visibility (Luka Dončić, Victor Wembanyama, etc.) translates into a real difference in pay, or whether that's more about marketing than market value.

## What's in this notebook

- **Part 1** — data import and cleaning, descriptive statistics, and probability distribution exploration (histograms, relative frequencies, conditional/joint probabilities).
- **Part 2 (Final Report)** — two hypothesis tests (salary by birth origin; proportion of US-born players), a 95% confidence interval for mean salary, a discussion of statistical assumptions and validity, business commentary, and a final written report synthesizing findings across the whole project (including the regression work from our Excel analysis).

## Key findings

- Salary is heavily right-skewed: mean (~$9.3M) is nearly triple the median (~$3.6M).
- No statistically significant salary difference between US-born and international players (p = 0.55), despite the league remaining ~75% US-born (p = 0.0013) — international visibility hasn't translated into a measurable pay premium or discount.
- Points and assists per game are the strongest predictors of salary (from our companion regression analysis, adjusted R² = 0.615).

## Team

This analysis was completed as a team project (Group 5) for a graduate statistics/Python programming course. This repository was assembled and is maintained by **Leah Fisher** as part of an individual course assignment.
